- To use [RDP](https://www.cyberark.com/resources/threat-research-blog/explain-like-i-m-5-remote-desktop-protocol-rdp) in Kali open the Remmina app.

### Some Command Examples

- Sample command to output a real-time expanding text file (like a log file) to terminal. This will also filter texts including "Key Error."

watch -d grep "Key Error" /var/log/server.log

- Next comand will do the same and will also export results into another text file:

watch -d grep "Key Error" /var/log/server.log >debug.log

- See the files having a text content of "Amir"

grep -Rwi "Amir"



