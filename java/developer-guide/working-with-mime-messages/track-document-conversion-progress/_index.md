---
title: Track Document Conversion Progress
type: docs
weight: 60
url: /java/track-document-conversion-progress/
---

## **Track Document Conversion Progress**
Aspose.Email provides the facility to track the document conversion progress. For this, the API provides [SaveOptions.CustomProgressHandler](https://apireference.aspose.com/email/java/com.aspose.email/SaveOptions#setCustomProgressHandler\(com.aspose.email.ConversionProgressEventHandler\)). which represents the method that handles the progress events. The progress event types are represented by the [ProgressEventType](https://apireference.aspose.com/email/java/com.aspose.email/ProgressEventType) enumeration. The [ProgressEventType](https://apireference.aspose.com/email/java/com.aspose.email/ProgressEventType) enumeration has the following members.

- [MimeStructureCreated](https://apireference.aspose.com/email/java/com.aspose.email/ProgressEventType#MimeStructureCreated): This event informs that the mime structure is created.
- [MimePartSaved](https://apireference.aspose.com/email/java/com.aspose.email/ProgressEventType#MimePartSaved): This event informs that saving of one mime part is finished.
- [SavedToStream](https://apireference.aspose.com/email/java/com.aspose.email/ProgressEventType#SavedToStream): This event informs that all mime parts are saved to stream.

The following sample code demonstrates the use of [SaveOptions.CustomProgressHandler](https://apireference.aspose.com/email/java/com.aspose.email/SaveOptions#setCustomProgressHandler\(com.aspose.email.ConversionProgressEventHandler\)) and [ProgressEventType](https://apireference.aspose.com/email/java/com.aspose.email/ProgressEventType) enumeration track the document conversion progress.

{{< gist "aspose-com-gists" "709d733586ce50505c3bca3f6e8bd18d" "Examples-src-main-java-com-aspose-email-examples-email-TrackDocumentConversionProgress-1.java" >}}

The following is the code for the custom class used in the code sample given above.

{{< gist "aspose-com-gists" "709d733586ce50505c3bca3f6e8bd18d" "Examples-src-main-java-com-aspose-email-examples-email-TrackDocumentConversionProgress-2.java" >}}
