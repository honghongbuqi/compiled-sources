===============================
find compiled sources in kernel
===============================

Usage::

   1) locate all output files in dir/

      $ make O=dir [targets]

   2) generate 'cscope.files' in dir/

      $ [KBUILD_ABS_SRCTREE=1] cs [dir/]
