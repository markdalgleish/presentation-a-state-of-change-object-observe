# &ldquo;A State of Change&rdquo;
## &mdash;On the future of Object.observe

### References

[The Future of JavaScript MVCs &mdash; Introducing Om](http://swannodette.github.io/2013/12/17/the-future-of-javascript-mvcs)

[Mori](swannodette.github.io/mori/)
A library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.

[immutable-js](https://github.com/facebook/immutable-js)
immutable provides Sequence, Range, Repeat, Map, OrderedMap, Set and Vector by using lazy sequences and hash maps tries. They achieve efficiency by using structural sharing and minimizing the need to copy or cache data.

[React](http://facebook.github.io/react/)
React uses a virtual DOM diff implementation for ultra-high performance. React implements one-way reactive data flow which reduces boilerplate and is easier to reason about than traditional data binding.

[virtual-dom](https://github.com/Matt-Esch/virtual-dom)
A JavaScript DOM model supporting element creation, diff computation and patch operations for efficient re-rendering

[Om](https://github.com/swannodette/om)
A ClojureScript interface to Facebook's React. Because ClojureScript data is immutable data, Om can always rapidly re-render the UI from the root. Thus Om UIs are out of the box snapshotable and undoable and these operations have no implementation complexity and little overhead.

[mercury](https://github.com/Raynos/mercury)
"A truly modular frontend framework" (Needs better docs...)

### Quotes

"Object.observe() is going to be the next with statement: a weird language idiosyncrasy solving a problem that wasn't very important."
[Pete Hunt &mdash; Twitter, 22 May 2014](https://twitter.com/floydophone/status/469214241732714497)

"Object.observe(data, function(){ throw new Error('NO') });"
[Nicolas Gallagher &mdash; Twitter, 22 May 2014](https://twitter.com/necolas/status/469257290084646912)

"Back when Object.observe was first announced, I was so excited. Today I'd much rather have proper support for immutable data structures."
[Pascal Hartig &mdash; Twitter, 22 May 2014](https://twitter.com/passy/status/469127322072014849)

"Great to see the TAG acknowledge how @reactjs has shaken up data binding on the web and requires rethinking. #MeetTheTAG"
[Pascal Hartig &mdash; Twitter, 1 Oct 2014](https://twitter.com/passy/status/517019680226410498)

"They just used it as an example for a problem that appeared to have enough common solutions that it could be standardized."
[Pascal Hartig &mdash; Twitter, 1 Oct 2014](https://twitter.com/passy/status/517025422941626369)

"But then React came along and all of a sudden it's not that clear anymore."
[Pascal Hartig &mdash; Twitter, 1 Oct 2014](https://twitter.com/passy/status/517025555901075456)

"just because it's in a spec doesn't mean it's The Future™"
[Pete Hunt &mdash; Twitter, 12 Aug 2014](https://twitter.com/floydophone/status/499082460555005952)

### Further Reading/Watching

[ES Wiki - Object.observe](http://wiki.ecmascript.org/doku.php?id=harmony:observe)

[The Value of Values [Video] &mdash; Rick Hickey, creator of Clojure](https://www.youtube.com/watch?v=-6BsiVyC1kM)

[Flux](facebook.github.io/flux/docs/overview.html)
