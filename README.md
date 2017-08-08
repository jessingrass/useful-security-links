<h1> Useful Security Links </h1>
<p>A page of useful links for those starting security testing, as well as a basic method for beginning to implement some security processes in your company
I have used all open-source tools, and they are licensed under the Creative Commons license, which you will see when you navigate to the links. </p>


<h2> Structuring The Process </h2>
<p>I started with looking at existing models for implementing a security system from the ground up. Caveat: a professional security scan should be a part of every business model!
However, if you are not able to do the scan, or want to improve accountability, then it is not a bad idea, in my opinion, to investigate the structures and tools
to build out internal security</p>

<h3> OWASP <a href=https://www.owasp.org/index.php/OWASP_SAMM_Project> OpenSAMM </a></h3>
<p> The OpenSAMM project offers a method of introducing security into the development practice from the ground up. If you are just interested in running scans on the product,
it is not likely something you'll care about. However, if you want to develop a strategy for building more robust security into the product, then you will
find a huge amount of help and inspiration in this document. The document separates implementation into four categories. Each category has three levels. You can use
those levels to identify where your company sits in terms of strategy, and evaluate next steps. I found that using this document as a framework
to choose tools and methodologies was a great help</p>

<h2> What to Analyze? </h2>
<p> Once you decide you should have security, the huge question of what you should do looms large. I recommend looking to <a href=https://www.owasp.org/index.php/Main_Page>OWASP</a> 
-- there are so many tools available and it is worth taking the time to research and decide what fits your organization. Since OWASP is tool agnositc
and open source, it is easy to implement flexibly. In deciding what to analyze and how, I took the following documents:
<br><a href= https://www.owasp.org/index.php/OWASP_Testing_Project> OWASP Testing Project v.4</a>
<br><a href= https://www.owasp.org/index.php/Category:OWASP_Application_Security_Verification_Standard_Project> OWASP Application Security Verification Standard Project </a>
<br><a href= https://www.owasp.org/index.php/OWASP_Secure_Coding_Practices_-_Quick_Reference_Guide> OWASP Secure Coding Practice Quick Reference </a>

The Testing Project offers a thorough plan with checklists and examples of the kinds of tests and responses one would expect to see as they are 
testing their application. The Application Security Verification Standard is more specific, an effort by the OWASP community to create standards for 
secure application development and security testing of applications. Three levels are highlighted, along with the standards that a product
must meet in order to be considered at level 1, 2, or 3. The aim is to have security practices at level 3, but the guide can help 
security testers and product managers who are implementing security practices from the ground up to have a scope and sequence for their work.

The Secure Coding Quick Reference provides a really nice checklist that gets to the main point. Using the checklist is a quick way to evaluate present
concerns, needs, current practices, and potential future practices. </p>

<h2> Tools to Test - Manual and Automated </h2>
<p> Once you have figured out the strategy to building security that you need in your company, and have figured out what pieces of your application
you want to evaluate, implementing test strategy and plans is then helpful, as the effort can be targeted. For the testing effort, it really depends
on what you want to implement, and how far down the rabbit hole you decide to go. The tools I have chosen are helpful for guiding vulnerability assessments,
internal penetration testing efforts, and automated daily security scans.
<br>
<a href=https://www.owasp.org/index.php/OWASP_OWTF> OWASP Offensive Web Testing Framework</a>
<br>
<a href=https://www.owasp.org/index.php/ZAP> OWASP ZAP </a>

The Offensive Web Testing Framework (OWTF) is designed to run with Kali Linux while penetration tests are being conducted. The tool aids testers
in keeping track of data, and developing reports from automated data collection. There are some good youtube videos about implementing the OWTF
framework during penetration testing. 

ZAP Proxy is a tool that can be used in penetration testing, but can also be run in passive mode so that it can be automated for non-intrusive, 
automated scans of the product. I have seen youtube tutorials about automating ZAP using selenium, as well as cucumber/BDD. I can post links and
videos if interest is indicated.

Hope this is helpful! This is not intended to be all-inclusive. Rather, I hope to provide a basic outline of resources as well as a sort of 
"orderly approach", since there are so many resources. Soon I will post all of the resources I have found in a list, but I wanted to get this started for now.
If you have resources, issues, etc., send a PR my way. Thanks. </p>





