Multivariate Testing
====================

A/B Testing
-----------

Testing More Than Two Variables
-------------------------------
For high traffic websites, it is possible to run more complex tests that investigate the effects of multiple sources of variation within a product or service. There are two important considerations when testing variations: (1) ability to measure interactions and (2) cost effectiveness.

Most people are taught to change one thing about a product at a time, ask for feedback, and use that feedback to assess the effectiveness of the change. This approach risks missing the impact of interactions between the different parts that make up a product. By using advanced multivariate testing methods, a designer can understand how a set of design changes impact product effectivess while taking into account the interactions of those design changes with each other. Let me illustrate with a simple scenario that compares A/B and Multivariate testing approaches.

The most common statistical quality control tool I’ve noticed software companies using is [design of experiments](http://en.wikipedia.org/wiki/Design_of_experiments). Often, companies like Google and Facebook will talk about using A/B testing, where they define an objective for users of an application, then test variations on the user interface and see which variation results in the highest rate of users achieving the objective. Here’s an example from Adrian Vender at CardinalPath, [A/B Testing with Google Analytics Content Experiments](http://bit.ly/UPaTOY). A/B testing can be extended, using design of experiments methods, to statistically assess the impact that multiple proposed design changes and their interactions will have on an application’s fitness for use.

### Scenario: Chocolate Chip Cookie
TODO: Validate this section, which is currently a conceptual placeholder.

Variables: Size, Chocolate, Baking Temperature

In traditional A/B testing, each variable of the cookie might be tested independently. Customers might be given a small cookie and then a large cookie. This test might indicate customers prefer a large cookie. Customers might be given a cookie baked at very high temperature and then a cookie baked at low temperature and might indicate a preferance for the low temperature cookie. However, running these experiments independent of one another, the cookie designer will not be able to investigate the interaction between cookie size and baking temperature.

In multivariate testing, a minimum set of randomized experiments is defined to investigate all three cookie variables at once, along with the interactions between variables. Cookies cost money to make and it can be bad for the bakery if too many customers try cookies that taste bad. Multivariate testing tools give us a way to test a minimum set of cookie variations and still arrive at a statistically significant conclusion about what cookie "settings" customers like best.

TODO: Add an example to this section