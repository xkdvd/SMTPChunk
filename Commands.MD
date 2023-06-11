Commands in SMTP are issued automatically without the need for the end user to enter them. As an example, the HELO command is the email client identifying itself to a server. Other SMTP commands include the following:

    MAIL. This command is used to initiate a message transfer. This tells the SMTP server that a new transaction is starting.
    RCPT. This command follows MAIL. It identifies the replicant email address.
    DATA. This command starts the transfer of data between the client and server. Message contents are moved to the SMTP server.
    QUIT. Once the email is sent, the client sends this command to the server to cease the connection.
    RSET. This command is used to abort the mail transaction. The command is sent to the server, where all data about the email is removed.
