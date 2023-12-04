### If You Don't Know, You Don't Know

It isn't uncommon that I get pushback from managers when I offer a response of
"I don't know" to the question of how long something will take. It's similarly
not uncommon for said managers to pull some number from thin air and proclaim my
deliverable to be that many days or weeks or months out from shipping.

This sucks. It's stressful, and the only thing it serves to do is incentivize me
to cut corners that wind up creating more wasteful rework down the line. This
kind of wasteful rework often results in bugs, which then serve to erode the
trust in the software and, ultimately, the brand. (Dare I say that this behavior
also betrays said manager never having read and internalized&mdash;well, beyond
the weirdly sexist parts&mdash;Fred Brooks' _The&nbsp;Mythical&nbsp;Man-Month_?)

I won't stand for it. As an individual contributor, software quality stops with
me, and I refuse to ship trash.

Agile has a tool for situations like this: the spike solution. The idea is to
spend time investigating some technical detail that inhibits delivery of some
desired behavior in the software. In Scrum, these are typically boxed in some
integral multiple of sprints, ideally one, but if the problems being solved are
truly novel, it could take more.

As far as product backlog items (henceforth, PBIs) go, a spike solution should
hopefully result in a working bag of code as an example (not to mention the
measure of time that it took someone to produce a working bag of code that does
part of what's needed, which is really what we're after), but it could just as
well yield a report of lessons learned. _Yeah, no, that's probably not so great
an idea, and here's why._ There's still tremendous value in delivering even
that.

Spikes are also useful for carving out time to meet with third-party vendors or
other teams within a large organization on matters of integrating with their
respective products. Reporting on this is also useful because, if it comes to
pass that a vendor's or team's product is insufficient, future investigation of
that same product can be undertaken with this context in mind.

Furthermore, this all also means that the facts have changed, and as we all
know, that's the only trigger beyond fixed-date PBIs (e.g., vacations, on-call
shifts, and family leave) for re-ordering our deliverables. Get the stakeholders
on the horn and alert them; they'll probably want to meet sooner rather than
later.
