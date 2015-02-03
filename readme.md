# Shannon

A JavaScript Library. Provides communication flow for your program systems.

Inspired by ["A Mathematical Theory of Communication"][1].

## Why?

Data management layer and view layer can be rewritten with new library, but communication flow will be the same.

## Ideas

 * Functional infrastructure
 * Unidirectional data flow
 * Declarative style

## Questions

 * What I'm trying to build?
 * What types of web pages will be supported by Shannon? (content pages, statefull apps)
 * How many instances can app has to stay simple? (2, 3)
 * How can we describe a protocol in communication system between app and user?
 * What about 3rd party libs for rendering and data persistance?
 * How can we manage a complex state of systems?
   * Is it possible to use only attrs for dynamic components?
 * Is it possible to abstract store instance to server implementation?

## License

MIT License

 [1]: http://cm.bell-labs.com/cm/ms/what/shannonday/shannon1948.pdf
 [2]: http://www.eden-study.org/articles/2006/abstraction-classes-sw-design_ieesw.pdf
 [3]: http://conal.net/papers/push-pull-frp/push-pull-frp.pdf
 [4]: http://shaffner.us/cs/papers/tarpit.pdf
 [5]: http://en.wikipedia.org/wiki/Control_theory
