# Find property information: terms of use

repo contains markdown version of the terms of use for gov.uk service Find property information.
we previously called this the terms and conditions.

## Last Updated
* Mon 7th August, 2017 - tag release - 1.3.0
* Mon 7th August, 2017 - accounts not being deleted after 12 months
* Tue 6th June, 2017 - tag release - 1.2.0
* Tue 6th June, 2017 - you can download a copy of the summary
* Wed 31st May, 2017 - tag release - 1.1.0
* Wed 31st May, 2017 - change organisation name to HM Land Registry
* Wed 24th May, 2017 - initial release tag - 1.0.0, and update release/tagging concept
* Wed 1st March, 2017 - to match agreed version in Google drive - doc V1 28-02-17

## Notes
* this is currently duplicated inside the prototype.

* this set of T and C may be different to the live build 

## In progress - Speak to Andy P
* Versioning strategy experiment - to support
	* improved workflow
	* ability to prove when a change was made / who made it
	* semantic versioning
	* consuming application to auto generate change history

### Tagging / semantic versioning
* To show history of change - add a line to the readme - date and summary of change
* Create a release and version / label it for proof and to allow consumer applications (FPI) to show a change log

#### How to version - proposal
* draft a release
* set tag version, based on the idea of [semantic versioning code](http://semver.org)
* Given a version number MAJOR.MINOR.PATCH, increment the:
	* MAJOR this version not backward compatible - e.g. legislative change, whole topic change, or significant rewrite, personal information change, data collection or retention change.
	* MINOR when changing a whole paragraph or lot of 'small changes' accross many paragraphs. 
	* PATCH when plain Englishing a sentence or fix a typo
	* example: changing "Land Registry" to "HM Land Registry" is MINOR: 1.0.0 --> 1.1.0
* give plain English title (would make sense to a user - this will be shown to the user)
* give plain English description (would make sense to the user - this will be shown to the user)



## todo - ideas - Speak to Andy P
* workflow for changes to this repo - e.g. lock the master branch
* get everyone working from this version of T and C
* make prototype consume this repo / md automatically
* make real front end consume this repo
* label changes to allow front end to consume signed off version of T&C - and be able to show changes (we could show to the user, the changes since last 'i accept the terms and conditions'
* prove in a court - when a change was made / who made it