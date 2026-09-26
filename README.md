# AI-Assisted GitHub-Based QA Documentation and Problem Solving for Electronics Projects

## 1. Project Overview

This project demonstrates the use of GitHub and AI-assisted quality assurance for a simple Arduino LED blinking project.

The project was developed to demonstrate code documentation, bug identification, issue tracking, collaboration through pull requests, and problem resolution.

## 2. Project Objective

The objective is to develop and test an Arduino LED blinking program and use AI assistance to identify and resolve a software bug.

## 3. Hardware

- Arduino board
- Built-in LED / LED connected to digital pin 13

## 4. Expected Behaviour

The LED should:

- Turn ON for 1 second
- Turn OFF for 1 second
- Repeat continuously

## 5. QA Issue

During QA testing, the OFF delay was incorrectly set to:

delay(10000);

This caused the LED to remain OFF for approximately 10 seconds.

## 6. AI-Assisted QA

ChatGPT was used to review the code and identify the incorrect delay value.

The AI-assisted review identified:

- The incorrect delay value
- The resulting impact on LED behaviour
- The required correction

## 7. GitHub QA Workflow

The following workflow was followed:

Bug Identification
→ AI Review
→ GitHub Issue
→ Pull Request
→ QA Comment
→ Code Fix
→ Review
→ Merge
→ Issue Closure

## 8. Resolution

The incorrect statement:

delay(10000);

was changed to:

delay(1000);

The corrected code was committed to the QA branch and merged into the main branch through a Pull Request.

## 9. Final Result

The final Arduino program produces the intended behaviour:

LED ON for 1 second → LED OFF for 1 second → Repeat

## 10. Learning Outcome

This activity provided practical experience in:

- GitHub repository management
- GitHub Issues
- Pull Requests
- Branch-based development
- AI-assisted code review
- Bug identification
- QA documentation
- Code correction
- Issue tracking and closure
- Software collaboration workflow
