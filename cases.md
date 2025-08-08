# Case 1 — Microloan Score from Phone Data 📱💸

What’s happening
A fintech startup uses an AI model to decide who gets small loans. Instead of (or in addition to) credit history, the model analyzes smartphone metadata: call/text frequency, battery-charge patterns, location clusters, and social-graph features (who you call). It produces an automatic “score” and auto-approves or auto-rejects microloan applications.

What’s problematic

- Privacy violation: Sensitive metadata (who you call, where you go, how often your phone charges) reveals intimate patterns — collected and used without clear, informed consent.
- Proxy bias & exclusion: Features like mobility or phone usage correlate with income, gender roles, caregiving, rural residency, or age. The model can systematically deny loans to people who are already financially underserved.
- Lack of transparency & recourse: Applicants get a score and a decision but no explanation or easy appeal. They can neither correct errors nor know which data mattered.
- Power imbalance & coercion: People may feel forced to share more personal data to access credit, deepening surveillance economics.
- Data security risk: Detailed behavioral data concentrated in one place is a lucrative hack target.

One improvement (responsible fix)
Limit and justify features + consent + human review. Only use features that are directly and narrowly predictive of repayment and that the applicant explicitly consented to after seeing clear examples. Apply strong privacy-preserving techniques (data minimization, differential privacy, delete raw metadata after feature extraction). Require any automatic reject to trigger a human review and give applicants a plain-language explanation plus an appeal path.

---

# Case 2 — Health-Help Post Takedown Bot 🩺🚫

What’s happening
A social platform uses an automated moderation model to remove content it labels as “dangerous medical advice.” The model scans posts for health-related keywords and sentiment, then automatically takes down posts that look like treatment recommendations. Many genuine patient support posts and peer-experiences (e.g., “how I managed my chemo side effects”) get removed as “advice.”

What’s problematic

- Over-blocking & chilling effect: Legitimate peer support and lived-experience sharing are suppressed, isolating vulnerable users who depend on community advice.
- Context blind: The model can’t reliably tell “I tried X, it helped me” from “You should do X instead of seeing a doctor.” Removing nuance harms free expression and support.
- Transparency & appeal gap: Users aren’t told why posts were removed or given quick, expert human review; they lose trust in the platform.
- Access inequality: Users with less institutional trust or limited healthcare access rely more on peer info — they’re disproportionately harmed.
- Potential safety trade-offs: Removing helpful information without providing alternatives (links to vetted resources) can worsen outcomes.

One improvement (responsible fix)
Use tiered moderation with human-in-the-loop + better labels. Instead of outright takedowns, automatically flag posts with confidence scores and route ambiguous or high-impact cases to trained human moderators (or health professionals). When auto-moderation is used, replace removal with contextual actions: label the post (e.g., “Personal experience — not professional advice”), attach vetted resources, and provide a fast appeal. Publish moderation standards and false-positive rates for health content.

