---
layout: default
---
## TODO lists

### STAT
1. request donations for mu3
2. (note weird placement of whitelisting which will break all dicom stuff if it's turned on)
1. remove agpl (2 of 3 done)
1. snomed rf2 (main done but still need to support in ccda stuff; https://github.com/openemr/openemr/blob/master/interface/modules/zend_modules/module/Carecoordination/src/Carecoordination/Model/EncounterccdadispatchTable.php#L2316-L2333) (work on this after SN finishes Zend upgrade)
1. CRSF support for api internal use (ongoing)
1. Ensure api internal use works (ongoing)
1. Fix redis in insane docker dev env (broken in the new security enhanced dockers)
1. Remove annoying write permission to zend file after zend 3 update in codebase

### Expedited
1. oe-blue-button-generate
1. CSRF implementation ongoing.
1. Blog post for google cloud launcher
1. couchdb ssl
1. phpunit
1. MIPS research
1. MU3 research

### Scheduled items to do
empty

### OpenEMR Code Reviews
* [Pull Requests](https://github.com/openemr/openemr/pulls)

### OpenEMR Issues
* [High Priority Codebase](https://github.com/openemr/openemr/milestone/4)
* [High Priority Devops](https://github.com/openemr/openemr-devops/milestone/1)
* [Normal Priority](https://github.com/openemr/openemr/milestone/5)
* [Low Priority](https://github.com/openemr/openemr/milestone/6)

### OpenEMR Project Admin
1. Upgrade wiki (mediawiki) to most recent version.(R working on)

### OEMR Organization
1. Restructuring

### OpenEMR Next Release
1. Upgrade (move edi,era,letter_templates(migrate custom_pdf.php to base site dir),procedure_results to inside documents); test mechanism in ubuntu package; add and test mechanism to docker; update the apache config in flex dockers and demo farm after 5.0.2 release.
1. Ensure 5.0.1 to 5.0.2 docker upgrade works with the new apache uid 1000 fix.
1. For next ubuntu package, don't secure files needed for install if auto-configuration was not done.(low priority)
