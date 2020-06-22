# JSON-Web-Token-Playground

At this time, there is no secure authentication involved. The current state of things is to just provide JWTs for a user.

## How to generate some random hex for the env secrets:


$ node

> require('crypto').randomBytes(64).toString('hex')
