# JSON-Web-Token-Playground

At this time, there is no secure authentication involved. The current state of things is to just provide JWTs for a user.

## A simple method to generate some random hex for our env secrets used to generate tokens:

> $ node

> '>' require('crypto').randomBytes(64).toString('hex')


