# Knight in Knight
This is a knight implementation within knight.

few notes:
Calling convention: 
	- Variables that begin with two `__` are global variables for functions and shouldn't be touched.
	- Variables that begin with `_` should be restored by the callee.
	- Arguments to functions should not be modified unless explicitly stated.
	- All other variables need to be saved by the caller.