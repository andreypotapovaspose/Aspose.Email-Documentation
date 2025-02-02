---
title: Working with MapiTask in PST
type: docs
weight: 60
url: /java/working-with-mapitask-in-pst/
---

## **Adding MapiTask to PST**
[Create New PST, Add Sub-folders and Messages](/email/java/create-new-pst-add-sub-folders-and-messages/) showed how to create a PST file and add a subfolder to it. With Aspose.Email you can add MapiTask to the Tasks subfolder of a PST file that you have created or loaded.

Below are the steps to add MapiTask to a PST:

1. Create a [MapiTask](https://apireference.aspose.com/email/java/com.aspose.email/MapiTask) object.
1. Set the [MapiTask](https://apireference.aspose.com/email/java/com.aspose.email/MapiTask) properties using constructor and different methods.
1. Create a PST using the [PersonalStorage.create()](https://apireference.aspose.com/email/java/com.aspose.email/PersonalStorage#create\(java.io.OutputStream,%20int\)) method.
1. Create a pre-defined folder (Tasks) at the root of the PST file by accessing the Root folder and then calling the [addMapiMessageItem()](https://apireference.aspose.com/email/java/com.aspose.email/FolderInfo#addMapiMessageItem\(com.aspose.email.IMapiMessageItem\)) method.

The code snippet below shows how to create a [MapiTask](https://apireference.aspose.com/email/java/com.aspose.email/MapiTask) and then add it to the Tasks folder of a newly created PST file.



{{< gist "aspose-com-gists" "709d733586ce50505c3bca3f6e8bd18d" "Examples-src-main-java-com-aspose-email-examples-outlook-pst-AddMapiTaskToPST-.java" >}}
