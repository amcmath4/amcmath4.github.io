# Welcome to our Fall 2021 IT Capstone Project!
## What was this project?
The IT Capstone Project is a class assigned to senior IT students at Kennesaw State University that is designed to apply their skills to real-world applications. In the case of our project we were assigned to build a small business web server, secure it with open-source software, and to attempt to infiltrate the servers of other teams assigned to the project.
\
\
Our class was instructed by Dr. Ying Xie, and our project sponsor was Dr. Lei Li.
## Who was involved in the project?
Here are the team members that formed our group:
  - Eric Whang
  - Mark Schuler
  - Daniel McDuffie
  - Ryan Smith
  - Samuel Olubummo
  - Alexander McMath

## What was done in the project?
### Milestone 1
Before we began building our server we were first tasked to formulate a project plan outlining the group member roles and final deliverables along with a Gantt Chart detailing the finalization dates and assignments of various project tasks. With those plans set and approved we moved to creating the web server itself. For this we constructed a web server on Red Hat Enterprise Linux, installed OpenCart, designed a website layout, built it with WordPress, and finally launched it with a provided IP address. All the progress up to this point was presented to the project sponsors in our Milestone 1 Presentation.
### Milestone 2
Following our presentation we were approved to move on toward securing the server. Our first step in that was to perform a risk analysis based on our fictional business' perspective, identifying assets to prioritize, threats, vulnerabilities, and ultimately sources of risk along with suggested controls. Past that came research into which open-source tools would be the best fit for our server while mitigating the identified risks. After discussing and deciding between the best options we decided to secure the server with RHEL's built-in Firewalld service, the OSSEC HIDS, and various WordPress plugins. After successfully installing and configuring these measures we reported on our progress again in our Milestone 2 Presentation.
### Milestone 3
Following that milestone all project groups were assigned other project servers to attempt to infiltrate. We gathered a variety of open-source penetration testing tools such as Nmap, Wpscan, John the Ripper, and DirBuster to test the opponent's website, but we were ultimately able to infiltrate our assigned server via a spear-phishing technique, at which point we were able to gain administrative access and establish a backdoor to the server. The process of our attack was documented in a vulnerability assessment write-up. In terms of our server we only saw one attempt on our server's defenses that was unsuccessful and logged, and we saw no signs of being breached. All the progress in this step was detailed in our Milestone 3 Presentation.
### Finalization
After that milestone the establishment, defending, and attacking phases of the project were complete, with mostly project reporting and presenting remaining. We began compiling our final project package, constructed a final report, created our IAB Presentation, created this website, and were selected to present at KSU's C-Day event. The completion of these tasks marked the completion of our Capstone Project. All the files referred to in this write-up are available through the links below.
## Project Files
- [GitHub Main Page](https://github.com/amcmath4/amcmath4.github.io)
- [Project Plan](https://github.com/amcmath4/amcmath4.github.io/blob/main/Project%20Plan%20-%20Security%20Solution%20for%20a%20Small%20Business.docx)
- [Gantt Chart](https://github.com/amcmath4/amcmath4.github.io/blob/main/Project7-GanttChart_Final.xlsx)
- [Milestone 1 PowerPoint](https://github.com/amcmath4/amcmath4.github.io/blob/main/Project7-Milestone1.pptx)
- [Project Risk Analysis](https://github.com/amcmath4/amcmath4.github.io/blob/main/Project7-Milestone2-Risk_Analysis.docx)
- [Project Security Suggestions](https://github.com/amcmath4/amcmath4.github.io/blob/main/Project7-Milestone2-Security_Suggestions.docx)
- [Milestone 2 PowerPoint](https://github.com/amcmath4/amcmath4.github.io/blob/main/Project7-Milestone2.pptx)
- [Vulnerability Assessment](https://github.com/amcmath4/amcmath4.github.io/blob/main/Project7-VulnerabilityAssessment.docx)
- [Milestone 3 PowerPoint](https://github.com/amcmath4/amcmath4.github.io/blob/main/Project7-Milestone3.pptx)
- [IAB Presentation](https://www.youtube.com/watch?v=Kw3uyeB7ChM)
