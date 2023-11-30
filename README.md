### Get Rid of Your Bug Tracker

One of the perhaps most laborious chores I've ever encountered has been
scrubbing bugs. I loathe to do it, and while some automation around, e.g., auto
closing bugs based on commit messages makes it suck less, the bug queue is
nonetheless where things ultimately go to be forgotten.

Does this mean throwing away all tracking entirely? Well, no. You should
definitely still keep a handle on defects in the design because those tend to
bubble up more pervasively. (Though, I'm keener to call these validation errors
because they're an expression that the software fundamentally does not solve the
problem at hand.)

No, I'm instead proposing that you pull the andon cord whenever someone flags a
potential bug and make that person (or those people) affected the most important
in the room. It's worth it to stop all work and regroup than to trudge along and
potentially have to undertake far, far more rework to patch the problem later.

If it comes to pass through that andon cord pull that the bug is no mere patch
but instead work that requires planning, that's great. Those are product backlog
items with deliverables. If you need to ship them sooner, that's also great. It
means that the facts have changed. You can have honest conversations with your
stakeholders about prioritizing and scheduling. Likewise, it's fine if this
causes you to have to abort your sprint.
