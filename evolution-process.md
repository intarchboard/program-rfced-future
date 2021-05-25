# DRAFT RFC Evolution Process

## Scope

This procedure is applicable to the evolution processes relating to the management and evolution of the RFC series, including format, tooling, publication, dissemination, and overall management of the series.

## Structure

The RFC evolution process is governed as follows:

 * The RFC Working Group, whose job it is to develop proposed changes, and establish community consensus of those changes.
 * The The RFC Approval Board, whose job it is to provide final review of proposals.

Each group is described below.

### The RFC Working Group (RFCWG)

All RFCWG meetings are open to any participant, subject to intellectual property policies which must be consistent to those of the IETF [Note Well]. At body's initial formation, all discussions are to take place on open mailing lists, and anyone is welcome to comment / discuss. The RFCWG may decide by rough consensus to use additional forms of communication (for example, Github as specified in [RFC8874]) that are consistent with [RFC2418]. The group will conform itself to an anti-harassment policy consistent with [RFC7154,RFC7776].

IETF chair and the Independent Submissions Editor shall each appoint and oversee a co-chair of the RFCWG. 

### The RFC Approval Board (RFCAB)

The RFC Approval Board consists of representatives from each RFC stream (at the time of this writing, the IAB, the IETF, the IRTF, and the Indepenent Series), as well as the RS[EA].  The sole function of this group is to review draft proposals approvedby the RFCWG.  The RFCAB may choose its chair as it sees fit.  The group is primarily expected to operate via email and through any necessary tooling.  A record of all proceedings (no matter the form) will be kept.

## Update Process

The following procedure is used to update the RFC process:

1. Someone writes a draft proposal in the form of an Internet-Draft.
2. If there is sufficient interest in the proposal, RFCWG will adopt the proposal as a working draft, much the same way a working group of the IETF would.
3. The RFCWG will then further develop the proposal.  All members of the RFCAB are expected to participate in discussion relating to all proposals.
4. At some point, if the chairs believe there may be rough consensus exists for the proposal to advance, they will issue a working group last call.
5. After a suitable period of time, the chairs will determine whether rough consensus for the proposal exists.  If comments have been received and substantial changes have been made, it is expected that additional last calls may be made.
6. Once working group consensus is established, a community call for comments will be issued.  Should substantial comments be received, the working group will again consider those comments and make revisions as they see fit.  At this same time, the RFCAB will consider the proposal.
7. Should substantial changes be made, additional community calls for comment should be issued, and again comments considered.
8. Once all comments have been been addressed, the working group chairs will transmit the latest proposal to the RFCAB.
9. Within a reasonable period of time, the RFCAB will then poll on the proposal.  Positions may be as follows:
	* "YES": the proposal should be approved
	* "CONCERN" : the proposal raises substantial concerns that must be addressed.
	* "RECUSE" : the person holding the position has a conflict of interest.

	Anyone holding a "CONCERN" position MUST explain their concern to the community in detail.  The explanation may or may not be actionable.

	A CONCERN may be made for two reasons:
	
	 * The proposal represents a serious problem for the group a particular member represents.
	 * The member believes that the proposal would cause serious harm to the overall series, including harm to the long term health and viability of the series.
	
	No CONCERN should ever come as a surprise to the RFCWG.

10. If a CONCERN exists, discussion will take place within the RFCWG.  Again, all RFCAB members MUST participate.
11. If all CONCERN positions are addressed, then the proposal is approved.  Again, if substantial changes have been made, an additional call for community input should be made.
12. If, after a suitable period of time, any CONCERN positions remain, a formal vote of the RFCAB is taken. If a majority of RFCAB members vote to approve, the proposal is approved.  Otherwise, it is returned to the RFCWG.  In the case of a tie, the proposal is approved.
13. When a proposal is approved, a notification is sent to the community, and it is published as an RFC.

### The roles of the LLC Board and ED

LLC Board members, staff, and the Executive Director, are invited to participate as community members in the RFCWG to the extent permitted by any relevant LLC policies.

## Appeals

Appeals of RFCAB decisions may only be made based on process failures, and not on the substance of a proposal.  These appeals SHALL be made to the ISOC BoT within thirty days of the RFCAB decision.  The ISOC BoT MAY decide only whether a process failure occurred, and what if any corrective action should take place.

## Discussion

The intent of this policy is to provide an open forum by which policies and procedures of the RFC series are evolved.  The general expectation is that all interested parties will participate in the RFCWG, and that only under extreme circumstances should the RFCAB members have to hold "CONCERN" positions.  To avoid that situation, WG members are encouraged to take RFCAB concerns seriously, and RFCAB members are encouraged to make those concerns known early, and to be responsive to the community.  In particular, people are encouraged to respect the value of each stream, and the long term health and viability of the RFC series.

This process is intended to be one of continuous consultation.  In particular, RFCAB members should be consulting with their constuent groups on an ongoing basis, so that when the time comes to consider a proposal, there should be no surprises.  Appointing bodies are expected to establish whatever processes they deem appropriate to facilitate this goal.
