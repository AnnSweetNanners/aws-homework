# aws-homework
Unit 12  AWS Cloud Homework

This bot was created to provide an investment recommendation to users looking to invest funds for retirement. It takes in Name, Age, Investment Amount, and desired risk level, and then provides a recommendation.

## I. Assumptions
The bot assumes that retirement investments cannot be made after the age of 64. These rules changed recently, and allow investments into certain account types while the participant is still earning income.

Additionally, this bot does not specify account type and assumes the investments can be held in the plan. Realistically certain plan types (specifically workplace plans) will limit investment options.

## II. Dependencies
The bot requires the use of Amazon Lex and Amazon Lambda.

## III. Summary of Findings
I could not get the chat bot to work with my own Amazon Lambda code. It did work when I ran the code from the solved file. I found Amazon Lex and creating the chatbot fairly easy. The difficulty came when trying to identify problem areas with Lambda. Using the test code did help identify where the location of the error was, but it was still hard to troubleshoot. Comparing my Lambda code to the solved file, I believe the error was the result of one of the following reasons:
    * In my code, i didn't create separate if/else statements for ages <0 and ages > 64.
    * Indent errors

*Note This is my first time creating video edits/GIFs of operational code. I don't have an editor at this time. If you have recommended editors for Windows users, I would appreciate suggestions!*