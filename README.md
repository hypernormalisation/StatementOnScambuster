# A response to the rejection of the Scambuster and Scambuster-Golemagg addons from the Curse addon platform.

On July 31st 2023, after 6 months of being published exclusively on the Curse platform, the Scambuster and Scambuster-Golemagg addons were rejected from Curse.
We include below the contents of the ticket submitted regarding this decision by the Golemagg Discord staff. You can find us and our server at:

- https://discord.gg/golemagg

___

I would like to discuss the delisting of two of my addons, and the stated reason for their rejection. The addons in question are "Scambuster" and "Scambuster-Golemagg".

The reason given for their rejection was the following:

> "After receiving numerous complaints and evaluating the "Scambuster" addons, it has been concluded that hosting these addons on CurseForge will not be permitted. Upon investigating the issue, it came to light that players were being unfairly blacklisted, with inconsistent and differing criteria applied by various groups, resulting in them being labeled as "scammers" to everyone on the server. This practice has even been misused to target particular players in some cases. If you possess evidence of certain players violating the game's rules, we urge you to report them to Blizzard through the appropriate channels."

I and the moderation team of the Golemagg discord have a number of comments/questions related to the above message to seek clarification on a few points, and would greatly appreciate it if anyone from Curse would have the time to engage with them - especially given nobody who develops and/or maintains our addons was privy to any deliberation on the viability of our addon's continued existance on the Curse platform.

## A comment on Scambuster's design philosophy

Prior to the existence of Scambuster, "blacklist" programs were widely disseminated by many realm discords in the form of WeakAuras to help their users avoid scammers and toxic users who were not being actively punished or stopped by Blizzard themselves. This had a few drawbacks:

- much work on the core functionality of how such a program should function was duplicated, and often implemented poorly/inefficiently and in a buggy fashion.
- the data on players who had committed infractions was bundled with the core WeakAura. Individual WeakAuras can often be difficult to keep updated, despite the existence of the WeakAura companion app (which at time of Scambuster release was still capable of producing extremely buggy and broken results in-game). Frequent updates to the data being used are a necessity of such a watchlist application.
- such lists used purely the names of the player toons involved in any harassment or scam. Name changes in wow are very easy, and this can also lead to false-positives where a vacant name previously used by a scammer or toxic player is taken up following a name-change by the original player.
- these programs rarely linked back to any concrete evidence on any infraction, with the user having to take the warnings by-word.
- the tendency of wow players to share weak-auras very freely (and perhaps carelessly) in-game meant that determining the original authors of such WeakAura programs, or determining if they had been in some way tampered with following their development, was difficult or impossible.

Scambuster attempted to do a few things differently:
- the core addon was simply a vehicle to scan fellow players during the user's interactions with them, and to cross-check their publicly identifiable information against an internal database, and to produce customisable warnings.
- such warnings are required to feature URL links back to the original evidence behind any case, such that trust was never naively assumed.
- ideally, cross-checking could be done using a player's Globally Unique IDentifier (GUID), avoiding the possibility of name-matches being false-positives, and allowing communities to track toxic or predatory users across name changes within the same WoW Classic server.
- the addon was designed explicitly as an open platform, such that communities would be able to leverage the development of Scambuster to curate their own lists for the needs of their own users. If a list was not well-curated, it would not see wide adoption. The developers of Scambuster made no judgements or assumptions about who would provide or curate high-quality information.
- in the event that a problematic extension addon was produced, Curse would be able to take action against it existing on its platform, whereas the ability of weakauras to be shared freely in-game limits Wago's ability to prevent the dissemination of improperly curated data.
- by moving the ecosystem to explicit addons, with open source code hosted on public sites and perhaps more easily interrogated for malicious code or intent than a WeakAura, the process could become more transparent.

We had hoped that this could result in the widescale improvement of one of the core service provided by almost every WoW Classic realm Discord, and result in more fair and transparent processes of complaints.

Certainly at Golemagg discord, the response to Scambuster in preventing our players from grouping with toxic or predatory individuals has been very overwhelmingly positive.

---

We would now like to address some parts of the Curse rejection message directly.

## 1

You state that the criteria for different groups were "inconsistent". This is largely a design feature of the addon; that it be decentralised such that different lists could be judged on their own merits and the quality of their curation.



I help oversee the management of the Golemagg server discord, and we spend a lot of time curating a fair and transparent list of infractions where players either behaved antisocially (using slurs or encouraging suicide/self-harm) and/or broke established loot rules that do not contravene Blizzard's rules (or do not contravene them badly enough for Blizzard to intervene). This list is of great value to our users in being alerted they are playing with people who will not respect their efforts or social boundaries before they commit a valuable lockout and their time to playing with others.

You state that "players were being unfairly blacklisted" - I would strongly argue that this is not the case for the Golemagg list, and this can be easily verified by going to our discord server at:

- https://discord.gg/golemagg

We have extensive quality-control that continually evolves, and each report is the subject of open and public debate among our userbase and moderation team. We also feature an appeals system whereby users put on the watchlist, and other users interested in the case, can give feedback after a case is closed, and whereby players who have committed infractions can demonstrate that they are willing to play by the established rules of the community and be taken off our lists.

Consequently, I do not think the Scambuster-Golemagg addon is fairly or accurately described by the phrase "players were being unfairly blacklisted... This practice has even been misused to target particular players in some cases".

I cannot attest to any other list that uses Scambuster as the approach leads to independently curated lists - I would have assumed that if any particular lists were curated in an unfair or problematic manner, the individual list addons themselves could be easily rejected by Curseforge. After all, WeakAuras is not considered responsible for every exploitative WeakAura that exists. A blanket ban on anything related to Scambuster seems like a crude and over-simplistic approach.

Why were the list addons themselves not rejected on an individual basis? Why was the base addon rejected?



## 2

Did Curse take specific issue with players being announced as "scammers"? Would Curse permit an addon that uses more general or less severe language to describe players on watchlists?



## 3 

Would Curse permit an addon that was incapable of broadcasting infractions to other users in a raid or party group, and merely presented the users with system messages of the relevant information?



## 4

Did Curse take specific issue with player information (in the form of GUIDs and toon names) being packaged into an addon? I ask because several addons that do exactly this still currently exist on your platform, e.g.

https://legacy.curseforge.com/wow/addons/benediction-blacklist

If so, why was the base Scambuster addon delisted and these addons remain active on your platform?

Has the Curse moderation team also checked addons like the above to verify that each player there is listed in a fair and transparent manner, apparently unlike our Scambuster-Golemagg that has been delisted? If so, what criteria would Curse expect of any discord moderation team attempting to curate a list of problematic players for their user base?

## 5 

Pertaining to the following:

"If you possess evidence of certain players violating the game's rules, we urge you to report them to Blizzard through the appropriate channels."

One issue with this statement is that not all behaviours from which players wish to protect themselves are restricted by Blizzard, and not all infractions of Blizzard's Terms of Service are actioned upon - though we always in turn suggest that our users also submit reports to official Blizzard channels even as they approach our Discord.

We have a very active and very valued LGBT+ community on the Golemagg WoW server, and on the Golemagg discord itself. We think it is also fair to say that the paratextual community surrounding WoW Classic is often not the most welcoming place for LGBT+ people, and note in particular the rampant transphobia that inflects so much of the playerbase and the spaces they create. We are very proud to have carved out a niche on our Discord server where LGBT+ players are more free to express themselves safely and without harassment or exclusion.

We also note that WoW Classic spaces can be places that feature a lot of racism and racist abuse, which in the EU in particular often focuses on players from Iran or who are of Iranian descent. We work hard to ensure a space where players of any race or nationalty can feel welcome, and part of this includes dealing with reports of racist language and slurs both in-game and via Discord private messages. Some of this racist language does not appear to be actionable via Blizzard.

One of the services we provide with our watchlist is alerting users that they are grouping with people who have a history of deploying extreme racist, homophobic and/or transphobic language etc, including slurs and incitement to self-harm and suicide. Blizzard do not always take action on such players, and any action is often extremely soft or impermanent.

We strongly disagree with that approach. We therefore include a "harassment" section of our list such that our players can be more safe when they play the game they enjoy.
This also extends to other exclusionary and intolerant behaviour and rhetoric, non-exhaustively including antisemitism, sexism etc.

You can see examples of these cases in:

- https://discord.com/channels/610036506974748700/1134246230424293508
- https://discord.com/channels/610036506974748700/1082700886540832828/1082958487333642250
- https://discord.com/channels/610036506974748700/1068810923235606618
- https://discord.com/channels/610036506974748700/1057732225992499210
- https://discord.com/channels/610036506974748700/1039246133945446410

To our knowledge, and after checking with some of the players involved who made the reports to us, Blizzard did not action upon these or did not action upon these in any permanent ways. Many of these players who used such extreme and aggressive language are still playing WoW Classic on the Golemagg server.

My question is then, if we report the bigoted and intolerant treatment of our userbase to Blizzard and Blizzard do nothing, what recourse do we then have if this type of information-sharing is not possible in-game to protect players from antisocial or violent behaviour?

Should players from vulnerable demographics not have some recourse to organise amongst themselves to better protect their communities if Blizzard's approach to protecting these players and their dignity is often piecemeal at best, and non-existant at worst?


## Moving Forward

The moderation team of the Golemagg discord would be very keen to continue to provide a service for our users to protect them from predatory and bigoted behaviour.
We see the ubiquity of "player reports" sections on WoW Classic realm discords as evidence that Blizzard's reporting functionality is not at all sufficient to stop players from being harassed by intolerant players, or taken advantage of by players with nefarious interests, and that some way of sharing information on such players in-game is a valuable service to provide.

Being part of the Curse ecosystem, and leveraging the Curse client, are vital to keeping our users up-to-date on people who have been taking advantage of or harassing other users - and equally vital to allow people who have reformed to be taken off of our watchlists promptly.

We would be very keen to move forward and work with Curse in such a way where we can produce a product that Curse does find acceptable to list on its platform.
To that end we seek clarification on:

- what are the rules regarding the packaging of such community watchlist addons?
- is it possible to tailor our product to be one that still provides the same core service, but in a way Curse finds amenable?


Thank you for your time.
