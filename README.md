# Lab 8 - Starter

1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why. 

Answer : The automated tests in my Recipe project development pipeline would be **within a Github action that runs whenever code is pushed**. The Github action would check that the code added or changed works, because checking locally only verifies that the code works on my machine. Furthermore, when the code is pushed the action can verify and determine whether the entire project is working properly. 

2. Would you use an end to end test to check if a function is returning the correct output? (yes/no) 

Answer: **No**, end to end (E2E) testing is not needed to check if a function is returning the correct output. E2E testing is used to test user actions from start to finish; however, verfiying what a function is returning is slightly out of such scope. Instead, a unit test is much more appropriate to check if a funciton is returing the correct output. 

3. Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.

Answer: **No** I would not use a unit test to test the "message" feature of a messaging application. There are many different components of a "message" feature of a messaging application, and a unit-test might be limiting. Instead, I would use end to end testing because it would allow me to test the “message” feature of a messaging application by automating different test cases and emulating user actions from start to finish. 

4. Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.

Answer: **Yes** I would use a unit test to test a specific feature. This is because a unit test's purpose is to test a small part of a program and the "max message length" feature is a small part of a messaging application.  
