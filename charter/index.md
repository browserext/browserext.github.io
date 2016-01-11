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
initially developed by Google for Chrome.
This Community Group aims to ensure
actual interoperability rather than mere similarity.

As the specifications developed in the Community Group mature
and as Browser Vendors confirm intent to implement them,
this community group may consider migrating them
to the appropirate W3C Working Group
where they can be put on the Recommendation track
with appropriate status and Intellectual Property (IP) considerations.

When existing specifications already worked on in other groups
cover topics needed for interoperable browser extensions,
this group will gather use cases and requirements
to inform the design of these specifications,
and communicate them to the relevant group.

## Scope

1. Specifying the APIs,
execution model and security model
that form the basis of the cross browser exentions.
Existing end-user documentation,
as provided by [Google](https://developer.chrome.com/extensions),
[Opera](https://dev.opera.com/extensions/),
or [Mozilla](https://wiki.mozilla.org/WebExtensions)
give a good indication of what is needed.

2. Specify other APIs on top of that common core
to offer additional functionality.

3. To minimize repackaging overhead for authors,
and so that extensions can actually run in any (standards compliant) browser,
even if the author overlooked some of them,
consider specifying:
    * packaging format
    * manifest format
    * file extension
    * mime type
    * deployment mechanisms

## Deliverables

This group will develop specifications,
possibly supported by test suites,
and may also write notes.
The exact list of documents that need to be written
to achieve the group's goals is not fully determined
at the time of writing this charter,
and will be one of the first work items
of this Community group.

All deliverables of this Community Group will use
the [W3C Software and Document License](http://www.w3.org/Consortium/Legal/2015/copyright-software-and-document).

This group maintains an [index]({{ "/work_items/" | prepend: site.url }})
of the documents it is working on.

## Dependencies and Liaisons

### W3C Groups

[Web Platform Working Group](http://www.w3.org/WebPlatform/WG/)
: The Web Platform Working Group develops many relevant specifications,
covering [HTML5](http://www.w3.org/TR/html5/),
various APIs for client-side development,
and many of the security policies
that apply in the current browser environment.

[Device API Working Group](http://www.w3.org/2009/dap/)
: The Device API Working Group’s deliverables
include an API for requesting and managing
user permissions to use device features.

## Communication

This group will conduct all of its technical work publicly,
primarily using the [public-browserext@w3.org](mailto:public-browserext@w3.org) mailing list
([archives](https://lists.w3.org/Archives/Public/public-browserext/))
for high level discussions,
and github for technical contributions
(See [Contribution Mechanics](#contribution-mechanics)).

Teleconferences and face-to-face meetings are not held regularly,
but may be occasionally when necessary,
provided sufficient advance notice is given.
Minutes of any such meeting
will be posted to the group’s public mailing list
in a timely manner,
and any resolution will be recorded in github
(See [Decision Policy](#decision-policy)).

Specifications, notes, and test suites produced by this Community Group
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
will be recorded in the relevant specification’s github issue list, and
is to be considered provisional
until 10 working days after publication.
If no objections are raised on within that time,
the resolution will be considered to have consensus
as a resolution of the Community Group.

When working on non contentious topics
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
The section on [Contribution Mechanics](#contribution-mechanics) describes how
W3C expects to monitor these contribution requests.

##Contribution Mechanics

Community Group participants agree to make contributions
in the GitHub repo for the project that they are interested in.
This may be in the form of a pull request (preferred),
by raising an issue,
or by adding a comment to an existing issue.

The Community Group mailing list must not be used
for discussing details of specific projects.

Specifications created for proposals in the Community Group
must use the [W3C Software and Document License](http://www.w3.org/Consortium/Legal/2015/copyright-software-and-document).

All Github repositories attached to the Community Group
must contain a copy of the
[CONTRIBUTING](https://github.com/browserext/browserext.github.io/blob/master/CONTRIBUTING.md)
and
[LICENSE](https://github.com/browserext/browserext.github.io/blob/master/license.md)
files.

Note: this CG will not use a contrib mailing list for contributions since all contributions will be tracked via Github mechanisms (e.g. pull requests).

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
