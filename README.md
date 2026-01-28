## What's this "smol" business?

I'm currently trying to kinda just rebuild a functioning PHP framework/library environment from scratch, but with a very different philosophy than the big dogs. I'm focusing on building libraries that eschew kitchen sink approaches and designs that are meant for massive scaling and complex execution environments, in favor of simple solutions that work fine with less complexity in what I'm calling "human-scale" software, or "software permaculture".

Why would I do this? I've been weighing the balance between using say a big framework like Symfony vs rolling your own microframework made of small, digestible libraries.

The thing is that a line of code is more often a liability than an asset, and pulling in a massive kitchen sink library that might be hundreds of thousands of lines might not be smart depending on your goals.

If you want to make a site that works in 20 years, internalizing maintenance of a handful of 1k-LOC-ish libraries that are easy to reason about and work on might actually be better than getting stuck needing patch some 100k-LOC-ish framework for a decade.

Conventional wisdom is that using a framework saves you writing code, but here's the thing: writing code isn't that hard. Writing maintainable code is hard, and what "maintainable" means changes a lot as the timescale you think at expands from quarterly reports to decades of institutional use.

If you commit to a full framework or massive CMS you're putting a LOT of trust in that project to govern and maintain itself, and if that stops you're hosed.

Similar to actual permaculture, this approach only works if you're staying put and patient. If you're farm-hopping every two years (i.e. changing job constantly) or need massive harvests fast (i.e. VC startup sprint mode), the monoculture makes sense (in that context anyway).

But if you're building institutional websites that need to be useful on timescales measured in decades? You shouldn't be building an industrial farm. You should be building a software food forest. Mature, productive, self-sustaining systems that get easier to maintain over time rather than harder.
