timetracker
===========

This is just a toy project to get to know GitHub and other tech a bit better. Time tracking is a fairly trivial domain but not everybody does it well, my employer included. So, this is where I'll start. It may be trivial yes, but it might still be great!

I see 3 components for this software:

+ a funky client. Can be native android, ios, etc. Could be a webclient.
+ backend, capable of storing times for many users, and many clients.
+ a backoffice where clients can manage how their users are to book their times, i.e. what booking positions are available, how much time can be booked on each position etc.

The client should be able to operate well for the user without the need of the backoffice. The backoffice provides the actual booking positions needed by a company's time management system, but the system should be useable by lone users as well without backoffice data. Also the client should be such that bookings can be made and organized on the client before the backoffice has sent data for that booking period. The data would be the booking positions, amounts to book etc as mentioned above. When this data is sent later, for example at the end of the month, then it should be posible to allocate this to the bookings already on the client. I think that this would be pretty awesome if done well!
