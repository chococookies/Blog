2/16/2014

- What did you do in the last week?
- 
Helped with laying out database schema. This required analizing the openbadges assertion specification: https://github.com/mozilla/openbadges-specification/blob/master/Assertion/latest.md

The 'hosted' badges we settled on require a URL to a json type object containing all the specs in the assertion. We decided on storing the data from the assertion in a mysql database (and after that sqllite). To do this I learned about the built-in database abstraction. (http://www.mediawiki.org/wiki/Manual:Database_access) for reference. After the meeting  Tyler mentioned the missing element, table creation, which Aizhuldyz and Chuying figured out on their own, as well. We prepared a lot of documentation to help in the upcoming task.

- Are there any barriers to your goals?
- 
Preparing the database schema might get us stuck, but it's not expected to be aproblem.

- What do you plan to accomplish for next week?
- 
Code review the finalized schema. Then work on implementing the schema into mediawiki's PHP. The information I found last week and the info Tyler prepared should make it a very direct task to complete. If done, then we can start using a special page to query into it.
