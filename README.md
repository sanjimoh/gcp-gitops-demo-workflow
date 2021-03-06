# GCP gitops demo workflow

Intention of this sample micro-service based application is to quickly onboard on GCP CI/CD pipeline with some 
meaningful and practical input.

This app allows users to vote for their favorite emoji,
and tracks votes received on a leaderboard. May the best emoji win!

The application is composed of the following 3 services:

* [emojivoto-web](emojivoto-web/): Web frontend and REST API
* [emojivoto-emoji-svc](emojivoto-emoji-svc/): gRPC API for finding and listing emoji
* [emojivoto-voting-svc](emojivoto-voting-svc/): gRPC API for voting and leaderboard

Demo app is built on top of an existing work available here -> https://github.com/BuoyantIO/emojivoto

## Demo workflow
![Demo workflow](assets/demo_workflow.png "Demo workflow")

## Sample UI screen
![Sample UI screen](assets/sample_ui.png "Sample UI screen")
![Sample UI screen](assets/sample_ui_2.png "Sample UI screen")
