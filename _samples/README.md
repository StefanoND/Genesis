# Samples

\_samples contains sample projects demonstrating some of the game systems built,
so it can be messed around and see how things should look by default.

This directory is specifically filtered out of game exports. This is never
intended to be used in any game code. So there's no reason to include them in
official game builds.

The reason I don’t do this with _debug as well is because I have to reference the debugging global in my game code to make use of the debugging tools, and I haven’t yet come up with a place to house my debugging global somewhere that makes sense other than in _debug itself. As mentioned before, this is running with a slightly imperfect solution, and if I come up with something that’s better I’ll work it in.
