# Lab 8 - Unit & E2E Testing 
### Chris Kim (No Partners)
- [Deployment](https://google.com)

1. Where would you fit your automated tests in your Recipe project development pipeline? 
   ```
   * Within a Github action that runs whenever code is pushed 
   * Manually run them locally before pushing code
   * Run them all after all development is completed
   ```
   > The Github action seems like the most efficient way to proceed, as it streamlines the entire process. I can just fix the code and upload, and the code will automatically receive feedback.

2. Would you use an end to end test to check if a function is returning the correct output? (yes/no)
   > No. E2E would check the entire workflow and isn't suitable for checking a particular output. Unit testing would limit the scope and result faster testing, thus more appropriate.

3. Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.
   > No. Although the messaging feature is viable for unit testing, since its a feature that is used together with other features, as well as high variability, I belive E2E testing to test for a specific workflow is more suitable.

4. Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.
   > Yes. I would use the unit test to specifically go over the max length as it really is a simple true/false answer to whether the feature works.
