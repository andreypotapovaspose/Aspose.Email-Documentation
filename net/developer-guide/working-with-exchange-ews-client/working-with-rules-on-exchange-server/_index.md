---
title: Working with Rules On Exchange Server
type: docs
weight: 90
url: /net/working-with-rules-on-exchange-server/
---


## **Managing Rules**
Aspose.Email for .NET can be used to manage the rules on Exchange Server using the [EWSClient](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/ewsclient) class. This class uses Exchange Web Services (EWS), which are available in Exchange Server 2007 and later releases. To show how to manage rules, this article explains how to:

- Read the rules already on the server.
- Create a new rule.
- Update an existing rule.

Microsoft Exchange Server 2010 Service Pack 1 is required for all features described in this article.
### **Read Rules**
To get all the rules from the Exchange Server:

1. Connect to an Exchange Server using the [IEWSClient](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/iewsclient) class.
1. Call the [IEWSClient.GetInboxRules()](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/iewsclient/methods/getinboxrules) method to get all the rules.
1. In a foreach loop, browse through all the rules and display the rule properties like conditions, actions, and name.

The following code snippet shows you how to read rules.



{{< gist "aspose-com-gists" "6e5185a63aec6fd70d83098e82b06a32" "Examples-CSharp-Exchange_EWS-ExchangeServerReadRules-ExchangeServerReadRules.cs" >}}
### **Creating a New Rule**
To create a new rule on the Exchange Server, perform the following steps:

1. Connect to an Exchange Server using the [IEWSClient](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/iewsclient) class.
1. Create a new instance of the [InboxRule](https://apireference.aspose.com/email/net/aspose.email.clients.exchange/inboxrule) class and set the following mandatory properties:
   1. DisplayName
   1. Conditions
   1. Actions
1. Call the [IEWSClient.CreateInboxRule()](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/iewsclient/methods/createinboxrule) method to create the rule.

The following code snippet shows you how to create a new rule.



{{< gist "aspose-com-gists" "6e5185a63aec6fd70d83098e82b06a32" "Examples-CSharp-Exchange_EWS-CreateNewRuleOntheExchangeServer-CreateNewRuleOntheExchangeServer.cs" >}}
### **Updating a Rule**
To update a rule on the Exchange Server:

1. Connect to an Exchange Server using the [IEWSClient](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/iewsclient) class.
1. Call the [IEWSClient.GetInboxRules()](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/iewsclient/methods/getinboxrules) method to get all the rules.
1. In a foreach loop, browse through all the rules and get the rule you want to change by matching the DisplayName in a condition.
1. Update the rule properties
1. Call the [IEWSClient.UpdateInboxRule()](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/iewsclient/methods/updateinboxrule/index) method to update the rule.

The following code snippet shows you how to update a rule.



{{< gist "aspose-com-gists" "6e5185a63aec6fd70d83098e82b06a32" "Examples-CSharp-Exchange_EWS-UpdateRuleOntheExchangeServer-UpdateRuleOntheExchangeServer.cs" >}}
