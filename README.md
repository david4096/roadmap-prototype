<img src="diagrams/maze.svg" alt="A small wooden maze" width="225" />

# roadmap-prototype

Programmers are often asked not only to predict how long it will 
take to develop this or that feature, but also how their software 
will change over time. It's difficult to express the intentions 
of how code will be maintained *in code itself* and so a roadmap 
is an attempt to provide those plans in written language.

This document is written as a roadmap itself so it can be easily 
copied and modified.

## Conceptual description/memo

The first section provides a description of the current status of 
the effort and its features. It provides a quick overview of where 
development is headed and any salient third-party APIs that may 
affect the long term development.

The roadmap-prototype is currently being written and is not officially
hosted. It will describe in text how to construct a simple roadmap 
for a project. Future versions will make it easier to modify to a 
specific project's needs and suggestions for integrating into existing 
documentation.

Some roadmaps could be very short: "Will support bugfixes in 0.1, no 
major changes expected."

## Milestones

By breaking down the effort into equivalent efforts of complexity we 
borrow on the analogy of markers on the side of a long road. At any 
point, we can check the milestone markers and see how far we've come!

Predicting how long a given effort can take is extremely difficult,
its easier to track progress even if the dates seem arbitrary at first. 
The point is to create a clear record of how well development could 
be predicted and how the project's direction is governed.

If you don't feel confident committing a date to the source repository, 
a ordered list of headers (with version numbers if it makes sense) is 
better than nothing. It's hard to learn to predict unless you try!

The bullet items under a milestone could link to issues, or groups of 
issues if its available.

### Designing it (June, 2018)

Without a document, there is nothing to maintain and no plan needed.

* Roadmap prototype markdown written (#1)
* Creation of repository

### Review (July, 2018)

Roadmaps need to be readdressed to see if goals have been meet.

* Review roadmap prototype content.
* Determine whether maintenance should be continued.
* Reach out to developers for suggestions.

### Governance (August, 2018)

Who gets to decide when milestone markers are going to be moved?

* Milestone marker buy-in
* Stakeholder voting
* Presenting forks in the road

### Automation (September, 2018)

What parts of planning/review/stake can be automated?

* Translating functional specs roadmaps
* Issue comments to stakeholder contracts
* Integrating with existing documentation

### Beyond

Roadmap itself is a very tried analogy for what we are trying to 
do. The roadmap itself should be renamed at some point to allow us
to think of software development differently as the interdependencies 
between human intention and code are made more clear.

This is also an attempt to future-proof our roadmaps to a time 
when cars have been obsoleted.

## Making Changes

The last section we'll provide is a record of major changes to the roadmap
and a link to a CHANGELOG if its available. If a major change to the 
software's direction was made, this is a good opportunity to provide any 
justification provided at the time.

This is the first version of the roadmap.

There is currently no way to make changes to this roadmap. After 
we have reached the first milestone changes can be proposed as 
git issues.

Maze image courtesy of [nicubunu on openclipart.org](https://openclipart.org/detail/11476/rpg-map-symbols-maze)/
