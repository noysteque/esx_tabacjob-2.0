# esx_tabacjob
ESX Tabac Job

If you want to modify or add somethings to the script please contact us or mention us
[REQUIREMENTS]

	* Auto mode
	* esx_service => https://github.com/ESX-ORG/esx_service
  
	* Player management (billing and boss actions)
	* esx_society => https://github.com/ESX-ORG/esx_society
	* esx_billing => https://github.com/ESX-ORG/esx_billing

[INSTALLATION]

1) CD in your resources/[esx] folder
2) Copy the repository
3) Import fr_esx_tabac.sql in your database.

4) Add this in your server.cfg :

```
start esx_tabacjob
```

5) If you want player management you have to set Config.EnablePlayerManagement on true in config.lua
