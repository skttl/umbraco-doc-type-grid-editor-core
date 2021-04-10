# Doc Type Grid Editor for Umbraco 9 (net core)

Hi there Umbraco Grid fans - this is my WIP of the port of Doc Type Grid Editor for the upcoming Umbraco 9.

First a few disclaimers
- I have never worked with .net core before. Don't expect me to be able to fix or answer everything.
- My goal is to have a comparable version of DTGE ready for v9
- I am probably going to need (a lot of) help fixing issues with this
- DTGE is in my opinion feature complete - I don't want to add any new features

You are welcome to take the code for a spin, so far the following works:
- When adding content to a grid, Doc Type Grid Editor comes up, and you can select the desired doc type, fill in content and save.
- Frontend rendering works - as long as you have a view in `[viewPath from config]/[contentTypeAlias]`. The old DTGE would first try to look up by the editor alias, but I can't get the view-lookup to work.

Check out the issue tracker for known issues. All issues need help, so if you want to see DTGE happen for Umbraco 9, then this is where you are needed!