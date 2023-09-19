# Assignment_1_OperatingSystem_PartyAnimals
A group of former high-school buddies decides to have a reunion. To celebrate, they organize a synchronized toasting party. In a synchronized toasting party, toasts are made by groups of 5 and work as follows. Each person fills her/his glass. Then, she/he raises his/her glass in preparation for the toast, and waits until there are (at least) four other buddies ready to toast. As soon as a group of 5 is ready to toast, each member of the group utters "Skol!" and then, only after all 5 have spoken, drinks up. Afterward, each individual mingles and eventually refills the glass, then waits for four other buddies to be ready for the next toast.

Use pthreads to simulate the reunion of 19 buddies (threads). Ensure a proper synchronization using semaphores (no condition variables, no barriers).

To simulate actions such as "fill glass" or "drink", use sleep( n ) where n is the number of seconds the action takes. Utterances ("Skol") are simple output messages. To spice things up, you can use a function such as rand() to generate a random number of seconds an action should take.

Groups of 5 are not predetermined; on the contrary, they must be formed on the spot as buddies are ready to toast. Moreover, in an effort to limit the disturbance caused to the neighbors who were not invited to the party, only one group can toast at a time.

Simulate for a length of time, say a couple of minutes. In the end, display the identifier of the individual who drunk the most, and of that who drunk the least.

