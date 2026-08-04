# Defensive Security Introduction — Active Recall

**Module:** 1  
**Platform:** TryHackMe  
**Method:** Questions were AI-generated based on the completed lesson. All answers were written independently from memory before feedback or corrections were shown.

## Initial Recall

### 1. What is defensive security?

> Defensive security is the prevention of security breaches through either the creation of systems to prevent attacks from occurring or responding to active attacks.

**Result:** Mostly correct—detection is also a central part of defensive security.

## Practical Recall

### 2. How did you identify the source of the suspicious activity?

> I examined the IP address of the source of suspicious activity, and the dashboard tool indicated that this source deserved investigation.

**Result:** Correct based on the information presented in the practical.

### 3. What did the URL Discovery Attempts show?

> The URL Discovery Attempts showed the different site paths accessed by the attacker. Given how the attempted site paths were all admin-related, they were trying to access information or power not authorized to them.

**Result:** Correct—the attacker was performing URL or directory discovery to find restricted functionality.

### 4. What did the firewall rule accomplish?

> The firewall rule blocked the IP address from accessing the website and was the appropriate action to prevent any damage or further damage from occurring.

**Result:** Correct—the rule contained traffic originating from that IP address.

### 5. What does containment mean, and does it remove the vulnerability?

> Containment means isolating the attacker from any further access to whatever security breach they were attempting. It does not remove the original vulnerability but temporarily prevents further damage.

**Result:** Correct.

### 6. Why would the firewall rule fail if the attacker changed IP addresses?

> The firewall rule is specific to the original IP address, so the firewall would do nothing to stop a new one. If the new IP address is detected, we can add a firewall rule for it to contain the threat until the vulnerability can be fully patched.

**Result:** Correct—blocking an IP contains the immediate threat, while patching provides a more lasting defense.

## Corrections Retained

- Defensive security involves preventing attacks as well as detecting and responding to them.
- URL or directory discovery is used to locate accessible website paths and functionality.
- Containment limits an active threat; remediation addresses the underlying vulnerability.

**Final understanding:** 9/10 — Ready to move on