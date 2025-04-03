
Petition to Open Source Initiative and To Publish 2025 Board of Directors Election Results
================================================================

We the undersigned petition the Open Source Initiative (OSI) to release
the complete and accurate results of the 2025 Board of Directors
Individual and Affiliate elections.

In 2012, the OSI began running annual community elections, and for many
years, those elections have determined the majority of its board
of directors. In 2025, OSI published [overall election
information](https://web.archive.org/web/20250319054143/https://opensource.org/about/board-of-directors/elections)
and eventually announced that [OSI Affiliate organizations would
nominate and elect two
candidates](https://web.archive.org/web/20250323020823/https://opensource.org/about/board-of-directors/elections/affiliate),
and [OSI Individual members would nominate and elect one
candidate](https://web.archive.org/web/20250126161015/https://opensource.org/about/board-of-directors/elections/individual). Community
elections have always been advisory to the board, but OSI has
consistently written about board members as elected by Affiliates
members or Individual members, including calling them Individual
directors and Affiliate directors.


In 2025, the polls for both elections closed on March 17th. On March
21st, OSI posted what it claimed to be the "Complete election
results"[4], but unfortunately, they plainly are not complete and they
misrepresent the votes that were cast. Essentially, OSI altered the
ballots to erase 3 of the candidates and shifted voters ranked
preferences to fill in the gaps. We don't know if this is a very
unfortunate mistake with some good intentions, but we have seen multiple
OSI representatives suggesting there is nothing wrong.

OSI has consistently stated that the online elections are being run
with Scottish STV (Single Transferable Vote) rules, and included a link
to [OpaVote, detailing
STV](https://opavote.com/methods/single-transferable-vote#scottish-stv)
. OpaVote is a service which facilitates online elections and which OSI
used for the collection of votes. Understanding how OpaVote was used
helps understand exactly what went wrong. On OpaVote, anyone can sign up
as an "election manager", and they get access to self-service forms
which facilitate running an online election. For each of the 2
elections, OSI logged into opavote.com as an election manager, uploaded
a list of voter's email addresses, a list of candidates, selected
Scottish STV rules, and clicked a button open the polls.

OpaVote then emailed each of the voters a unique ballot url on
opavote.com. Here is [a screenshot of an unmarked
ballot](https://codeberg.org/OSI-Concerns/election-results-2025/src/branch/main/osi-2025-unmarked-ballot-example.png)
of the OSI 2025 Individual election, and [a filled in
one](https://codeberg.org/OSI-Concerns/election-results-2025/src/branch/main/osi-2025-marked-ballot-example.png). The
only way to fill in the ballot is by specifying a 1st preference and
then optionally a 2nd preference, and then optionally a 3rd, etc. After
the polls close, OpaVote provides the election manager an option to
publish the voting results to the voters. OSI did not use that
option. Instead, it seems they downloaded the ballot data, altered the
ballots, and used this to publish altered election results. In OSI's
results announcement, it is stated that [that 3 candidates were not
included in the final tally because of a failure to sign an agreement
with
OSI](https://opensource.org/blog/announcing-the-new-directors-of-osi-board). They
did not state which candidates had been removed from which
elections. What we quickly figured out is that in the individual
elections, Richard Fontana and Bentley Hensel were erased from final
ballots and apparently replaced with lower preference votes or if no
lower preference had been specified, then no preference at all. For the
Affiliates election, the same procedure was used to erase Bradley Kuhn
from the results.

We content what hopefully seems obvious: the correct and true election
results include the actual preferences that voters marked on their
ballots. There are several points of evidence beyond common sense to
show this. The link that OSI [uses to describe STV](https://opavote.com/methods/single-transferable-vote#scottish-stv)
contains a set of rules, and the rules
are clear that altering ballots is not an allowed part of the
procedure. This is nothing unique to STV, this is widely accepted
practice in elections.  OpaVote states that it follows the relevant
parts of the actual Scottish legislation
https://www.legislation.gov.uk/ssi/2007/42/made/data.xht?view=snippet&wrap=true
. That legislation is quite clear that there is no case in which a
voter's list of preferences may be altered, and the full election
results which must be announced are:

> give public notice of–
>
> (i)the name of the candidates elected;
>
> (ii)the number of first and subsequent preference votes for each candidate;
>
> (iii)the numbers of ballot papers transferred and their transfer values at each stage of the count;
>
> (iv)the number of votes credited to each candidate at each stage of the count;
>
> (v)the number of non transferable ballot papers at each stage of the count; and
>
> (vi)the number of rejected ballot papers under each head shown in the statement of rejected ballot papers.

Furthermore, we contacted OpaVote to find out their opinion of this
election. In an email, they stated "I understand your point; you want
the full results of the election to be published in the interest of
transparency." OpaVote cannot force OSI to publish the full results, but
they can see, just as we do, that contrary to [OSI's official
statement](https://opensource.org/blog/announcing-the-new-directors-of-osi-board),
the "complete election results" have not been published.

According to the Scottish STV rules, even in the event of a candidate's
death, if the full election results have already been determined, they
must be announced. And if a candidate's death is known before an
election's results are determined, the election is immediately canceled,
the ballots are never counted, and the election is rerun. The three
candidates have told us that they were disqualified after the polls had
closed. At that point, the full results had already become available to
OSI. Whatever disagreement OSI has or had with the three candidates, the
voters have no part in it. We only ask OSI to live up to a simple and
basic obligation of any election.

Some of us have heard from OSI what sounded like the theory that if OSI
had run an election without these 3 candidates, then voters would have
voted with the same preferences as the altered ballots, so the voters
haven't lost anything. We reject that idea. First of all, we've already
heard that additional candidates would have run if one of the existing
candidates had not. Secondly, there are several common and legitimate
voting strategies which do not conform to that assumption, and the
voters do not deserve to be punished for using them. The voters trusted
OSI to publish their true votes and have every right to feel that trust
has been broken.

We also know that if the OSI board were to override the will of the
voters by invoking the advisory nature of the elections, that would be
legitimate. But at this point, we cannot agree with OSI's claim that any
candidate has been elected by the Individual or Affiliate voters until
we know the true election results.

An [article at *LWN*](https://lwn.net/SubscriberLink/1014603/ac0cfc0a74755501/)
covers many other details about related contention around this election.

Many of us believe there are OSI board members and perhaps election
candidates who will hear our petition and realize that somehow, these
two elections have gotten off-track and steer OSI to do the right thing.


Petition detail
----------------

This is an open petition. The signed document is available on Codeberg
[here](https://codeberg.org/OSI-Concerns/election-results-2025), and
supporters are encouraged to submit their signature through a merge
request. If you have a relationship with OSI (e.g., a Member, Former
Director, etc.), pease indicate your relationship to OSI in your
signature.

We ask that OSI Affiliates have their Affiliate Representative sign on behalf
of the organization; they and other Affiliate employees/volunteers can of
course sign separtely on their own behalf, too.

Respectfully,

SIGNATORIES HERE
