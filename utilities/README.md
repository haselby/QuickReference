LastUpdated: 20200811

*Setting up Markdown as a service*

	su - root
	
	cp markserv.service /usr/lib/systemd/system/
	
	chown root:root /usr/lib/systemd/system/
	
	systemctl daemon-reload
	
	systemctl list-unit-files --type service | grep markserv
	
	systemctl enable markserv.service
		
	systemctl list-unit-files --type service | grep markserv

	systemctl start markserv
	

