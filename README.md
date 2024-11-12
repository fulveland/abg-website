# Alberta Basketry Guild Website

### Building

#### Terminal tab 1
Run Ivan's special shortcut `cds` to cd into your sites folder. Then run `cd abg-future` to cd into the abg-future folder.    
	*cd means change directory

Run `cake start` to work on the project locally on your computer.

#### Terminal tab 2
Run Ivan's special shortcut `cds` to cd into your sites folder. Then run `cd abg-future` to cd into the abg-future folder.    
	*cd means change directory


Run `git s` to see the *status* of your git repo

Run `git aa` to *stage* all changed files
- Advanced: You can also stage just some of the files

Run `git cim "my message"` to commit all staged files

Run `git push` to push all commits to github

### Folder structure

* `public/` — Destroyed and rebuilt on every change, so don't put anything in here.
* `source/`
  * `pages/` — Any HTML files in here are wrapped with `_template.html`, then copied to `public`.
  * `scripts/` — Any scripts in here are concatenated and compiled to `public/scripts.js`.
  * `styles/` — Any stylesheets in here are concatenated and compiled to `public/styles.css`.

### Notes

When linking to a page, don't include the `.html`
* Good: `<a href="/about">`
* Bad: `<a href="/about.html">`



