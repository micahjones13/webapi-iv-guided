Enviorments === physical server (hardeware)

[developemnt] <> [testing] <> [production]

configuration 

-DNS (Domain Name Service) translates the url into the ip address (address of the server) You can't have 2 apps working on the same port. 

must add a "start": "node index.js" to package.json in the scripts section 