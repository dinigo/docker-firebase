# docker-firebase
## Purpose
This image was created specifically for usage with continuous integration systems, and contains the minimum
requirements to deploy a project to [Firebase]. Currently being used with [Gitlab CI], but should meet the requirements
for most CI systems.

## Details
### Base Image
* [Node 8] - Node Carbon LTS using the alpine image.

### Additional Node Modules
* [Firebase CLI] - yarn install of Firebase Command Line Tools. Required to deploy to Firebase.


[Gitlab CI]: https://about.gitlab.com/features/gitlab-ci-cd/
[Firebase]: https://firebase.google.com/
[Firebase CLI]: https://github.com/firebase/firebase-tools
[Node 8]: https://hub.docker.com/r/library/node/