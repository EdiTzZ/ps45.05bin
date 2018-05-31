# ps45.05bin
The standalone payload loader for PS4 5.05

NETCAT: nc -w 3 "PS4 IP" 9023 < payload.bin<br>
SOCAT: socat -u FILE:payload.bin TCP:"PS4 IP":9020
