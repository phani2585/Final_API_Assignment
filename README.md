# Final_API_Assignment

REST API endpoints - 1
----------------------------------------------
UserController
1. signup - "/user/signup"
2. signin - "/user/signin"
3. signout - "/user/signout"

CommonController
1. userProfile - "/userprofile/{userId}"

AdminController
1. userDelete - "/admin/user/{userId}"

-----------------------------------------------
REST API endpoints - 2
-----------------------------------------------
QuestionController
1. createQuestion - "/question/create"
2. getAllQuestions - "/question/all"
3. editQuestionContent - "/question/edit/{questionId}"
4. deleteQuestion - "/question/delete/{questionId}"
5. getAllQuestionsByUser - "question/all/{userId}"
-------------------------------------------------
REST API endpoints - 3
---------------------------------------------------
AnswerController
1. createAnswer - "/question/{questionId}/answer/create"
2. editAnswerContent - "/answer/edit/{answerId}"
3. deleteAnswer - "/answer/delete/{answerId}"
4. getAllAnswersToQuestion - "answer/all/{questionId}"
---------------------------------------------------------
*The database password have been set as the same by all group members in application.yaml and localhost.properties file
*Seperate business services have been implemented for all the API End Points to make sure all exceptions are checked for
