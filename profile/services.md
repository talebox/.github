# Services Available
The box will have a collection of available services. These services are meant to work independently of each-other and only interact with each-other through their respective endpoints. Yes, microservices.

## Stable 
- 

## Development
- 

## Aproved
- 

## Sandbox
- Board
- Notes
- Files
- GitD
- Security
- Dash
- Social
- Mail

<br/>
<br/>

# Descriptions
Implementations for each one of the available services, this would act as an initial readme for each of these repos, when they're created.

Each one of these projects/services will:
1. Expose it's own api endpoints.
2. Be self-contained/independent.
3. 

## Board (a Whiteboard)
Board solution, will take inspiration from [WBO](wbo.ophir.dev) to create a real-time offline-first experience.

## Notes
A notes app, based on my own stripped down notes app, literally only a handful of endpoints.

## Files
A solution for file synchronization... similar to Dropbox, though maybe something simpler like rsync or sftp already works well enough. Maybe just a Web UI?, since all devices that aren't able to use sftp or rsync easily usually only need 1 file and are mobile user/loser devices. I still gotta ponder on this tho.

## GitD
A solution for git synchronization... similar to Github.

## Dash
Page to be served on a root path HTTP GET / from ports 80/443.

### Menus
- Services (add/remove/toggle services)
- Storage (view total/used/left)
- Power (view total/used/left)
- Security 
	- Replication
	- Users

## Security
