# coding-standard

* KISS / DRY / YAGNI / Pareto's 80-20 Law
* Complexity considered harmful.
  * Shorter is preferred over longer.
  * Doing less is preferred over doing more.
  * Being ad-hoc and specific is preferred over being generic.
  * Simpler solutions are preferred over complex ones.
* Old browsers considered harmful.
  * ES6+ preferred over prior.
  * Asynchronous preferred over synchronous.
  * Async/await preferred over promises.
  * Promises preferred over callbacks.
* Workholism considered harmful.
  * Re-use and automate as much as possible.
  * Not just in your solution but just about everything in the solution development process including coding and testing.
* 133tism considered harmful.
  * Use allman style code braces. I.e. all code block braces go on new lines. People who write "if (xyz) {" on the same line...GAH! They're animals!
  * Use 2 spaces for indentation.
  * There are no line width limit.
  * If it causes problems with your favourite IDE, it is time for an upgrade.
* Anti-adaptation design patterns considered harmful.
  * Good old abstraction is your best friend for maximising asset longevity.
  * Don't include at all or abstract away things that are likely to be dated. E.g. front-end specific stuff, database specific stuff, devops specific stuff etc.
* Nerdness considered harmful.
  * Fully spell out variable names. Go become a mathematician instead of you want to write x, y, z for variable names. Codebase full of properly named things preferred over fully commented codebase.
  * Fail fast. If it ain't broke, don't fix it.
  * Put common code you think other projects might be able to use in a separate library and put them in npm.
  * Keep this codebase and associated test cases relevant to the specific requirements of this project. If you have tested for all your requirements and still can't get 80%+ coverage, you have too much junk code. If your test cases do not reflect customer requirements, you have entered nerdgasm territory. Time to go get a life!
