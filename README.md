
CashCow development tree
================================

http://www.cashcow.com

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2014 CashCow Developers


What is CashCow?
------------------

CashCow is a PoS-based cryptocurrency.  After an initial PoW period,
CashCow switches to PoW/PoS before eliminating PoW permanently.  CashCow
derived from the BlackCoin code base, which is derived from NovaCoin.

CashCow is intended to be a proof of concept of the definite stake reward idea.  For more
information about this idea, please see the Proof of Stake: Definite white paper.


License
-------

CashCow is released under the terms of the MIT license. See `COPYING` for
more information or see http://opensource.org/licenses/MIT.


CashCow Features
------------------

* 72 second block spacing
* PoW/PoS for the first 150,000 blocks, yielding ~900 million to 1 billion coins
* The PoW subsidy decreases every 5 days at a predetermined rate (7% every 5 days after day 15)
* The maximum PoW reward is 24,000 coins
* CashCow has virtually no hard cap, but grows at ~5% annually using PoS
* CashCow uses a new PoS derived from BlackCoin PoS 2.0 called Proof of Stake: Definite that rewards definite stake rewards of 120 COW per block 

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
stable release versions of CashCow.

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
