# Introduction #
There has been quite a lot of development recently on BU. I have actually decided to not release the next 2 versions which have already been made due to many bugs - however the next version which is currently being developed has all these issues fixed already, i'm implementing a few new features which is why I have deciden not to release it yet But it will be available very soon


# Details #

Changes:
  * The Copy method is completely different in the new version, far more stable and with 100% success rate so far.
  * The new copy method uses a temp folder to avoid problems when backing-up to the same directory
  * Added calculation for the backup size, and automatically displays how much space is on the destination folder/drive and how much space is left on the temporary drive
  * Added - if there is not enough space on the temp/destination drive, you will be notified, and backup will not continue.

TODO:
  * Eliminate the need of the temporary folder if backing up to a different drive - This will save on time and will not matter if there is not enough space on the temp folder.
  * Adding Progress (may even leave this in the next version)
  * dding Registry Backup