# contentDocument
A trigger on Content Document link on insert and update and delete trigger on ContentDocument
I had a trigger on Attachment. An object Inventory has a status field. When status is 'Final', I prevent the users from deleting
inserting or updating the Attachement.

Since we are now moving to using Files(ContentVersion), the same trigger needs to created on ContentDocumentLink for the 
insert, update but for the prevention of deletion, write trigger on ContentDocument.
