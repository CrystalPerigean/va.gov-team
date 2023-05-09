# Project outline: Migrate direct deposit for comp & pen from EVSS > Lighthouse

**Last Updated: March 23, 2023**

### Communications

- **Github labels**: vsa-authenticated-exp; profile; direct-deposit
- **Slack channel**: [#accountexp-authexp](https://dsva.slack.com/channels/accountexp-authexp); [#vfs-evss-service-migration](https://dsva.slack.com/channels/vfs-evss-service-migration)

### Roles  
  
[This is managed by the VA.gov profile team](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/profile/README.md#roles).

#### Lighthouse team

|Name|Role|Email|
|----|----|-----|
|Lee Helmer| Lead on the entire EVSS > Lighthouse effort| lee.helmer@adhocteam.us|
|Lorri Glover | Involved with the direct deposit migration|glover_Lorri@bah.com|
|Greg Feliberty |Involved with the direct deposit migration|feliberty_gregory@bah.com|
|Andrew Ramos | Involved with the direct deposit migration| ramos_andrew@bah.com|
|Dana Harris | Involved with the direct deposit migration|dana.harris@adhocteam.us|

### Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Goals](#goals)
- [User Outcomes](#user-outcomes)
- [Business Outcomes](#business-outcomes)
- [Measuring Success](#measuring-success)
- [Key deliverables](#key-deliverables)
- [Key dates](#key-dates)
- [Backend](#backend)

## Overview

EVSS -- the VA backend that stores direct deposit for comp & pen, disability ratings, and more -- is being retired in favor of the Lighthouse platform. Lighthouse has been working hard to migrate data from EVSS to their platform, and they have successfully done so with direct deposit for comp & pen information. This means that we need to reintegrate the VA.gov profile to point to Lighthouse instead of EVSS.

## Problem Statement

As a person that receives payments from VA, I want to be able to easily view and update my direct deposit information.

## Goals

- Migrate from EVSS to Lighthouse without any disruptions in service for veterans and other users.
- See improvements in direct deposit save success rates, which are only about 90% currently.

## User outcomes

### Desired User Outcomes

- Users see no interruptions in service or issues with updating their direct deposit for comp & pen info as this migration happens.

### Undesired User Outcomes

- Users have additional issues or blockers in updating their direct deposit for comp & pen information.

## Business outcomes

### Desired Business Outcomes

- Direct deposit works seamlessly with no interruption.
- We are one step closer to retiring EVSS.

### Undesired Business Outcomes

- There are disruptions or issues as a result of the migration from EVSS > Lighthouse.

## Measuring success

**Objective 1: Improve save success rates by migrating to Lighthouse**.

|Save success rate 1 month pre-launch [dates]|Save success rate 1 month post-launch to 100% of users [dates]|Save success rate 2 months post-launch to 100% of users [dates]|
|------|------|-----|
|TBD|TBD|TBD|

## Key deliverables

|Deliverable|Date completed|
|-----------|--------------|
|[Project epic: #51900](https://app.zenhub.com/workspaces/vft-59c95ae5fda7577a9b3184f8/issues/gh/department-of-veterans-affairs/va.gov-team/51900)| N/A|
|[QA spreadsheet](https://docs.google.com/spreadsheets/d/12gvlkGnwt206BBYY89gDIYG1AtD6j9uCYMr5x99Nzns/edit#gid=0)| TBD|
|UAT results|TBD|
|Release plan|TBD|

## Key dates

- Early 2022: Support Lighthouse's discovery
- December 2022: Lighthouse is ready for us to begin integration
- January 2023: Profile team begins discovery
- February 2023: Backend migration
- March 2023: Backend migration continues; FE + BE updates; QA planning
- April 2023: QA & Pre-launch activities
- May 2023: On hold while Samara is on maternity leave
- June 2023: On hold while Samara is on maternity leave
- July 2023: Launch

## Backend

- We need to request OAuth credentials to sandbox. We'll also need production credentials.

### Documentation

- [Developer.va.gov documents](https://developer.va.gov/explore/benefits/docs/direct-deposit-management?version=current)
- [Request Sandbox Access](https://developer.va.gov/onboarding/request-sandbox-access)
- [Max.gov API docs](https://community.max.gov/pages/viewpage.action?pageId=2286748585)

### How to test

- [Sandbox Test Accounts for Direct Deposit Management API](https://github.com/department-of-veterans-affairs/vets-api-clients/blob/master/test_accounts/direct_deposit_test_accounts.md)
