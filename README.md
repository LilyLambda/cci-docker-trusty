# cci-docker-trusty #

Example of Docker caching problems in CircleCI's beta Trusty container.

The code in this repo is exactly the same as the code in https://github.com/LilyLambda/cci-docker/. However, this repo is built using CircleCI's beta Trusty container. Notice that caching of Dockerfile steps works in `cci-docker`, but not here.
