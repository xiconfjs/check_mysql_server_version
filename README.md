# check_mysql_server_version
Simple script to return the version of mysql server without logging in

The script initializes a tcp connection to the mysql server and waiting for a initial response which usually contains the version number. This is useful, if you don't have login credentials for a mysql instance but want to check for the version in use.

## usage
`./check_mysql_server_version <host> <port>`

This should return the version number.

## notes
**Warning: ANY USE OF THE SOFTWARE IS ENTIRELY AT YOUR OWN RISK**
