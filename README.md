# cs-305-portfolio
# Artemis Financial – Secure Software Practices

## Portfolio Artifact: CS 305 Module Eight Submission

**Artifact:** Artemis Financial Practices for Secure Software Report  
**Course:** CS 305 – Software Security  
**Author:** Connor Martin  
**Date Submitted:** 06/14/2025  

---

## Reflection

Artemis Financial is a financial services company that needed help improving the security of their software systems. They wanted support identifying vulnerabilities in their application and ensuring that secure coding practices were in place. My task was to help them protect sensitive data and reduce the risk of cyberattacks through better software design and security tools.

I think I did well identifying vulnerable dependencies using tools like OWASP Dependency-Check and implementing security features like encryption and HTTPS. Writing secure code is important because it helps prevent things like data breaches and builds trust with users. For a company like Artemis Financial, strong software security is essential to protecting both their data and their reputation.

One part I found challenging at first—but really useful—was learning how to suppress false positives in the OWASP report using a `suppression.xml` file. It taught me how to focus on real issues and avoid wasting time on non-threats.

To increase security layers, I enforced HTTPS, used encryption, and created a self-signed certificate. If I were to do another assessment in the future, I’d use a mix of automated tools and manual reviews to find and fix issues, depending on the risk level.

After I made changes to the code, I retested everything and ran the dependency scan again to confirm that nothing new was broken or exposed. I also checked the security configurations to make sure everything was set up right.

Some of the tools and practices I used—like OWASP Dependency-Check, Java Keytool, Maven, and input validation—are things I’ll definitely use in future assignments. They’ve helped me build a stronger foundation for secure software development.

If a future employer asked for examples of my work, I’d be proud to share this project. It shows that I can find and fix vulnerabilities, work with security tools, and follow secure coding practices that are important in the real world.
