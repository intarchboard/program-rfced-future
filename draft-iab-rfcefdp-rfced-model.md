---
title: "RFC Editor Model (Version 3)"
abbrev: "RFC Editor Model v3"
docname: draft-iab-rfcefdp-rfced-model-00
category: info
obsoletes: RFC8728
ipr: trust200902
area: Internet
keyword: Internet-Draft
stand_alone: yes
pi: [toc, sortrefs, symrefs]

author:
 -
    role: editor
    ins: P. Saint-Andre
    name: Peter Saint-Andre
    organization: Mozilla
    email: stpeter@jabber.org

normative:

informative:
  RFC2418:
  RFC3777:
  RFC5378:
  RFC5620:
  RFC6635:
  RFC7154:
  RFC7282:
  RFC7322:
  RFC7776:
  RFC7991:
  RFC8179:
  RFC8700:
  RFC8711:
  RFC8716:
  RFC8728:
  RFC8729:
  RFC8730:
  RFC8874:


--- abstract

This document describes Version 3 of the RFC Editor model. As
specified here, the model divides the responsibilities for the 
RFC Series into two high-level functions: policy definition 
governing the Series as a whole, and policy implementation
through publication of documents in the Series. The policy
definition function is the responsibility of the RFC Series
Working Group (RSWG), which produces policy proposals that
are subject to approval by the RFC Series Approval Board (RSAB).
The policy implementation function is primarily the responsibility
of the RFC Production Center (RPC), under the ultimate authority
of the IETF Administration Limited Liability Company (LLC).

This document reflects experience gained with version 1 of the 
RFC Editor Model as specified in RFC 5620 and with version 2
as specified in RFC 6635 and RFC 8728. 

This document obsoletes RFC 8728.


--- middle

# Introduction

NOTE: This document is a work in progress. Although it is intended 
to describe consensus forged in the RFC Editor Future Development 
Program, many aspects are not yet settled; as a result, this document 
contains proposals and conjectures that do not yet have consensus 
in the Program. Where possible, open issues are identified herein to 
foster discussion.

Documents in the Request for Comments (RFC) series have been 
continually published since 1969 {{RFC8700}}. The RFC series is 
described in {{RFC8729}}. RFC 8729 uses the term "RFC Editor
function" or "RFC Editor" to identify the collective set of
responsibilities for publishing documents in the RFC series.

The processes and organizational models for publication of RFCs
have changed significantly over the years. Most recently, in 2009 
{{RFC5620}} defined the RFC Editor Model (Version 1) and in 2012 
{{RFC6635}} defined the RFC Editor Model (Version 2), since 
modified slightly in 2020 by {{RFC8728}}.

In order to provide a sustainable basis for continued publication of 
the RFC series, this document describes Version 3 of the RFC Editor 
model, which divides the responsibilities for the RFC Series into 
two high-level functions: policy definition governing the Series 
as a whole, and policy implementation through publication of 
documents in the Series. The policy definition function is the 
responsibility of the RFC Series Working Group (RSWG), which produces 
policy proposals that are subject to approval by the RFC Series 
Approval Board (RSAB). The policy implementation function is 
primarily the responsibility of the RFC Production Center (RPC), 
under the ultimate authority of the IETF Administration Limited 
Liability Company (LLC) {{RFC8711}}.  

This document obsoletes RFC 8728 by making a full update to the RFC
Editor Model, changing the responsibilities of existing bodies and
functions, and introducing new functions (see Section 7 of this
document for a summary of the changes from Version 2).


# Overview of the Model

Version 2 of the RFC Editor Model {{RFC8728}} specified a structure
consisting of the RFC Series Editor, the RFC Production Center, and 
the RFC Publisher, with oversight provided by the RFC Series Oversight
Committee (RSOC) on behalf of the Internet Architecture Board (IAB).

Discussion within the RFCED-Future Program has led in the direction 
of a more consensus-oriented structure (similar in some respects to 
the structure of technical work within the IETF or IRTF) that retains 
roles for specialized expertise in document editing and publication.

The policy definition function is performed by the RFC Series Working 
Group (RSWG), which produces policy proposals that are subject to 
approval by the RFC Series Approval Board (RSAB), after which such 
policies are formally established. The RSWG is an open 
working group (as described below) that seeks input and participation 
from a wide range of persons who have an interest in the RFC Series. 
The RSAB consists of appointed members who represent the various RFC 
streams {{RFC8728}} as well as an expert in technical publishing, the
RFC Series Editor/Advisor (RSEA).

The policy implementation function is performed by the RFC Production 
Center (RPC), under the ultimate authority of the IETF Administration 
Limited Liability Company (IETF LLC).

In short:

* The RSWG establishes policy, with input from the community, the RSAB, and 
  the RSEA.
* The RSAB considers those proposals and approves or returns as appropriate.
* The RPC periodically reports to the RSAB on how it is implementing established 
  policies.
* The RSEA provides expert advice to the RPC and RSAB on how to implement 
  established policies on an ongoing and operational basis, which can include
  raising issues or initiating proposed policy changes within the RSWG.
* If issues arise with the implementation of particular policies, the RPC brings 
  them to the RSAB who interprets the policy and provides interim guidance to 
  the RPC, informing the RSWG of those interpretations.

The remainder of this document describes the model in greater detail.


# Policy Definition Function

Policies governing the RFC series as a whole shall be defined in the
open through proposals that are generated by and discussed within the RFC
Series Working Group (RSWG) and then approved by the RFC Series Approval
Board (RSAB).

Policies under the purview of the RSWG and RSAB might include but
are not necessarily limited to document formats, processes for 
publication and dissemination of RFCs, and overall management of 
the RFC series.


## Structure and Roles

### RFC Series Working Group (RSWG)

The RFC Series Working Group (RSWG) shall
formulate proposals regarding policies that govern the RFC series. The
intent is that the RSWG operate in a way similar to working groups 
in the IETF and research groups in the IRTF. Therefore, all RSWG 
meetings shall be open to any participant, subject to intellectual 
property policies which must be consistent with those of the IETF
as specified in BCP 78 {{RFC5378}} and BCP 79 {{RFC8179}}. 

The RSWG shall operate by rough consensus, a mode of operation
informationally described in {{RFC7282}}. 

When the RSWG is formed, all discussions shall take place on an 
open email discussion list. Subsequently, the RSWG may decide by rough 
consensus to also use additional tooling (e.g., GitHub as specified in 
{{RFC8874}}), forms of communication (e.g., in-person or online 
meetings), and working methods (e.g., design teams) as long as they 
are consistent with {{RFC2418}}. 

All interested persons are welcome to participate in the RSWG
(subject to anti-harassment policies as described below). This
includes participants in the IETF and IRTF, IAB and IESG members, RFC 
authors, individuals who use RFCs in procurement decisions, and the
like. The IETF LLC Board members, staff, and the IETF Executive Director are 
invited to participate as community members in the RSWG to the extent 
permitted by any relevant IETF LLC policies. Members of the RSAB are
also expected to participate actively.

The RSWG shall have two chairs, one appointed by the IESG and the 
other appointed by the IAB. When the RSWG is formed, the chair 
appointed by the IESG shall serve for a term of one (1) year and
the chair appointed by the IAB shall serve for a term of two (2) 
years; thereafter, chairs shall serve for a term of two (2)
years, with no term limits on renewal. The appointing bodies shall
determine their own processes for making these appointments, such
as provision for an open nominations period. Community members who 
have concerns about the performance of an RSWG chair should direct
their feedback to the relevant appointing body. Each appointing 
body shall have the power to remove its appointed chair at its 
discretion.

It is the responsibility of the chairs to encourage rough consensus 
within the RSWG and to follow that consensus in their decision-making,
for instance regarding advancement of proposals to the RSAB.

NOTE: This section is intended to address 
[ISSUE #9](https://github.com/intarchboard/program-rfced-future/issues/9), 
[ISSUE #14](https://github.com/intarchboard/program-rfced-future/issues/14), 
[ISSUE #16](https://github.com/intarchboard/program-rfced-future/issues/16), 
[ISSUE #41](https://github.com/intarchboard/program-rfced-future/issues/41), 
[ISSUE #44](https://github.com/intarchboard/program-rfced-future/issues/44),
[ISSUE #68](https://github.com/intarchboard/program-rfced-future/issues/68), and
[ISSUE #72](https://github.com/intarchboard/program-rfced-future/issues/72).


### RFC Series Approval Board (RSAB)

The RFC Series Approval Board (RSAB) shall act as the approving body 
for proposals generated within the RSWG. The sole function of RSAB 
is to review policy proposals generated by the RSWG; it shall have 
no independent authority to formulate policy on its own. It is 
expected that the RSAB will respect the rough consensus of the
RSWG wherever possible, without ceding its review function.

The voting members of the RSAB shall be as follows:

* One delegate representing the IETF stream, appointed by the IESG
* One delegate representing the IAB stream, appointed by the IAB
* The IRTF Chair, representing the IRTF stream
* The Independent Submissions Editor {{RFC8730}}
* The RFC Series Editor/Advisor

To ensure the smooth functioning of the RFC Series, the RSAB shall 
include the IETF Executive Director as a non-voting member since 
the IETF LLC is ultimately responsible for the operation of the 
policy implementation function. The RSAB may at its discretion include 
additional non-voting members, for instance a liaison from the RPC.

The IAB and IESG delegates must be selected by the Nominating
Committee {{RFC3777}} to their respective bodies (i.e., they 
must not be liaison or ex-officio members). These delegates shall 
serve for one-year renewable terms. If it becomes necessary to 
replace such a delegate for any reason, then for the sake of continuity 
the IAB or IESG should name a new delegate to complete the term.

Whenever a new stream is created (see below), the document that
creates the stream shall specify if a voting member representing 
that stream shall also be added to the RSAB, along with any rules
and processes related to that representative (e.g., whether the
representative is a member of the body responsible for the stream 
or an appointed delegate thereof.

The RSAB shall choose a chair from among its members using a method to
be determined by the RSAB. 

The RSAB is expected to operate via email, in-person meetings, 
teleconferencing systems, and any additional tooling it deems
necessary. 

The RSAB shall keep a public record of its proceedings, including minutes 
of all meetings and a record of all decisions.

The RSAB shall announce plans and agendas for their meetings on the 
RFC Editor website and by email to the RSWG at least a week before 
such meetings. The meetings shall be open for public attendance and 
the RSAB may consider allowing open participation. If the RSAB needs 
to discuss a confidential matter in executive session, that part of 
the meeting shall be private to the RSAB, but must be noted on the 
agenda, and must be documented in the minutes with as much detail as 
the confidentiality requirements permit.

NOTE: This section is intended to address 
[ISSUE #9](https://github.com/intarchboard/program-rfced-future/issues/9), 
[ISSUE #38](https://github.com/intarchboard/program-rfced-future/issues/38), 
[ISSUE #50](https://github.com/intarchboard/program-rfced-future/issues/50), and 
[ISSUE #53](https://github.com/intarchboard/program-rfced-future/issues/53).


## Process

### Intent

The intent is to provide an open forum by which policies related to the 
RFC series are defined and evolved. The general expectation is that all 
interested parties will participate in the RSWG, and that only under 
extreme circumstances should RSAB members need to hold "CONCERN"
positions as described below. 

Because policy issues can be difficult and contentious, RSWG
participants and RSAB members are strongly encouraged to work together 
in a spirit of good faith and mutual understanding to achieving rough 
consensus (see {{RFC7282}}). In particular, RSWG members are 
encouraged to take RSAB concerns seriously, and RSAB members are 
encouraged to clearly express their concerns early in the process and 
to be responsive to the community. All parties are encouraged to respect 
the value of each stream and the long term health and viability of 
the RFC series.

This process is intended to be one of continuous consultation. RSAB 
members should consult with their constituent stakeholders (e.g.,
authors, editors, tool developers, and consumers of RFCs) on an ongoing 
basis, so that when the time comes to consider a proposal, there should 
be no surprises. Appointing bodies are expected to establish whatever 
processes they deem appropriate to facilitate this goal.


### Specifics

The following process shall be used to formulate or modify processes related
to the RFC series:

1. An individual participant in the RSWG generates a proposal in the form of 
an Internet-Draft.
2. If there is sufficient interest in the proposal, RSWG may adopt the proposal 
as a draft proposal of the RSWG, much the same way a working group of
the IETF or IRTF would (see {{RFC2418}}).
3. The RSWG shall then further develop the proposal. Members of the
RSAB are expected to participate in discussion relating to such proposals
so that they are fully aware of proposals early in the policy definition 
process and so that any issues or concerns that they have will be raised
during the development of the proposals and will not be left until
the RSAB review period.
4. At some point, if the RSWG chairs believe there may be rough consensus 
for the proposal to advance, they will issue a working group last call.
5. After a suitable period of time, the RSWG chairs will determine whether 
rough consensus for the proposal exists. If comments have been received and 
substantial changes have been made, it is expected that additional last calls 
may be necessary.
6. Once consensus is established in the RSWG, the RSAB shall issue a 
community call for comments as further described below. Should substantial comments be received,
the RSWG will again consider those comments and make revisions as they see 
fit. At this same time, the RSAB will consider the proposal. 
7. Should substantial changes be made, additional community calls for comment 
should be issued by the RSAB, and again comments considered by the RSWG.
8. Once all comments have been addressed, the RSWG chairs will
submit the proposal to the RSAB for its consideration.
9. Within a reasonable period of time, the RSAB will then poll on the 
proposal. Positions may be as follows:
* "YES": the proposal should be approved
* "CONCERN": the proposal raises substantial concerns that must be addressed.
* "RECUSE": the person holding the position has a conflict of interest.

Anyone holding a "CONCERN" position must explain their concern to the community in detail. The explanation may or may not be actionable.

A CONCERN may be made for two reasons:

 * The proposal represents a serious problem for the group a particular member represents.
 * The member believes that the proposal would cause serious harm to the overall series, including harm to the long term health and viability of the series.

No CONCERN should ever come as a surprise to the RSWG.

10. If a CONCERN exists, discussion will take place within the RSWG. 
Again, all RSAB members are expected to participate.
11. A proposal without any CONCERN positions is approved. 
If substantial changes have been made in order to address CONCERN positions, 
an additional call for community input might be necessary.
12. If, after a suitable period of time, any CONCERN positions remain, 
a formal vote of the RSAB is taken. If a majority of RSAB members 
vote to approve, the proposal is approved. Otherwise, it is returned to 
the RSWG. In the case of a tie, the proposal is approved.
13. When a proposal is approved, a notification is sent to the community, 
and the document enters the queue for publication as an RFC.

[ISSUE #22](https://github.com/intarchboard/program-rfced-future/issues/22): 
In which stream {{RFC8729}} are these documents published?
Is a new stream (e.g., the "Editorial Stream") needed?

### Community Calls for Comment

When a community call for comment is made, the RSAB sends a notice containing:

* A subject line beginning with 'Call for Comment:'
* A clear, concise summary of the proposal
* A URL for the proposal document 
* Any commentary or questions for the community that the RSAB deems necessary 
(using their usual decision-making procedures)
* Clear instructions on how to provide public comments
* A deadline for comments

Notices will always be sent to the rfc-interest mailing list. The RSAB and 
RSWG should also send notices to other communities that may be interested 
in or impacted by a proposal as they see fit, following policies for those 
fora as appropriate. Notices are also to be made available and archived on 
the rfc-editor.org website, and other communication channels can be 
established for notices (e.g., using an RSS feed, social media).

A comment period will not last less than two weeks. Comments will be publicly 
archived on the rfc-editor.org website.

NOTE: This section is intended to address 
[ISSUE #67](https://github.com/intarchboard/program-rfced-future/issues/67).

### Appeals

Appeals of RSWG decisions shall be made to the RSAB. Decisions of the 
RSWG can only be appealed on grounds of failure to follow the correct 
process. Appeals should be made within 30 days of any action, or in 
the case of failure to act, of notice having been given to the RSWG. 
The RSAB will then decide if the process was followed and will direct 
RSWG chairs as to what procedural actions are required.

Appeals of RSAB decisions shall be made to the IAB and should be made 
within thirty (30) days of public notice 
of the relevant RSAB decision (typically, when minutes are posted). 
The appeals body shall decide whether a process failure 
occurred and what if any corrective action should take place.

NOTE: This section is intended to address 
[ISSUE #16](https://github.com/intarchboard/program-rfced-future/issues/16) and 
[ISSUE #36](https://github.com/intarchboard/program-rfced-future/issues/36).

### Anti-Harassment Policy

The [IETF anti-harassment policy](https://www.ietf.org/about/groups/iesg/statements/anti-harassment-policy/) also applies to the RSWG and RSAB, 
which strive to create and maintain an environment in which people 
of many different backgrounds are treated with dignity, decency, 
and respect. Participants are expected to behave according to 
professional standards and demonstrate appropriate workplace 
behavior. See also {{RFC7154}}, {{RFC7776}}, and {{RFC8716}}.


# RFC Series Editor/Advisor (RSEA)

NOTE: Discussion continues within the RFCED-Future Program
regarding the roles and responsibilities of an expert in technical
publication processes. To retain flexibility (e.g., as to whether this
individual plays more of an advisory role or more of a singular 
leadership role), this document temporarily refers to the individual 
as the "RFC Series Editor/Advisor" ("RSEA"). 

The RFC Series Editor/Advisor (RSEA) is a senior technical 
publishing professional who will apply their deep knowledge of 
technical publishing processes to the RFC series. 

The primary responsibilities of the RSEA are as follows:

* Serve as a voting member on the RSAB.
* Identify problems with the RFC publication process and opportunities for improvement.
* Provide expert advice regarding policy proposals within the RSWG.
* If requested, provide expert advice to the RPC and IETF LLC.

Matters on which the RSEA might be consulted could include proposed 
changes to the RFC style guide {{RFC7322}}, RFC formatting in general, 
web presence, copyright matters, archiving policy, and dissemination 
and cataloguing of RFCs.

NOTE: This section is intended to address 
[ISSUE #12](https://github.com/intarchboard/program-rfced-future/issues/12) and
[ISSUE #24](https://github.com/intarchboard/program-rfced-future/issues/24).


## RSEA Selection

The RSEA will be selected by a search committee formed by the IETF 
Executive Director, taking into account the 
[role definition](https://github.com/intarchboard/program-rfced-future/blob/master/Issue12-RSE-role.md) 
as well as other information that the committee
deems necessary or helpful in making its decision.


## RSEA Performance Evaluation

Periodically, the IETF Executive Director will send out to the community a 
call for input on the performance of the RSEA. The evaluation will be 
based on criteria specified in the role definition. Criteria could
include matters such as the following:

* Was the RSEA an active participant in RSWG/RSAB discussions and meetings?
* Did the RSEA provide useful advice to the RSWG and RPC?  
* Did the RSEA exercise good judgment in RSAB decision-making?
* Was the RSEA effective in advising the community on policy direction?

The IETF Executive Director will review the feedback, consulting with stream 
manager representatives, and then produce a recommendation to the IETF LLC 
Board. The LLC will then make a decision, taking into account the
IETF Executive Director's recommendation.

Whether the RSEA role is structured as a contractual or employee relationship 
is a matter for the IETF LLC and the IETF Executive Director to determine.


# Policy Implementation Function

## Roles and Processes

Publication of RFCs shall continue to be handled by the RFC Production
Center (RPC) function in accordance with high-level policies currently in 
force or yet to be defined following the processes specified in the foregoing 
sections of this document.

All matters of budget, timetable and impact on its performance 
targets, are between the RPC and IETF LLC.

The RPC shall report regularly to the RSAB, RSWG, and broader 
community regarding the contents and progress of its work program and any 
key risks or issues affecting it. 

In the event that the RPC is required to make a decision without 
consultation that would normally deserve consultation, or makes a 
decision against the advice of the RSAB, then it must notify the 
RSAB.

This document does not specify the exact relationship between the IETF LLC 
and the RPC function; for example, the RPC function could be provided 
by a separate corporate entity under contract to the IETF LLC, it could 
be performed by employees of the IETF LLC, or the IETF LLC could work with 
independent contractors for some or all aspects of the RPC function. The
exact relationship is a matter for the IETF LLC and the IETF Executive Director 
to determine.

The IETF LLC has authority over negotiating performance targets for the 
RPC and also has responsibility for ensuring that those targets are 
adhered to. The IETF LLC is empowered to appoint a manager or to convene 
a committee to complete these activities.

Community members who have concerns about the performance of the RPC
can request that the IETF LLC look into the matter. Even if the IETF
LLC opts to delegate this activity, concerns should be raised 
with the IETF LLC. The IETF LLC is ultimately responsible to the 
community via the mechanisms outlined in its charter.


## Editorial and Publication Policies

Under and consistent with the high-level policies defined for the RFC 
Series in general or particular streams, the RPC shall define more 
particular policies regarding matters related to the editorial preparation
and final publication and dissemination of RFCs. Examples include:

* Maintenance of a styleguide that defines editorial standards to which 
RFCs must adhere (see {{RFC7322}} and related updates).

* Policies regarding the file formats that are accepted as input to the 
editing and publication process.

* Policies regarding the final structure and layout of published documents; 
in the context of the XML vocabulary ({{RFC7991}}), such policies could
include matters such as the exact XML elements and attributes used to
capture the semantic content of RFCs.

## Resolution of Disagreements between Authors and the RPC

NOTE: This section is intended to address 
[ISSUE #59](https://github.com/intarchboard/program-rfced-future/issues/59) and 
[ISSUE #6](https://github.com/intarchboard/program-rfced-future/issues/6).

During the process of editorial preparation and publication, disagreements 
can arise between the authors of an RFC-to-be and the RPC. Where an existing
policy clearly applies, typically such disagreements are handled in a 
straightforward manner through direct consultation between the authors and 
the RPC, sometimes in collaboration with other individuals such as a document 
shepherd, IETF working group chair, IRSG research group chair, or IETF Area 
Director.

However, if it is unclear whether an existing policy applies, or if the 
interpretation of an existing policy is unclear, the parties may need to 
consult with additional individuals or bodies (e.g., RSAB, IESG, IRSG, or 
stream manager) to help achieve a resolution. The following points are 
intended to provide more particular guidance.

* If there is a conflict with a policy for a particular stream, the 
RPC should consult with the relevant stream manager to help achieve a 
resolution, if needed also conferring with a per-stream body such as the 
IESG or IRSG.

* If there is a conflict with a cross-stream policy, the RPC should consult 
with the RSAB to achieve a resolution.

* If the disagreement raises a new issue that is not covered by an existing
policy or that cannot be resolved through consultation between the RPC and 
other relevant individuals and bodies as described above), the issue 
should be brought to the RSWG in order to formulate a new policy. However,
in the interest of time the disagreement may be resolved as the parties 
best see fit while the RSWG formulates a more general policy.

## Administrative Implementation

The exact implementation of the administrative and contractual
activities described here are a responsibility of the IETF LLC.

### Vendor Selection for the RFC Production Center

Vendor selection is done in cooperation with the streams and 
under the final authority of the IETF LLC.

The IETF LLC develops the work definition (the Statement of Work) 
for the RPC and manages the vendor selection process.  The work
definition is created within the IETF LLC budget and takes into
account the stream managers and community input.

The process to select and contract for an RFC Production Center
and other RFC-related services, is as follows:

*  The IETF LLC establishes the contract process, including the steps
   necessary to issue an RFP when necessary, the timing, and the
   contracting procedures.

*  The IETF LLC establishes the Selection Committee, which will
   consist of the IETF Executive Director and other
   members selected by the IETF LLC in consultation with the 
   stream managers. The Committee shall select a chair from 
   among its members.

*  The Selection Committee selects the vendor, subject to the
   successful negotiation of a contract approved by the IETF LLC.  In
   the event that a contract cannot be reached, the matter shall be
   referred to the Selection Committee for further action.

### Budget

The expenses discussed in this document are not new expenses. They
have been and remain part of the IETF LLC budget.

The RFC Series portion of the IETF LLC budget shall include funding
to support the RSE/A, RFC Production Center, and the Independent 
Stream.

The IETF LLC has the responsibility to approve the total RFC Editor
budget (and the authority to deny it). All relevant parties must work 
within the IETF LLC budgetary process.

# Streams

NOTE: This section is intended to address
[ISSUE #22](https://github.com/intarchboard/program-rfced-future/issues/22). 

## Editorial Stream

This document creates the Editorial Stream.

Any and all future documents produced by the RSWG and approved by 
the RSAB shall be published in the Editorial Stream.

## Creating and Deleting Streams

Creation and deletion of streams within the RFC Series shall be 
accomplished within the Editorial Stream: proposals for such
changes shall be made in the RSWG and, if approved by the RSAB,
such changes shall be documented in RFCs published within the 
Editorial Stream.


# IANA Considerations

This document defines several functions within the overall RFC Editor
structure, and it places the responsibility for coordination of
registry value assignments with the RFC Production Center. The IETF
LLC will facilitate the establishment of the relationship between the
RFC Production Center and IANA.

This document does not create a new registry nor does it register any
values in existing registries, and no IANA action is required.

# Security Considerations

The same security considerations as those in {{RFC8729}} apply. 
The processes for the publication of documents must prevent the
introduction of unapproved changes. Since the RFC Editor maintains
the index of publications, sufficient security must be in place to
prevent these published documents from being changed by external
parties. The archive of RFC documents, any source documents needed
to recreate the RFC documents, and any associated original documents
(such as lists of errata, tools, and, for some early items, originals
that are not machine-readable) need to be secured against any kind of
data storage failure.

The IETF LLC should take these security considerations into account
during the implementation and enforcement of the RFC Editor component
contracts.


# Changes from Version 2 of the RFC Editor Model

## RFC Series Editor

The RSWG and RSAB together provide a public process by which policies 
for the RFC series can be defined. It is expected that these
bodies will therefore cover some of the responsibilities of the RFC
Series Editor under Version 2.

## RFC Series Oversight Committee (RSOC)

In practice, the relationships and lines of authority and responsibility
between the IAB, RSOC, and RSE have proved unwieldy and somewhat opaque.
To overcome some of these issues, this document dispenses with the RSOC.



# IANA Considerations

This document has no actions for IANA.


--- back

# Acknowledgments
{:numbered="false"}

Portions of this document were borrowed from {{RFC5620}},
{{RFC6635}}, {{RFC8728}}, and earlier proposals within the
RFCED-Future Program by Martin Thomson, Brian Carpenter, and Michael 
StJohns. Thanks to the chairs of the Program, Eliot Lear and Brian
Rosen, for their leadership and assistance. Thanks also for feedback 
and proposed text and feedback to 
Jari Arkko,
Sarah Banks,
Scott Bradner,
Carsten Bormann,
Nevil Brownlee,
Ben Campbell,
Jay Daley,
Martin Duerst,
Lars Eggert,
Adrian Farrel, 
Stephen Farrell,
Sandy Ginoza,
Bron Gondwana,
Joel Halpern,
Wes Hardaker,
Bob Hinden,
Russ Housley,
Christian Huitema,
John Klensin,
Mirja Kuehlewind,
Ted Lemon,
John Levine,
Lucy Lynch,
Andrew Malis,
Larry Masinter,
S. Moonesamy,
Mark Nottingham,
Tommy Pauly,
Colin Perkins,
Julian Reschke,
Eric Rescorla,
Adam Roach,
Alice Russo,
Doug Royer,
Rich Salz,
Tim Wicinski,
and Nico Williams.

