Building

- open site.xml
	- click build all
	- delete content.jar and artifacts.jar (current eclipse builds these with wrong content and they aren't needed)

------------------------------
Re-building and local testing

- start eclipse with -clean on any reinstall of feature
- when testing remote update site, may need to delete eclipse cache in .eclipse/org.eclipse.oomph.p2
- sometimes need to restart eclipse when updatesite will not build
- delete existing plugins of current version.  Will not overwrite with new versions sometimes.