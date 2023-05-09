# [DRAFT] Research Plan: 10-10CG facility selection study, 1010 Team, February 2023

**This study will be combined with the end-to-end usability study; refer to that Research Plan/Convo Guide - [Research folder](https://github.com/department-of-veterans-affairs/va.gov-team/tree/master/products/caregivers/research/2023-04-Facilities%20and%20Overall%20Usability%20Research)**


## Background

- [Caregivers Product Outline](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/caregivers/10-10CG%20Caregiver%20application%20product-outline.md)
- [Initiative Outline](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/caregivers/Improve%20Facility%20Selection/Improve%20Facility%20Selection%20-%20Initiative%20Brief.md)

This research is to be conducted on the application for Family Caregiver Benefits (10-10CG) by the 1010 team.

During previous usability studies on this form (research findings: [February 2021](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/caregivers/1010cg-mvp/Usability%20Study-Sign%20as%20Representative-%20February%202021/research-findings.md), [April 2021](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/caregivers/1010cg-mvp/Sign-as-Rep-Round2-Usability-April%202021/research%20findings.md)) we have found the VA medical facility selection page caused many users confusion. A few trends include:
1. Users are confused why the facility they are familiar with isn't listed. (The current dropdown list only includes facilities with a Caregiver support staff and not all possible facilities.)
2. Users are uncertain which facility to specify (Eg. Primary care, therapist, oncologist, most recent, etc.)
3. Users that live on state borders potentially would have to select a different state from where they live in order to find their preferred facility (located in another state).

- [Sketch Wireflow with research notes](https://www.sketch.com/s/5a676881-7aa8-4054-9b6e-34d86ced43d8/a/eK1L73z)

Additional technical and user experience concerns include:
1. The team wants to update and use an upcoming release of the facility API to manage the list of all community and VA locations and include search by zip code and city in additon to state.
2. By including both community and VA health care facilities in the search list, this could potentialy add confusion to the process around where a Caregiver Support Coordinator is located. 
3. The question content needs to be in plain language as well as make the process clear as to how this answer will impact the caregiver and/or Veteran during their application process. 


### OCTO Objectives 

Which [OCTO objectives](https://github.com/department-of-veterans-affairs/va.gov-team/tree/master/strategy#readme) does this research support? 

Goals
- Veterans and their families can apply for all benefits online

**Increase**
- Percent of applications submitted online
- Completion rate of online transactions

**Decrease**
- Time to successful complete and submit online transactions
- Time to process online applications


### Veteran Journey
Where does your product fit into the [Veteran journey](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/platform/design/va-product-journey-maps/Veteran%20Journey%20Map.pdf)?
Are there moments that matter? 

- Taking care of myself
- Putting down roots
- Aging



## Research Goals	

The goals of this user research are to:

1. Determine if the facility question is easily understandable.
2. Determine if the confirmation page add clarity or confusion for the applicant to know how the information provided will be used during the caregiver application process.
3. Determine the accessibility of the facility search and selection process. 

### Outcome

The outcome of this study will help guide this design implementation and future iterations to improve the clarity of the question and selection process, including accessibility testing. 


### Research questions

**Goal 1: Understandable content**
- Is the new version of this question easy to understand and answer with little confusion?
- Does this new version result in clarifying questions or additional information needed to complete? 

**Goal 2: Clear how this is used in caregiver application process**
- Is the new version easy for the participant to understand why they are selecting a facility and how it impacts the caregiver application process?
- Does the confirmation screen after selection add any additional confusion or result in clarifying questions?

**Goal 3: Search and selection of facilities**
- Are users able to navigate through the facility selection without difficulty?
- Do they know what to input in the text search field?
- Can users easily use the search input and understand what choices are populated from that search?
- Is it clear how to reselect a facility if one is selected in error?
- How do screen reader participants respond to the confirmation pages?


### Hypothesis

**Hyphotesis 1**
- Our hypothesis is that users will understand what they are selecting and how that impacts the caregiver applicaiton process and find the confirmation page to be helpful and informative. 


**Hyphotesis 2**
- Our hypothesis is that users will be able to navigate through the facility selection relatively easily, but may have issues with the following:
- The amount of results shown
- Desire to filter results and how
- Not recognizing the name of the facility they are looking for
- Understanding the difference between community and VA facilities/Caregiver Support Facilities




## Methodology	

**Moderated usability task analysis*

This will be a focused study on only the facility question(s) that is part of the caregiver application. The goal is to understand the usability impact to content, location search and selection, and confirmation messaging.  


### Location

A remote task-based usability study will be conducted remotely with Zoom using the Perigean contract. 



### Research materials
- [Conversation Guide](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/caregivers/Improve%20Facility%20Selection/Research/conversation-guide.md)

- Designs: 



> - Testing: Will be using the [staging environment](https://staging.va.gov/family-member-benefits/apply-for-caregiver-assistance-form-10-10cg/introduction) for this study.


## Recruitment	

For these remote moderated studies with Veterans and caregivers, we will be using Perigean to recruit participants.


### Recruitment approach

Our intended audience for this research is a mix of Veteran's and caregivers. 



### Recruitment criteria

|Total requested|Completed sessions|Veterans|Family Member|Caregivers|Service Members|
|:-------------:|:----------------:|:------:|:-----------:|:--------:|:-------------:|
|      15       |            10    |4       |  1          |   5      |               | 


**Primary criteria (must-haves)**

- Participants must be able to use Zoom, locate and use the chat function in Zoom, and to share their screen through Zoom
- At least 3 people over the age of 55
- At least 3 people with cognitive disability
- At least 4 people who plan to use their mobile device for the session
- At least 3 people who plan to use screen reader assistive technology for the session


**Secondary criteria (nice-to-haves)**
Participant pool should in diverse in:
- Branch of service
- Gender (35% or more women)
- Disability rating of 50% or higher representative of applicant demographics
- Education
- Race
- Geography
- Density (rural)


### Screener questions


**For recruiting 3 screen reader users**
- Do you need to use assistive technology to use the internet such as VoiceOver on an Apple device, TalkBack on an Android device, or JAWS on a computer? (Proceed to question 3a if yes, if no, disqualify)

3a. Are you able to join the Zoom session using this assistive technology? (Answer should be yes to satisfy criteria for screen reader)



**For recuriting 4 mobile users**

- Are you able to join the Zoom session from a smart phone such as a Samsung Galaxy or Apple iPhone? Any kind of smart phone will work, as long as it connects to the internet. (Answer should be yes to satisfy criteria for 4 mobile users)







## Timeline
Please submit artifacts for [Research Review](https://depo-platform-documentation.scrollhelp.site/collaboration-cycle/Research-review.1781891143.html) 8-9 days prior to the first planned research day for remote studies so Perigean can begin recruiting one week prior. Perigean requires 2+ weeks for in-person. 



### Prepare
When will the thing you are testing be finalized? Ideally it's ready a week before testing begins and has also been through a [Midpoint review](https://depo-platform-documentation.scrollhelp.site/collaboration-cycle/Midpoint-review.1781039167.html).



A pilot session is required. Please indicate the date and name of a mock participant for a pilot session. 
* Pilot participant email:
* Date and time of pilot session: 


### Research sessions
* Planned dates of research:




### Length of sessions
* Session length: 45 minutes
* Buffer time between sessions: 60 minutes
* Maximum Sessions per day: 4


### Availability
	
Team Availability | Time (EST)
------------------|--------------
TBD      | TBD EST
TBD       | TBD EST





## Team Roles	
- Moderator: Jessica Stump (jessica.stump@adhocteam.us) 
- Research guide writing and task development: Moderator	
- Participant recruiting & screening: Perigean
- Project point of contact: Moderator
- Participant(s) for pilot test: 
- Note-takers: Perigean, 1010 Team
- Observers: Heather Justice (heather.justice@adhocteam.us), Matt Long (matt.long@adhocteam.us), Lihan Li (lihan@adhocteam.us), David Kennedy (david.kennedy@adhocteam.us), Erin Flaherty (erin.flaherty@adhocteam.us) 


> **List email addresses for those who should attend and observe the sessions: VA Stakeholders, engineering team members, design team members, any other people who might find this research relevant to their work.** Spread observers across sessions so that there are no more than 5-6 total attendees (moderator, notetaker(s), observer(s)) per session on the VA side 



## Resources	
- [Project Initiative Brief](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/caregivers/Improve%20Facility%20Selection/Improve%20Facility%20Selection%20-%20Initiative%20Brief.md)
- [Conversation Guide](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/caregivers/Improve%20Facility%20Selection/Research/conversation-guide.md)
- Design drafts: [Sketch](https://www.sketch.com/s/5a676881-7aa8-4054-9b6e-34d86ced43d8/p/D741171D-81BD-4CEF-A7A2-69A548C8D346)
- Synthesis: TBD
- Research Findings: TBD
