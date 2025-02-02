---
title: Working with MapiJournal in PST
type: docs
weight: 70
url: /net/working-with-mapijournal-in-pst/
---


## **Adding MapiJournal to PST**
[Create a New PST File and Add Subfolders](/email/net/create-new-pst-file-and-add-subfolders/#creating-a-new-pst-file-and-add-subfolders) showed how to create a PST file and add a subfolder to it. With Aspose.Email you can add [MapiJournal](https://apireference.aspose.com/email/net/aspose.email.mapi/mapijournal) to the Journal subfolder of a PST file that you have created or loaded. Below are the steps to add [MapiJournal](https://apireference.aspose.com/email/net/aspose.email.mapi/mapijournal) to a PST:

1. Create a [MapiJournal](https://apireference.aspose.com/email/net/aspose.email.mapi/mapijournal) object
1. Set the [MapiJournal](https://apireference.aspose.com/email/net/aspose.email.mapi/mapijournal) properties using a constructor and methods.
1. Create a PST using the [PersonalStorage.Create()](https://apireference.aspose.com/email/net/aspose.email.storage.pst/personalstorage/methods/create/index) method.
1. Create a pre-defined folder (Journals) at the root of the PST file by accessing the root folder and then calling the [AddMapiMessageItem()](https://apireference.aspose.com/email/net/aspose.email.storage.pst/folderinfo/methods/addmapimessageitem) method.

The following code snippet shows you how to create a [MapiJournal](https://apireference.aspose.com/email/net/aspose.email.mapi/mapijournal) and then add it to the journal folder of a newly created PST file.



{{< gist "aspose-com-gists" "6e5185a63aec6fd70d83098e82b06a32" "Examples-CSharp-Outlook-CreateNewMapiJournalAndAddToSubfolder-CreateNewMapiJournalAndAddToSubfolder.cs" >}}
## **Adding Attachments to MapiJournal**
The following code snippet shows you how to add attachments to [MapiJournal](https://apireference.aspose.com/email/net/aspose.email.mapi/mapijournal).



{{< gist "aspose-com-gists" "6e5185a63aec6fd70d83098e82b06a32" "Examples-CSharp-Outlook-AddAttachmentsToMapiJournal-AddAttachmentsToMapiJournal.cs" >}}
