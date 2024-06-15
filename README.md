![Vega Sat 1](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/8a51be88-df29-41a8-925f-2f6398f0b165)

<h1>**What is VEGA?**</h1>

**VEGA** is a **web vulnerability scanning tool** used to keep websites and web applications secure by finding vulnerabilities. It works by scanning the site, detecting issues like **SQL injection** and **cross-site scripting**, and reporting these vulnerabilities. **VEGA** automates the process of finding security weaknesses, saving time and effort. As an open-source tool, it’s free to use and can be customized to meet specific needs. Overall, **VEGA** helps developers fix security issues before hackers can exploit them.

**Task 1: Project Introduction and Overview of SOW.**

A) Open Google on your terminal, and then find, open, and read the **(SOW) Statement of Work**.![Vega Sat 2](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/259a91bd-882c-44a5-b530-d1143a76c61d) 
![VEGA Sat 3](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/f97b548c-3b7a-4cdd-ba20-e33d579ce5bb)

What is a (SOW) Statement of Work?
**_A (SOW) Statement of Work_** _outlines the project’s scope, objectives, deliverables, and timelines for implementing a web vulnerability scan. This ensures everyone involved understands the project requirements, leading to better planning, execution, and accountability._

**Review the sections of the (SOW) Statement of Work**:

| 1 Introduction | 2 Background | 3 Scope | 4 Tasks, Deliverables, & Schedule |
| --- | --- | --- | --- |
| 5 Reporting and Communication | 6 Work Performance | 7 Acceptance Criteria and Payment |     |

_Conducting a web vulnerability scan without a (SOW) Statement of Work can lead to several potential issues and risks, both legal and operational._

B) From the desktop open **VEGA**
![VEGA Sat 4](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/81cfdee1-6c45-4547-8fa0-f3a4f7e1b75e)![VEGA Sat 5](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/cbf0fc7d-1f0c-4f0f-bcd8-5dc739a095b5)

**Task 2: Overview of VEGA and a vulnerable “test” website.**

![VEGA Sat 6](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/5efa52b2-226f-423f-8fff-d8b481798e90)
A) Click on New Scan > Enter a base **URL (Universal Recourse Locator)** for the scan:

B) Go the (SOW) Statement of Work to get the URL for the web vulnerability scan, i.e., **testphp.vulnweb.com**
![VEGA Sat 7](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/c6edd072-e46d-4ec6-8cd0-010316712e91)

C) Take a moment to **review the different sections** of the **web page**, the scanner will be testing the **entire page**.

| Home | Categories | Artists | Disclaimer |
| --- | --- | --- | --- |
| Your Cart | Guestbook | AJAX Demo | Search Art |
| Signup | Your Profile | Our Guestbook | PHP Scanner |
| PHP Vuln Helper | Fractal Explorer | About Us | Contact Us |

**Task 3: Configure VEGA’s automatic scan with the “test” website.**

A)Copy and paste the URL [**http://testphp.vulnweb.com/**](http://testphp.vulnweb.com/) into the Scan Target and click **Next>**.
![VEGA Sat 8](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/aaa4c666-c9be-454c-adba-aaa6145edde4)

B) **Injection Modules** or **Response Processing Modules** appear.
![VEGA Sat 9](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/20ddf9fe-3e3d-4ca1-9a49-61fc78472dc9)

C) Review the **Injection Modules** that can test the listed vulnerabilities.
![VEGA Sat 10](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/0f28a49f-663c-4d4b-a519-fb3659dd88ba)

🗹Checkmark the vulnerabilities that you want to test for.

\*\*Customize the scan based on the company’s request\*\*

D) The top **10 VEGA Injection Modules** ranked by severity and frequency.

| **VEGA Injection Modules** | **Ranked by severity and frequency** |
| --- | --- |
| 1 SQL Injection | **Malicious SQL code inserted** into queries and can lead to **unauthorized access** to a database. |
| 2 (XSS) Cross-Site Scripting | Detects places where an attacker can i**nject malicious scripts** into web pages viewed by other users. **XXS can steal session cookies, deface websites, or redirect users**. |
| 3 OS Command Injection | Tests for the ability to **execute arbitrary commands on the server’s** operating system. This can give an attacker full **control over the server.** |
| 4 XPath Injection | Checks for **vulnerabilities in the use of XPath queries**, which can be manipulated to access **unauthorized parts of an XML document**. |
| 5 Blind SQL Injection | A variant of SQL injection that **does not directly reveal data** but can still be used to **infer information from the database** by analyzing server responses. |
| 6 (RFI) Remote File Inclusion | Tests for the ability to **include remote files in the server’s execution** context, which can be used to **execute arbitrary code.** |
| 7 (LFI) Local File Inclusion | Detects vulnerabilities that **allow local files to be included in the server’s execution** context, potentially leading to code execution or **information disclosure**. |
| 8 XML Injection | Looks for **weaknesses in XML processing** that could allow attackers to manipulate or disclose data by injecting malicious XML. |
| 9 HTTP Header Injection | Identifies vulnerabilities where an attacker can **inject malicious data into HTTP headers,** which can lead to various attacks, including **XSS and cache poisoning**. |
| 10 Format String Injection | Tests the format string vulnerabilities that could allow an attacker to execute arbitrary code or **cause a program crash by manipulating format string functions.** |

E) Review **Response Processing Modules** that can to test the listed vulnerabilities.
![VEGA Sat 11](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/5f3107d3-3eda-4c8d-bff0-ae42fca6023f)

🗹Checkmark the vulnerabilities that you want to test for.








![VEGA Sat 11](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/3e38124e-424b-4063-b48f-0fbba2ccceef)
![VEGA Sat 9](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/06161b8f-8e0a-4e27-a35e-287f908fd05a)

\*\*Customize the scan based on the company’s request\*\*

F) The top 10 VEGA **Response Processing Modules** ranked by severity and frequency.

| **VEGA Response Processing Modules** | **Ranked by severity and frequency** |
| --- | --- |
| 1 Directory Listing | Detects if **directory listings are enabled**, which can expose the contents of a directory to users. |
| 2 Error Page Detection | Identifies **server error pages** that might **disclose sensitive information** about the server or application. |
| 3 Cross-Domain Policy Check | Checks for **insecure cross-domain policies** that could allow **unauthorized cross-origin** **request**. |
| 4 Version Control Strings | Searches for **version control** information that might be **exposed in HTTP responses,** which can help attackers find specific exploits. |
| 5 File Extension Analyzer | **Analyzes file extensions** in responses to detect potentially **unsafe file types** that should not be served by the web server. |
| 6 Server Banner Disclosure | Looks for **server banners in HTTP headers** that **reveal the software and versions** running on the server, which can be useful for targeted attacks. |
| 7 Information Disclosure | Detects **generic information disclosure vulnerabilities** in the content of HTTP responses, such as **debug information** or **internal paths**. |
| 8 Email Disclosure | Searches for **email addresses** in responses, which can be used for **social engineering** attacks. |
| 9 IP Address Disclosure | **Identifies IP addresses** disclosed in responses, which can be useful for **network** **mapping** and further attacks. |
| 10 HTML Comments | **Analyzes HTML comments** in the response content that **may contain sensitive** **information or clues** about the application’s functionality. |

G) Click on **Finish** to start the scan.
![VEGA Sat 12](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/2cc92385-05f4-44f9-95ee-f05ba047606f)
H) **Scanner Progress** collecting Alerts.
![VEGA Sat 13](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/4732fa5e-7b13-463e-b55c-00339aa22365)
3I) The **VEGA** **Scan Alert Summary** is complete.
![VEGA Sat 14](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/61bcdb9d-b983-4f35-b70f-bc17b072595e)
Observe the **Scan Alerts** section, drill down into items you want to access.

|     |     |     |     |
| --- | --- | --- | --- |

**Task 4: Validate Cross-Site Scripting**

A) Observe High risk classification for the Cross Site Scripting Input Validation Error.
![VEGA Sat 15](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/ba9327b0-4c42-4abe-a301-df3414067e0f)

B) Open the ⏵REQUEST **POST /searchFor=vega’--> “>’>”’ goButton=go\]**
![VEGA Sat 16](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/11689441-e57b-4949-9f48-047ad6c4f85a)

C) When you enter xss into search art in returns searched for: xss onto the web page as a pop-up indicating there may be a vulnerablity.
![VEGA Sat 17](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/6ac65de7-872f-41ed-8177-474655b4ee0c)


D) When you enter <script>alert("xss")</script> into search art in returns a pop-up message indicating a redirection vulnerability.
![VEGA Sat 18](https://github.com/TDCybersecurity/VEGA-Web-Application-Scanner/assets/142702123/60176762-0d47-450d-84a9-1bc6a4b97865)

**DISCUSSION**

(XSS) Cross-site scripting (XSS) is a class of vulnerabilities affecting web applications that can result in security controls implemented I browsers being circumvented. When a browser visits a page on a website, script code originating in the website domain can access and manipulate the (DOM) document object model, a representation of the page and its properties in the browser. Script code from another website cannot.

**IMPACT**

- The precise impact depends greatly on the application
- XSS is generally a threat to web applications which have authenticated users or are otherwise security sensitive.
- Malicious code may be able to manipulate the content of the site, changing its appearance and/or function for another user.
- This includes modifying the behavior of the web application (such as redirecting forms, etc.)
- The code may also be able to perform actions within the application without user knowledge.
- Script code can also obtain and retransmit cookie values if they haven’t been set HTTP only.

**REMEDIATION**

- The developer must identify how the untrustworthy data is being output to the client without adequate filtering.
- There are various language/platform specific techniques for filtering untrustworthy data.
- General rules for preventing XSS can be found in the recommended OWASP XSS Prevention Cheat Sheet (see references).

**REFERENCES**

Some additional links with relevant information published by third parties:

- Cross-Site Scripting **_Wiki_**
- Cross-Site Scripting **_OWASP_**
- XSS Prevention **_Cheat Sheet_**
- Cross-Site Scripting **_WASC_**

A)Enter a random search term

B)Enter a script: **&lt;script&gt;alert(“xss”) &lt;/script&gt;**

C)After clicking on the **go** box, a popup appears:**testphp.vulnweb.com _says xss_**
