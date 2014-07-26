mailmate-bundles
================

Bundles for the MailMate OS X email client

## Open Case in Fogbugz

Adds a command to quickly open a FogBugz case referenced from a FogBugz status email.  

Can be activated from the `Commands` menu, or with the "F" keyboard shortcut.

To use, you must set one variable:

```
defaults write com.freron.MailMate FogBugzDomain -string "flightaware.fogbugz.com"
```

