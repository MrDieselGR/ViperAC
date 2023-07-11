Installation:
-------------------------------------

1) Install the SQL database (viper_ac.sql), or it will be automatically installed.
2) Fill out the config file with your choices.
3) Add the following lines to the server.cfg file or your start cfg:

• add_ace group.admin viper.bypass allow // This grants bypass permissions to users with admin or higher permissions. If you want to grant bypass to a different group, change "group.admin" to "group.GROUPNAME".
• add_principal identifier.steam:[STEAM ID HERE] group.admin (or discord:)

4) Make sure that your Anticheat license date is valid before starting your server.

Requirements:
-------------------------------------
1) mysql-async 
2) es_extended
3) screenshot-basic // It is important for taking player screenshots
