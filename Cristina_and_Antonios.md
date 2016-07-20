## Git

*AS A* marionete_developer
*I WANT TO* be fluent in GIT repos
*SO THAT I* can improve my productivity

| Working Copy                | Staging Copy                           | Repository               |
|-----------------------------|----------------------------------------|--------------------------|
| Git add . (adds to staging) | Git commit -m "will be ready to comit" |                          |
|                             | Git push origin master (sends do repo) | Git pull (get from repo) |

## Agile

### USER STORIES
 
*INVEST* concept

Independent
Negotiable
Valuable
Estimable
Sized Appropreately (Small)
Testable

Independent:  Stories should be as independent as possible.  When thinking of independence it is often easier to think of “order independent.”  In other words, stories can be worked on in any order.  Why is this important?  It allows for true prioritization of each and every story.  When dependencies come into play it may not be possible to implement a valuable story without implementing other much less valuable stories.

Negotiable:  A story is not a contract.  A story IS an invitation to a conversation.  The story captures the essence of what is desired.  The actual result needs to be the result of collaborative negotation between the customer (or customer proxy like the Product Owner), developer and tester (at a minimum).  The goal is to meet customer needs, not develop something to the letter of the user story if doing so is insufficient!  Remember, you can always ask the magic question to help drive the conversation.

Valuable:  If a story does not have discernable value it should not be done.  Period.  Hopefully user stories are being prioritized in the backlog according to business value, so this should be obvious.  Some people say each story should be valuable to the customer or user.  I don’t like that way of thinking because business value encompasses more than just customer or user facing value.  It includes internal value which is useful for things which are normally called “non-functional requirements” or something similar.  I prefer to say the story has value to the “user” in the user story.  In this way it is clear who is to be satisfied.  Finally, remember the “so that <value>” clause of the user story.  It is there for a reason – it is the exact value we are trying to deliver by completing the story!

Estimable:  A story has to be able to be estimated or sized so it can be properly prioritized.  A value with high value but extremely lengthy development time may not be the highest priority item because of the length of time to develop it.  What happens if a story can’t be estimated?  You can split the story and perhaps gain more clarity.  Sometimes splitting a story doesn’t help though.  If this situation occurs it may be necessary to do some research about the story first.  Please, please, please timebox the research!  If you do not, it will take all available time thereby depriving the product of something else which could have been done instead.

Small:  Obviously stories are small chunks of work, but how small should they be?  The answer depends on the team and the methodology being used.  I teach agile and suggest two week iterations which allow for user stories to average 3-4 days of work – TOTAL!  This includes all work to get the story to a “done” state.  Also remember not to goldplate user stories.  You should do the simplest thing that works – then stop!

Testable:  Every story needs to be testable in order to be “done.”  In fact, I like to think of testable meaning acceptance criteria can be written immediately.  Thinking this way encourages more collaboration up front, builds quality in by moving QA up in the process, and allows for easy transformation to an acceptance test-driven development (ATDD) process.  As with negotiable above, asking the magic questioncan help ensure the user story is testable as well.


*What to do with large user stories?*

SSST

Spike
Slice
Stub
Time-box


*EPIC* is a group of related User Stories

## Docker
* Content agnostic
* Hardware agnostic
	
There are no worries about missing dependencies!

## Mesos
It's  a scheduler that allows distributed applications

As a developers
We build *distributed applications*
That run on a *multi-tenant cluster*
That runs on *an framework*
That is *mesos*

