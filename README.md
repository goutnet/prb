prb
===

# This script is intended to help PRB member to facilitate their review process
# for this to work, you must create a directory (change the variable prb_base) that contains
# various installations of c5 named concreteVERISION, a directory called after the variable archive
# and another one called after the variable reviews :
#
# example :
#
# . ${prb_base}
# |
# +--- concrete5.6.0.2          # installation of c5 version 5.6.0.2
# +--- concrete5.6.1            # installation of c5 version 5.6.1
# +--- ${archives}              # directory that will contain all archives
# +--- ${reviews}               # directory that will contain extracted directories
# 
# this script configuration is at the end of the file (this script can actually be used as a lib too)

To get an idea of the commands just run "prb --help" or just "prb"
