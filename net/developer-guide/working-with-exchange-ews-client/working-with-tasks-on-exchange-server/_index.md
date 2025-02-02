---
title: Working with Tasks on Exchange Server
type: docs
weight: 100
url: /net/working-with-tasks-on-exchange-server/
---


## **Working with Tasks**
Aspose.Email supports processing tasks on Exchange using the [ExchangeTask](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/exchangetask) class. Different properties exposed by [ExchangeTask](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/exchangetask), like [Subject](https://apireference.aspose.com/email/net/aspose.email.calendar/task/properties/subject), [Status](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/exchangetask/properties/status), [DueDate](https://apireference.aspose.com/email/net/aspose.email.calendar/task/properties/duedate), and [Priority](https://apireference.aspose.com/email/net/aspose.email.calendar/task/properties/priority), can be used to configure the task on Exchange. The [EWSClient](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/ewsclient) class exposes functions like [CreateTask](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/iewsclient/methods/createtask/index), [UpdateTask](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/iewsclient/methods/updatetask/index), and [DeleteTask](https://apireference.aspose.com/error/404?path=email/net/aspose.email.clients.exchange.webservice/iewsclient/methods/deletetask/index) which are used to process tasks on Exchange. This article shows how to:

- Create a new task.
- Set a task's timezone.
- Update a task.
- Delete a task.
- Send Task Request
- Save Task to Disc
### **Create New Task**
The following code snippet shows you how to use create a new task.



{{< gist "aspose-com-gists" "6e5185a63aec6fd70d83098e82b06a32" "Examples-CSharp-Exchange_EWS-ProcessExchangeTasksUsingIEWSClient-ProcessExchangeTasksUsingIEWSClient.cs" >}}
### **Specifying Timezone**
The [IEWSClient](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/iewsclient) interface and [ExchangeTask](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/exchangetask) provide the TimeZoneId property for setting timezone information when creating a task. The following code snippet shows you how to specify Timezone.



{{< gist "aspose-com-gists" "6e5185a63aec6fd70d83098e82b06a32" "Examples-CSharp-Exchange_EWS-SpecifyTimeZoneForExchange-SpecifyTimeZoneForExchange.cs" >}}
### **Update Task**
The following code snippets show how to update a task on an Exchange server.



{{< gist "aspose-com-gists" "6e5185a63aec6fd70d83098e82b06a32" "Examples-CSharp-Exchange_EWS-UpdateTaskOnExchange-UpdateTaskOnExchange.cs" >}}
### **Delete Task**
The following code snippet shows you how to delete a task on an Exchange server.



{{< gist "aspose-com-gists" "6e5185a63aec6fd70d83098e82b06a32" "Examples-CSharp-Exchange_EWS-DeleteTaskOnExchange-DeleteTaskOnExchange.cs" >}}
### **Sending Task Request**
Aspose.Email Exchange service provides the capability to send task requests similar to Outlook. The following code snippet shows you how to load a task request message from the disc and send it using the [IEWSClient](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/iewsclient).



{{< gist "aspose-com-gists" "6e5185a63aec6fd70d83098e82b06a32" "Examples-CSharp-Exchange_EWS-SendTaskRequestUsingIEWSClient-SendTaskRequestUsingIEWSClient.cs" >}}
### **Saving Task to Disc**
Aspose.Email also allows saving Exchange Tasks to disc in Outlook MSG format. The following code snippet shows you how to save a task to disc.



{{< gist "aspose-com-gists" "6e5185a63aec6fd70d83098e82b06a32" "Examples-CSharp-Exchange_EWS-SaveExchangeTaskToDisc-SaveExchangeTaskToDisc.cs" >}}
### **Listing Tasks from Exchange Server**
[IEWSClient](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/iewsclient) provides the [ListTasks](https://apireference.aspose.com/email/net/aspose.email.clients.exchange.webservice/iewsclient/methods/listtasks/index) method that can be used to fetch tasks from an Exchange Web Service. It has several overloads that can be used to retrieve the list of tasks from a specific folder or using some search criteria. The below code sample illustrates getting all or specific tasks from the Tasks folder.



{{< gist "aspose-com-gists" "6e5185a63aec6fd70d83098e82b06a32" "Examples-CSharp-Exchange_EWS-ListTasksFromExchangeServer-ListTasksFromExchangeServerWithEWS.cs" >}}
### **Filtering Tasks from Exchange Server**
Aspose.Email provides the capability to retrieve specific tasks from the server instead of retrieving all tasks from the server. The API can be used to retrieve tasks by task's status such as Completed, Deferred, In Progress, Not started or Waiting on others. The [ExchangeQueryBuilder](https://apireference.aspose.com/email/net/aspose.email.clients.exchange/exchangequerybuilder) class can be used to specify the desired criterion utilizing the Status property. It also allows specifying multiple conditions for retrieving desired tasks from Exchange Server. This is demonstrated by the following code sample.
