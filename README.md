# OWASP Penetration Test Reporting Standard (OPTRS)

## Overview  

This is a fork of the **OWASP Penetration Test Reporting Standard (OPTRS)** which provides a **structured, machine-readable JSON format** for penetration test reports. We use it for other things here at SeveredOrg.

### Why OPTRS?  

Penetration testing reports often lack **consistency, automation capabilities, and interoperability** across security tools. OPTRS solves this by:  

- **Standardizing report structures** for better comparability  
- **Enabling automation** with a JSON-based format  
- **Improving interoperability** between security teams, SIEMs, and vulnerability management tools  
- **Providing clear, actionable insights** for faster remediation  

## Schema  

The OPTRS JSON schema defines a **structured format for penetration test reports**, ensuring that findings are:  

- **Categorized properly**  
- **Easily ingested by security tools**  
- **Machine-readable for automation workflows**  

### 📄 [View the OPTRS JSON Schema](https://github.com/OWASP/www-project-penetration-test-reporting-standard/blob/main/optrs-schema-v1.json) 

### Example JSON Report  

For a real-world example of how OPTRS structures a penetration test report, see the **sample report**:  

### 📄 [OPTRS Sample Report](https://github.com/OWASP/www-project-penetration-test-reporting-standard/blob/main/assets/sample/optrs-sample.json) 
 
## How to Use OPTRS  

1. **Adopt the Schema:** Use OPTRS as the format for penetration test reports.  
2. **Integrate with Security Tools:** Automate ingestion into SIEMs, vulnerability management platforms, or custom dashboards.  
3. **Contribute Feedback:** Help refine the standard by sharing feedback.  

## Get Involved  

We encourage security professionals, penetration testers, and developers to:  

- **Provide feedback** on the schema  
- **Adopt OPTRS** in security assessments  
- **Contribute to development and integrations**  

### 💬 [Join the Discussion on GitHub](https://github.com/OWASP/www-project-penetration-test-reporting-standard/discussions)  

Join the conversation in our GitHub Discussions forum to collaborate, share insights, and help improve OPTRS.  

### 📩 Contact & Community  

For direct collaboration, you can also join the OWASP Slack:  
[OWASP Slack #penetration-testing Channel](https://owasp.slack.com/archives/C08BYRE903Z)  
