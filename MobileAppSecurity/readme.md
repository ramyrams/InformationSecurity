# Mobile App Security

#
* Is your application storing payment information or credit card details?
* Does your application use secure network protocols?
* Can they be switched to insecure ones?
* Does the application ask for more permissions than it needs?
* Does your application use certificates?
* Does your application use a Device ID as an identifier?
* Does your application require a user to be authenticated before they are allowed to access their data?
* Is there a maximum number of login attempts before they are locked out?

# Mobile Security Testing Guide
* [Mobile Security Testing Guide -MSTG] (https://github.com/OWASP/owasp-mstg) - The Mobile Security Testing Guide (MSTG) is a comprehensive manual for mobile app security testing and reverse engineering.

## Mobile App Security Requirements and Verification

# CheckList
* [OWASP Mobile App Security Checklist](https://github.com/OWASP/owasp-mstg/blob/master/Checklists/Mobile_App_Security_Checklist.xlsx)
* [Mobile app security testing checklist](https://codifiedsecurity.com/2016/04/28/mobile-app-security-testing-checklist/)
* [Android Client-Side Attacks and Tests](https://appsec-labs.com/android-attacks-tests/)
* [Mobile App Security Checklist](http://www.ministryoftesting.com/wp-content/uploads/2014/01/SmartBear-Mobile-Testing-Checklist-V2.pdf)

OWASP Mobile Security Top 10 vulnerabilities :
* [M1: Weak Server Side Controls](https://www.owasp.org/index.php/Mobile_Top_10_2014-M1)
* [M2: Insecure Data Storage](https://www.owasp.org/index.php/Mobile_Top_10_2014-M2)
* [M3: Insufficient Transport Layer Protection](https://www.owasp.org/index.php/Mobile_Top_10_2014-M3)
* [M4: Unintended Data Leakage](https://www.owasp.org/index.php/Mobile_Top_10_2014-M4)
* [M5: Poor Authorization and Authentication](https://www.owasp.org/index.php/Mobile_Top_10_2014-M5)
* [M6: Broken Cryptography](https://www.owasp.org/index.php/Mobile_Top_10_2014-M6)
* [M7: Client Side Injection](https://www.owasp.org/index.php/Mobile_Top_10_2014-M7)
* [M8: Security Decisions Via Untrusted Inputs](https://www.owasp.org/index.php/Mobile_Top_10_2014-M8)
* [M9: Improper Session Handling](https://www.owasp.org/index.php/Mobile_Top_10_2014-M9)
* [M10: Lack of Binary Protections](https://www.owasp.org/index.php/Mobile_Top_10_2014-M10)

![1](https://media.licdn.com/mpr/mpr/AAEAAQAAAAAAAAVRAAAAJGRmYWYzNjIwLTZkOWItNDc0MS04OWYxLTZkMDEwY2U3YzEwMQ.png)


![1](https://www.owasp.org/images/thumb/a/ac/2014-01-26_20-23-29.png/825px-2014-01-26_20-23-29.png)
![1](https://www.owasp.org/images/3/3a/IOS_Arsenal.png)
![1](https://www.owasp.org/images/4/4c/Reverse_Engineering_Arsenals.png)

## OWASP Mobile Security Project
* [OWASP Mobile Security Project](https://www.owasp.org/index.php/OWASP_Mobile_Security_Project#tab=M-Tools)

# OASAM
* [OASAM](https://github.com/b66l/OASAM)-OASAM is the acronym of Open Android Security Assessment Methodology and its purpose is to become a reference framework on Android application vulnerability assessments.

Mobile App Testing Checklist
https://www.slideshare.net/manojmastiff/mobile-app-testing-23270329

# MAM-Security-Checklist
Checklist intended to be used as a baseline for assessing, designing, and testing the security of a MAM (Application Wrapping) solution
https://github.com/GDSSecurity/MAM-Security-Checklist

https://github.com/GDSSecurity/Whitepapers/blob/master/GDS%20Labs%20-%20Analysis%20of%20Mobile%20Application%20Management%20(MAM)%20Solutions.pdf?raw=true


# The Process of Mobile Application Security Testing
There are three basic steps suggested by experts while performing security testing for mobile apps:
* Threat Modeling: 
	This method is used for identifying threats in the app
* Vulnerability Analysis: 
	This method is used for identifying vulnerabilities in the application with the previously created test cases using Runtime analysis, Dynamic methods, and forensic methods.
* Intelligence Gathering: 
	This method is used for gathering as much information as possible about the application



# Secure Coding Best Practices
* User authentication
* Authorizations
* Input validation mechanisms
* Configuration data protection
* Information confidentiality
* Information integrity
* Cryptography and key management
* Password policy
* Session management
* System administration interface protection
* Secure access to databases
* Endpoint protection for sensitive data
* Runtime error management
* Auditing & logging

# Black Box Penetration Testing

What is Black Box Testing?
Black box testing is the process of simulating a skilled attack, using the techniques and tools aimed to detect security vulnerabilities and exploit them.

Our experts will simulate a real attack on the application. The testing process covers a wide range of application-level vulnerabilities as defined by OWASP and WASC, targeting potentially harmful vulnerabilities in your application.

The testing process will reveal the vulnerabilities, potential exploitation damage and severity.

The detailed report you receive will include recommendations that will assist you in securing your systems and protecting your companies’ assets and integrity.

All application level vulnerabilities will be covered in the context of a Black Box test. Specifically, the testing methodologies used are OWASP and WASC, which provides full coverage over application level vulnerabilities. Some of the covered attacks:

# Vulnerabilities Covered
SQL Injection – taking control over the database
Hidden Backdoors – used by attackers to easily infiltrate the system over and over
Cross-site Scripting – injecting malicious code to innocent user browsers
Cross-site Request Forgery – impersonating an innocent user and performing actions in his name
Bypassing Authentication – taking over user and administrator accounts
Authorization Breaches – performing unauthorized actions and accessing unauthorized information
Bypassing Crypto – viewing confidential and private information by unauthorized people
Open Redirects – an open door to phishing attacks and scams
Command Injection – injecting commands to a remote server and taking over
Forceful Browsing – bypassing restrictions and performing unauthorized actions
Bypassing Business-Logic Restrictions – performing application-specific actions that are not authorized by the company’s regulations
LFI/RFI – injecting malicious code to a vulnerable application
Denial of Service – making the application unavailable to remote users


# Gray Box Penetration Testing

## Vulnerabilities Covered
Gray Box test provides a full, comprehensive test which results in a hybrid between finding vulnerabilities which are relevant for both White Box test and a Black Box test. The testing methodologies are OWASP and WASC methodologies which cover wide-range of application security vulnerabilities. Some of the covered vulnerabilities:

* SQL Injection – taking control over the database
* Hidden Backdoors – used by attackers to easily infiltrate the system over and over
* Cross-Site Scripting (XSS) – injecting malicious code into innocent user’s browsers
* Cross-Site Request Forgery (CSRF) – impersonating an innocent user and performing actions in his name
* Bypassing Authentication – taking over users and administrators accounts
* Authorization Breaches – performing unauthorized actions and accessing unauthorized information
* Bypassing Crypto – viewing of confidential and private info by unauthorized people
* Open Redirects – an open door to phishing attacks and scams
* Command Injection – injecting commands to a remote server and taking over
* Forceful Browsing – bypassing restrictions and perfoming unauthorized actions
* Bypassing Business-Logic Restrictions – performing application-specific actions that are not authorized by the company’s regulations
* LFI/RFI – injecting malicious code to a vulnerable application
* Denial of Service – making the application unavailable to remote users



List of Web Application Attacks and Tests Performed During Penetration Testing
https://appsec-labs.com/web-attacks-tests/


List of IoT (Connected Device) Attacks and Tests Performed During Penetration Testing
https://appsec-labs.com/iot-attacks-tests/

Android Client-Side Attacks and Tests
https://appsec-labs.com/android-attacks-tests/


iOS Client-Side Attacks and Tests
https://appsec-labs.com/ios-attacks-tests/


* [Mobile Application Security Report 2015](https://appsec-labs.com/wp-content/uploads/2015/08/Mobile-App-Security-Report-2015.pdf)



Examples of open-source security testing tools for mobile apps include:

* **Santoku:**  A virtual machine that contains a number of open source tools specific to mobile application security testing, forensics and data recovery, and malware analysis.
* **Mobile Security Framework (MobSF):** Automated penetration testing framework for Android and iOS apps including static and dynamic analysis and web API testing capabilities.
* **Mitmproxy:** Allows a user to intercept and modify requests and responses exchanged between an app and backend services in order to inspect any data transferred.
* **Drozer:** Identifies security vulnerabilities in Android apps and devices and supports the use and sharing of public exploits.
* **Frida:** An analyst can use Frida to inject JavaScript snippets into native Windows, Mac, Linux, iOS, and Android apps. Created and maintained by NowSecure researcher Ole André V. Ravnås and sponsored by NowSecure.
* **Radare:** A reverse-engineering framework used to analyze and inspect iOS and Android binaries. Created and maintained by NowSecure researcher Sergi Álvarez and sponsored by NowSecure.


# Mobile App Security Testing Service Vendor
https://www.nowsecure.com/solutions/mobile-app-security-testing/

# Mobile Security Framework (MobSF)
* [Mobile Security Framework - MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF)

Mobile Security Framework (MobSF) is an intelligent, all-in-one open source mobile application (Android/iOS/Windows) automated pen-testing framework capable of performing static and dynamic analysis. It can be used for effective and fast security analysis of Android, iOS and Windows mobile Applications and supports both binaries (APK, IPA & APPX ) and zipped source code. MobSF can also perform Web API Security testing with it's API Fuzzer that can do Information Gathering, analyze Security Headers, identify Mobile API specific vulnerabilities like XXE, SSRF, Path Traversal, IDOR, and other logical issues related to Session and API Rate Limiting.

# URL


Pentests
Security Engineering
security Training

# Security Engineering
https://opensecurity.in/

# 5 Open-Source Mobile App Security Testing Tools
* **OWASP Zed Attack Proxy Project.** It is one of the most popular free testing tools. The detection of system vulnerabilities can be performed automatically.
* **MobiSec.** The framework provides a real environment for mobile testing – infrastructure and mobile devices. It supports the installation of additional tools and platform for penetration testing. The framework can be booted on any Intel-based system.
* **Clang Static Analyzer.** It is a source code tool for detecting issues in iOS, C, C++ programs. It can be run within Xcode. It is a part of the Clang project.
* **iMAS**. This tool is used for iOS security app testing. It provides the data lost on iOS apps and discovers the product weaknesses. It was created by the MITRE corporation.
* **QARK**. It is short for Quick Android Review Kit. It is the security testing tool for Android-based applications. It ensures the detection of common vulnerabilities in source code and APKs for Android.


Application Testing Tool
Code Review Tools
Penetration Testing
Run time Application Self Protection
Security Review Software
Software Testing Tools
Vulnerability Assessment
Vulnerability Assessment and Penetration Testing
Vulnerability Scanner


* [Needle](https://github.com/mwrlabs/needle) -  iOS Security Testing Framework 
* [Drozer](http://mobiletools.mwrinfosecurity.com/) - The Android Security Assessment Framework 

* [nathan](Android Emulator for mobile security testing)
* [CSI (Continuous Security Integration) Framewor](https://github.com/ninp0/csi)

* [MARA_Framework](https://github.com/xtiankisutsa/MARA_Framework) - MARA is a Mobile Application Reverse engineering and Analysis Framework. It is a toolkit that puts together commonly used mobile application reverse engineering and analysis tools to assist in testing mobile applications against the OWASP mobile security threats. 

* [Damn Vulnerable iOS App (DVIA) ](https://github.com/prateek147/DVIA) - Damn Vulnerable iOS App (DVIA) is an iOS application that is damn vulnerable. Its main goal is to provide a platform to mobile security enthusiasts/professionals or students to test their iOS penetration testing skills in a legal environment.


https://github.com/gadgetfox/MobileSecurity


https://www.owasp.org/images/0/04/Security_Testing_Guidelines_for_mobile_Apps_-_Florian_Stahl%2BJohannes_Stroeher.pdf
