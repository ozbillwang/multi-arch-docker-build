# Multi-Arch docker buld

- Circle CI - [![CircleCI](https://circleci.com/gh/ozbillwang/multi-arch-docker-build.svg?style=svg)](https://circleci.com/gh/ozbillwang/multi-arch-docker-build)

- Github Action - Todo

Due to these free online pipelines keep changing with docker version, **these builds are triggered weekly** to confirm the stabilities.

### Notes

There are other two supported CICD in original upstream repo, but I would not work on them currently

- Gitlab CI - it can't nicely handle secrets with special charactors (https://gitlab.com/gitlab-org/gitlab/-/issues/196871). So it is no-go for me.

- (Decommissioned) Travis CI - [![Build Status](https://app.travis-ci.com/ozbillwang/multi-arch-docker-build.svg?branch=master)](https://app.travis-ci.com/ozbillwang/multi-arch-docker-build) The CI changed their free model in year 2022, I don't have enough free credit to run any docker build projects now


### Reference

[Multi-arch build, what about Travis?](https://www.docker.com/blog/multi-arch-build-what-about-travis/)

[Multi-arch build, what about CircleCI?](https://www.docker.com/blog/multi-arch-build-what-about-circleci/)

[Circle CI - Available Docker versions](https://support.circleci.com/hc/en-us/articles/115013849727-Available-Docker-versions)
