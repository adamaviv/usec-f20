# Project

## Description

You are required to complete a semester long project related to usability security and privacy. Projects are individual efforts, not group work, although you may discuss your project with others to get feedback. The work of the project itself should be your own. While it is not necessarily required, it is expected that all projects have a user study that can either be qualitative or quantitative. 

## Project Proposal

Your project topic is at the discretion of the instruction. A list of suggested topics are at the end of this document. I encourage you to read through them and think of a few that interest you before deciding. You can talk to your instructor to help winnow down a list. 

Eventually, you must submit a **initial** project proposal for approval on one topic. That proposal could become your **approved** proposal, you may need to submit an updated one following conversations with the instructor. 

If you would like to work on a topic not listed below, you may propose a new topic to the instructor.

### Proposal Requirements

Your proposal should include the following information, approximately one paragraph per-point.

1. What research questions/hypothesis do you plan to address?
2. What methods will you use in your investigate?
3. What is your recruitment plan and target demographic?
4. What is a timeline for your work?
5. What are the ethical considerations?
6. What is your analysis plan for any data you collect?

Following submission of your proposal, your group will schedule meetings with the instructor to get feedback and provide updates. Once the topic is approved, you are expected to make edits on your initial proposals for a final proposal. 

Submit your Inital Project Proposal here: https://classroom.github.com/a/A9NjX4hQ

## Ethics Review

As part of your project, you will be required to complete an IRB Application that contains the following information:
* [IRB application from](https://docs.google.com/document/d/1bvEF7X5oFGrp-qirZMLADJPm24OkzHmb4RnPlhc-Vpo/edit?usp=sharing) 
* [Informed Consent](https://docs.google.com/document/d/17J6efNvzT-igbk9jHgWzDpS4EGErb0M_E3VnjQfowqk/edit?usp=sharing)
* Study Questions/Survey/Transcript -- these do not need to be final, but should cover the kinds of things you are asking about. 

This is based on the standard IRB submission requirements at GW. As this project is for the purposes of education, not generalizable knowledge, we do not require official IRB approval. However, we expect you to uphold the same standards as an IRB approved research. This includes:

1. Treating all participants ethically and fairly
2. Providing confidentiality linking personal information of participants to data.
3. Informing participants that they are participating in a research project for a class.
4. If deception was used, providing post-procedure information to participants.

Submit your IRB Application here: https://classroom.github.com/a/UP88Nsc2

## Status Updates

You are required to provide one status update for your project. This should include all the same material as the proposal, but with substantive updates on work completed and any changes that occurred since submission.

## Presentations

You will make two presentations about your project in class. The first is a "Lightening Talk" which will be a short 5 minute talk introducing the topic and your methods. This will enable all class members to learn about the work of everyone else.

The second presentation will be your final project presentation, which will be 15 minutes in length with 5 minutes of questions. These presentations should be inline with conference/workshop style presentations and provide some depth of the methods, analysis, and conclusions. 

## Project Final Report

Your final report should be between 6-8 pages, not includeing bibliography and appendix. It should be formatted as [ACM, two column format](https://www.acm.org/publications/proceedings-template). You can easily find this on [overleaf](https://www.overleaf.com/gallery/tagged/acm-official#.WOuOk2e1taQ). You should use the `\documentclass[sigconf]{acmart}` header for the two collumn format.

Your paper should have the following outline (and descriptions):
* Abstract
  * One paragraph description of your research questions and motivations and a brief summary of the conclusion
* Introduction (containing the following details)
  * Motivation (one/two-paragraph)
  * Related work doesn’t cover this!
  * Research Question (…)
  * Method (…)
  * Results (…)
  * Conclusions/Contributions (…)
* Related Work
  * Enumerate what’s come before but also(!) include how that related work matters to this research
* Methodology
  * What was the method of investigation (survey/interview)
  * Description of the survey 
  * Who do you recruit and from where
  * Limitations
* Results
  * How did you analyze it?
  * What did you find?
  * Address each hypthosis/research question, what is their answer?
* Discussion
  * Interpretation and place in the context
  * Now that you know the answer to a RQ, what doe that mean…
  * What does this mean and how do we apply
  * Future work/future directions
* Conclusion
   * Rehashing of the motivations/research-question/methods/results/contributions
* Appendix
  * Entire survey/interview instrument
  * Codebook (qualitative)
  * Any additional figures and material is relevant for me to review

 

 

Submit your final report here: https://classroom.github.com/a/KwwKmB4S

## Project Schedule

* 9/30: Initial Project Proposal is Due (https://classroom.github.com/a/A9NjX4hQ)
* 10/1-7: Proposal Feedback meetings (to be scheduled with the instructor)
* 10/9:  Approved Project Proposal is Due
* 10/26: IRB Application Due (https://classroom.github.com/a/UP88Nsc2)
* 11/4: Lightening Talks and Project Status Updates due
* 11/6-8: Status update meetings (to be schedule with the instructor)
* 11/16-20: Project Status Meetings
* 12/9: Project Presentations
* 12/18: Final Project Reports Due


## Grading

* Final Report: 50%
* Final Presentation: 20%
* Lightening Talk: 5%
* Ethics Document: 10% 
* Initial Proposal: 5%
* Final Proposal: 10%

## Project Topics

Below is a non-exhaustive list of topics and some general research questions that you can use to build a proposal. You may also propose your own topics. Note that you will need to develop your own more specific research question and methods of investigation for your research. 

* Authentication

  * Biometric Authentication
    * As more and more devices use biometrics, how does this new convenient method of authentication impact knowledge based methods of authentication choices and the perceptions therein? 
  
    * Do people choose weaker PINs/Passwords if they have a biometric? What are people's opinions comparing biometrics with knowledge based authentication?

  * Mobile Authentication
    * How do users manage passwords on their mobile devices, how does that differ than how they manage them in traditional settings? Does it differ between applications and browsing?
    * Some secure messaging services, like Signal, ask users to select a PIN, do users do this? Do they understand how the PINs are used? Also there was a lot of reminders about entering your PIN on signal, did they work or annoy?
    * Even if the phone is locked, there are some items that are visable. What settings do users use for "locked access" and how do they choose them?
 
  * Password Managers
    * Why do users or why do they not use a password manager in different settings? Mobile vs. Desktop? 
    * What are users preferences and features for password managers?
    * How well do Password Managers actually work at auto filling? Can you empirically measure auto-filling success and failures of password managers in different settings?
    * Many password managers have features for users to review and update passwords. How well do these work? Do users user them? If they do use them, do they understand them?
    * What if we asked users who weren't previously using a password manager to set one up? What do they do? How does it affect them?
    
* Digital Sharing 
  * Users want/need to share secrets online, such as a password or PII. If so tasked, how would they do it? Would they use email or text message or something else? What are the threat models and security understanding of users when they share secrets online?
  * We share a lot of documents in the cloud, how often have you gone back to actually review all of that sharing? If users were to reflect on documents they previously shared, would they change anything by adding more restrictions, or just leave it be? What are the threat models of sharing documents this way?
  
* Security of Signal/Whatsapp/SMS
  * More and more users are using texting applications that provide end-to-end encryption. Do users user all these features? How do they understand the security provided?
  * Can two users properly establish secure channels using these apps?
  * (see the mobile authentication one for PINs in signal)
  
* Sharing of Venmo payments
  * What kinds of social payment sharing is acceptable and how do people make these choices?
  * What if you made people go back and look at their Venmo sharing history, what do they think? Is there anything they would want to make private? 
  
* Voice Assistants
  * Creepy or necessary? How do people understand and use voice assistant technology? 
  * Voice assistants often record conversations even when users are not aware, but you can go a look at these recordings. How do people feel about these un-aware recordings? 
  
* Two Factor Authentication
  * It's clearly better, but what might stop users from using it? How many accounts do ussrs actually have 2fa installed on?
  * If there is two-factor, do people end up making worse choices elsewhere because they have a false sense of security? 
  

* Video Conferencing Privacy and Security
  * So many more people are using video conferencing, what are their concerns? How do they mitigate them? 
  
* Private Browsing Mode
  * What do people actually use this for and what is their expectations of privacy when using private browsing mode? 
  
* Developer Studies
  * So much development happens in the open on github---that's public information!---so take a look at all the open issues for security related issues. How quickly are they closed? Do developers care about them?
  
* Breaches and Identify Theft
  * We have all probably been a part of a breach, but how do we understand what happens when we are a pat of breach? Do we do anything about it? You can study participants responses after looking up their information in a breach database. 
  * You may have signed up for identify theft, perhaps in response to a breach or other notification--- what then? How often do you use? Is it helpful? How usable are these services in the first place?
  

  
