ADD_LIBRARY(cliopts OBJECT cliopts.c)
SET_TARGET_PROPERTIES(cbsasl-lcb PROPERTIES COMPILE_FLAGS "${LCB_CORE_CFLAGS}")
