# SMTPChunk
SMTP Server and Command Line Client 
TODO: test alternate smtp server in winodws 110702

- Iteratively Update Client with Command Line Options
- payload as attatchment

PREREQUISITES
------------------------------
- Python3
- Wireshark
        https://askubuntu.com/questions/700712/how-to-install-wireshark


DIRECTIONS
------------------------------
run in two seperate terminal sessions

  terminal_1 
  (server)
  
  sudo python -m smtpd -c DebuggingServer -n 127.0.0.1:25 (linux)
  python -m smtpd -c DebuggingServer -n 127.0.0.1:25 (windows)

  terminal_2 
  (client)
  
  python3 ./smtp_client.py
  
