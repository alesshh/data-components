[vue]: http://vuejs.org
[riot]: http://riotjs.com
[react]: https://facebook.github.io/react

# FAQ

## What does "unstable" mean?

It means that the project may have larger, potentially breaking changes that will occur during iteration towards the next even numbered (stable) release. It will contain all of the latest code and bug fixes, but will have higher volatility and churn than the stable branch while we work out all of the bugs in new release.

## "Why don't you use that other library?"

So why not just use something like [Vue][vue], [Riot][riot] or even [React][react]? Well, they're full featured UI libraries that offer way more than I usually need. Some features provided by such libraries that `data-components` don't care about at all:

* Reinvent Web Components
* Rendering Performance
* Templating
* The component API
* Data binding
* Dependency injection
* Event system
* Messaging system
* Fancy stuff like filters and directives
* Programming paradigm

We just use regular data attributes and a list of ids (component name) that correspond to a simple function (component implementation).
Just look at the source code, there's really not much to it.
