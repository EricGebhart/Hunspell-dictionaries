These are hunspell dictionaries.

[check out hunspell here](https://hunspell.github.io/)

The basic requirements are _.dic_ and _.aff_ files. hyphenation files are prefixed with *hyph_* for 
instance *hyph_en-us.dic*. Thesauraus files have an extension of .dat.

[Read more here.](https://en.wikipedia.org/wiki/Hunspell)


There are two sets of dictionaries in this repository, 
one is just pure hunspell dictionaries, the other are dictionaries 
from Open Office and Mozilla / Firefox.

Each directory has it's own install script which will install all the 
dictionaries it has in _/Library/Spelling/_.

The hunspell dictionaries are a simple zip file with a _.dic_, a _.aff_
and a description.

Open Office uses an extension of _.oxt_ for it's dictionaries and 
Mozilla uses _.xpi_.

Both types of files are actually zip files, change the extension to zip,
unzip it and find the _.dic_ and _.aff_ files inside..

Open office dictionaries are available here.
[open office dictionaries] (http://extensions.openoffice.org/en/search?f[0]=field_project_tags%3A157)

Mozilla / Firefox dictionaries are here.
[Mozilla dictionaries] (https://addons.mozilla.org/en-US/firefox/language-tools/)

The only real difference beyond that is that the xpi files keep
the dictionaries in a sub folder named dictionaries.

The install script accommodates both kinds of files and installs
the dictionaries in _/Library/Spelling/_ the default location for
dictionaries on OS X. Alternatively they can go in _~/Library/Spelling/_ but
why bother ?

If you only wish to install a few dictionaries, unzip them and
copy the _.dic_ and _.aff_ files to _/Library/Spelling/_.

