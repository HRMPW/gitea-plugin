# Changes

<!-- Each version newest first -->

<!-- Template:

## Version X.Y.Z (yyyy-MM-dd)

* details

-->

## Version 1.0.6 (unreleased)

* ...

## Version 1.0.5 (2018-03-14)

* Fix receipt of `pull_request` webhooks.
* Fix parsing of clone URLs when Gitea is publishes scp style clone URLs ([JENKINS-49768](https://issues.jenkins-ci.org/browse/JENKINS-49768))
* Misc fixes in Branch discovery strategies and pull request discovery traits

## Version 1.0.4 (2017-12-18)

* Added support for Webhook notification of repository creation / deletion now that Gitea 1.3 supports those events
* Verified branch deletion events sent by Gitea 1.3 are parsed correctly

## Version 1.0.3 (2017-10-24)

* Update to new Gitea logo

## Version 1.0.2 (2017-08-08)

* Fix Webhook notification of pushes to branches
* Add webhook notification and management of non-`SCMSource` based job types

## Version 1.0.1 (2017-07-28)

* Disable shallow clone when we know a merge will take place ([JENKINS-45771](https://issues.jenkins-ci.org/browse/JENKINS-45771))

## Version 1.0.0 (2017-07-18)

* Initial release
