---
layout: default
---
## TODO lists

### STAT
1. request donations for mu3
1. Issues (patient portal report to mPDF and get working(Issue was created))
2. (note weird placement of whitelisting which will break all dicom stuff if it's turned on)
1. remove agpl (2 of 3 done)
1. snomed rf2 (main done but still need to support in ccda stuff; https://github.com/openemr/openemr/blob/master/interface/modules/zend_modules/module/Carecoordination/src/Carecoordination/Model/EncounterccdadispatchTable.php#L2316-L2333)
1. token methods centralize/integrate
1. CRSF support for api internal use
1. get rid of html2pdf

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
