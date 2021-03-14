NOTE: The various react directories are dockerized, however not set up to communicate with each other.
So one still needs to run the react directories with "npm start", instead of running the container.
- One also needs to do the "npm install", "npm audit fix --force", and "npm install cors" before running the "npm start" on each react directory.

