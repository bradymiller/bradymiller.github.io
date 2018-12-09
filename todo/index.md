---
layout: default
---
## TODO lists

### Expedited
1. oe-blue-button-generate
1. make whitelist docs default (add standard entries and fix whitescreen bug)
1. CSRF implementation ongoing.
1. Blog post for google cloud launcher
1. Ensure 5.0.1 to 5.0.2 docker upgrade works with the new apache uid 1000 fix (after do this, can then update the 5.0.1 docker to support swarm)
1. snomed rf2
1. couchdb ssl
1. apache 2.2 updates
1. phpunit
1. MIPS research
1. MU3 research

### Scheduled items to do
1. When php 7.3 dockers are available, update the insane dev environment.
1. When Alpine 3.9 is released. Update 5.0.2 docker and flex dockers. Upgrade dev npm/nodejs version to 10 and update npm/nodejs version used in ubuntu 18.04 demo farm docker to 10.

### OpenEMR Code Reviews
* [Pull Requests](https://github.com/openemr/openemr/pulls)

### OpenEMR Issues
* [High Priority](https://github.com/openemr/openemr/milestone/2)
* [Normal Priority](https://github.com/openemr/openemr/milestone/4)
* [Very Low Priority](https://github.com/openemr/openemr/milestone/5)

### OpenEMR Project Admin
1. Upgrade wiki (mediawiki) to most recent version.(R working on)

### OEMR Organization
1. Restructuring

### OpenEMR Next Release
1. Removed ubuntu perl dependencies, so will need to build a new version development ubuntu package at some point. In this package could also stream line the clone with the `--depth 1` setting.
1. For next ubuntu package, don't secure files needed for install if auto-configuration was not done.(low priority)
