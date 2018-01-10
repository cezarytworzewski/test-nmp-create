# Jak stworzyć plik ```package.json``` ?
##

### Przechodzimy do naszego katalogu w konsoli `cmd	`
### Zakładam, że każdy posiada narzędzie NPM
	Następnie wykonujemy polecenie:

- ```npm init``` 
	
	i wykonujemy polecenia - wypeniając informacje o projekcie

U mnie wygląda do następująco:



		Cezary@CZAREK-DOM C:\Users\Cezary\Documents\KURS\Projects\test-nmp-create
		$ npm init
		This utility will walk you through creating a package.json file.
		It only covers the most common items, and tries to guess sensible defaults.
	
		See `npm help json` for definitive documentation on these fields
		and exactly what they do.
	
		Use `npm install <pkg>` afterwards to install a package and
		save it as a dependency in the package.json file.
	
		Press ^C at any time to quit.
		package name: (test-nmp-create) myapp
		version: (1.0.0) 0.0.1
		description: Learning use NPM
		entry point: (main.js)
		test command:
		git repository:
		keywords:
		author: Cezary Tworzewski

 wynikiem powyższego wypełniania jest stworzenie pliku package.json


	About to write to C:\Users\Cezary\Documents\KURS\Projects\test-nmp-create\package.json:                                                                                 
                                                                                     
	{                                                                                    
	  "name": "myapp",                                                                   
	  "version": "0.0.1",                                                                
	  "description": "Learning use NPM",                                                 
	  "main": "main.js",                                                                 
	  "scripts": {                                                                       
	    "test": "echo \"Error: no test specified\" && exit 1"                            
	  },                                                                                 
	  "author": "Cezary Tworzewski",                                                     
	  "license": "ISC"                                                                   
	}                                                                                    
	                                                                                     
	                                                                                     
	Is this ok? (yes) y     


# Brawo!!! Stworzyłeś plik package.json, który jest niezbędny w każdym projekcie!                                                            