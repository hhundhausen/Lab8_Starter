# Lab 8 - Starter

1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Answer : The automated tests in my Recipe project development pipeline would be **within a Github action that runs whenever code is pushed**. The GitHub action would check that the code added or changed works, because only checking locally limits the code to ensuring it only works on my machine; not necessarily, any machine. Furthermore, the when the code is pushed it can detect if the entire project is working properly. 

2. Would you use an end to end test to check if a function is returning the correct output? (yes/no) 


Answer: **No**, end to end (E2E) testing is not needed to check if a function is returning the correct output. E2E testing is used to test user actions from start to finish; however, verfiying a function is slightly out of that scope. 

3. Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.

Answer: **No** I would not use a unit test to test the "message" feature of a messaging application. I would use E2E, because the application's testing needs to involve emulating user actions from start to finish. 

4. Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.

Answer: **Yes** I would use a unit test to test a specific feature because its purpose is to test a small part of a product, and the "max message length" feature is a small part of a messaging application. 