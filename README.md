# iyana.ai

iyana.ai is an infinite, generative shared world you explore through a terminal.

you play a netrunner freeing a superintelligence. 

the best part: it's multiplayer, all the time. your friends can join you on your adventure.

## tech stack

- react, vite
- hono
- vercel's ai sdk
- redis
- bun

when a user enters a command to (e.g. `cd` into a directory), it's hashed. if it's a new command, it's simulated by Claude and added to the world cache. if it's not a new commmand, the output in the world cache is returned. this way, players explore the same computers and directories. 

we're mapping this world together.

[iyanaai.netlify.app
](https://iyanai.netlify.app)
