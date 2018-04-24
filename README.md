# ShitBlocker 💩🚫

This is a very simple Safari extension that blocks CSS on some distracting sites. This doesn't completely prevent you from accessing them, but it's enough to immediately remind you that you were supposed to be working and not mindlessly opening those sites.

I might develop this into a proper app one day and put it on the App Store, but in the meantime, feel free to use it to stop yourself from wasting time reading some shit.

(Yes, this is literally just a fresh Mac app + content blocker target from a template with one custom blocking rule. But as they say, if something looks stupid, but it works, it's not stupid...)

## Setup

* `git clone git@github.com:mackuba/ShitBlocker.git`
* open the project in Xcode
* change the development team in project settings to your account
* open the [blockerList.json](ContentBlocker/blockerList.json) file and add all the shit relevant to you to the list (a star before the domain name means this domain + all subdomains)
* build and run
* open Safari extensions preferences and enable ShitBlocker (you might need to restart Safari to see it there)
* profit

## Usage

The UI is pure minimalism, i.e. there isn't one:

* open Safari preferences and disable the extension when you want to read some shit (e.g. with the morning coffee)
* then open the preferences again and turn the extension back on when you want to stop reading shit and do some actual work

## Copyright

Licensed under WTFPL, obviously.
