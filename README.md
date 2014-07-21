
BlankCoin development tree
================================

http://www.blankcoin.com

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2014 BlankCoin Developers


What is BlankCoin?
------------------

BlankCoin is a PoS-based cryptocurrency.  After an initial PoW period,
BlankCoin switches to PoW/PoS before eliminating PoW permanently.  BlankCoin
derived from the BlackCoin code base, which is derived from NovaCoin.


License
-------

BlankCoin is released under the terms of the MIT license. See `COPYING` for
more information or see http://opensource.org/licenses/MIT.


BlankCoin Features
------------------

* 1 minute block spacing
* PoW for the first 100,000 blocks, yielding 1 billion coins
* The PoW subsidy decreases each week at a predetermined rate
* The maximum PoW reward is 20000 coins
* BlankCoin has a maximum coin cap of 2 billion coins


Development process
-------------------

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
stable release versions of BlankCoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'.
