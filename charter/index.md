---
title: Browser Extension Community Group Charter
---

<div class="warn">This is a work in progress, not an active charter</div>

This charter:
: <a href='{{ page.url | remove: "index.html" | prepend: site.url }}'>{{ page.url | remove: "index.html" | prepend: site.url }}</a>

Feedback about this document:
: [Github issues](https://github.com/browserext/browserext.github.io/issues)

## Goal

This Community Group provides a lightweight venue to facilitate discussion
between Web Browser vendors,
as well as other interested parties,
in order to establish a set of standards
for interoperable browser extensions.

Several browser vendors have already started converging
towards a common approach,
based on the model and APIs
initially developped by Google for Chrome.
This Community Group aims at ensuring
actual interoperability rather than mere similarity.

As the specifications developed in the Community Group mature
and as Browser Vendors confirm intent to implement them,
it is expected that these specifications
will be migrated to the appropirate W3C Working Group
where they can be put on the Recommendation track
with appropriate status and Intellectual Property (IP) considerations.

When existing specifications already worked on in other groups
cover topics needed for interoperable browser extensions,
this group will gather use cases and requirements
to inform the design of these specifications,
and communicate them to the relevant group.

## Scope

## Deliverables

This group will develop specifications,
possibly supported by test suites,
and may also write notes.
The exact list of documents that need to be written
to achieve the group's goals is not fully determined
at the time of writing this charter,
and will be one of the first work items
of this Community group.

This group maintains an [index]({{ "/work_items/" | prepend: site.url }})
of the documents it is working on.

## Dependencies and Liaisons

### W3C Groups

[Web Applications Working Group](http://www.w3.org/2008/webapps/)
: One of the areas of collaboration 
cross-site resource sharing deliverable
as joint work with the Web Applications Working Group.

[HTML Working Group](http://www.w3.org/html/wg/)
: The [HTML5](http://www.w3.org/TR/html5/) specification
defines many of the security policies
that apply in the current browser environment.

[Device API Working Group](http://www.w3.org/2009/dap/)
: The Device API Working Group’s deliverables
include an API for requesting and managing
user permissions to use device features.

## Communication

This group will conduct all of its technical work publicly,
primarily using the [public-browserext@w3.org](mailto:public-browserext@w3.org) mailing list
([archives](https://lists.w3.org/Archives/Public/public-browserext/)).

Teleconferences and face-to-face meetings are not held regularly,
but may be occasionally when necessary,
provided sufficient advance notice is given.
Minutes of any such meeting
will be posted to the group’s public mailing list
in a timely manner.

Specifications and test suites produced by this Community Group
are hosted on the group’s [Github](https://github.com/browserext). 

The group uses an internal mailing list ([internal-browserext@w3.org](mailto:internal-browserext@w3.org))
for administrative purposes,
such as organizing meetings,
requesting commit access to Github,
etc.
Up-to-date information about the group
is maintained at the Browser Extension Community Group’s
[wiki on Github](https://github.com/browserext/browserext.github.io/wiki).

## Decision Policy

This group will seek to make decisions when there is consensus,
and favors proposals that create the weakest objections.
This is preferred over proposals that are supported
by a large majority
but that cause strong objections from a few people.
When the Chair puts a question and observes dissent,
after due consideration of different opinions,
the Chair should record a decision (possibly after a vote)
and any objections, and move on.

Any resolution taken in a face-to-face meeting
or a teleconference
is to be considered provisional
until 10 working days after the publication of the resolution
in minutes sent to the group’s mailing list.
If no objections are raised on the mailing list within that time,
the resolution will be considered to have consensus
as a resolution of the Community Group.

When working on non contentious topics,
and early drafts,
Editors are trusted to make progress
without needing an explicit resolution for every change.
However, they should seek feedback from the Community Group
and publish regular status updates
via the public mailing list.
This allows group participants to monitor progress
without having to directly watch every repo. 

## Community and Business Group Process and Patent Policy

The group operates under the [Community and Business Group Process](https://www.w3.org/community/about/agreements/).
Terms of in this charter that conflict
with those of the Community and Business Group Process
are void.

As with other Community Groups,
W3C seeks organizational licensing commitments
under the [W3C Community Contributor License Agreement (CLA)](http://www.w3.org/community/about/agreements/cla/)
(Proposals in this Community Group charter are applicable "Specification" in the CLA).
When people request to participate
without representing their organization’s legal interests,
W3C will in general approve those requests for this group
with the following understanding:
W3C will seek and expect an organizational commitment
under the CLA
starting with the individual’s first request
to make a contribution to a group deliverable.

## Chair Selection

Participants in this group choose their Chair(s)
and can replace their Chair(s)
at any time using whatever means they prefer.

However, if 5 participants
—no two from the same organization—
call for an election,
the group must use the following process
to replace any current Chair(s) with a new Chair,
consulting the Community Development Lead
on election operations (e.g., voting infrastructure and using [RFC 2777](https://tools.ietf.org/html/rfc2777)).

1. **Participants announce their candidacies**.
Participants have 14 days to announce their candidacies,
but this period ends as soon as all participants
have announced their intentions.
If there is only one candidate,
that person becomes the Chair.
If there are two or more candidates,
there is a vote.
Otherwise, nothing changes.
2. **Participants vote**.
Participants have 21 days to vote for a single candidate,
but this period ends as soon as all participants have voted.
The individual who receives the most votes
—no two from the same organization—
is elected chair.
In case of a tie,
[RFC 2777](https://tools.ietf.org/html/rfc2777) is used to break the tie.
An elected Chair may appoint co-Chairs.

Participants dissatisfied with the outcome of an election
may ask the Community Development Lead to intervene.
The Community Development Lead,
after evaluating the election,
may take any action including no action. 

## Amendments to this Charter

This Charter can be amended by the Chairs with consultation of the Community Group,
if the change is agreed to by W3C’s Community Development Lead
(Community Development Lead is described in the CG Process).
