#Description

This is a fork of the eth-proxy developed by dwarfpool. 

Changes by Philon:
	- Linux only
	- Must be placed in /opt/eth-proxy/
	- Added the file "eth-proxy.service". This is a systemd service to place in /etc/systemd/system. 
	- Allows to be started by "service eth-proxy start". "stop" and "restart" are also possible.
	- Automatically restarts on crash
	- Automatically restarts on the "Job outdated" error. 
	