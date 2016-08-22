---
layout: default
---
## TODO lists

### Expedited
* G3 items to work on: In process of collecting paperwork and setting up testing times.
* Clarify MU2 testing history with Infogard when M returns on 8/25.

### OpenEMR Code Reviews
1. <span style="color: red">Ray eye form.(now working on integration)</span>
1. Matthew website.
1. Scott legacy scripts removal.
1. Scott js and css organization.
1. Stephen ICD10 2016 set.
1. Scott html2pdf removal.
1. Appchecker stuff.
1. Matrix Zend patient validation module.(already committed into codebase; need to get the modify demographics 'edit' zend module popup to work smoothly and remove the 'closeBeforeOpening=1')
1. Kevin M. EDI module.(already committed into codebase, but need to go through each script and incorporate html escaping)
1. Craig Codes gui update.(Rod reviewed; awaiting response from Craig)
1. Srinivasa daily summary form.(community reviewing)
1. Scott html2pdf (or not html2pdf) composer import versus Scott mpdf transition and composer import.(Scott is testing this)
1. Matthew manual testing stuff.(awaiting more work from Matthew)
1. Ra. security fix.
1. Scott path uppercase cleanup.
1. Visolve add rows lists and default on for the active box.
1. Visolve import lists.
1. Terry duplicate appt bug fix (plan to help integrate this fix).
1. MD Support onsite patient portal signon update.
1. Terry mod of floating alerts.
1. Terry exclude insurance.
1. Visolve multi-provider bug fix.
1. MD Support PE form.
1. Terry HFCA printout.
1. Sherwin document drag and drop.
1. Art x10 4010 smackdown.
1. Sherwin auto save (pending issues by Brady and MD Support).
1. Sherwin prior auth form (pending issue by Rod).
1. Sherwin labs form (pending issues by Terry and Arnab).

### OpenEMR Project Admin
1. Convert github openemr account to an organization
1. Fix demo farm to not start apache until the entire install is done.(note no longer need to start apache earlier since the appliance serving the development translations is not pulling the translations from itself anymore)
1. Upgrade demo farm from Ubuntu 12.04 to 14.04/16.04.
1. Migrate website to server that can support SSL.
1. Upgrade wiki (mediawiki) to most recent version.

### OEMR Organization
1. Discuss registration project on forums and placemark it on the active projects page.
1. Discess Weno project on forums and placemark it on the active projects page.
1. Bring in all board members as members(still a couple members left to do: L,S) to allow bringing in new board members.
1. Revocation (turned in by Treasurer; awaiting reply).
1. Taxes (2015 turned in by Treasurer, although likely not needed until revocation complete).
1. Confirm registered agent and USPS address change.
1. New OEMR logo(have budget of $100).
1. Budget.
1. Fund-raising(options are donations grants, crowd-sourcing etc; d/w L regarding crowd-sourcing).

### MU2
1. Complete last item G3 (have 3 volunteers (R,J,J); now just waiting to get test ready).
1. Clarify MU2 testing history with Infogard (may be a couple gaps to fill).
1. Current budget is Visolve develop/testing G3 item fee which is $1500.

### MU3
1. Complete wiki planning page.
1. Current budget is about 31 developer months plus $22,000 testing fee. 

### OpenEMR Next Release
1. Plan release after get Complete MU2 Certification
1. Need to rebuild development ubuntu package since removed the /library/freeb directory.
1. In documentation for when upgrading to 4.3.1 or greater from a version less than 4.3.1, warn that it can take anywhere from 3 minutes to several hours (and will see a whitescreen until is is completed).
1. New ubuntu dependencies: none for now
1. For next ubuntu package, don't secure files needed for install if auto-configuration was not done.(low priority)
