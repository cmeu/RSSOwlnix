updates feed: https://xyrio.github.io/RSSOwlnix-site/updates.rss

2.5.5-beta
- fixed type check for preferences

2.5.4-beta
- updated httpclient to 4.5.6
- removed version+date from branding/about view (version still visible on start in splash screen)

2.5.3-beta
- updated eclipse rcp to 4.7.3a

2.5.2-beta
- fixed missing 256x256 program logo icon #14

2.5.1-beta
- added right to left sorting for title column of classic view (appends "<-" to Title column)
- linux: do not force xulrunner (PR: sciamano)

2.5.0-beta
- main program is now updateable (addons and translation available through Help/Install new Software...) * does not work correctly
- renamed to RSSOwlnix
- updated httpclient to 4.5.5
- updated eclipse rcp to 4.7.2

2.4.0-beta
- removed old update manager and added new p2 one (addons work so far)

2.3.0-beta
- runs with java 9
- https websites which needed JCE should work without it when jre 9+ is used. https://sourceforge.net/p/rssowl/discussion/296910/thread/6dc4a203/
- updated eclipse rcp to 4.7
- updated httpclient to 4.5.3
- fixed 2 (maybe) memory leaks

based on RSSOwl 2.2.1

---

how to build: https://github.com/Xyrio/RSSOwlnix/wiki/How-To-Build

wiki: https://github.com/Xyrio/RSSOwlnix/wiki

bug reports: https://github.com/Xyrio/RSSOwlnix/issues

addons repository: https://github.com/Xyrio/RSSOwlnix-plugins-addons

translations repository: https://github.com/Xyrio/RSSOwlnix-plugins-translation
