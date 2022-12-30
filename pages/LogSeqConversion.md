alias:: LogSeq Conversion

- The conversion of [[BMC/Garden]] to #LogSeq
- DONE Figure out how to include the ~~blog and~~ [[BMC/Archive]] for searching and linking
  collapsed:: true
	- Technically included in the graph now
	- Trying out `archive:: true` and changing `created` from a Unix time stamp to a LogSeq compatible and human readable `Jun 1st, 2003`
	- I might use the #published property instead of created since that’s what I already use for external articles
	- Maybe I’ll just slowly convert? I think so!
	- Pages remain in the same folder, but with a filename the same as the page name
	- #completed [[Dec 27th, 2022]]
- TODO Move posts out of _posts structure
	- Keep an archive folder and a blog folder
- TODO Convert more recent blog posts
	- Needs a plan for footnotes, currently uses [[Littlefoot]] which I quite like
	- LogSeq supports Markdown footnotes already, so let’s just make a backlog item
	- LATER Support [[Littlefoot]] for footnotes in published LogSeq [[BMC/Backlog]]
- TODO Flow for new blog posts
	- Use #published to give them a date
	- ~~Tag them with #blog~~
	- Use property [[BMC/Blog]]
	- Turn off outline bullets / special styling?
- TODO What goes on the home page, how to theme a custom home page for LogSeq
- TODO Troubleshoot Fission publishing
- TODO Switch back to main bmannconsulting domain / main branch of repo
- TODO Theming for static LogSeq sites
- TODO Write up feedback to the [[logseq-publish]] repo, including feature request for non-hash based routing
-