NB: These items are copied verbatim from OBSIDIAN and include WIKI STYLE links that will not work as copied (needs update, but checking into repo as is to document the process)

First, need to mimic STS with MyriadView

	- added nav page component: MyriadView
		- copied MyriadView from [[STS]] to views/ folder (using "New File..." in VSCode and "Copy Raw Contents" on Github)
		- copied MyriadLinks from [[STS]] to components/ folder (same as last step)
		- added MyriadView to router/index.ts, see [[STS]]
		- added router-link to App.vue, see [[STS]]
		- updated MyriadView and MyriadLinks to replace [[BALG]] data and branding where [[STS]] data and branding was in the raw copies from GitHub

Then, add CourseView:

	- added nav page component: CoursesView #balg/done 
		- copied CoursesView from MyriadView in views/ folder (using "Copy" and "Paste" commands directly in the Explorer Pane of VSCode, renaming the autgenerated copy name, and then updating the content and references as appropriate)
		- copied CoursesAnnouncement from MyriadLinks in components/ folder
		- added CoursesView to router/index.ts, see [[STS]]
		- added router-link to App.vue, see [[STS]]
		- added [[BALG SCA Blurb]] content to Anouncement page