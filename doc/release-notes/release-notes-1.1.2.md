Termucoin version 1.1.2 is now available from:

  <https://github.com/termucoin/termucoin/releases/tag/v1.1.2/>

This is a new version release, including important security updates and
changes to network efficiency. All Termucoin users - miners, services,
relay operators and wallet users - are strongly recommended to upgrade.

Please report bugs using the issue tracker at github:

  <https://github.com/termucoin/termucoin/issues>

Important Security Updates
--------------------------

This release contains fixes that harden node and network security. These fixes
are important for every node operator and wallet user.

Fee Recommendation
------------------

This release changes the recommended dust limit for all participants on the
Termucoin from 0.01 TERM to 0.00001 TERM. The full recommendation can be found
[in the documentation](fee-recommendation.md).

This change has been implemented in the wallet as the default value of
`-discardthreshold`,
