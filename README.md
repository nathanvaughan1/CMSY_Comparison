# CMSY_Comparison

Three comparison CMSY model implementations.

#----------------------#
# CMSY_O_7q_Original.R #
#----------------------#

This is the original code written by Rainer Froese, Gianpaolo Coro and Henning Winker to 
estimate r, K, and MSY from a catch time-series dataset.

#------------------------#
# CMSY_O_7q_Vectorized.R #
#------------------------#

This is a modified version of the original CMSY function, written by Nathan Vaughan, that 
incorporates vectorized code to speed model run time.

#-----------------#
# CMSY_O_7q_New.R #
#-----------------#

This is a modified version of the original CMSY function, written by Nathan Vaughan, that 
incorporates vectorized code, modified parameter sampling logic, and automatically  adjustable
depletion priors to speed model run time and improve fitting success.
