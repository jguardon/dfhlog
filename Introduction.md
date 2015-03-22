# Introduction #

Hamradio operators need to log their contacts into a Logger Application, spreadsheet or similar. Since a number of them still are using MSWindows as O.S, and they want to definitely migrate to Linux, the lack of related applications is slowing down this migration.

**dfhLog**, yet under development, may be the piece of software which Hamradio Operators were waiting for to jump definitely to Linux Systems.


# Details #

Linux General purpose Amateur Radio logging application, written in Gambas2, as the current offer on this subject is very limited. Uses hamlib to control radios and xplanet to plot spots from clusters on maps. Also, uses custom maps to keep track of Maidenhead Locators worked on all bands. It's able to import/export from other programs from/to the well known ADIF format. Databases are sqlite3 for better portability. Developing using the last stable version of 'Gambas 2' in a Ubuntu box.


License: GNU General Public License (GPL) (gpl)