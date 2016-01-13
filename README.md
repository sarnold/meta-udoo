OpenEmbedded/Yocto BSP layer for the UDOO i.mx6 based boards
===========================================================

This layer provides support for UDOO i.mx6 family based platforms for
use with OpenEmbedded and/or Yocto Freescale's BSP layers.

This layer depends on:

URI: git://git.openembedded.org/openembedded-core
branch: master
revision: HEAD

URI: git://git.yoctoproject.org/meta-fsl-arm
branch: master
revision: HEAD


Contributing
------------

To contribute to this layer you should the patches for review to the
mailing list.


Source code:

    https://github.com/graugans/meta-udoo

When creating a patch of the last commit, use

    git format-patch -s --subject-prefix='meta-udoo][PATCH' -1

To send it to the community, use

    git send-email --to ch@ege.io <generated patch>

Patches are normally intended for the master branch.

Patches for other branches should be sent separately so they can be tracked
individually in Patchwork and should have the branch name in brackets.

For example, use this to generate a patch for branch 'dizzy':

    git format-patch -s \
	--subject-prefix='meta-udoo][dizzy][PATCH' -1
