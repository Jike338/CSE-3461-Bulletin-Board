Bulletin-Board-System
The client server application simulates the news bulletin board system, and uses socket programming and multithreading to realize the server

Dependencies:
Python 3.10

Author: Jike Zhong, Haojia Feng

Instructions:

cd part1 (or part2)

Compile the server:
python3 server1.py --port 8888
Compile the client:
python3 client1.py --port 8888


Notice: Work in Mac system when applying this to Windoes system, because select methoud is different from Windows and Mac, it only can be used in Mac

Functionality:


For part 1:
%join             : Join the discussion board
%help             : Display commands again
%quit             : Quit the chat room
%users            : View users in this discussion board
%message <id>     : View the content of a message
%leave            : Leave the discussion board
%post <subject> <content>: Post to the discussion board

For part 2:
%groups                                  : View available groups
%mygroups                                : View the groups you have joined
%groupjoin <group_id>                    : Join a group
%help                                    : Display commands again
%quit                                    : Quit the chat room
%groupusers <group_id>                   : View users in this group
%groupmessage <group_id> <message_id>    : View the content of a message
%groupleave <group_id>                   : Leave the group
%grouppost <group_id> <subject> <content>: Post to the group