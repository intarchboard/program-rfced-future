---
title: "RFC Editor Model (Version 3)"
abbrev: "RFC Editor Model"
docname: draft-iab-rfcefdp-rfced-model-05
category: info
obsoletes: RFC8728
updates: RFC7841, RFC8729, RFC8730
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
    email: stpeter@stpeter.im

normative:

informative:
  I-D.draft-carpenter-rfced-iab-charter:
  RFC2418:
  RFC2850:
  RFC3777:
  RFC5378:
  RFC5620:
  RFC6635:
  RFC7154:
  RFC7282:
  RFC7322:
  RFC7776:
  RFC7841:
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

This document describes updated processes for defining and 
implementing policies regarding the RFC Series as a whole and 
thus specifies version 3 of RFC Editor Model. The model defines 
two high-level tasks related to the RFC Series. Policy definition 
is the responsibility of the RFC Series Working Group (RSWG), 
which produces policy proposals that are subject to approval 
by the RFC Series Approval Board (RSAB). Policy implementation 
is primarily the responsibility of the RFC Production Center 
(RPC), under the ultimate authority of the IETF Administration 
Limited Liability Company (IETF LLC).

This document obsoletes RFC 8728. This document updates RFC 7841,
RFC 8729, and RFC 8730.

--- middle

# Introduction

The Request for Comments (RFC) Series is the archival series 
dedicated to documenting Internet technical specifications,
including general contributions from the Internet research and
engineering community as well as standards documents. As described
in [RFC8700], RFCs have been published continually since 1969.
The overall framework for the RFC Series and the RFC Editor 
function are described in {{RFC8729}} and updated here.

The processes and organizational models for publication of RFCs
have changed significantly over the years. Most recently, in 2009 
{{RFC5620}} defined the RFC Editor Model (Version 1) and in 2012 
{{RFC6635}} defined the RFC Editor Model (Version 2), since 
modified slightly in 2020 by {{RFC8728}}. 

This document reflects experience gained with version 1 and 
version 2 of the Model, and therefore describes version 3 of 
the Model while remaining consistent with {{RFC8729}}.

In 2020, following up on meetings led by the RFC Series Editor
in 2019, the IAB formed an open program to conduct a community 
discussion and consensus process for the further evolution of 
the RFC Editor model. Under the auspices of this program, the 
community considered changes that would increase transparency 
and community input regarding the definition of policies for 
the RFC Series as a whole, while at the same time ensuring the
continuity of the RFC Series, maintaining RFC quality, 
maintaining timely processing, ensuring document accessibility,
and clarifying lines of authority and responsibility.

More specifically, in order to ensure sustainable maintenance 
and support of the RFC Series based on the principles of expert 
implementation, clear management and direction, and appropriate 
community input {{RFC8729}}, this document divides the 
responsibilities for the RFC Series into two high-level tasks: 

1. Policy definition governing the Series as a whole. This is 
the responsibility of the RFC Series Working Group (RSWG), which 
produces policy proposals that are subject to approval by the 
RFC Series Approval Board (RSAB). 

2. Policy implementation through publication of documents in the 
Series. This is primarily the responsibility of the RFC Production 
Center (RPC), under the ultimate authority of the IETF 
Administration Limited Liability Company (LLC) {{RFC8711}}.  

In this model, documents are produced and approved through 
multiple document streams. The stream manager for each stream 
is responsible for the content of that stream. The RFC Editor 
function is responsible for the packaging and distribution of 
the documents. As such, documents from these streams are 
edited and published by the Production Center.

The four streams that now exist are described in {{RFC8729}}.
This document adds a fifth stream, the Editorial Stream.

This document obsoletes {{RFC8728}}. This document updates 
{{RFC7841}}, {{RFC8729}}, and {{RFC8730}}.

# Overview of the Model

Version 2 of the RFC Editor Model {{RFC8728}} defined a structure
consisting of the RFC Series Editor, the RFC Production Center, and 
the RFC Publisher, with oversight provided by the RFC Series Oversight
Committee (RSOC) on behalf of the Internet Architecture Board (IAB).

By contrast, version 3 of the RFC Editor Model, specified here, 
provides a more consensus-oriented framework (similar in some 
respects to the structure of technical work within the IETF or 
IRTF) that retains roles for specialized expertise in document 
editing and publication.

Policy definition happens within the RFC Series Working Group (RSWG), 
which produces policy proposals that are subject to approval by the 
RFC Series Approval Board (RSAB), after which such policies are 
formally established through publication in the Editorial Stream 
within the RFC Series. The RSWG is an open working group (as described 
below) that seeks input and participation through a public process 
from a wide range of individuals who have an interest in the RFC Series. 
The RSAB consists of appointed members who represent the various RFC 
streams {{RFC8728}} as well as an expert in technical publishing, the 
RFC Series Consulting Editor (RSCE). 

Policy implementation is performed by the RFC Production Center (RPC), 
under the ultimate authority of the IETF Administration Limited Liability 
Company (IETF LLC).

In short:

* The RSWG proposes policies that govern the RFC Series as a whole, with 
  input from the community, the RSAB, and the RSCE.
* The RSAB considers those proposals and approves them, returns them to 
  the RSWG for further consideration, or declines to publish them, as 
  appropriate.
* If approved, such proposals are published as RFCs in the Editorial 
  Stream and thus define the policies to be followed by the RSWG, RSAB, 
  RSCE, and RPC.
* The RSCE provides expert advice to the RPC and RSAB on how to implement 
  established policies on an ongoing and operational basis, which can include
  raising issues or initiating proposed policy changes within the RSWG.
* The RPC implements the policies defined by the Editorial Stream in its
  day-to-day editing and publication of RFCs from other streams.
* If issues arise with the implementation of particular policies, the RPC 
  brings those issues to the RSAB, which interprets the policies and provides 
  interim guidance to the RPC, informing the RSWG of those interpretations.

This model is designed to ensure public processes and policy documents,
clear responsibilities and mechanisms for updates and changes to policies
governing the RFC Series as a whole, and operational implementation of the
RFC Series, thus meeting the requirements specified in Section 4 of {{RFC8729}}.

The remainder of this document describes the model in greater detail.

# Policy Definition

Policies governing the RFC Series as a whole are defined in the open 
through proposals that are generated by and discussed within the RFC
Series Working Group (RSWG) and then approved by the RFC Series Approval
Board (RSAB).

Policies under the purview of the RSWG and RSAB might include but
are not necessarily limited to document formats, processes for 
publication and dissemination of RFCs, and overall management of 
the RFC Series.

## Structure and Roles

### RFC Series Working Group (RSWG)

The RFC Series Working Group (RSWG) shall formulate proposals 
regarding policies that govern the RFC Series. The intent is 
that the RSWG operate in a way similar to working groups in the 
IETF and research groups in the IRTF. Therefore, all RSWG meetings 
shall be open to any participant, and all RSWG contributions 
shall be subject to intellectual property policies, which must be 
consistent with those of the IETF as specified in BCP 78 {{RFC5378}}
and BCP 79 {{RFC8179}}.

The RSWG shall operate by rough consensus, a mode of operation
informally described in {{RFC7282}}. 

When the RSWG is formed, all discussions shall take place on an 
open email discussion list. Subsequently, the RSWG may decide by rough 
consensus to also use additional tooling (e.g., GitHub as specified in 
{{RFC8874}}), forms of communication (e.g., in-person or online 
meetings), and working methods (e.g., design teams) as long as they 
are consistent with {{RFC2418}}.

All interested individuals are welcome to participate in the RSWG
(subject to anti-harassment policies as described below). This
includes participants in the IETF and IRTF, IAB and IESG members, 
individuals who use RFCs in procurement decisions, authors of RFCs 
and Internet-Drafts, developers of tools used to authors RFCs, and 
the like. The IETF LLC Board members, staff, and the IETF Executive 
Director are invited to participate as community members in the RSWG 
to the extent permitted by any relevant IETF LLC policies. Members 
of the RSAB are also expected to participate actively.

The RSWG shall have two chairs, one appointed by the IESG and the 
other appointed by the IAB. When the RSWG is formed, the chair 
appointed by the IESG shall serve for a term of one (1) year and
the chair appointed by the IAB shall serve for a term of two (2) 
years; thereafter, chairs shall serve for a term of two (2)
years, with no term limits on renewal. The appointing bodies shall
determine their own processes for making these appointments. 
Community members who have concerns about the performance of an 
RSWG chair should direct their feedback to the relevant appointing 
body. Each appointing body shall have the power to remove its 
appointed chair at its discretion at any time, and to name a 
replacement who shall serve the remainder of the original chair's 
term.

It is the responsibility of the chairs to encourage rough consensus 
within the RSWG and to follow that consensus in their decision making,
for instance regarding acceptance of new proposals and advancement of 
proposals to the RSAB.

Absent specific guidance in this document regarding the roles and
responsibilities of the chairs, the general guidance provided in
Section 6.1 of {{RFC2418}} should be considered appropriate.

### RFC Series Approval Board (RSAB)

The RFC Series Approval Board (RSAB) shall act as the approving body 
for proposals generated within the RSWG. The only policy-making role 
of the RSAB is to review policy proposals generated by the RSWG; it shall 
have no independent authority to formulate policy on its own. It is 
expected that the RSAB will respect the rough consensus of the
RSWG wherever possible, without ceding its responsibility to provide
appropriate review of RSWG proposals.

The voting members of the RSAB are as follows:

* As the stream representative for the IETF stream, an IESG member
  or a member of the community selected by the IESG
* As the stream representative for the IAB stream, an IAB member
  or a member of the community selected by the IAB
* As the stream representative for the IRTF stream, the IRTF chair 
  or their delegate appointed by the IRTF Chair
* As the stream representative for the Independent stream, the 
  Independent Submissions Editor (ISE) {{RFC8730}} or their 
  delegate appointed by the ISE
* The RFC Series Consulting Editor

The appointing bodies shall determine their own processes for 
appointing RSAB members (note that processes related to the RSCE 
are described below). Each appointing body shall have the power to 
remove its appointed RSAB member at its discretion at any time. 
Appointing bodies should ensure that voting members are seated at 
all times and should fill any vacancies with all due speed, if 
necessary on a temporary basis. In the case that the IRTF chair 
or ISE is incapacitated or otherwise unable to appoint a delegate, 
the IAB (as the appointing body for the IRTF chair and ISE 
respectively) shall appoint a temporary member until the IRTF 
chair or ISE has been appointed by the IAB. 

In the case of vacancies by voting members, the RSAB shall operate 
as follows:

* Activities related to implementation of policies already in force
  shall continue as normal.
* Voting on approval of policy documents produced by the RSWG shall
  be delayed until the vacancy or vacancies have been filled, up to a
  maximum of 3 months; this clause does not apply to a vacancy of the
  RSCE role, only of the stream representatives enumerated above.

To ensure the smooth operation of the RFC Series, the RSAB shall 
include the IETF Executive Director as a non-voting member since 
the IETF LLC is ultimately responsible for implementation of policies
governing the RFC Series. The RSAB may at its discretion include 
additional non-voting members, for instance a liaison from the RPC.

Whenever a new stream is created, the document that
creates the stream shall specify if a voting member representing 
that stream shall also be added to the RSAB, along with any rules
and processes related to that representative (e.g., whether the
representative is a member of the body responsible for the stream 
or an appointed delegate thereof). In effect, the RSCE is the voting
member representing the Editorial Stream.

The RSAB shall annually choose a chair from among its members using 
a method of its choosing.  If the chair position is
vacated during the chair's term, the RSAB should choose a new chair
from among its members.

The RSAB is expected to operate via email, in-person meetings, 
teleconferencing systems, and any additional tooling it deems
necessary. 

The RSAB shall keep a public record of its proceedings, including 
minutes of all meetings and a record of all decisions.

The RSAB shall announce plans and agendas for their meetings on the 
RFC Editor website and by email to the RSWG at least a week before 
such meetings. The meetings shall be open for public attendance and 
the RSAB may consider allowing open participation. If the RSAB needs 
to discuss a confidential matter in executive session, that part of 
the meeting shall be private to the RSAB, but must be noted on the 
agenda, and must be documented in the minutes with as much detail as 
confidentiality requirements permit.

## Process

### Intent

The intent is to provide an open forum by which policies related to the 
RFC Series are defined and evolved. The general expectation is that all 
interested parties will participate in the RSWG, and that only under 
extreme circumstances should RSAB members need to hold "CONCERN"
positions as described below. 

Because policy issues can be difficult and contentious, RSWG
participants and RSAB members are strongly encouraged to work together 
in a spirit of good faith and mutual understanding to achieve rough 
consensus (see {{RFC7282}}). In particular, RSWG members are 
encouraged to take RSAB concerns seriously, and RSAB members are 
encouraged to clearly express their concerns early in the process and 
to be responsive to the community. All parties are encouraged to respect 
the value of each stream and the long-term health and viability of 
the RFC Series.

This process is intended to be one of continuous consultation. RSAB 
members should consult with their constituent stakeholders (e.g.,
authors, editors, tool developers, and consumers of RFCs) on an ongoing 
basis, so that when the time comes to consider a proposal, there should 
be no surprises. Appointing bodies are expected to establish whatever 
processes they deem appropriate to facilitate this goal.

### Workflow

The following process shall be used to formulate or modify processes 
related to the RFC Series:

1. An individual participant in the RSWG generates a proposal in the 
   form of an Internet-Draft, which is submitted in full conformance 
   with the provisions of BCP 78 {{RFC5378}} and BCP 79 {{RFC8179}}.

2. If in following procedures for rough consensus the chairs determine 
   that there is sufficient interest in the proposal, the RSWG may 
   adopt the proposal as a draft proposal of the RSWG, in much the 
   same way a working group of the IETF or research group of the IRTF 
   would (see {{RFC2418}}).

3. The RSWG shall then further develop the proposal. Members of the
   RSAB are expected to participate in discussion relating to such 
   proposals so that they are fully aware of proposals early in the 
   policy definition process and so that any issues or concerns that 
   they have will be raised during the development of the proposal,
   not left until the RSAB review period. The RSWG chairs 
   are also expected to participate as individuals.

4. At some point, if the RSWG chairs believe there may be rough 
   consensus for the proposal to advance, they will issue a last call 
   for comment within the working group.

5. After a comment period of suitable length, the RSWG chairs will 
   determine whether rough consensus for the proposal exists (taking 
   their own feedback as individuals into account along with feedback 
   from other participants). If comments have been received and 
   substantial changes have been made, additional last calls may be 
   necessary.

6. Once consensus is established in the RSWG, the RSAB shall issue a 
   community call for comments as further described below. If 
   substantial comments have been received, the RSWG will again consider 
   those comments and make revisions as they see fit. At this same time, 
   the RSAB will also consider the proposal. 

7. If substantial changes have been made, additional community calls 
   for comment should be issued by the RSAB, and again comments considered 
   by the RSWG.

8. Once all comments have been addressed, the RSWG chairs will submit 
   the proposal to the RSAB for its consideration.

9. Within a reasonable period of time, the RSAB will then poll among 
   its members regarding the proposal. Positions may be as follows:

   * "YES": the proposal should be approved
   * "CONCERN": the proposal raises substantial concerns that must be 
     addressed
   * "RECUSE": the person holding the position has a conflict of 
     interest

Any RSAB member holding a "CONCERN" position must explain their concern 
to the community in detail. The explanation might or might not be actionable.

A position of CONCERN may be filed for two reasons:

   * The proposal represents a serious problem for the stream or group 
     that a particular member represents.
   * The RSAB member believes that the proposal would cause serious harm 
     to the overall Series, including harm to the long-term health and 
     viability of the Series.

Because RSAB members should have been participating in discussions
within the RSWG, no position of CONCERN should ever come as a surprise 
to the RSWG.

10. If a CONCERN exists, discussion will take place within the RSWG. 
    Again, all RSAB members are expected to participate.

11. A proposal without any CONCERN positions is approved. If 
    substantial changes have been made in order to address CONCERN 
    positions, an additional call for community input might be needed.

12. If, after a suitable period of time, any CONCERN positions remain, 
    a vote of the RSAB is taken. If at least three voting members vote 
    YES, the proposal is approved.

13. When a proposal is approved, a notification is sent to the community, 
    and the document enters the queue for publication as an RFC within
    the Editorial Stream.

### Community Calls for Comment

When a community call for comment is made, the RSAB sends a notice containing:

* A subject line beginning with 'Call for Comment:'
* A clear, concise summary of the proposal
* A URL to the Internet-Draft that defines the proposal
* Any commentary or questions for the community that the RSAB deems necessary 
  (using their usual decision-making procedures)
* Clear instructions on how to provide public comments
* A deadline for comments

Notices will always be sent to the rfc-interest mailing list. The RSAB and 
RSWG should also send notices to other communities that may be interested 
in or impacted by a proposal as they see fit, following policies for those 
communities as appropriate. Notices are also to be made available and archived 
on the rfc-editor.org web site. In addition, other communication channels can 
be established for notices (e.g., using an RSS feed or social media).

A comment period will not last less than two weeks. Comments will be publicly 
archived on the rfc-editor.org web site.

### Appeals

Appeals of RSWG decisions shall be made to the RSAB. Decisions of the 
RSWG can be appealed only on grounds of failure to follow the correct 
process. Appeals should be made within 30 days of any action, or in 
the case of failure to act, of notice having been given to the RSWG. 
The RSAB will then decide if the process was followed and will direct 
the RSWG chairs as to what procedural actions are required.

Appeals of RSAB decisions shall be made to the IAB and should be made 
within thirty (30) days of public notice of the relevant RSAB decision 
(typically, when minutes are posted). The IAB shall decide whether a 
process failure occurred and what if any corrective action should take 
place.

### Anti-Harassment Policy

The [IETF anti-harassment policy](https://www.ietf.org/about/groups/iesg/statements/anti-harassment-policy/) also applies to the RSWG and RSAB, 
which strive to create and maintain an environment in which people 
of many different backgrounds are treated with dignity, decency, 
and respect. Participants are expected to behave according to 
professional standards and to demonstrate appropriate workplace 
behavior. For further information about these policies, see 
{{RFC7154}}, {{RFC7776}}, and {{RFC8716}}.

### RFC Boilerplates

As part of the RFC Style Guide (see {{RFC7322}} and
[style guide web page](https://www.rfc-editor.org/styleguide/)),
new or modified RFC boilerplates (see {{RFC7841}}) considered under
version 3 of the RFC Editor Model must be approved by the following 
parties, each of which has a separate area of responsibility with 
respect to boilerplates:

* Each stream to which the boilerplate applies, which approves that 
  the boilerplate meets its needs
* The RSAB, which approves that the boilerplate is not in conflict with 
  the boilerplate used in the other streams
* The RPC, which approves that the language of the boilerplate conforms 
  to the RFC Style Guide
* The IETF Trust, which approves that the boilerplate correctly states 
  the Trust's position regarding rights and ownership

# Policy Implementation 

## Roles and Processes

Publication of RFCs is handled by the RFC Production Center (RPC).

A few general considerations apply: 

* The general roles and responsibilities of the RPC are defined by 
  RFCs published in the Editorial Stream (i.e., not directly by the 
  RSWG, RSAB, or RSCE).

* The RPC is advised by the RSCE and RSAB, and has a duty to 
  consult with them under specific circumstances, such as those 
  relating to disagreements between authors and the RPC.

* The RPC is contractually overseen by the IETF LLC to ensure that 
  it performs in accordance with contracts in place.

All matters of budget, timetable, and impact on its performance 
targets, are between the RPC and IETF LLC.

The RPC shall regularly provide reports to the IETF LLC, RSAB, RSWG, 
and broader community regarding its activities and any key risks or 
issues affecting it. 

In the event that the RPC is required to make a decision without 
consultation that would normally deserve consultation, or makes a 
decision against the advice of the RSAB, the RPC must notify the 
RSAB.

This document does not specify the exact relationship between the 
IETF LLC and the RPC; for example, the work of the RPC could be 
performed by a separate corporate entity under contract to the 
IETF LLC, it could be performed by employees of the IETF LLC, or 
the IETF LLC could engage with independent contractors for some or 
all aspects of such work. The exact relationship is a matter for 
the IETF LLC to determine.

The IETF LLC is responsible for the method of and management of the
engagement of the RPC.  Therefore, the IETF LLC has authority over 
negotiating performance targets for the RPC and also has responsibility 
for ensuring that those targets are adhered to. The IETF LLC is empowered 
to appoint a manager or to convene a committee to complete these 
activities.

If individuals or groups within the community have concerns about the 
performance of the RPC, they can request that the IETF LLC look into 
the matter. Even if the IETF LLC opts to delegate this activity, concerns 
should be raised with the IETF LLC. The IETF LLC is ultimately responsible 
to the community via the mechanisms outlined in its charter.

## Implementation-Specific Policies

Under and consistent with the high-level policies defined for the RFC 
Series in general or particular streams, the RPC shall define more 
particular policies regarding matters related to the editorial preparation
and final publication and dissemination of RFCs. Examples include:

* Maintenance of a style guide that defines editorial standards to which 
  RFCs must adhere (see {{RFC7322}} and the 
  [style guide web page](https://www.rfc-editor.org/styleguide/)).

* Policies regarding the file formats that are accepted as input to the 
  editing and publication process.

* Policies regarding the final structure and layout of published documents. 
  In the context of the XML vocabulary ({{RFC7991}}), such policies could
  include matters such as the exact XML elements and attributes used to
  capture the semantic content of RFCs. More generally, such policies 
  could address the readability and presentation of information in RFCs.

## RPC Responsibilities

The core responsibility of the RPC is continuous improvement regarding 
the implementation of RFC policies (including the dimensions of document 
quality, timeliness of production, and accessibility of results), while 
taking into account issues raised by the community through the RSWG and
by the stream managers. More specifically, the RPC's responsibilities 
include the following:

1. Editing inputs from all RFC streams to comply with the RFC Style Guide.

2. Creating and preserving records of edits performed on documents.

3. Identifying where editorial changes might have technical impact
   and seeking necessary clarification.

4. Engaging in dialogue with authors, document shepherds, IANA, or
   stream-specific contacts (e.g., working group chairs and stream
   managers) when clarification is needed.

5. Creating and preserving records of dialogue with document authors.

6. Requesting advice from the RSAB and RSCE as needed.

7. Providing suggestions to the RSAB and RSCE as needed.

8. Participating in the creation of new Editorial Stream RFCs that 
   impact the RPC, at least in an advisory capacity.

9. Providing reports to the community on its performance and plans.

10. Consulting with the community on its plans.

11. Negotiating its specific plans and resources with the IETF LLC.

12. Providing sufficient resources to support reviews of RPC
    performance by the IETF LLC.

13. Coordinating with IANA to ensure correct documentation of 
    IANA-performed protocol registry actions.

14. Assigning RFC numbers.

15. Establishing publication readiness of each document through
    communication with the authors, document shepherds, IANA, or
    stream-specific contacts, and, if needed, with the RSAB and RSCE. 

16. Liaising with stream managers and other representatives of the
    streams as needed.

17. Announcing and providing on-line access to RFCs.

18. Providing an on-line system to submit RFC Errata.

19. Providing on-line access to approved RFC Errata.

20. Providing backups.

21. Providing storage and preservation of records.

27. Authenticating RFCs for legal proceedings.

## Resolution of Disagreements between Authors and the RPC

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
  other relevant individuals and bodies (as described above), the issue 
  should be brought to the RSWG in order to formulate a new policy. However,
  in the interest of time the disagreement may be resolved as the parties 
  best see fit while the RSWG formulates a more general policy.

## External Representation

From time to time, individuals or organizations external to the IETF and 
the broader RFC Series community may have questions about the RFC Series. 
Such inquiries should be directed to the rfc-editor@rfc-editor.org email 
alias and then handled by the appropriate bodies (e.g., RSAB, RPC) or 
individuals (e.g., RSWG chairs, RSCE). 

## Administrative Implementation

The exact implementation of the administrative and contractual
activities described here are a responsibility of the IETF LLC. This
section provides general guidance regarding several aspects of such
activities.

### Vendor Selection for the RFC Production Center

Vendor selection is done in cooperation with the streams and 
under the final authority of the IETF LLC.

The IETF LLC develops the work definition (the Statement of Work) 
for the RPC and manages the vendor selection process.  The work
definition is created within the IETF LLC budget and takes into
account the needs of stream managers as well as community input.

The process to select and contract for an RFC Production Center
and other RFC-related services is as follows:

*  The IETF LLC establishes the contract process, including the steps
   necessary to issue an RFP when necessary, the timing, and the
   contracting procedures.

*  The IETF LLC establishes a selection committee, which will
   consist of the IETF Executive Director and other
   members selected by the IETF LLC in consultation with the 
   stream managers. The committee shall select a chair from 
   among its members.

*  The selection committee selects the vendor, subject to the
   successful negotiation of a contract approved by the IETF LLC.  In
   the event that a contract cannot be reached, the matter shall be
   referred to the selection committee for further action.

### Budget

The expenses discussed in this document are not new expenses. They
have been and remain part of the IETF LLC budget.

The RFC Series portion of the IETF LLC budget shall include funding
to support the RSCE, the RFC Production Center, and the Independent 
Stream.

The IETF LLC has the responsibility to approve the total RFC Editor
budget (and the authority to deny it). All relevant parties must work 
within the IETF LLC budgetary process.

# RFC Series Consulting Editor (RSCE)

The RFC Series Consulting Editor (RSCE) is a senior technical 
publishing professional who will apply their deep knowledge of 
technical publishing processes to the RFC Series. 

The primary responsibilities of the RSCE are as follows:

* Serve as a voting member on the RSAB
* Identify problems with the RFC publication process and 
  opportunities for improvement
* Provide expert advice regarding policy proposals within the RSWG
* If requested, provide expert advice to the RPC and IETF LLC

Matters on which the RSCE might be consulted could include the
following (see also Section 4 of {{RFC8729}}):

* Editing, processing, and publication of RFCs
* Publication formats for the RFC Series
* Changes to the RFC style guide
* Series-wide guidelines regarding document content and quality
* Web presence for the RFC Series
* Copyright matters related to the RFC Series
* Archiving, indexing, and accessibility of RFCs 

The IETF LLC is responsible for the method of and management of the
engagement of the RSCE, including selection, evaluation, and the timely 
filling of any vacancy. Therefore, whether the RSCE role is structured 
as a contractual or employee relationship is a matter for the IETF LLC 
to determine.

## RSCE Selection

The IETF LLC will form a selection committee, including members 
from the community, that will be responsible for making a 
recommendation to the IETF LLC for the RSCE role. The selection 
committee will take into account the definition of the role
as well as any other information that the committee deems 
necessary or helpful in making its decision. The IETF LLC is 
responsible for contracting or employment of the RSCE.

## RSCE Performance Evaluation

Periodically, the IETF LLC will evaluate the performance of the RSCE, 
including a call for confidential input from the community. The IETF LLC
will produce a draft performance evaluation for the RSAB (not including
the RSCE), which will provide feedback to the IETF LLC.

## Conflict of Interest

The RSCE is expected to avoid even the appearance of conflict of
interest or judgment in performing these roles.  To ensure this, the
RSCE will be subject to a conflict of interest policy established by
the IETF LLC.

# Editorial Stream

This document creates the Editorial Stream as separate space for
publication of policies, procedures, guidelines, rules, and related 
information regarding the RFC Series as a whole.

All documents produced by the RSWG and approved by the RSAB shall be 
published as RFCs in the Editorial Stream with a status of Informational. 
(Note that the Editorial Stream is not authorized to publish RFCs that 
are Standards Track or Best Current Practice, since such RFCs are 
reserved to the IETF Stream {{RFC8729}}.)

The Editorial Stream will be used only to specify and update policies, 
procedures, guidelies, rules, and related information regarding the 
RFC Series as a whole; no other use of the Editorial Stream is authorized 
by this memo and no other streams are so authorized. This policy may be 
changed only by agreement of the IAB, IESG, and IETF LLC.

The requirements and process for creating any additional RFC streams are
outside the scope of this document.

## Editorial Stream Boilerplate

This document specifies the following text for the "Status of This Memo"
section of RFCs published in the Editorial Stream. Any changes to this
boilerplate must be made through the RFC Series Policy Definition process
specified in this document.

Because all Editorial Stream RFCs have a status of Informational, 
the first paragraph of the "Status of This Memo" section shall be 
as specified in Appendix A.2.1 of {{RFC7841}}.

The second paragraph of the "Status of This Memo" section shall be 
as follows:

"This document is a product of the RFC Series Policy Definition process.
It represents the consensus of the RFC Series Working Group approved by 
the RFC Series Approval Board. Such documents are not candidates for any 
level of Internet Standard; see Section 2 of RFC 7841."

The third paragraph of the "Status of This Memo" section shall be 
as specified in Section 3.5 of RFC 7841.

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
during the implementation and enforcement of any relevant contracts.

# IANA Considerations

This document places responsibility for coordination of registry 
value assignments with the RPC. The IETF LLC facilitates management 
of the relationship between the RPC and IANA.

This document does not create a new registry nor does it register any
values in existing registries, and no IANA action is required.

--- back

# Changes from Version 2 of the RFC Editor Model

## RFC Editor Function

Several responsibilities previously assigned to the "RFC Editor"
or, more precisely, the "RFC Editor function" are now performed 
by the RSWG, RSAB, RPC, and IETF LLC (alone or in combination). 
These include various aspects of strategic leadership (Section 
2.1.1 of {{RFC8728}}), representation of the RFC Series (Section 
2.1.2 of {{RFC8728}}), development of RFC production and 
publication (Section 2.1.3 of {{RFC8728}}), development of the 
RFC Series (Section 2.1.4 of {{RFC8728}}), operational oversight 
(Section 3.3 of {{RFC8729}}), policy oversight (Section 3.4 of 
{{RFC8729}}), the editing, processing, and publication of 
documents (Section 4.2 of {{RFC8729}}), and development and 
maintenance of Series-wide guidelines and rules (Section 4.4 of 
{{RFC8729}}). In addition, various details regarding these 
responsibilities have been modified to accord with the new 
framework defined in this document.

## RFC Series Editor

Implied by the changes outlined in the previous section, the 
responsibilities of the RFC Series Editor (RSE) as a person or 
role (contrasted with the overall "RFC Editor function") are now
split or shared amongst the RSWG, RSAB, RPC, and IETF LLC (alone 
or in combination). More specifically, the responsibilities of
the RFC Series Consulting Editor (RSCE) under version 3 of the RFC 
Editor Model differ in many ways from the responsibilities of the 
RFC Series Editor under version 2 of the Model. In general, 
references in existing documents to the RSE can be taken as 
referring to the "RFC Editor function" as described herein, but 
should not be taken as referring to the RSCE.

## RFC Publisher

In practice the RFC Production Center (RPC) and RFC Publisher roles 
have been performed by the same entity and this practice is expected 
to continue; therefore this document dispenses with the distinction
and refers only to the RPC.

## IAB

Under earlier versions of the RFC Editor Model, the IAB was 
responsible for oversight of the RFC Series and acted as a body 
for final conflict resolution regarding the Series. The IAB's 
authority in these matters is described in the IAB's charter 
({{RFC2850}} as updated by {{I-D.draft-carpenter-rfced-iab-charter}}). 
Under version 2 of the Model, the IAB delegated some 
of its authority to the RFC Series Oversight Committee (see below). 
Under version 3 of the Model, authority for policy definition 
resides with the RSWG as an independent venue for work by members 
of the community (with approval of policy proposals as the 
responsibility of the RSAB, representing the streams and the RSCE), 
whereas authority for policy implementation ultimately resides with 
the IETF LLC.

## RFC Series Oversight Committee (RSOC)

In practice, the relationships and lines of authority and responsibility
between the IAB, RSOC, and RSE have proved unwieldy and somewhat opaque.
To overcome some of these issues, this document dispenses with the RSOC.
References to the RSOC in documents such as {{RFC8730}} are obsolete 
because this document does away with the RSOC.

## RFC Series Advisory Group (RSAG)

Version 1 of the RFC Editor Model {{RFC5620}} specified the existence of 
the RFC Series Advisory Group (RSAG), which was no longer specified in 
version 2 of the Model. For the avoidance of doubt, this document affirms 
that the RSAG is obsolete and its charter is no longer in force.

## Editorial Stream

This document creates the Editorial Stream in addition to the streams
already described in {{RFC8729}}.

# Acknowledgments
{:numbered="false"}

Portions of this document were borrowed from {{RFC5620}}, 
{{RFC6635}}, {{RFC8728}}, {{RFC8729}}, and earlier proposals 
submitted within the IAB's RFC Editor Future Development Program 
by Martin Thomson, Brian Carpenter, and Michael StJohns. Thanks 
to the chairs of the Program, Eliot Lear and Brian Rosen, for 
their leadership and assistance. Thanks also for feedback and 
proposed text to 
Jari Arkko,
Sarah Banks,
Carsten Bormann,
Scott Bradner,
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
Ole Jacobsen,
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

