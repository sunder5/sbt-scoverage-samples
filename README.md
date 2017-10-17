scoverage-samples
==================

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/6550db23f90f44b39f63e3e7483a08d6)](https://www.codacy.com/app/sunder5/sbt-scoverage-samples?utm_source=github.com&utm_medium=referral&utm_content=sunder5/sbt-scoverage-samples&utm_campaign=badger)
[![Build Status](https://travis-ci.org/scoverage/sbt-scoverage-samples.svg?branch=master)](https://travis-ci.org/scoverage/sbt-scoverage-samples)
[![CircleCI](https://circleci.com/gh/sunder5/sbt-scoverage-samples.svg?style=svg)](https://circleci.com/gh/sunder5/sbt-scoverage-samples)


A sample program for demonstrating scoverage's code coverage. This sample is an akka based mock quote engine. Note: This project deliberately doesn't have 100% coverage for demonstration purposes.

It uses:

* Akka 2.4.16
* Scalatest for unit tests
* Scoverage 1.5.0

To run:

```
sbt clean coverage test coverageReport
```

## License
```
This software is licensed under the Apache 2 license, quoted below.

Copyright 2014 Stephen Samuel

Licensed under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License. You may obtain a copy of
the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations under
the License.
```
