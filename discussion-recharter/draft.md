---
title: Rechartering the IETF Discussion List
abbrev:
docname: draft-nottingham-discussion-recharter-00
date: {DATE}
category: info
updates: 3005

ipr: trust200902
area: General
workgroup: GENDISPATCH
keyword: Internet-Draft

stand_alone: yes
smart_quotes: no
pi: [toc, tocindent, sortrefs, symrefs, strict, compact, comments, inline]

author:
 -
    ins: M. Nottingham
    name: Mark Nottingham
    organization:
    street: made in
    city: Prahran
    region: VIC
    country: Australia
    email: mnot@mnot.net
    uri: https://www.mnot.net/


--- abstract

This document updates RFC3005, the charter of the IETF discussion list.


--- note_Note_to_Readers

*RFC EDITOR: please remove this section before publication*

The issues list for this draft can be found at <https://github.com/mnot/I-D/labels/discussion-recharter>.

The most recent (often, unpublished) draft is at <https://mnot.github.io/I-D/discussion-recharter/>.

Recent changes are listed at <https://github.com/mnot/I-D/commits/gh-pages/discussion-recharter>.

See also the draft's current status in the IETF datatracker, at
<https://datatracker.ietf.org/doc/draft-nottingham-discussion-recharter/>.

--- middle

# Introduction

The IETF discussion list was chartered to '\[further] the development and specification of Internet technology through discussion of technical issues, and \[host] discussions of IETF direction, policy, meetings and procedures.'{{!RFC3005}} It is thus considered the primary venue where the operation of the IETF is discussed, as well as the default home for technical discussions that don't have a more focused venue.

Over time, it has become the favoured venue for the IESG to 'take the temperature' of the IETF as a whole, especially for proposals that affect many either administratively or technically. Support on the list is taken as a sign that there is support within the IETF overall; objections on the list can stop a proposal from being enacted.

This draft contends that the IETF discussion list is not an appropriate venue for that, because it is not representative of the IETF community ({{representative}}), and because it is not productive ({{unproductive}}). {{recommendations}} recommends re-scoping the charter of the IETF discussion list to reflect this.


## The IETF discussion list is not representative {#representative}

The IETF discussion list is often said to be the place where the IETF community comes together. Discussion there often influences decisions made about the direction of the organisation, as well as specific technology choices. However, measuring how representative it is of the IETF community is difficult.

One way to approximate is to compare its membership with other IETF lists. Although this has many limitations (e.g., some may use different addresses; some may have subscribed and then disabled delivery rather than unsubscribing; subscription to a mailing list is only a weak proxy for participation in the IETF), it is nevertheless illuminating.

As of writing, the IETF discussion list has 1,751 members who have made their e-mail address public; 29 members have not made their addresses public.

Comparing its membership to a sample of other IETF mailing lists, we find that there are typically many members that are not taking part on the IETF discussion list:

| List        | Members | Overlap | % on IETF list |
|-------------+---------+---------+----------------|
| 6MAN        |   1,698 |     246 | 14.5%          |
| DISPATCH    |     436 |     111 | 25.5%          |
| DNSOP       |   1,041 |     204 | 19.6%          |
| GENDISPATCH |      54 |      37 | 68.5%          |
| OPSAWG      |     423 |     100 | 23.6%          |
| QUIC        |     853 |     121 | 14.2%          |
| RTGWG       |     610 |     119 | 19.5%          |
| SECDISPATCH |     153 |      50 | 32.7%          |
| TLS         |   1,257 |     134 | 10.7%          |
| WEBTRANS    |     110 |      39 | 35.5%          |
| WPACK       |      98 |      24 | 24.5%          |

When combined, the lists above have 5,355 unique addresses subscribed; only 628 (11.7%) of them are on the IETF discussion list.

The proportion of subscribed RFC authors is another lens to examine the IETF discussion list with. Again, this has many shortcomings, but can nevertheless help us to understand how representative the IETF discussion list is.

As of 11 August 2020, the RFC Editor queue contained 167 drafts, which had 352 unique author addresses. Of that group, 83 (23.6%) are also members of the IETF discussion list.

Using these two imperfect measurements, we can conclude that the entire IETF community is definitely not represented on the IETF discussion list; roughly, only 20-30% of both groups cross-participate. It's more difficult to draw other conclusions (such as what an acceptable level of representation should be, or why IETF participants choose not to subscribe to the IETF discussion list).

That said, discussion on the IETF discussion list does not imply knowledge or consent by the IETF community as a whole.


## The IETF discussion list is unproductive {#unproductive}

{{!RFC3005}} also specifies that 'considerable latitude is allowed' in what is considered acceptable on this mailing list.

This latitude has helped to make it difficult for the community to come to an agreement about the boundaries of discussion. {{!RFC3005}} empowers the IETF Chair, the IETF Executive Director or a sergeant-at-arms (SAA) appointed by the Chair to 'restrict posting by a person, or of a thread, when the content is inappropriate and represents a pattern of abuse.'

Subsequently, the SAA developed a Standard Operating Procedure (SoP) in consultation with the community, in an effort to assure that the community understood how this power would be used, that it was used in a fair and non-discriminatory fashion, and so that participants had more confidence about what was appropriate for the list.

When that power was recently exercised, there was considerable pushback within the community about its use, and the IETF Chair directed the SAA to rescind the restriction.

Without examining the issue as to whether it was appropriate for the SAA to use their power to restrict posting in that instance, this incident has made it clear that the tools available to the SAA to guide the nature of the discussion -- even once it's declared to be off-topic -- are blunt.

The mechanisms in {{!RFC3005}} are not adequate to reasonably guide discussion on this list to be productive, and as a result anecdotal evidence suggests that several participants are choosing to leave it, thereby making it even less representative of the IETF community.


# Re-Scoping the IETF discussion list {#recommendations}

This document updates {{!RFC3005}} by recommending that:

0. Discussion of IETF Last Calls continue to take place on the last-calls mailing list.

1. The IESG should not consider the IETF discussion list as an appropriate venue for notifying IETF participants of its actions or items under consideration. More suitable channels include the IETF Announcements list and the GENDISPATCH Working Group, depending on the notification.

2. The IESG should not consider the IETF discussion list as representative of the broader IETF community. As noted above, many participants are not active there, and some of those who are amplify their positions to distort a 'reading of the room.'

3. IETF participants who wish to make proposals about or discuss the IETF's direction, policy, meetings and procedures should do so in GENDISPATCH or other Working Group, if one more specific to that topic should exist.

4. IETF participants who wish to make proposals about or discuss technical issues should do so in the most appropriate Working Group or Area mailing list to the topic -- ideally publishing an Internet-Draft to further that discussion as appropriate. Topics without an obvious home and cross-area topics have been proven to be well-handled by the DISPATCH-style Working Groups.

5. Cross-area review should continue using a combination of review directorates, cross-participation, AD oversight and the Last Call discussion list.

6. There should be no explicit or implicit requirement for IETF leadership or any other person to be subscribed to the IETF discussion list.

7. Operational documents (such as <https://www.ietf.org/about/participate/tao/>, <https://www.ietf.org/how/lists/> and <https://www.ietf.org/how/lists/discussion/>) should be rewritten to reflect this understanding of the role of the IETF discussion list. In particular, newcomers to the IETF should not be steered towards subscribing to the IETF discussion list. Likewise, presentations to new IETF participants should be updated.

8. Operational documents should be updated to explain the role of the DISPATCH groups more clearly to newcomers.


# Security Considerations

The security of the Internet had better not depend upon the IETF discussion list.


--- back
