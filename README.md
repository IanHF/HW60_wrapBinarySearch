# HW60_wrapBinarySearch

2. Recalling inverse functions and logarithms:

'y = log[base 2] times x' definition:

	y equals whatever two must be raised to in order to get x. The graph of this equation shows growth which is constantly slowing(but still growing) as x approaches infinity.

3. Recursive solution description:

	0. Problem:
		To search a list for the recovery of the index of a given value.
	1. Abstraction:
		When I am asked to search a list for the recovery of the index of a given value, I will make a decision whether or not to divide my search in half(either above or below one of my boundary values) or to apply a base case for a correct value.
	2. Correspondence to generalized recursive abstraction:
		Decision - should the search be concluded or be divided into half of the currently examined list?
		Base case - return the index of the value found to match the given
		Recursive case - divide the searched list in half, searching the new smaller list
			Minimum - a tiny list, consisting of only one invocation
			Normal - a small-large list, consisting of 2 significant figures of invocations
			Extreme - a very large list(perhaps thousands or millions of elements)
