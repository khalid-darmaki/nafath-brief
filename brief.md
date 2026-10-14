Version: NAFATH-V4
Track: Data

## Overview
A national service provider depends on code written by others, machine learning models, mobile apps and internet routes. Any of these can be secretly altered. Software teams must keep secrets out of code, so a leaked repository doesn't give attackers access. AI models can be tricked or poisoned through manipulated data. Mobile apps need a clear standard against which their security can be verified. Internet routes can be hijacked unless route origins are validated. Log4Shell showed how one hidden flaw in a shared library can expose thousands of organisations, and a Software Bill of Materials lets teams quickly find which products contain the affected component. Together, these six fields form one chain of trust.
## Software
The Twelve-Factor App says configuration, meaning anything that changes between deployments such as database addresses and credentials, should be stored in environment variables, strictly separated from code. A useful test is whether you could make the codebase open source at any moment without leaking credentials. Secrets in code are risky because they get copied into version control, are visible to anyone who can read the repository, and are hard to change per environment without rebuilding.

Resource: The Twelve-Factor App, III. Config - https://12factor.net/config
## AI
Adversarial attacks on machine learning fall into categories. Evasion attacks change inputs at prediction time, for example, adding small noise to an image so the model misclassifies it. Poisoning attacks corrupt the training data or the model, so it learns wrong or hidden behavior, such as a backdoor. Privacy attacks extract information about training data or the model, and abuse attacks target generative AI systems. The differences are the stage attacked (deployment versus training) and the attacker's goal.

Resource: NIST AI 100-2 E2025, Adversarial Machine Learning: A Taxonomy and Terminology of Attacks and Mitigations - https://csrc.nist.gov/pubs/ai/100/2/e2025/final
## Mobile
OWASP MASVS is an industry standard that lists security requirements for Android and iOS apps. Its controls are grouped into categories such as storage, cryptography, authentication, network communication, platform interaction, code quality, resilience, and privacy. It is used as a baseline: developers design to it, and testers check an app against each control, using the OWASP Mobile Application Security Testing Guide (MASTG) for the how-to. The result shows which requirements the app meets.

Resource: OWASP Mobile Application Security Verification Standard (MASVS) - https://mas.owasp.org/MASVS/
## Networking

## Cybersecurity

## Data

## Misconception in My Track

## Open Question
