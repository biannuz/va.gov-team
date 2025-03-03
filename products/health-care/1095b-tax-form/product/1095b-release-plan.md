# 1095-B Release Plan
---

## Phase I: moderated production testing (also known as User Acceptance Testing, or UAT)

### Planning:
-Product will be launched April 1 (pending legal review) but will not be announced to Veterans or linked to from other VA.gov pages yet
- Desired date range or test duration: 3/21/22 to 3/23/22 
- Desired number of users: 3-5
- How you'll recruit the right production test users: Currently in contact with HEC
- How you'll conduct the testing: Through HEC UAT process
- How you'll give the test users access to the product in production w/o making it live on VA.gov: TBD

### Results:
- Number of users: x
- Number of bugs identified / fixed: x/x
- Was the data submitted (if any) easy for VA to process?: yes/no, lorem ipsum
- Types of errors logged: lorem ipsum
- Any UX changes necessary based on the logs, or feedback on user challenges, or VA challenges? yes/no 
- If yes, what: lorem ipsum

## Phase II: Staged Rollout (also known as unmoderated production testing)

### Do I need a staged rollout?

**Yes**, a staged rollout is required unless you can confidently answer "yes" to all of the following:

* This change does not add substantial new functionality to VA.gov
* This change does not impact user flows through tasks
* This change does not affect traffic to backend services

*Example*: a change to a page's text content **could skip** staged rollout

*Example*: a minor visual redesign to a page that doesn't affect user flows **could skip** staged rollout

*Example*: adding a new field to an existing form **could skip** staged rollout

*Example*: a new feature on an existing application that creates new backend traffic **needs staged rollout**

*Example*: a significant change to how users navigate an existing form **needs staged rollout**

*Example*: a feature that will route significantly more users (and therefore more backend traffic) to an existing application **needs staged rollout**

#### Exceptions

Right now, [feature toggles](https://department-of-veterans-affairs.github.io/veteran-facing-services-tools/platform/tools/feature-toggles/) are the primary tool VSP provides for facilitating staged rollout. If feature toggles don't work for your use case, you can request an exception from staged rollout in Staging Review.

| Feature type | Possible with feature toggles? |
| --- | --- |
| New feature in existing application | Yes |
| New application | Yes |
| Static content changes | Doable but tricky |
| URL redirects | No |

Other exceptions to this requirement can be approved by DEPO VSP leads.

### Planning
- As the 2023 tax season preparations ramp up, we will begin to broadcast the digitized form now being available
- Desired date range: October - December 2022 (TBC with Business Owner)
- How will you make the product available in production while limiting the number of users who can find/access it: TBD
- What metrics-based criteria will you look at before advancing rollout to the next stage ("success criteria")?: \[use your KPIs to help guide this. It could be things like _abandonment rate < 20%_, _reported contact center calls < 2 calls_, _error rate < 5%_, etc.\]
- Links to dashboard(s) showing "success criteria" metrics: _\[link here\]_

_The stages and number of users below are provided as example values recommended by VSP, but can be customized to your team's needs._

### Stage A: Canary

_Test a small population of users to make sure any obvious bugs / edge cases are caught._

#### Planning

- Length of time: One day
- Percentage of Users (and roughly how many users do you expect this to be): x% (500 users) (_Recommendation: select a percentage that targets ~500 users, or at most 10%_)

#### Results:
- Number of unique users: x
- Metrics at this stage (per your "success criteria"): x
- Was the data submitted (if any) easy for VA to process?: yes/no, lorem ipsum
- Types of errors logged: lorem ipsum
- What UX changes (if any) are necessary based on the logs, or feedback on user challenges, or VA challenges?

### Stage B: moderate

_Test a larger population of users to make sure there are no issues exposed by larger usage patterns._

#### Planning

- Length of time: Three days
- Percentage of Users (and roughly how many users do you expect this to be): 25% (x users)

#### Results:
- Number of unique users: x
- Metrics at this stage (per your "success criteria"): x
- Was the data submitted (if any) easy for VA to process?: yes/no, lorem ipsum
- Types of errors logged: lorem ipsum
- What UX changes (if any) are necessary based on the logs, or feedback on user challenges, or VA challenges?

_More stages? Sure! If it makes sense for your product! Plan them out with the same structure as above._

## Go Live!

### Planning:
- Desired date: 04/01/22 (pending legal review)
- Post-launch KPI 1: Number of downloads
- Post-launch KPI 2: Number of download errors
- Post-launch KPI 3: xx lorem ipsum
- etc
- Go / No Go: (ready / not ready)[https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/platform/product-management/go-no-go-meeting-template.md]

### 1-week results:
- Number of unique users: x
- Post-launch KPI 1 actual: xx lorem ipsum
- Post-launch KPI 2 actual: xx lorem ipsum
- Post-launch KPI 3 actual: xx lorem ipsum
- Any issues with VA handling/processing?: yes/no, lorem ipsum
- Types of errors logged: lorem ipsum
- Any UX changes necessary based on the logs, or feedback on user challenges, or VA challenges? yes/no 
- If yes, what: lorem ipsum

### 1-month results:
- Number of unique users: x
- Post-launch KPI 1 actual: xx lorem ipsum
- Post-launch KPI 2 actual: xx lorem ipsum
- Post-launch KPI 3 actual: xx lorem ipsum
- Any issues with VA handling/processing?: yes/no, lorem ipsum
- Types of errors logged: lorem ipsum
- Any UX changes necessary based on the logs, or feedback on user challenges, or VA challenges? yes/no 
- If yes, what: lorem ipsum

## Post-launch Questions 

_To be completed once you have gathered your initial set of data, as outlined above._ 

1. How do the KPIs you gathered compare to your pre-launch definition(s) of "success"?
1. What qualitative feedback have you gathered from users or other stakeholders, if any?
1. Which of the assumptions you listed in your product outline were/were not validated? 
1. How might your product evolve now or in the future based on these results?

