# Sprint goals for Benefits Disability Experience Team 

## Sprint 5
Period - 05/10/2023 - 05/23/2023
### Sprint goals TBD
- **Expedited**
   - [ ] Self-Assessment Part A to BDD 526 claims - staging review and contact center review
   - [ ] Bug - Fix - BDD flow asking for past service exit date
   - [ ] Bug - Fix - Identification issue - Update phone number on 526-EZ alert
   - [ ] Bug - Discovery - priority #2
- **Non-negotiable**
   - eVSS to Lighthouse Migration 
        - rated disailities endpoint
            - [ ] Retrieve ICN  
            - [ ] Ticket for using ICN and testing?
        - Intent to File endpoint 
            - [ ] Continue migration - Implement calls for GET and POST
            - [ ] Integration testing with LH in dev, sandbox and staging environments 
        - BRD
            - [ ] Discovery - Whether EVSS is used in DisabilityCompensationFormsController (BRD)
        - Submit - too many endpoints at the same time?
            - [ ] Discovery - Whether EVSS is used in DisabilityCompensationFormsController (BRD)
- **Features**
   - Landing page changes and 526ez current with paper form
      - [ ] Design and Content changes - Intro page
      - [ ] Accessible prototype for the Intro page
      - [ ] Research plan and screener for landing pages
   - [ ] Analytics
      - [ ] Understanding calculations behind current DOMO metrics
      - [ ] Survey Feedback Data Analysis - Part 2
 
## Sprint 4
Period - 04/26/2023 - 05/09/2023
### Sprint goals TBD
- **Expedited**
   - [ ] Implement content and design changes for adding Self-Assessment Part A to BDD 526 claims - pending content review 
   - [ ] Bug - BDD flow asking for past service exit date - Discovery for the scale of the issue and cause/fix proposal
- **Non-negotiable**
   - eVSS to Lighthouse Migration 
        - rated disailities endpoint
            - [ ] Get our Veteran Verification API credentials pushed to the higher environment and test
            - [ ] Integration testing with LH in dev, sandbox and staging environments for rateddisabilities
            - [ ] Swap out evss call at Form526RapidReadyForDecisionConcern#disabilities_not_service_connected
        - Intent to File endpoint 
            - [ ] Continue migration - Implement calls for GET and POST
        - BRD
            - [ ] Continue discovery for PCIU Address Service 
- **Features**
   - Landing page changes and 526ez current with paper form
      - [ ] Design and Content changes - Intro page
      - [ ] Accessible prototype for the Intro page
      - [ ] Research plan and screener for landing pages
   - [ ] Analytics
      - [ ] Understanding calculations behind current DOMO metrics
      - [ ] Survey Feedback Data Analysis - Part 2
 
## Sprint 3
Period - 04/12/2023 - 04/25/2023
### Sprint goals
- **Expedited**
   - [ ] Implement content and design changes for adding Self-Assessment Part A to BDD 526 claims
- **Non-negotiable**
   - eVSS to Lighthouse Migration 
        - rated disailities endpoint
            - Get our Veteran Verification API credentials pushed to the higher environment
        - Intent to File endpoint 
            - [ ] Start migration - Abstract provider calls for GET and POST
        - 526 submit workflow 
            - [ ] Technical discovery for any other endpoint not yet identified
- **Features**
   - Error messaging/validation 
      - [ ] Complete Discovery
   - 526ez current with paper form
      - [ ] Design and Content changes for items not requiring research
   - Landing page changes
      - [ ] Review of existing content research
      - [ ] Design and Content changes - start
      - Content and Design for landing page (Is this the form I need?)
   - [ ] Analytics
      - [ ] Understanding Key metric calculations
         - [ ] Number of sessions to complete
         - [ ] Satisfaction ratings
         - [ ] Others identified as useful metric for our goals

## Sprint 2
Period - 03/29/2023 - 04/11/2023
### Sprint goals
- Expedited
   - [x] Discovery and iterative plan for adding Self-Assessment Part A to BDD 526 claims
- Non-negotiable
   - React component deprecation 
        - [x] Technical Discovery for a migration plan 
   - eVSS to Lighthouse Migration 
        - BRD endpoint -> **pulled back from sprint as Cole is OOO**
            - [ ] Technical Discovery - Relationship between PCIU Address and BRD
            - [ ] Continue migration work 
        - rated disailities endpoint
             - [ ] Continue migration work  
            - Successfully code complete to the best of our knowledge
            - New ticket for testing in sandbox, staging and prod
            - Working on getting credentials for the other environments - dependency on platform team
            - Issues with LH 
        - Intent to File endpoint 
            - [x] Technical Discovery 
            - Discovery complete
            - Identified 2 calls to evss, requires 2 new migration tickets
        - [x] Common API Migration
            - [x] Technical Discovery 
            - No migration work required for 526ez flow
 - Features 
   - [x] Synthesis of call center feedback submitting claims using for 526ez form
      - Over 700 responses
      - Reviewed introduction and start page comments - about 400 responses
      - Identification error - 
         - 68 users when starting the form
         - some users saw it close to ITF expiry team
         - Created a ticket for discovery for this error
   - [ ] Discovery for error messaging/validation
      - Needs to continue into the next sprint
   - [x] Epic-stories breakdown for prioritized ideas
      - Started entering stories in the product backlog
      - Enough epics / tickets created to start a roadmap draft 
      - This will be work in progress 

## Sprint 1
Period - 03/15/2023 - 03/28/2023
### Sprint goals
- [ ] Engineering work
   - [x] Technical discovery on the future date of claim bug
         - Did not find a root cause in 526 flow
         - Identified a validation flow that would prevent future exit dates being sent for veterans
         - Need a write-up for stakeholders
   - [x] Pull a report for recent validation errors
   - [ ] rated disabilities endpoint migration
   - [x] start work on BRD endpoint migration to Lighthouse
 - [ ] Research Discovery
   - [ ] Work with stakeholders/product/team to and 
      - [x] Priortize ideas
      - [ ] Add them as user stories in the product backlog 
          -  Moved to sprint 2 as prioritization was completed by end of sprint    
   - [x] Analyze low ratings on 526 form from Domo dashboard
         -  Captured analytics not relevant to 526ez form
   - [x] Seek written responses to survery on 526ez form
         -  Got Medallia written response data from the contact center in an excel worksheet
   - [x] Start discovery on making 526ez and ancillary forms on va.gov current with paper version of the form
         -  Notes about locations that need changes
         -  Recommendations on which ancillary forms to keep in 526 flow based on discussions with IA and Forms Digitization
- [ ] Work taken on mid-work
   - [x] Front-end bug where an icon was hiding some text - Spacing/css broken on an icon
   
## Sprint 0
Period - 03/01/2023 - 03/14/2023
### Sprint goals
- [x] Complete sprint team norming and draft agreements on
   - [x] Cadence for scrum ceremonies 
   - [x] What to include/exclude for each ceremony
   - [x] Relative sizing estimates
   - [x] Definition of Ready(DoR) and Definition of Done(DoD)
   - [x] Team communication norms
   - [Team norms mural board link](https://app.mural.co/t/agilesixapplications0942/m/agilesixapplications0942/1676581509383/4d94293dcf22719dc7ba6267740466fb2f172c93?sender=u1dc3a1dc47390e0b38d61593)
- [ ] Engineering work
   - [x] Complete spike for common framework for eVSS endpoint migration with the following outcome <br>
         - Working software that can be used to implement a single endpoint migration <br>
    - [x] Identify what else is needed for endpoint migration framework <br>
    - [ ] Starting technical discovery on the date of claim bug <br>
          -  Not started 
          -  EKS migration effort was discovered mid-sprint and took priority over working on this issue
    - [ ] Do we think we have capacity/time to take on the rated disabilities endpoint migration? <br>
          -  Was a stretch goal and not pulled in
    - [x] Work taken on mid-sprint  <br>
          - EKS Migration endpoint testing in staging  <br>
 - [ ] Research Discovery
   - [x] Identify ideas for improvement for core submission as identified by existing research 
   - [x] Research around 526 form validation problem <br>
         - Researched top 5 errors based on # of occurances  <br>
         - Identified potential causes of errors and whether they are in this team's control for remediation <br>
         - Will require current data pull to understand what error types are still an issue <br>
         - Will need tickets for researching/fixing individual error types based on the new report <br>
   - [ ] Work with product/team to priortize these ideas and break them down for future work <br>
         - Not started  <br>
         - Blocker - not able to meet with PO and stakeholders to review  <br>
   - [ ] Get the ideas as user stories in the product backlog  <br>
         - Not started  <br>
         - Dependency - Review ideas from reserach dicsovery with PO and stakeholders  <br>
   - [ ] Do we think we have time/capacity to start looking at what we need from analytics?  <br>
         - Did not pull in this work 
