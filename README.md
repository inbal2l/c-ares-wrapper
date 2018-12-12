# c-ares-wrapper

This API is created as an attempt to provide orginized wrapper for the c-ares lib. 
It distinguishes c-ares a-synchronic DNS retriving behaviour from the application's syncronic (or other) Event Loop.  
Hopfully, it will enable implement c-ares more easly in applications.

NOTICE: It can also be used to implement c-ares lib with different types of job schedualing in the application. (such as threads, etc.)
