# Bidding cheat-sheet

## Contents

- [Hand evaluation](#hand-evaluation)
  - [HCP](#hcp)
  - [LSDP](#lsdp)
  - [SSDP](#ssdp)
  - [TP](#tp)
  - [Advisory TP levels for Game and Slam](#advisory-tp-levels-for-game-and-slam)
- [Constructive bidding](#constructive-bidding)
  - [Opening bids](#opening-bids)
  - [Opening bids with a NT hand](#opening-bids-with-a-nt-hand)
  - [Responses](#responses)
  - [\[TODO\] Re-announces by Opener](re-announces-by-opener)
  - [\[TODO\] Slam exploration](#slam-exploration)
- [\[TODO\] Overcalls (competitive bidding)](#overcalls-competitive-bidding)
- [Doubles](#doubles)
  - [Take-out double](#take-out-double)
  - [Balancing double](#balancing-double)
  - [Negative double](#negative-double)
  - [Power double](#power-double)
  - [Penalty double](#penalty-double)
  - [Support double](#support-double)
  - [Lead-directing double](#lead-directing-double)
- [Conventions](#conventions)
  - [Stayman](#stayman)
  - [Smolen](#smolen)
  - [Transfer](#transfer)
  - [Texas transfer](#texas-transfer)
  - [Puppet Stayman](#puppet-stayman)
  - [Splinter](#splinter)
  - [Drury](#drury)
  - [Lebensohl](#lebensohl)
  - [Jacoby 2NT](#jacoby-2nt)
  - [Gambling](#gambling)
  - [RKCB](#rkcb)
  - [Gerber](#gerber)
  - [Multi-Landy](#multi-landy)
  - [Fourth suit forcing](#fourth-suit-forcing)
  - [New minor forcing](#new-minor-forcing)

---

## Hand evaluation

#### HCP

High Card Points. A=4, K=3, Q=2, J=1

A hand containing 12 HCP or more is good enough to make a constructive [opening bid](#opening-bids).

Rule of 20: if HCP + number of cards in the two longest suits \(\ge \) 20, hand is also worth an opening bid.

Hands with less HCP may open at level 2 or above (as a preempt), given a proper color distribution. [↑](#contents)

#### LSDP

Long Suit Distribution Points. LSDP for a given suit is defined as suit length minus 4. Those are then summed for all suits in player's hand.

*Example:* 6-5-1-1 hand will have an LSDP of 3. [↑](#contents)

#### SSDP

Short Suit Distribution Points. Only used after a fit is found. [↑](#contents)

| Suit Length   | SSDP |
| ------------- | ---- |
| 0 (void)      | 5    |
| 1 (singleton) | 3    |
| 2 (doubleton) | 1    |

#### TP

Total Points. 

TP = HCP + LSDP. Applicable when no fit exists, or it's not found yet)

TP = HCP + SSDP. Only applicable after a fit is found.

Do not combine SSDP and LSDP. [↑](#contents)

#### Advisory TP levels for game and slam

- 25+ TP = 3NT

- 26+ TP = 4♥️/♠️

- 28+ TP = 5♣️/♦️

- 33+ TP = 6♣️/♦️/♥️/♠️/NT

- 37+ TP = 7NT [↑](#contents)

## Constructive bidding

- General approach during constructive bidding is to keep the bid as low as possible, thus leaving more space to better describe hands. On the contrary - the faster a contract is reached, the weaker the hand that places the contract is.

- Prioritize majors (♥️/♠️) over minors (♣️/♦️).

- Prioritize playing NT contract with a balanced distribution in both hands, even when fit is found.
- Mind vulnerability [↑](#contents)

### Opening bids

Opening bid is the very first non-pass bid in the auction.


| Bid                   | HCP   | Description                                                  |
| --------------------- | ----- | ------------------------------------------------------------ |
| 1♣️                    | 12–21 | 3+♣️, 3-♦️, 4-♥️, 4-♠️                                           |
| 1♦️                    | 12–21 | 4-♣️4+♦️, 4-♥️, 4-♠️ **or** 2♣️3♦️4♥️4♠️                             |
| 1♥️/♠️                  | 12–21 | 5+♥️/♠️. Bid longer suit first. With equal lengths bid ♠️       |
| 1NT                   | 15–17 | Balanced or semi-balanced                                    |
| 2♣️<sup>A RF</sup>     | 22+   | Any hand with 22+HCP **or** 16+ HCP with 9+ tricks           |
| 2♦️<sup>A</sup>        | 6-10  | 5♥️ and 4♠️ **or** 5♠️ and 4♥️                                   |
| 2♥️/♠️                  | 6–10  | 6♥️/♠️, 3- in the other major                                  |
| 2NT                   | 20–21 | Balanced or semi-balanced                                    |
| 3♣️/♦️/♥️/♠️              | 6–10  | 7 card suit                                                  |
| 3NT<sup>A</sup>       | 9-15  | [Gambling](#gambling). AKQxxxx (7+) in ♣️/♦️. No outside A or K |
| 4♣️/♦️/♥️/♠️              | 5–10  | Preempt, 8 card suit                                         |
| 5♣️/♦️<sup>NONVUL</sup> | 0–10  | Preempt, 9 card suit [↑](#contents)               |

- Bids marked with <sup>A</sup> shall be alerted.

- <sup>GF</sup> denotes a game forcing bid (no pass below game level).

- <sup>RF</sup> denotes a round forcing bid (no immediate pass by partner, unless opener is guaranteed another chance to bid).

- <sup>NONVUL</sup> denotes a bid that is only recommended when non-vulnerable. When vulnerable, bid at a lower level.

- When more than one bid is possible according to the table, the lowermost such row must be chosen. Examples: prioritize 1NT over 1♥️/♠️ if both are possible. Prioritize 1♥️/♠️ over 1♦️.

- Rule of 20 applies [↑](#contents)

### Opening bids with a NT hand

Balanced hand is a hand with no singleton or void and at most one doubleton. Patterns: 4-3-3-3, 4-4-3-2 and 5-3-3-2.

Semi-balanced hand is a hand with no singleton or void and at most two doubletons. Patterns: 5-4-2-2 and 6-3-2-2.

With a balanced or semi-balanced hand, the aim is to show HCP holdings. This may take either one or two bids, as described: [↑](#contents)

| Bid                            | HCP   |
| ------------------------------ | ----- |
| 1♣️/♦️/♥️/♠️ then 1NT              | 12–14 |
| 1NT                            | 15–17 |
| 1♣️/♦️/♥️/♠️ then 2NT              | 18-19 |
| 2NT                            | 20-21 |
| 2♣️ then 2NT **or** 2♣️ then 3NT | 22+   |

### Responses

- Most responses are only applicable in case of an unopposed bidding.
- <sup>PASSED</sup> denotes a hand that's already been passed once, making it HCP-restricted. This may result in the same response meaning different things for a passed hand, compared to a non-passed one.
- Bidding a new non-jump suit<sup>GF</sup> at level 2 always shows 12+ HCP. This is the core of 2 over 1 system.
- After an opening bid of 1♦️/♥️/♠️, responder must stick to a level 1 response when holding only 6-11 HCP. [↑](#contents)


| Opening Bid | Response                            | HCP            | Description                                                  |
| ----------- | ----------------------------------- | -------------- | ------------------------------------------------------------ |
| 1♣️          |                                     |                |                                                              |
|             | PASS                                | 0-5            |                                                              |
|             | 1♦️/♥️/♠️<sup>RF</sup>                 | 6+             | 4+♦️/♥️/♠️. Bid longest suit first. With 4-4 bid lower, with 5-5 higher. Prioritize over fitting partner in minor. |
|             | 1NT                                 | 6-9            | no 4+ major                                                  |
|             | 2♣️<sup>RF</sup>                     | 10+            | Inverted minor: 5+ suit, no 4+♥️/4+♠️                          |
|             | 2♦️/♥️/♠️                              | 6-10           | 6+ suit. Preempt                                             |
|             | 2NT                                 | 10-11          | 3-♥️, 3-♠️                                                     |
|             | 3♣️                                  | 0-6            | 5+♣️. Preempt                                                 |
|             | 3NT                                 | 13+            | Balanced, 3-♥️, 3-♠️                                           |
|             | 4♥️/♠️                                |                | Unbalanced weak hand. No slam interest [↑](#contents)        |
| 1♦️          |                                     |                |                                                              |
|             | PASS                                | 0-5            |                                                              |
|             | 1♥️/♠️<sup>RF</sup>                   | 6+             | 4+♥️/♠️. Bid longer suit first. With 4-4 bid lower, with 5-5 higher.<br />Prioritize over fitting partner in minor. |
|             | 1NT                                 | 6-9            | no 4+ major                                                  |
|             | <sup>PASSED</sup> 2♣️                | 4-11           | 6+♣️, 3-♥️, 3-♠️. Non-forcing                                   |
|             | 2♣️<sup>GF</sup>                     | 13+            | 5+♣️, 3-♥️, 3-♠️                                                |
|             | 2♦️                                  | 10+            | Inverted minor: 5+♦️, 3-♥️, 3-♠️                                |
|             | 2♥️/♠️                                | 6-10           | 6+ suit. Preempt                                             |
|             | 2NT                                 | 10-11          | Balanced invite, 3-♥️, 3-♠️                                    |
|             | 3♦️                                  | 0-6            |                                                              |
|             | 3NT                                 | 13+            | Balanced, 3-♥️, 3-♠️                                           |
|             | 4♥️/♠️                                |                | Unbalanced weak hand. No slam interest [↑](#contents)        |
| 1♥️          |                                     |                |                                                              |
|             | PASS                                | 0-5            |                                                              |
|             | 1♠️<sup>RF</sup>                     | 6+             | 4+♠️                                                          |
|             | 1NT<sup>RF</sup>                    | 6-12           | 3-♠️                                                          |
|             | <sup>PASSED</sup> 2♣️<sup>A GF</sup> | 10-11          | [Drury](#drury). 3+♥️                                         |
|             | 2♣️/♦️<sup>GF</sup>                   | 12+            | 4+♣️/♦️                                                        |
|             | 2♥️                                  | 6-9            | 3+♥️                                                          |
|             | <sup>PASSED</sup> 2NT               | 10-11          | Game invite. 2-♥️ Stopers in ♣️♦️♠️                              |
|             | 2NT<sup>GF</sup>                    | 12+            | [Jacoby 2NT](#jacoby-2nt). 4+♥️                               |
|             | <sup>PASSED</sup> 3♥️                | 10-11          | Game invite. 3+♥️                                             |
|             | 3♠️<sup>GF</sup>                     | 11-14          | [Splinter](#splinter). 4+♥️, 1- in bid suit                   |
|             | 4♣️/♦️<sup>GF</sup>                   | 11-14          | [Splinter](#splinter). 4+♥️, 1- in bid suit                   |
|             | 4♥️                                  | 0-9            | 5+♥️ [↑](#contents)                                           |
| 1♠️          |                                     |                |                                                              |
|             | PASS                                | 0-5            |                                                              |
|             | 1NT<sup>RF</sup>                    | 6-12           | 3-♠️                                                          |
|             | <sup>PASSED</sup> 2♣️<sup>A GF</sup> | 10-11          | [Drury](#drury). 3+♠️                                         |
|             | 2♣️/♦️<sup>GF</sup>                   | 12+            | 4+♣️/♦️                                                        |
|             | 2♥️<sup>GF</sup>                     | 12+            | 5+♥️                                                          |
|             | 2♠️                                  | 6-9            | 3+♠️                                                          |
|             | <sup>PASSED</sup> 2NT               | 10-11          | Game invite. 2-♠️ Stopers in ♣️♦️♥️                              |
|             | 2NT<sup>GF</sup>                    | 12+            | [Jacoby 2NT](#jacoby-2nt). 4+♠️                               |
|             | <sup>PASSED</sup> 3♠️                | 10-11          | Game invite. 3+♠️.                                            |
|             | 4♣️/♦️/♥️<sup>GF</sup>                 | 11-14          | [Splinter](#splinter). 4+♠️, 1- in bid suit                   |
|             | 4♠️                                  | 0-9            | 5+♠️ [↑](#contents)                                           |
| 1NT         |                                     |                |                                                              |
|             | PASS                                | 0-6            |                                                              |
|             | 2♣️                                  | 7+             | [Stayman](#stayman). Exploring for 4-4 major fit.            |
|             | 2♦️/♥️/♠️/NT                           | 0+             | [Transfer](#transfer). 5+ ♥️/♠️/♣️/♦️                            |
|             | 3NT                                 | 10-16          | Balanced                                                     |
|             | 4♣️                                  | 12+            | [Gerber](#gerber)                                            |
|             | 4♦️/♥️<sup>A GF</sup>                 | 10+            | [Texas transfer](#texas-transfer). 6+ ♥️/♠️ [↑](#contents)     |
| 2♣️          |                                     |                |                                                              |
|             | 2♦️<sup>A</sup>                      | 0-7            | A = 2 controls, K = 1 Control.<br />Up to 2 controls         |
|             | 2♥️<sup>A GF</sup>                   | 8+             | Exactly 2 controls                                           |
|             | 2♠️<sup>A GF</sup>                   | 8+             | Exactly 3 controls                                           |
|             | 2NT<sup>A GF</sup>                  | 8+             | Exactly 4 controls                                           |
| 2♦️          |                                     |                |                                                              |
|             | 2♥️/♠️                                | 0+             | Better major [↑](#contents)                                  |
| 2♥️/♠️        |                                     |                |                                                              |
|             | 2NT<sup>A RF</sup>                  | 17+            | Asks partner to either show an outside Ace or King, or signoff. |
|             | New suit<sup>RF</sup>               | 16+            | 6+ suit or 5+ suit very strong                               |
|             | 3♥️/♠️                                | 6-9            | 2+ fit. Preempt                                              |
|             | 3NT                                 | 16+            | Stoppers in all other suits                                  |
|             | 4♥️/♠️                                | 6-9 **or** 16+ | 6-9+ HCP and 4+ fit **or** 16+ HCP and 2+ fit [↑](#contents) |
| 2NT         |                                     |                |                                                              |
|             | 3♣️                                  | 4+             | [Puppet Stayman](#puppet-stayman)                            |
|             | 3♦️/♥️/♠️                              | 0+             | [Transfer](#transfer). 5+ ♥️/♠️/♣️                              |
|             | 3NT                                 | 4-8            | To play                                                      |
|             | 4♣️                                  | 12+            | [Gerber](#gerber)                                            |
|             | 4♦️/♥️<sup>GF</sup>                   | 5+             | [Texas transfer](#texas-transfer). 6+ ♥️/♠️                    |
|             | 4NT                                 | 11-12          | Quantitative invite to 6NT [↑](#contents)                    |
|             |                                     |                |                                                              |

### [TODO] Re-announces by Opener

... [↑](#contents)

### [TODO] Slam exploration

... [↑](#contents)

## [TODO] Overcalls (competitive bidding)


| Opponent | Overcall            | HCP   | Description                                                  |
| -------- | ------------------- | ----- | ------------------------------------------------------------ |
| 1♣️/♦️     |                     |       |                                                              |
|          | X                   | 12+   | [Take-out double](#take-out-double), 2- in suite (or Power double, 16+ HCP). |
|          | 1♥️/♠️                | 7+    | Natural, 5+ suit                                             |
|          | 1NT                 | 16-18 | Balanced. Stopper in the bid suit                            |
|          | 2♣️/♦️<sup>A RF</sup> | 0-5   | Michaels cue bid. 5+♥️ and 5+♠️ [TODO] review or delete        |
|          |                     |       |                                                              |
|          | 2NT<sup>A RF</sup>  |       | Unusual 2NT. At least 5♥️ and 5 of the unbid minor suit       |
| 1♥️/♠️     |                     |       |                                                              |
|          | X                   | 12+   | [Take-out double](#take-out-double), 2- in suite (or Power double, 16+ HCP). |
|          | 2NT                 |       | 5+♣️ and 5+♦️                                                  |
|          |                     |       | 1                                                            |
| 1NT      |                     |       |                                                              |
|          | X                   | 16-18 | Balanced.                                                    |
|          | 2♣️/♦️/♥️/♠️/NT         |       | [Multi-Landy](#multi-landy)                                  |
| ...      |                     |       |                                                              |
| 2♥️/♠️     |                     |       |                                                              |
|          | X                   |       | [Take-out double](#take-out-double), 2- in suite (or Power double, 16+ HCP).<br />[Lebensohl](#lebensohl) responses by partner apply. [↑](#contents) |
|          |                     |       |                                                              |

## Doubles

- All doubles up to 3♠️ are round forcing <sup>RF</sup>.

- Any double coming as a first bid by the player is also round forcing <sup>RF</sup>. [↑](#contents)

#### Take-out double

Applicable when neither doubler nor his partner have made a prior non-pass bid. Shows 12+ HCP. Shortness (2-) in doubled suit. 3+ in other suits. With no shortness, do a trap pass instead. With 16-18HCP and a stopper bid 1NT, instead.

May later turn out to be a [Power double](#power-double).

Responses to take-out double up to level 2: [↑](#contents)

| Partner | Responder                         | Description                                                  |
| ------- | :-------------------------------- | :----------------------------------------------------------- |
| X       |                                   |                                                              |
|         | New suit, non-jump                | 0-8 HCP. 3+ (usually 4+) cards in suit                       |
|         | New suit, jump                    | 9-12 HCP. 4+ cards in suit. Invite                           |
|         | NT, non-jump                      | 7-10 HCP, stopper in doubled suit                            |
|         | NT, jump                          | 10-12 HCP if 2NT, Invite.                                    |
|         | 3NT                               | 13+ HCP. To play.                                            |
|         | Cue bid, non-jump <sup>A RF</sup> | 10+ HCP.                                                     |
|         | Cue bid, jump<sup>A RF</sup>      | 13+ HCP, no stopper in doubled suit. Asking partner to bid 3NT with a stopper [↑](#contents) |

#### Balancing double

Only used by 4th seat player to prevent opponents from playing too low. 10+ HCP<sup>VUL</sup> and 8+ HCP<sup>NONVUL</sup>. Shortness (2-) in doubled suit.

Most frequently used when opponent's suit is passed at level 1.

Also possible by a previously passed hand<sup>PASSED</sup> at level 2 when partner has shown a higher suit than opponent's. [↑](#contents)

#### Negative double

6+ HCP. Over 1 from partner and 1 overcall from opponent, shows exactly 4 cards in all unbid majors. Might have a 5-card ♥️only in 1♣️/♦️ - 1♠️ scenario with 9- HCP, since bidding 2♥️ requires 10HCP.

May later turn out to be a [Power double](#power-double). [↑](#contents)

#### Power double

16+ HCP. Any take-out, balancing or negative double can transform into a power double if the player bids again (incl. a second double). Showing a power-double invalidates any previous assumptions for hand's distribution. [↑](#contents)

#### Penalty double

A penalty double shows enough values and distribution to fail the contract. Penalty doubles are only used at 3NT and above (this doesn't necessarily mean that all doubles 4♣️ and above are for penalty).

Responder may also transform any take-out or power double into penalty double, when at level 3+ (preferably 4+) by passing. [↑](#contents)

#### Support double

Shows exactly 3 cards in partner's last bid suit, which has been overcalled by opponents. Same for support re-double if suit was doubled  instead of overcalled. With 4-card support, raise level instead. [↑](#contents)

#### Lead-directing double

- Doubling any artificial bid (e.g. [2♣️ Stayman](#stayman) or [RKCB](#rkcb) responses) is lead-directing for that suit.
- Lighter double - doubling of a voluntarily bid slam usually shows a void and asks partner not to lead trumps. If declarer or dummy bid a side suit, that's the one to lead. Otherwise the longest suit in hand must be lead.
- Doubling of a voluntarily bid 3NT asks for leading dummy's first suit. [↑](#contents)

## Conventions

#### Stayman

After 1NT - 2♣️, opener's rebids are as follows: [↑](#contents)

| Strong hand (1NT-2♦️) | Weak hand (2♣️)        | Description                |
| :------------------- | --------------------- | :------------------------- |
| 2♦️                   |                       | 3-♥️, 3-♠️                   |
|                      | 2NT                   | Invite. 8-9HCP             |
|                      | Color at level 3 or 4 | [Smolen](#smolen). 10+HCP. Unbalanced |
|                      | 3NT                   | 10+ HCP, 4-♥️, 4-♠️          |
| 2♥️                   |                       | 4♥️, may have 4♠️            |
|                      | 2♠️                    | 4♠️                         |
|                      | 2NT                   | Invite. 8-9HCP             |
|                      | 3NT                   | 10+ HCP, 3-♥️, 3-♠️          |
| 2♠️                   |                       | 4+♠️ 3-♥️                    |
|                      | 2NT                   | Invite. 8-9HCP             |
|                      | 3NT                   | 10+ HCP, 4-♥️, 3-♠️ [↑](#contents) |

#### Smolen

Convention is used after [Stayman](#stayman), only when holding enough values for a game and two major suits (5-4 or 6-4).
After 1NT - 2♣️ - 2♦️, with 10+ HCP responder shows 5-4 in majors by bidding the four-card major with a jump-shift, effectively promising 5 in the other one. In case of a 6-4 in majors, responder makes a transfer at level 4. ↑](#contents)

| Weak Hand (2♣️)    | Strong Hand (1NT-2♦️) | Description              |
| :---------------- | -------------------- | :----------------------- |
| 3♥️<sup>A GF</sup> |                      | 10+HCP. Promises 4♥️, 5♠️  |
|                   | 3NT                  | 2-♠️                      |
|                   | 4♠️                   | 3♠️                       |
| 3♠️<sup>A GF</sup> |                      | 10+HCP. Promises  4♠️, 5♥️ |
|                   | 3NT                  | 2-♥️                      |
|                   | 4♥️                   | 3♥️                       |
| 4♦️<sup>A GF</sup> |                      | 10+HCP. Transfer. 6♥️, 4♠️ |
|                   | 4♥️                   | Completing the transfer  |
| 4♥️<sup>A GF</sup> |                      | 10+HCP. Transfer. 6♠️, 4♥️ |
|                   | 4♠️                   | Completing the transfer  |

#### Transfer

After 1NT, responder shows a 5+ suite and asks opener to bid it.

| Opener | Responder | Description |
| ------ | :-------- | :---------- |
| 1NT    |           |             |
|        | 2♦️        | 5+♥️         |
|        | 2♥️        | 5+♠️         |
|        | 2♠️        | 5+♣️         |
|        | 2NT       | 5+♦️         |

Opener then completes the transfer at level 2 (default), or at level 3 (invite) when holding 17 HCP and 4+ fit. Responder raises to game when holding enough values. [↑](#contents)

#### Texas transfer

After 1NT, responder shows a 6+ major suite and asks opener to bid it.

| Opener | Responder         | Description |
| ------ | :---------------- | :---------- |
| 1NT    |                   |             |
|        | 4♦️<sup>A GF</sup> | 6+ ♥️        |
|        | 4♥️<sup>A GF</sup> | 6+ ♠️        |

Opener then completes the transfer at level 4 or initiates [slam exploration](#slam-exploration). [↑](#contents)

#### Puppet Stayman

After a 2NT opening, responder will often find themselves holding enough values for game.
In such cases responder shall bid 3♣️<sup>A GF</sup>, thus initiating the puppet.
Auction proceeds with an attempt to find a major fit (5-3 or 4-4) and have a Game declared by the strong hand: [↑](#contents)

| Strong Hand (2NT) | Weak Hand (3♣️) | Strong Hand (2NT) | Description                                                  |
| :---------------- | -------------- | ----------------- | :----------------------------------------------------------- |
| 3♦️<sup>A</sup>    |                |                   | 4♥️ **or** 4♠️                                                 |
|                   | 4♣️<sup>A</sup> |                   | 4♥️ and 4♠️. Slam interest                                     |
|                   |                | 4♦️<sup>A SF</sup> | Slam accept. Weak hand picks a major suit. Strong hand initiates [RKCB](#rkcb) |
|                   |                | 4♥️/♠️              | 4♥️/♠️. To play                                                |
|                   | 4♦️<sup>A</sup> |                   | 4♥️ and 4♠️. No slam interest                                  |
|                   |                | 4♥️/♠️              | Fit                                                          |
| 3♥️/♠️              |                |                   | 5+♥️                                                          |
|                   | 3NT            |                   | No fit                                                       |
|                   | 4♥️/♠️           |                   | Fit                                                          |
| 3NT               |                |                   | 3-♥️, 3-♠️ [↑](#contents)                           |

#### Splinter

A double jump-shift response to 1♥️/♠️ shows 4+ fit and shortness (1-) in bid suit. Always a game forcing <sup>GF</sup>.  [↑](#contents)

| Opening Bid | Response        | Description                        |
| ----------- | --------------- | ---------------------------------- |
| 1♥️          |                 |                                    |
|             | 3♠️<sup>GF</sup> | 4+♥️, 1-♠️                           |
|             | 4♣️<sup>GF</sup> | 4+♥️, 1-♣️                           |
|             | 4♦️<sup>GF</sup> | 4+♥️, 1-♦️                           |
| 1♠️          |                 |                                    |
|             | 4♣️<sup>GF</sup> | 4+♠️, 1-♣️                           |
|             | 4♦️<sup>GF</sup> | 4+♠️, 1-♦️                           |
|             | 4♥️<sup>GF</sup> | 4+♠️, 1-♥️ [↑](#contents) |

#### Drury

Drury is a conventional 2♣️<sup>A RF</sup> response by a passed hand after opener bids 1♥️/♠️.

| Opening bid | Drury bid                           | Response      | Description                     |
| ----------- | ----------------------------------- | ------------- | ------------------------------- |
| 1♥️/♠️        |                                     |               |                                 |
|             | <sup>PASSED</sup> 2♣️<sup>A RF</sup> |               | 10-11HCP, 3♥️/♠️                  |
|             |                                     | 2♦️            | 10-12HCP, sub-minimum           |
|             |                                     | 2♥️/♠️          | 12+ HCP                         |
|             |                                     | 2♥️ after 1♠️   | 4+♥️, can be sub-minimum         |
|             |                                     | any other bid | 12+ HCP, natural [↑](#contents) |

#### Lebensohl

Lebensohl is a way to describe the strength of a non-passed hand in the following scenarios:

- after 1NT by partner and 2♦️/♥️/♠️ overcall by opponent.

- after weak 2♦️/♥️/♠️ by opponent and double by partner.

With a minimum hand bid 2NT<sup>A RF</sup>, to which partner always responds with 3♣️<sup>A</sup>. Pass with clubs in hand, or pick a proper suit at level 3.

With an invitation hand bid a suit at level 3.

Holding enough for a game, make a cue-bid, bid 2NT->3NT or an immediate 3NT. [↑](#contents)

| Bid                         | HCP  | Description                                                  |
| --------------------------- | ---- | ------------------------------------------------------------ |
| 2NT<sup>A RF</sup>          | 0-7  | Minimum.                                                     |
| 2NT<sup>A RF</sup> then 3NT | 12+  | Stopper in opponent's suit                                   |
| suit at level 3             | 8-11 | Invite                                                       |
| cue-bid<sup>A GF</sup>      | 12+  | No stopper in opponents' suit. 4+ major suit                 |
| 3NT<sup>A GF</sup>          | 12+  | No stopper in opponents' suit. No 4+ major suit [↑](#contents) |

#### Jacoby 2NT

Over 1♥️/♠️ show 12HCP, 4+ fit by bidding 2NT<sup>A GF</sup>. Game forcing. [↑](#contents)

#### Gambling

9-15 HCP. AKQxxxx (7+) in ♣️/♦️. No outside A or K

If partner already passed, bid may be done with 21- HCP.

#### RKCB

Roman Key Card Blackwood. Used when partners agreed to a trump suit and is interested in slam. 4NT<sup>A RF</sup> bids asks partner how many key cards he holds. Key cards consist of all Aces plus the King of trumps. Responses: [↑](#contents)

| Asking bid         | Response       | Description                                                  |
| ------------------ | -------------- | ------------------------------------------------------------ |
| 4NT<sup>A RF</sup> |                |                                                              |
|                    | 5♣️<sup>A</sup> | 0 or 3 key cards                                             |
|                    | 5♦️<sup>A</sup> | 1 or 4 key cards                                             |
|                    | 5♥️<sup>A</sup> | 2 or 5 key cards. No Q in trump suit                         |
|                    | 5♠️<sup>A</sup> | 2 or 5 key cards. Has Q in trump suit [↑](#contents) |

##### Kings ask

After any RKCB response, 5NT rebid asks for Kings. Partner then answers how many kings he holds: [↑](#contents)

| Asking bid         | Response       | Description                       |
| ------------------ | -------------- | --------------------------------- |
| 5NT<sup>A RF</sup> |                |                                   |
|                    | 6♣️<sup>A</sup> | 0 Kings in hand                   |
|                    | 6♦️<sup>A</sup> | 1 King                            |
|                    | 6♥️<sup>A</sup> | 2 Kings                           |
|                    | 6♠️<sup>A</sup> | 3 Kings [↑](#contents) |

##### Queen ask

After a standard 0/3 or 1/4 response, the 4NT bidder may ask for Queen of trumps by bidding at the cheapest non-trump suit.  [↑](#contents)

| Asking bid                                                   | Response                   | Description                                         |
| ------------------------------------------------------------ | -------------------------- | --------------------------------------------------- |
| Relay - any non-trump suite at the lowest possible level<sup>A RF</sup> | Trump suit<sup>A</sup>     | No Q                                                |
|                                                              | 5NT<sup>A</sup>            | Has Q, no side-suit K                               |
|                                                              | Non-trump suit<sup>A</sup> | Has Q, has K in that suit [↑](#contents) |

#### Gerber

Immediate 4♣️<sup>A GF</sup> as a response to a natural 1NT or 2NT opening. Asking for Aces. Responses<sup>A</sup> follow the pattern 04-1-2-3. [↑](#contents)

| Asking bid        | Response        | Description |
| ----------------- | --------------- | ----------- |
| 4C<sup>A GF</sup> |                 |             |
|                   | 4♦️<sup>A</sup>  | 0 or 4 Aces |
|                   | 4♥️<sup>A</sup>  | 1 Ace       |
|                   | 4♠️<sup>A</sup>  | 2 Aces      |
|                   | 4NT<sup>A</sup> | 3 Aces      |

Optional follow-up 5♣️<sup>A RF</sup> asking for Kings. Responses follow the same pattern: 04-1-2-3. [↑](#contents)

#### Multi-Landy

Multi-Landy utilizes an artificial overcall bid at the 2nd level after opponents open 1NT.
All bids are artificial and shall be alerted <sup>A</sup>.
Overcalls are described in the table: [↑](#contents)

| Overcall           | Description                 |
| :----------------- | :-------------------------- |
| 2♣️ <sup>A RF</sup> | At least 5-4 in majors      |
| 2♦️ <sup>A RF</sup> | 6+ major, 3- in other suits |
| 2♥️ <sup>A</sup>    | 5+♥️ and 4+ minor            |
| 2♠️ <sup>A</sup>    | 5+♠️ and 4+ minor            |
| 2NT<sup>A RF</sup> | 5+♣️ and 5+♦️                 |

##### Responses:

| Overcall           | Response                | Description                                         |
| :----------------- | ----------------------- | :-------------------------------------------------- |
| 2♣️ <sup>A RF</sup> |                         |                                                     |
|                    | Pass                    | Good 6+♣️, non-forcing                               |
|                    | 2♦️                      | Equal length in majors. Asks partner to pick        |
|                    | 2♥️/♠️                    | Sign-off, to play                                   |
|                    | 3NT♠️                    | To play                                             |
|                    | 4♣️/♦️                    | Transfer for ♥️/♠️                                    |
| 2♦️ <sup>A RF</sup> |                         |                                                     |
|                    | 2♥️                      | Partner to pass or correct to 2♠️                    |
|                    | 2♠️                      | Partner to pass or correct to 3♥️                    |
| 2♥️/♠️ <sup>A</sup>  |                         |                                                     |
|                    | Pass                    | To play                                             |
|                    | 2NT                     | No support for major, asks partner to bid his minor |
|                    | 3♥️/♠️ (same suit)        | 3+ in suit, preempt                                 |
|                    | 3♣️/♦️/♥️/♠️ (another suit) | Good 6+ suit, no support, not forcing               |
|                    | 2NT                     | No support for major, asks partner to bid his minor |
|                    | 3NT                     | To play                                             |
| 2NT<sup>A RF</sup> |                         | 5+♣️ and 5+♦️                                         |
|                    | Any response at level 3 | To play                                             |
|                    | 4♣️/♦️                    | Invite for 5♣️/♦️                                     |
|                    | 4♥️/♠️                    | To play [↑](#contents)                   |

#### Fourth suit forcing

Any fourth suit<sup>A RF</sup> bid at level 2 or above is an artificial game forcing, promising no values or length in that suit. Opener's next bid is a natural one, but shall stick to the following priority:

| Priority | Bid                  | Description                               |
| -------- | :------------------- | :---------------------------------------- |
| Highest  | Raise partner's suit | 3 cards in suit                           |
| ..       | Re-bid own suit      | 5 cards in suit                           |
| ..       | NT with a jump       | Two stoppers in fourth suit               |
| ..       | NT without a jump    | Stopper in fourth suit                    |
| Lowest   | Raise fourth suit    | 4 cards in suit [↑](#contents) |

4SF does not apply in the following scenarios:

- 1♣️ - 1♦️ - 1♥️ - 1♠️ is natural
- After a 2/1<sup>GF</sup> or a reverse <sup>GF</sup> fourth suit is natural, since team already agreed to play a game
- Jump-shift in the fourth suit (e.g. 1♦️ - 1♠️ - 2♣️ - 3♥️) - shows a two-suited hand
- When opponents overcall or make a double

#### New minor forcing

After 1m-1M-1NT, bidding the other minor is a round-forcing and shows at least invitational values. Convention is only used in uncontested auctions, as shown:

| Opener | Responder | Opener | Responder                               | Description    |
| ------ | :-------- | ------ | --------------------------------------- | :------------- |
| 1♣️/♦️   |           |        |                                         | Natural        |
|        | 1♥️/♠️      |        |                                         | Natural. 4+♥️/♠️ |
|        |           | 1NT    |                                         | 12-14 HCP      |
|        |           |        | The other minor at level 2<sup>RF</sup> | 11+ HCP        |

##### Responses:

| Priority | Opener's rebid             | Description                                            |
| -------- | :------------------------- | :----------------------------------------------------- |
| Highest  | New major (can only be ♥️)  | 4♥️                                                     |
| ..       | Partner's major at level 2 | 3 cards in suit, min hand                              |
| ..       | Partner's major at level 3 | 3 cards in suit, max hand                              |
| ..       | 2NT                        | Stopper in fourth suit, min hand                       |
| ..       | 3NT                        | Stopper in fourth suit, max hand                       |
| ..       | Raise fourth suit          | 4 cards in suit                                        |
| Lowest   | Rebid own suit             | If none of the above applies [↑](#contents) |
