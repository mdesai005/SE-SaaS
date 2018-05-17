# Solution Engineering SaaS Interviews

***Note:*** This document is best viewed by clicking on this [github.io link](https://mdesai005.github.io/SE-SaaS/articles/solution-engineering-SaaS/index.html)

***If you are currently interviewing and using Oracle provided Cloud accounts - Please READ the updated "Guidelines for Oracle Cloud Account Usage" section below***

## The Role
Solutions Engineering is more BREADTH than depth. You take the products that have already been built - extend them with your coding skills and integrate them with other products thereby building a “SOLUTION”. **This is primarily a technical job** with client interactions and we are looking for good communications and potential business acumen as well. We are a "CUSTOMER FACING" organization.

For a successful solution engineer - you need the following traits
* Strong technical skills
* Good communication skills - you don’t build solutions for yourself -you build them for customers and the REAL world!
* Desire to push yourself to understand a little of lot of things (you may touch upon Machine Learning, Analytics and at the same time core database or non-technical skill like project management).  This is probably the most critical -do you have the drive and motivation to learn a lot!!
* Ability to work under tight deadlines - our projects can be 2-6-week bursts and most of them are directly driven by our customers' desire to see some capability in Oracle Cloud.
* Desire to collaborate and innovate to create solutions.

## Interview Schedule

The face-to-face interview process is a technical interview outlined below:

## Technical Presentation and Demo - up to 45 minutes

| Interview Section | Minutes | Description |
| --- | --- | --- |
| Overview | 3 - 5 | Brief overview of yourself, covering your capabilities and technical experience |
| Journey to Cloud Presentation | 15 | Brief overview of Oracle's cloud platform to a potential customer that is interested in making the journey to the cloud |
| Tech Deep dive - Oracle Cloud Demo (HIGHLY PREFERRED) or Project Highlight | 15 | Brief demo on Oracle Cloud Product(s) of interest using the account that has been provided by your recruiter OR Overview of a development project on which you have recently worked |  
| Technical Q & A Interview | 10 | Technical Question and Answer Interview - Expect to be asked about projects where you were a MAJOR contributor |

## Overview

During this presentation, we ask that you provide a brief overview of yourself, including your technical experience and skills. It's not necessary to go into detail, as we will ask more questions during the **Technical Question and Answer Interview** section of the interview.

## Journey to Cloud: Presentation

The scenario for the presentation is one where you need to present a technical/business overview of Oracle’s cloud platform to a potential customer that is interested in making the journey to the cloud. The customer audience consists of technical and business level attendees. This customer is interested in moving to the cloud but is not sure whether it makes sense and whether Oracle is the right vendor.  It is important to address both the business value and the technical value of the proposed solution.

This **presentation** should be no longer than <u>**15 minutes**</u> and can be based on the content found in the links provided below.A [Powerpoint deck is available at this link](FY18_Candidate_Cloud_SaaS_Presentation.pptx). You do not have to use this specific presentation so feel free to customize it.  We suggest that you use your own words in presenting the slides.

Key focus areas:
- Expect the audience to ask for clarification on any content you show and actively INTERRUPT
- Make sure you know the differences between DaaS, SaaS, PaaS and IaaS.
- Do NOT read out of your notes!.  

Below are some links to study Oracle’s cloud platform, yet feel free to use other resources as well:

- [http://Oracle.com/cloud](http://Oracle.com/cloud)
- [https://www.oracle.com/cloud/cloud-summary.html](https://www.oracle.com/cloud/cloud-summary.html)
- [https://www.oracle.com/applications/customer-experience/data-cloud/solutions/data-as-a-service/index.html](https://www.oracle.com/applications/customer-experience/data-cloud/solutions/data-as-a-service/index.html)
- [https://www.oracle.com/cloud/saas.html](https://www.oracle.com/cloud/saas.html)
- [https://www.oracle.com/cloud/paas.html](https://www.oracle.com/cloud/paas.html)
- [https://www.oracle.com/cloud/iaas.html](https://www.oracle.com/cloud/iaas.html)


## Touch the Cloud: Oracle Cloud Research and Demo

![Touch The Cloud](./images/Touch-the-Cloud.jpg)

In this section of the interview, you will select **a single option** from the 2 options below. **Remember: You only have 15 Minutes!**

### **Option 1: Demo Using Oracle Cloud Account (Preferred)**

Please use the Oracle cloud account provided by your recruiting coordinator.

**Expectation:**

We expect that you have made a sincere effort in using the cloud service(s) that you select to do the following:

- Show your capability to learn Oracle’s cloud services
- Provide us with critical feedback if there were roadblocks.
- Build out a simple solution/product/project leveraging one or more Oracle Cloud services.  While we would like to see a finished product (even if it is simple), we are more interested in your approach to building things out.

**Cloud Services Suggestions  (Feel free to try more than one if you have time):**

- Use an IAAS compute instance (we welcome OS variants -Windows or Linux) and may be MySQL instance to create a 3 or 2-tier web app.  
- Look at data sets from Kaggle or other areas in public domain, leveraging REST APIs from popular non-Oracle cloud services (Maps, Twitter, Instagram, Dropbox, Box etc).  
- Use any programming language of your choice while coding. Python, Java, Node.js, React.js, i.e. anything that you are comfortable with -  doesn’t matter to us.
-  Use Oracle Analytics Cloud and create visualizations
- It's always good practice to create a quick video of your work -just in case you run into issues.
- To net this OUT - Even if you are unable to get something deployed in our Cloud -we will look for EFFORT here OVER showcasing a PROJECT

**Guidelines for Oracle Cloud Account usage:**

- Do not use total of more than 3 OCPU'S and 400 GB of storage.
- Do NOT get yourself LOCKED OUT!. We get a LOT of emails for this issue - you likely have typed in the password correctly. If you do get locked out - use  user "lisa.jones" to login back again.  
- You only need 1 OCPU for each PaaS service.
- Use **cloud.admin** user instead of **lisa.jones** if you are planning to provision compute instance @ OCI (Oracle Cloud Infrastructure).
- Do NOT use Oracle IOT Cloud service or Big Data Cloud Service or Mobile Cloud Service as you will easily run out of CPU counts allocated to the environment.
- If you do get locked out of your account (happens on you entering incorrect password 3 times in succession), use lisa.jones !. You can also change password to your choice once you login for the first time!.
- If you are running into any technical issues, Please reach out to recruiting team ONLY after you search online!.
- Are you seeing an Overage issue message?. Likely you are running too many OCPUs (see the note about 3 OCPUs and storage). Stop things that you don't need and delete those instances. If you run into Overage issues and gets suspended, delete instances and wait for at least 4 hours for the account to unlock.
- Pay attention to service dependencies. For example:- You can't run an Analytics cloud without running a DB instance. And you need to remember what you did for setting up the DB instance (as you provide that password not us)

**Oracle Cloud Login Instructions**
- Go to https://cloud.oracle.com/en_US/sign-in
- Enter Cloud Account Name provided by recruiter @ Cloud Account Name box
- Click on My Services.
- Login with provided credentials.

### **Option 2: Recent Project Presentation**
If you are planning to present your project it will NOT be equally weighted as what you do with Oracle Cloud. Please keep that in mind when selecting the project as we are suggesting it only as a secondary preference. If you use powerpoint to start, please keep your presentation to approximately 3 Slides.
**Guidelines for Project walkthrough**
- How did you get involved in this project (We prefer individual project OR a team project that is not coursework related)
- How big was the team (if there was one)
- What is your specific role and contribution ( For example: I coded front-end and collected requirements for project OR I coded some piece of the front-end) We are looking for "I" not "WE"
- Walk through the code ( whatever the code may be - this could be methods you may have written, or if you used R-Studio -show us what you did in R)
	- Any libraries you used or didn’t use
	- Any coding challenges
	- Was any DevOps process used (this is more likely for internships)
	- Is there a GitHub that we can look at this code

## Technical Question and Answer Interview

During this section of the interview we will ask technical questions based on your experience and our requirements of the Solution Engineering position. We hope to gain a better understanding of your development expertise, your understanding of development methodologies, and your experience with various programming languages and open source tools and frameworks.

## Visual Aids

- The interview room will be furnished with a whiteboard and laptop that you can use to present your **Journey to Cloud** and **Touch the Cloud** Presentations.
- Oracle Supplied Laptop: We will have a laptop and projector available for your use. The laptop will have connectivity to the internet, and you can bring a USB drive if you desire to load a presentation to the laptop.
