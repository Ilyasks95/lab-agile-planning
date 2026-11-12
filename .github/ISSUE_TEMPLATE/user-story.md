---
name: User Story
about: This template is for creating user stories
title: ''
labels: ''
assignees: ''

---

**As a** [Founder]  
 **I need** [an abstract payment provider gateway for online payments]  
 **So that** [customers anywhere benefits from our services on their own currencies]  

 ### Details and Assumptions
 * [There should be no hardcoded payment provider, the platform shouldn't assume one either, the provider of choice is a feature flag, API keys and Class.]

 ### Acceptance Criteria  

 ```gherkin
 Given [international customers]
 When [they need to pay online on our platform]
 Then [they pay in their currency without hitting a dead-end]
 ```
