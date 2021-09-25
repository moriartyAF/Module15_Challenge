# Module15_Challenge

#Correct_Dialog

{
  "messageVersion": "1.0",
  "invocationSource": "DialogCodeHook",
  "userId": "John",
  "sessionAttributes": {},
  "bot": {
    "name": "RoboAdvisor",
    "alias": "$LATEST",
    "version": "$LATEST"
  },
  "outputDialogMode": "Text",
  "currentIntent": {
    "name": "recommendPortfolio",
    "slots": {
      "firstName": "John",
      "age": "40",
      "riskLevel": "Low",
      "investmentAmount": "5000"
    },
    "confirmationStatus": "None"
  }
}


![image](https://user-images.githubusercontent.com/35455504/134787886-be2b26b5-3e57-452f-b610-f947e613e802.png)

#Age_Error

{
  "messageVersion": "1.0",
  "invocationSource": "DialogCodeHook",
  "userId": "John",
  "sessionAttributes": {},
  "bot": {
    "name": "RoboAdvisor",
    "alias": "$LATEST",
    "version": "$LATEST"
  },
  "outputDialogMode": "Text",
  "currentIntent": {
    "name": "recommendPortfolio",
    "slots": {
      "firstName": "John",
      "age": "67",
      "riskLevel": "Low",
      "investmentAmount": "5000"
    },
    "confirmationStatus": "None"
  }
}


![image](https://user-images.githubusercontent.com/35455504/134787905-e5acd2bc-3f3e-4081-8217-d16f532f2470.png)

#Incorrect_Amt_Error

{
  "messageVersion": "1.0",
  "invocationSource": "DialogCodeHook",
  "userId": "John",
  "sessionAttributes": {},
  "bot": {
    "name": "RoboAdvisor",
    "alias": "$LATEST",
    "version": "$LATEST"
  },
  "outputDialogMode": "Text",
  "currentIntent": {
    "name": "recommendPortfolio",
    "slots": {
      "firstName": "John",
      "age": "40",
      "riskLevel": "Low",
      "investmentAmount": "500"
    },
    "confirmationStatus": "None"
  }
}


![image](https://user-images.githubusercontent.com/35455504/134787922-570dbcd5-5404-4694-a941-0ab2fc54fdcf.png)

#Negative_Age_Error

{
  "messageVersion": "1.0",
  "invocationSource": "DialogCodeHook",
  "userId": "John",
  "sessionAttributes": {},
  "bot": {
    "name": "RoboAdvisor",
    "alias": "$LATEST",
    "version": "$LATEST"
  },
  "outputDialogMode": "Text",
  "currentIntent": {
    "name": "recommendPortfolio",
    "slots": {
      "firstName": "John",
      "age": "-2",
      "riskLevel": "Low",
      "investmentAmount": "5000"
    },
    "confirmationStatus": "None"
  }
}


![image](https://user-images.githubusercontent.com/35455504/134787947-bd9c6e0e-2a41-43a6-8c37-5552c45e3e7a.png)



