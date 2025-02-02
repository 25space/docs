# RobSafe - Backupsoftware
Product-Website: n/a

## Download
RobSafe is a own Backupsoftware for Windows Servers and Clients installations. The software was release from the "mdct Group" in different editions. 
Download software: https://25space.com/support/download

## Out of support
RobSafe is currently not supported (out of scope).

## Support-Topics
### RobSafe does not copy
RobSafe puts a log file on C: \. Check the permissions. You can delete the creation of the log file. To do this, completely remove the parameter “/LOG+:C:\robsafe2013.log”.

### RobSafe – No connection to the source.
When executing RobSafe, the source error occurs. Identifier # rs0002. Solution: Check if RobSafe can reach the source. The source address is not the source path for the backup at the same time. For a local application, use “localhost”.

### RobSafe – No connection to the destination
When executing RobSafe, the destination error occurs. ID # rs0003. Solution: Check if RobSafe can reach the destination. The destination address is not the destination path for the backup at the same time. For a local application, use “localhost”.

### RobSafe – System error
The system error occurs while running RobSafe. ID # rs0001. Solution: This can have different causes Always check information such as the source and destination paths. In addition, the parameters. Often with self-modified code.

### RobSafe does not work with Windows XP/Server 2003
NO SUPPORT FOR WINDOWS XP/Server 2003! This is because XP does not yet support the Robocopy feature. This should normally be fixed with an update from Microsoft. Verify that all updates have been properly installed. Alternatively, you can download the Robocopy support manually
