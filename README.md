# Aurus
Discord bot to setup your server in a snap

### Database Structure
Server IDs:

|    id    	|     prefix     	|
|:--------:	|:--------------:	|
| Guild ID 	| Command Prefix 	|

### Available Properties for Commands
| Name        	| Type    	| Description                                                      	| Required 	| Default 	|
|-------------	|---------	|------------------------------------------------------------------	|----------	|---------	|
| name        	| string  	| Name of the command and the primary alias                        	| true     	| <none>  	|
| description 	| string  	| Description of the command that will be shown in !help           	| true     	| <none>  	|
| aliases     	| array   	| Other alias that will also invoke command                        	| false    	| []      	|
| args        	| boolean 	| Whether the command requires arguments                           	| false    	| false   	|
| argsUsage   	| string  	| Example of how the arguments should be used                      	| false    	| null    	|
| cooldown    	| integer 	| Number of seconds before command can be invoked again            	| false    	| 3       	|
| permissions 	| array   	| Valid Discord permissions the author requires to execute command 	| false    	| null    	|
| serverOnly  	| boolean 	| Whether the command is limited to servers only                   	| false    	| false   	|
