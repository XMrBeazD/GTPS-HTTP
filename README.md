# GTPS-HTTP
simple http for gtps. This http only for growtopia http server.
credit to https://github.com/Alexander9673

# How to Use
1. cd GTPS-HTTP
2. npm install @types/node --save
3. Create folder with name `assets`
4. ts-node index.ts

# About GTPS-HTTP
this http only accept ``growtopia1.com`` and ``growtopia2.com`` and will block except that domain. if you would to use .apk and need domain you can add it like this.

```
if (req.headers["host"] == 'growtopia2.com'){
				console.log(`[${req.url}]: ${req.connection.remoteAddress} ${req.headers["host"]}`)
			}```
			
		
      
