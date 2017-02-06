# nexus-version-recorder

[![Build Status](https://travis-ci.org/dangernoodle-io/nexus-version-recorder.svg?branch=master)](https://travis-ci.org/dangernoodle-io/artifact-version-recorder)
[![Coverage Status](https://coveralls.io/repos/github/dangernoodle-io/nexus-version-recorder/badge.svg?branch=master)](https://coveralls.io/github/dangernoodle-io/artifact-version-recorder?branch=master)

Adds the ability to resolve the version of an artifact that was just built by Jenkins.

### Known Issues / Caveats

This plugin will not work with `maven` reactor projects that choose to invidivdually version submodules.
