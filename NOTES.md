# Introduction

[...]

And today I'm here because I'd like to talk to you about, well, monads and stuff.

Not because they're useful - although they are, just maybe not quite the absolute requirement some make them out to be - but because, well. Anybody that's anybody in FP has written or spoken about them, and I'd really like to be somebody that's somebody at some point. So there were are.

I realise that this might not be the best way to motivate attendants, so here's my promise to you: if you stick with me to the end, you will understand what these abstractions are (although not why they're called the way they are, let's not get carried away), why and when you might need them and, just as importantly, when you might not.

Now, I'll be using Scala to illustrate things, and Scala in its most modern incarnation. The issue with that is that the community seems to have landed on a few new idioms that are particularly noisy and boilerplatey and, in my opinion, just generally unpleasant. Slides contain complete and valid code so that you can paste it in a REPL session and play with it later, but you absolutely do not need to understand it all. I'll be explaining the intent of the code and if you can follow that, it's enough. Do not allow yourself to become discouraged because the syntax for extension methods is an exercise in obfuscation, it really doesn't matter to the point of the talk.

As usual, I'll be using a slightly romanticised version of personal experience to illustrate these concepts. Here, the release of the PlayStation 5 - don't know if you're into games, but when this came out, it was *really* hard to get your hands on one. So hard, in fact, that it was almost reasonable to write some code that'd monitor known resellers for deals or just simple availability and notify me immediately.

# Conclusion
