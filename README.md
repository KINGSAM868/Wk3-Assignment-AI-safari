# Responsible AI in Fintech and Healthtech

This repository examines two case studies in artificial intelligence: one in the fintech sector and another in healthtech. It highlights the ethical challenges, potential harms, and proposed responsible fixes for each scenario.

# Case 1: Microloan Score from Phone Data 📱💸

# What’s Happening
A fintech startup uses an AI model to provide microloan scores. The model analyzes smartphone metadata like call frequency, location data, and social connections instead of traditional credit history.

# Problems
Privacy Violation: The model collects sensitive, personal metadata without clear user consent.  
Proxy Bias: The model can unfairly exclude financially underserved groups based on their phone usage or mobility patterns.  
Lack of Transparency: Applicants receive a score but no explanation, making it impossible to appeal or correct errors.  
Power Imbalance: Users may feel coerced into sharing private data to access financial services.  
Data Security: The concentration of personal behavioral data creates a significant security risk.

# Responsible Fix
Consent & Minimization: Use only directly predictive features with explicit user consent.  
Privacy Preservation: Implement strong privacy techniques and delete raw data after use.  
Human Review: Require human review for all rejected applications and provide a clear appeal path.

---

## Case 2: Health-Help Post Takedown Bot 🩺🚫
Case 2: Health-Help Post Takedown Bot 🩺🚫

What’s Happening  
A social media platform uses an automated AI bot to remove posts labeled as "dangerous medical advice." The bot often removes legitimate patient support and peer-experience posts.

Problems  
- Over-blocking: The bot suppresses genuine peer support, isolating vulnerable users.  
- Context Blindness: The model struggles to differentiate between "personal experience" and "professional advice."  
- Transparency & Appeal: Users are not given clear reasons for content removal or a fast way to appeal decisions.  
- Access Inequality: Users who rely on peer support due to limited healthcare access are disproportionately affected.  
- Safety Trade-offs: Removing potentially helpful information without providing alternatives can be harmful.

Responsible Fix  
- Tiered Moderation: Use a human-in-the-loop approach, routing ambiguous cases to trained human moderators or health professionals.  
- Contextual Actions: Instead of outright removal, label posts with a disclaimer (for example, "Personal experience - not professional advice") and provide links to vetted resources.  
- Transparency: Publish moderation standards and false-positive rates for health-related content