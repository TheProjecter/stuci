STUCI is most commonly used to connect a UCI chess engine to a Yahoo chess server.

There are two variants of STUCI.
1. STUCI Classic
2. STUCI Windows

They both generally do the same thing, which is allow a user to connect to the Yahoo chess server and play chess, in many cases, with an engine, but not always.


STUCI Classic is based on YtoICS code which was coded in the Perl scripting language. It is mostly text-based, though you can connect a GUI-based client such as Winboard to view a chessboard. It's been around for a couple of years now and changes to its code happen infrequently because it is very stable already.


STUCI Windows is based on the promising Chessy client, and meant to compete with easy-to-setup Chess Buddy. It was coded in C#. It provides it's own GUI and chessboard and requires no external programs except maybe the user's favorite chess engine.


Both programs will eventually support multiple protocols to login. The two major ones are common Yahoo-JAVA and newer Yahoo-FLASH. It should be extensible to support other non-yahoo server protocols as well.