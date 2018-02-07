# Assignment11
Regular expressions

Something that you'll be asked to do as a coder is to work with [regular expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions), also known as regex.

## Setup
There are many JavaScript functions and modules which utilize regular expressions and the syntax may slightly vary in the calling method.

Additionally, there is a command line (UNIX) program named `sed` which allows you to modify text files in place. We'll be using this program in a terminal to practice the syntax of regular expressions.

Ref:  [digitalocean](https://www.digitalocean.com/community/tutorials/the-basics-of-using-the-sed-stream-editor-to-manipulate-text-in-linux)
Ref:  [lifewire](https://www.lifewire.com/example-uses-of-sed-2201058)

## Exit criteria
Use the included text file in this repository to practice editing it in place.

* Write a series of regular expressions using `sed`. You may find it easiest to practice first using the `` argument before changing this argument to `` to do the actual edit.
  * Look for the `key:` variable and remove the value seen there
  * Look for the `upnpUuid;` variable and replace this with `11111111-2222-3333-4444-555555555555`
