# The Events Calendar Dash Docset

A docset of [The Events Calendar][1] WordPress plugin by [Modern Tribe][2] for the popular Mac OS X app, [Dash][3].

## Installation

1. Download a Zip archive of this repository
2. Extract the file to your Desktop
3. Copy **The Events Calendar.docset** to `~/Library/Application Support/Dash/Docsets/The Events Calendar`
4. Launch Dash
5. Open Dash's Preferences (⌘,) then select the **Docsets** tab
6. Click the **Rescan** button
7. _The Events Calendar_ will appear in the list of installed Docsets

## Alternate Installations

If you prefer using a Terminal to the Finder, use the following commands:

1. `mkdir -p ~/"Library/Application Support/Dash/DocSets/The Events Calendar" && cd "$_"`
2. `curl -#OkL https://github.com/ryanjbonnell/The-Events-Calendar.docset/archive/master.tar.gz`
3. `tar -xzf master.tar.gz --strip-components 1 && rm master.tar.gz`
4. `open "The Events Calendar.docset"`

An even more succinct version is:

`mkdir -p ~/"Library/Application Support/Dash/DocSets/The Events Calendar" && cd "$_" && curl -#kL https://github.com/ryanjbonnell/The-Events-Calendar.docset/archive/master.tar.gz | tar -xz --strip-components 1 && open "The Events Calendar.docset"`

## Changelog

**Version 3.5.1** (01 April 2014)

[1]: http://tri.be/shop/wordpress-events-calendar/
[2]: http://tri.be/
[3]: http://kapeli.com/dash