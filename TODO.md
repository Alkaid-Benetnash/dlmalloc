1. During destruction (e.g. destroy_mspace), current code does not munmap
   the right size (should be entire reserved size instead of allocated/mprotected size).
