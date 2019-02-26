---
layout: default
---
## TODO lists

### STAT
1. request donations for mu3
2. Issues (patient portal report to mPDF and get working; fix patient portal session issue likely with the secure php setting)
3. (bypass the need for the mime_content_type() function in whitelisting(could also get support in alpine with php7-fileinfo and note this is part of common php7 package in ubuntu; so thinking best to support by adding php7-fileinfo); also note weird placement of whitelisting which will break all dicom stuff if it's turned on)

### Expedited
1. oe-blue-button-generate
1. make whitelist docs default (add standard entries and fix whitescreen bug)
1. CSRF implementation ongoing.
1. Blog post for google cloud launcher
1. Ensure 5.0.1 to 5.0.2 docker upgrade works with the new apache uid 1000 fix (after do this, can then update the 5.0.1 docker to support swarm)
1. snomed rf2
1. couchdb ssl
1. phpunit
1. MIPS research
1. MU3 research

### Scheduled items to do
empty

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
1. For next ubuntu package, don't secure files needed for install if auto-configuration was not done.(low priority)
