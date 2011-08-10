# A collection of Doctrine1 patches

I had them lying around. Some of them are actually needed and
fix things, some of them are performance improvements and
some of them are probably not so useful.

The most interesting patch would probably be ```collection-add-performance.patch```
which very much improves the speed of object hydration and is really needed when
dealing with thousands of records per collection (but helps with smaller colletions
too).

They all should apply on top of Doctrine 1.2.4 and the ```series``` file is included
to show the order should that matter at all.

Feel free to (not) use them however you like.
