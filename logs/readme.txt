The following files contain logs token on 14/09/2022 starting from around 09:30 GMT+2

User A:
If a document is written to the database before the first replication occurs then NO documents are replicated.
A_with_write.txt

If the document is not written to the database then ALL documents are correctly replicated.
A_without_write.txt

User B:
If a document is written to the database before the first replication occurs then SOME documents are replicated.
B_with_write.txt
If the document is not written to the database then ALL documents are correctly replicated.
B_without_write.txt