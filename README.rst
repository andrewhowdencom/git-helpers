Project Outline
----------------

Project Goals
`````````````
1. Provide some helper scripts to make the more mundane git tasks easier. 

This is made quite a bit easier by a git behaviour that makes a script with the syntax ``git-foo`` available with the command ``$ git foo``. 

Summary
```````
============= ============ ==============
License       Code Style   Code Locale
------------- ------------ --------------
Apache-2      Existing     en-AU [lang]_
============= ============ ==============

Installation
------------
- Clone the repository
- Add the bin directory to your $PATH
- ???
- Profit

Usage
-----

There are no commands at the moment. I'll try to ducment them as I write them.

git-mark
````````

Store keys and values using the git notes behaviour::

  $ git mark foo bar
  $ git log

  commit 9607819bc585ffb0c8d7b5448fce17806e031d44
  Author: Andrew Howden <hello@andrewhowden.com>
  Date:   Sat Apr 9 18:13:57 2016 +1000

      Add Apache license

      Notes:
          state: hairy
          foo: bar


Contributing
------------
Contributions are always welcome! I mirror my work on GitHub, however, if you'd like to open an issue I'd love the feedback!

References
-----------
.. [lang] Lingoes.net,. (2015). Language Code Table. Retrieved 4 June 2015, from http://www.lingoes.net/en/translator/langcode.htm
