# SMTPChunk
SMTP Server and Command Line Client

run in two seperate terminal sessions

  terminal1 
  (server)
  
  sudo python3 ./smtpd_server.py

  terminal2 
  (client - uses server to send a test email and creates network data packets for wireshark)
  
  python3 ./smtp3.py
