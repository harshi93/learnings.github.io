# Multi Armed Bandit Problem:
Multi-armed bandit problem are those questions that requires you to deal with dilemma of how long to stick with loosing option before you move on to next option.

# Stay win /Lose Shift:
The easiest approach to improving your odds at the slot machines is called “stay-win, lose-shift” – but it may not be the best strategy.

All you have to do is stick with one machine as long as you’re winning and shift to another one once you lose. But this approach can be misleading since a one-time loss isn’t the best indicator of how your luck will turn out.

# Upper Confidence Bound: 

The algorithm takes into account occasional loosing, this is the best option.

Here’s how you use it: First, find the machine that offers the best expected value for playing. In this case, the only information you have is the jackpot counter, so you pick the one with the biggest jackpot. As you’re playing, keep track of the real outcome – in this case, how much money you’re winning – and note whether it’s gradually getting better or gradually getting worse than you’d expect. If the real outcome is continually disappointing you, that’s when you move to the next machine with the second biggest jackpot. And so on.

Since this algorithm takes into account the fact that a good machine can still provide an occasional loss, it increases your chances of winning.