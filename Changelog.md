Changelog for SpamAssassin DQS Plugin 

- 250820
	- Fixed issue with wrong usage of check_rbl_sub()
	- Scores adjusted to work with the default SpamAssassin required_score of 5
	  This is a work in progress, scores may change again in future based on feedback

- 270520
	- Added SA version checking at lint time

- 190520 (v.1.1.0)
	- Tagged version 1.1.0 (no code changes)
	- Same tag as Rspamd plugin with HBL

- 300420
	- Added a Changelog file :)
	- Made the plugin compatible with SpamAssassin 3.4.1
	- Added support for the HBL zone
	- Various fixes
