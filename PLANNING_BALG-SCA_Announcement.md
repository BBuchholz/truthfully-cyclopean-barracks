NB: These items are copied verbatim from OBSIDIAN and include WIKI STYLE links that will not work as copied (needs update, but checking into repo as is to document the process)

First, need to mimic STS with MyriadView

	- [ ] add nav page component: MyriadView
		- [ ] copy MyriadView from [[STS]] to views/ folder
		- [ ] copy MyriadLinks from [[STS]] to components/ folder
		- [ ] add MyriadView to router/index.ts, see [[STS]]
		- [ ] add router-link to App.vue, see [[STS]]

Then, add CourseView:

	- [ ] add nav page component: CourseView
		- [ ] copy CourseView from MyriadView in views/ folder
		- [ ] copy CourseLinks from MyriadLinks in components/ folder
		- [ ] add CourseView to router/index.ts, see [[STS]]
		- [ ] add router-link to App.vue, see [[STS]]