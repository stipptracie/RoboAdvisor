# AWS_Robo_Adviser

Lex bot created using AWS Lex and Lambda functions to deliver an automated chat service detailing risk on an investment.

---

## Technologies

Language: Python 

[Amazon Lex](https://aws.amazon.com/lex/) - AWS service for creating automated chat bots

[Amazon Lambda](https://aws.amazon.com/lambda/) - AWS service for creating complex functions for use in other AWS services such as Lex


---

## Installation Guide

There is nothing to install as Amazon Web Services are accessed through **[aws.amazon.com](aws.amazon.com)**


---

## Usage

This bot has not been published so there is no public usage at this point. There are GIFs below showing how it works.

Ultimately the user inputs their first name, age, amount for investment and their acceptable risk level.

The bot stores this information and recommends a split of bonds (AGG) and/or stocks (SPY)


---

## Overview of Project

### Bot Set Up

Slots:
<div style="text-align: left"><img src="https://github.com/stipptracie/RoboAdvisor/blob/main/Images/slots.png?raw=true" width="600" /></div>

Utterances:
<div style="text-align: left"><img src="https://github.com/stipptracie/RoboAdvisor/blob/main/Images/utterances.png?raw=true" width="600" /></div>


### Helper Functions
<div style="text-align: left"><img src="https://github.com/stipptracie/RoboAdvisor/blob/main/Images/validation_function.png?raw=true" width="600" /></div>
<div style="text-align: left"><img src="https://github.com/stipptracie/RoboAdvisor/blob/main/Images/recommendation_function.png?raw=true" width="600" /></div>


### Test Cases

Incorrect Amount: <div style="text-align: left"><img src="https://github.com/stipptracie/RoboAdvisor/blob/main/Images/incorrectAmount.png?raw=true" width="800" /></div>

Negative Age: <div style="text-align: left"><img src="https://github.com/stipptracie/RoboAdvisor/blob/main/Images/negativeAgeError.png?raw=true" width="800" /></div>

Too High of an Age: <div style="text-align: left"><img src="https://github.com/stipptracie/RoboAdvisor/blob/main/Images/ageError.png?raw=true" width="800" /></div>

Correct Info: <div style="text-align: left"><img src="https://github.com/stipptracie/RoboAdvisor/blob/main/Images/correctDialog.png?raw=true" width="500" /></div>


### Recommendation Display

Unsuccessful.

---

## Gifs of Bot Working

### Test

![Gif_Test](https://github.com/stipptracie/RoboAdvisor/blob/main/Images/AmazonLex.gif)

### Full Build

Despite multiple attempts to get the full build to run, the Lambda Function would not run through the Lex Chat Bot.  Tests were successful in Lambda.  More time is needed to troubleshoot.

---

## Contributors

Created by Tracie Stipp while in the UW FinTech Bootcamp
> Contact Info:
> email: stipptracie@gmail.com |
> [GitHub](https://github.com/stipptracie) |
> [LinkedIn](https://www.linkedin.com/in/tracie-stipp-0719691b/)

---
