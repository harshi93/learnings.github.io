# Retransmitted till breakdown:

The first method they devised is called retransmitted till breakdown. The idea would be to send in messenger after messenger, hoping that one will eventually make it through without being captured.

# Exponential backoff:

Let’s say that every time you’re going to check your email you’re getting an error saying the server is overloaded.

In this case, the Exponential Backoff method can help. Instead of frantically hitting refresh, wait a couple minutes for the traffic to ease up. And if you’re still getting the error after that, double the waiting time to four minutes before trying again, and keep doubling until it gets through.

# Additive Increase / Multiplicative Decrease: 

To prevent the overload problem in the first place, a method called Additive Increase, Multiplicative Decrease (AIMD).

This algorithm helps you determine the maximum amount of data a network can handle. It starts by sending just one package of data; then it sends double the amount each subsequent time until it reaches the point of overload.

Then it tries to pinpoint the limit by sending the highest amount before the failure occurred and increasing the subsequent packages by a tiny amount until the limit is reached.

# Bonus Facts:
Rested employees are more performant than the overworked ones