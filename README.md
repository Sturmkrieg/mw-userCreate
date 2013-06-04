mw-userCreate
=============

Modified createAndPromote.php maintenance script for MediaWiki that allows administrators to specify specific user groups to add to new accounts, rather than the fixed sysop and bureaucrat groups.  This fixes problems of not being able to auto promote users to other user groups upon creation.  Adding groups in the same manner as bureaucrat was unacceptable because many groups are not used in the MediaWiki core.
