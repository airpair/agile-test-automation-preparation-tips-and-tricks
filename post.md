## Hello world!

Lets say we are in a perfectly technical world, where the user of the technology is the technology itself. Everything can be automated then. Let the fun begin!

In an Agile environment it is easy to think that every ticket in a sprint needs to be automated. Thats what people new to automation attempt to do. However, it is imperative that you justify (and carefully estimate) automation task on every ticket. Below are the scenarios you might want to consider.

## What is true today may not be true tomorrow

Watch out for **test redundancy**. Will my test become redundant and get run only once? Will changes in the application make my tests inapplicable in the short run?

## Return of Investment - Don't do anything without it!

What is the **ROI** for my automation work? It may take 2 weeks to automate a particular task but 1 hour to execute it manually. You can either park the automation for a suitable sprint with less work load and sign off the change after the short manual test. Or you can work on it for 2 weeks then move onto other tasks.  It is worth asking the business what is more suitable. E.g. the business can help you get more people to balance the load during your sprint. Do not settle for a test not to be automated or park it for later if the business provides help or agrees to automate in the current sprint. Remember that the rest of the team will move onto new tasks while you are still solving an old problem.

## Timing is everything!

The **best time to automate a ticket is when the underlying application is being implemented**. In that way, you can request for changes required to unblock you. Hence, within the sprint itself time your automation so that the relevant people can help you through.

## Consider complexity

In case estimations show that you can complete 7 tickets for automation in a sprint, (if business permits) **pick the ones with the lowest complexity first**. If you start with the easy ones first you'll get up to speed with the more complex ones later. Also more often than not initially you need to solve technical challenges that are common to most of the tickets in the sprint. It is better to unblock those issues at a relatively simple task than the complex ones.

## People and other things are important!

**Don't forget People and other dependencies**. Some tasks may involve people. In some cases, they may be external teams or vendors. Initiate those contacts first and park the tasks until they get back to you. You can always move onto another task while you are waiting on their response.

## Know your peers

**Pick tickets based on your and your peer's strengths**. In case you get more hands in your project to automate tasks, remember that you are familiar with the application already, the new team member may not be. Distribute the tasks to the new member that are more generic and easy to get up to speed. Take the lead!

## Don't forget the other systems

When we estimate test automation task we often think about the complexity and time only. Remember, automation is coding. **Code may depend on code from other teams**. Similarly the task itself may require people, new hardware implementation, new cloud service subscription, payment approval, etc. **Most importantly the dependency on the change in application itself**. E.g. if the change that you are going to automate will not finish until the end of the sprint, in most cases you can only prepare to automate the application, you can not get it to DONE state. Exception would be when you can automate before the change is implemented.

## See yah!

Getting automation done in an Agile environment is tricky. Things move fast and there is less documentation. The tips above are from years of experience in Agile Test Automation. They worked for me.

Now, I'd like to hear from you. It would be interesting to know what worked for you and what didn't.

