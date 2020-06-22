# JSON-Web-Token-Playground

At this time, there is no secure authentication involved. The current state of things is to just provide JWTs for a user.

A simple method to generate some random hex for our env secrets used to generate tokens:

$ node
> require('crypto').randomBytes(64).toString('hex')
'11483946e89c113ed26efba2d732da78c89f7e82c2ebd597c85b0c0380a3257bffa32640bc296211f19ca707154a993ea38c3e2924fe8be432ff1d67640288f0'
> .exit

