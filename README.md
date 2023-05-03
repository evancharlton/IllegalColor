# Illegal Color

This is a demo app to demonstrate a problem with the Android SDK.

## The problem

In `colors.xml`, this app specifies an illegal hex code: `#0xE1E1E1`.
The app compiles & installs just fine, but fails to run.

## The solution

This shouldn't have been allowed to be compiled - `#0xE1E1E1` is not a valid
hex code.