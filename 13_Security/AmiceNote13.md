
> 📘 This note is part of my personal learning journal while reading *Software Engineering for Data Scientists*.
> Some sentences are quoted directly from the book for educational purposes only.  
> All rights belong to the original author and publisher.


## Security Risk regarding Data Scientists:

- Credentials : Easy passwords, saving passwords
- Physical security : computer hardware stolen
- Social Engineering : Phishing emails, scam
- 3rd party packages
- Python pickle Module
- Version Control Risks
- API Security Risks (e.g. SQL injection, Cross-site scripting, etc.)

## Tools
- Secure Coding tools
  - SonarQube, Checkmarx, Dependabot (by GitHub)
  - bandit -- give you the security analysis on code (vulnerability)
    ```
    pip install bandit
    bandit -r
    ```
# Security of ML System
1. Attack on a deployed model
   - The attacker has some knowledge of the basis of the model.
   - manipulate the output by a viral input
     
2. Attack on training data
   - training data extraction
   - particularly if trained on sensitive data
  
3. Model theft
   - theft of intellectual property
   - send enough queries and record enough response, to recreate the model
  
4. Data/Open source contamination
   - Attacker influences the source of datasets
   - Attacker influences the code of open source

---
tags: [personal-note, SE4DS, learning, non-commercial]

