# CallerIDCheck

Two BASH scripts to interface with Asterisk to auto dial a list of numbers using a list of different outbound caller ID for each call. The calls last 11 secs or enough time to ring about 2 times. If the call is answered then a recording plays and the call disconnects. 

1. download files
2. chmod +x autocalleridcheck
3. chmod +x singlelinecheck

Use the scripts

1. Modify both lists with the numbers you need to check and call
1a. callerids.list 
(list of outbound called IDs the calls will come from)
1b. testphones.list
(list of phone numbers to call using the oubound caller IDs from the above list for each call)
2. ./autocalleridcheck

or

1. ./singlelinecheck 303-303-3031 720-720-7201
(call 720-720-7201 using the outbound caller ID of 303-303-3031)

