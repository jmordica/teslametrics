# teslametrics

The home for the [telegraf](https://github.com/influxdata/telegraf) plugin written in Go to collect important metrics about your Telsa Model (S/X/3).

This plugin calls the Tesla API using a username and password. It also takes care of regenerating the expiring auth token automatically. Username and password can be an argument or specified in ENV VAR's.

Feel free to make PR's!
