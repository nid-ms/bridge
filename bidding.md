# Bidding cheat-sheet

## Hand Evaluation

#### HCP

High Card Points. A=4, K=3, Q=2, J=1

#### LSDP

Long Suit Distribution Points. LSDP for a given suit is defined as suit length minus 4. Those are then summed for all suits in player's hand.

*Example:* 6-5-1-1 hand will have an LSDP of 3.

#### SSDP

Short Suit Distribution Points. Only used after a fit is found.

| Suit Length   | SSDP |
| ------------- | ---- |
| 0 (void)      | 5    |
| 1 (singleton) | 3    |
| 2 (doubleton) | 1    |

#### TP

Total Points. 

TP = HCP + LSDP. Applicable when no fit exists, or it's not found yet)

TP = HCP + SSDP. Only applicable after a fit is found.

Do not combine SSDP and LSDP.

#### Advisory HCP and TP levels for Game and Slam

- 25+ HCP = 3NT

- 26+ TP = 4♥️/♠️

- 28+ TP = 4♣️/♦️

- 33+ HCP = 6NT

- 37+ HCP = 7NT

  

## Constructive bidding

- General approach during constructive bidding is to keep the bid as low as possible, thus leaving more space to better describe hands. On the contrary - the faster a contract is reached, the weaker the hand that places the contract is.

- Prioritize majors (♥️/♠️) over minors (♣️/♦️).

- Prioritize playing NT contract with a balanced distribution in both hands, even when fit is found.
- Mind vulnerability

### Opening Bids

Opening bid is the very first non-pass bid in the auction.


| Bid                   | HCP   | Description                                                  |
| --------------------- | ----- | ------------------------------------------------------------ |
| 1♣️                    | 12–21 | 3+♣️, 3-♦️, 4-♥️, 4-♠️                                           |
| 1♦️                    | 12–21 | 4-♣️4+♦️, 4-♥️, 4-♠️ **or** 2♣️3♦️4♥️4♠️                             |
| 1♥️/♠️                  | 12–21 | 5+♥️/♠️. Bid longer suit first. With equal lengths bid ♠️       |
| 1NT                   | 15–17 | Balanced or semi-balanced (4-3-3-3 or 5-3-3-2)               |
| 2♣️<sup>A RF</sup>     | 22+   | Any hand with 22+HCP **or** 16+ HCP with 9+ tricks           |
| 2♦️<sup>A</sup>        | 6-10  | 5♥️ and 4♠️ **or** 5♠️ and 4♥️                                   |
| 2♥️/♠️<sup>A</sup>      | 6–10  | 6 ♥️/♠️ **or** 5♥️/♠️ and a 4 card minor. 3- in the other major. |
| 2NT                   | 20–21 | Balanced or semi-balanced (4-3-3-3 or 5-3-3-2)               |
| 3♣️/♦️/♥️/♠️              | 6–10  | 7 card suit                                                  |
| 3NT<sup>A</sup>       | 9-15  | [Gambling](#gambling). AKQxxxx (7+) in ♣️/♦️. No outside A or K |
| 4♣️/♦️/♥️/♠️              | 5–10  | Preempt, 8 card suit                                         |
| 5♣️/♦️<sup>NONVUL</sup> | 0–10  | Preempt, 9 card suit                                         |

- Bids marked with <sup>A</sup> shall be alerted.

- <sup>GF</sup> denotes a game forcing bid (no pass below game level).

- <sup>RF</sup> denotes a round forcing bid (no immediate pass by partner, unless opener is guaranteed another chance to bid).

- <sup>NONVUL</sup> denotes a bid that is only recommended when non-vulnerable. When vulnerable, bid at a lower level.

- When more than one bid is possible according to the table, the lowermost such row must be chosen. Examples: prioritize 1NT over 1♥️/♠️ if both are possible. Prioritize 1♥️/♠️ over 1♦️.

### Opening Bids With NT Hand

With a balanced or semi-balanced hand (4-3-3-3 or 5-3-3-2), aim is to show partner HCP holdings. This may take either one or two bids, as described:

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


| Opening Bid | Response                 | HCP            | Description                                                  |
| ----------- | ------------------------ | -------------- | ------------------------------------------------------------ |
| 1♣️          |                          |                |                                                              |
|             | PASS                     | 0-5            |                                                              |
|             | 1♦️/♥️/♠️<sup>RF</sup>      | 6+             | 4+♦️/♥️/♠️. Bid longest suit first. With 4-4 bid lower, with 5-5 higher. Prioritize over fitting partner in minor. |
|             | 1NT                      | 6-9            | no 4+ major                                                  |
|             | 2♣️<sup>RF</sup>          | 10+            | Inverted minor: 5+ suit, no 4+♥️/4+♠️                          |
|             | 2♦️/♥️/♠️                   | 6-10           | 6+ suit. Preempt                                             |
|             | 2NT                      | 10-11          | no 4+ major                                                  |
|             | 3♣️                       | 0-6            | Preempt                                                      |
|             | 3NT                      | 13+            | Balanced, no 4+ major                                        |
|             | 4♥️/♠️                     |                | Unbalanced weak hand. No slam interest                       |
| 1♦️          |                          |                |                                                              |
|             | PASS                     | 0-5            |                                                              |
|             | 1♥️/♠️<sup>RF</sup>        | 6+             | 4+♥️/♠️. Bid longer suit first. With 4-4 bid lower, with 5-5 higher.<br />Prioritize over fitting partner in minor. |
|             | 1NT                      | 6-9            | no 4+ major                                                  |
|             | <sup>PASSED</sup> 2♣️     | 4-11           | 6+♣️, 3-♥️, 3-♠️. Non-forcing                                   |
|             | 2♣️<sup>GF</sup>          | 13+            | 4+♣️, no 4+♥️/♠️                                                |
|             | 2♦️                       | 10+            | Inverted minor: 5+ suit, no 4+♥️/4+♠️                          |
|             | 2♥️/♠️                     | 6-10           | 6+ suit. Preempt                                             |
|             | 2NT                      | 10-11          | no 4+ major                                                  |
|             | 3♦️                       | 0-6            |                                                              |
|             | 3NT                      | 13+            | Balanced, no 4+ major                                        |
|             | 4♥️/♠️                     |                | Unbalanced weak hand. No slam interest                       |
| 1♥️          |                          |                |                                                              |
|             | PASS                     | 0-5            |                                                              |
|             | 1♠️<sup>RF</sup>          | 6+             | 4+♠️                                                          |
|             | 1NT<sup>RF</sup>         | 6+             | 3-♠️                                                          |
|             | <sup>PASSED</sup> 2♣️/♦️   | 4-11           | 6+♣️/♦️, 3-♥️, 3-♠️. Non-forcing                                 |
|             | 2♣️/♦️<sup>GF</sup>        | 12+            | 4+♣️/♦️                                                        |
|             | 2♥️                       | 6-9            | 3+♥️                                                          |
|             | <sup>PASSED</sup> 2NT    | 10-11          | Game invite. 2-♥️ Stopers in ♣️♦️♠️                              |
|             | 2NT<sup>GF</sup>         | 12+            | [Jacoby 2NT](#jacoby-2nt). 4+♥️.<br />Bid is not applicable for a passed hand. |
|             | <sup>PASSED</sup> 3♥️     | 10-11          | Game invite. 3+♥️.                                            |
|             | 3♠️<sup>GF</sup>          | 11-14          | [Splinter](#splinter). 4+♥️, 1- in bid suit                |
|             | 4♣️/♦️<sup>GF</sup>        | 11-14          | [Splinter](#splinter). 4+♥️, 1- in bid suit                |
|             | 4♥️                       | 0-             | 5+♥️                                                          |
| 1♠️          |                          |                |                                                              |
|             | PASS                     | 0-5            |                                                              |
|             | 1NT<sup>RF</sup>         | 6+             | 3-♠️                                                          |
|             | 2♣️/♦️<sup>GF</sup>        | 12+            | 4+♣️/♦️                                                        |
|             | 2♥️<sup>GF</sup>          | 12+            | 5+♥️                                                          |
|             | 2♠️                       | 6-9            | 3+♠️                                                          |
|             | <sup>PASSED</sup> 2NT    | 10-11          | Game invite. 2-♠️ Stopers in ♣️♦️♥️                              |
|             | 2NT<sup>GF</sup>         | 12+            | [Jacoby 2NT](#jacoby-2nt). 4+♠️                            |
|             | <sup>PASSED</sup> 3♠️     | 10-11          | Game invite. 3+♠️.                                            |
|             | 4♣️/♦️/♥️<sup>GF</sup>      | 11-14          | [Splinter](#splinter). 4+♠️, 1- in bid suit                |
|             | 4♠️                       | 0+             | 5+♠️                                                          |
| 1NT         |                          |                |                                                              |
|             | PASS                     | 0-6            |                                                              |
|             | 2♣️                       | 7+             | [Stayman](#stayman). Exploring for 4-4 major fit.         |
|             | 2♦️/♥️/♠️/NT                | 0+             | [Transfer](#transfer). 5+ ♥️/♠️/♣️/♦️                         |
|             | 3NT                      | 10-16          | Balanced                                                     |
|             | 4♦️/♥️<sup>GF</sup>        | 10+            | [Texas transfer](#texas-transfer). 6+ ♥️/♠️                 |
| 2♣️          |                          |                |                                                              |
|             | 2♦️                       | 0-7            | A = 2 controls, K = 1 Control.<br />Up to 2 controls         |
|             | 2♥️<sup>GF</sup>          | 8+             | Exactly 2 controls                                           |
|             | 2♠️<sup>GF</sup>          | 8+             | Exactly 3 controls                                           |
|             | 2NT<sup>GF</sup>         | 8+             | Exactly 4 controls                                           |
| 2♦️          |                          |                |                                                              |
|             | 2♥️/♠️                     | 0+             | Better major                                                 |
| 2♥️/♠️        |                          |                |                                                              |
|             | 2♠️/3♣️/3♦️/3♥️<sup>RF</sup> | 16+            | 5+ suit. Round forcing.                                      |
|             | 3♥️/♠️                     | 6-9            | Preempt                                                      |
|             | 3NT                      | 16+            | Stoppers in all other suits                                  |
|             | 4♥️/♠️                     | 6-9 **or** 16+ | 6-9+ HCP and 4+ fit **or** 16+ HCP and 2+ fit                |
| 2NT         |                          |                |                                                              |
|             | 3♣️                       | 4+             | Puppet Stayman. Exploring for 4-4 and 5-3 major fit          |
|             | 3♦️/♥️/♠️                   | 0+             | [Transfer](#transfer). 5+ ♥️/♠️/♣️                              |
|             | 3NT                      | 4-8            | No interest in finding a major fit (4-3-2-2)                 |
|             | 4♦️/♥️<sup>GF</sup>        | 5+             | [Texas transfer](#texas-transfer). 6+ ♥️/♠️                    |
|             | 4NT                      | 11-12          | Quantitative invite to 6NT                                   |
|             |                          |                |                                                              |

### [TODO] Re-announces by Opener

...

### [TODO] Slam Exploration

...

## [TODO] Overcalls (Competitive Bidding)


| Opponent | Overcall            | HCP   | Description                                                  |
| -------- | ------------------- | ----- | ------------------------------------------------------------ |
| 1♣️/♦️     |                     |       |                                                              |
|          | X                   | 12+   | [Take-out double](#take-out-double), 2- in suite **or**<br />Power double 16+ HCP. |
|          | 1♥️/♠️                | 7+    | Natural, 5+ suit                                             |
|          | 1NT                 | 16-18 | Balanced. Stopper in the bid suit                            |
|          | 2♣️/♦️<sup>A RF</sup> | 0-5   | Michaels cue bid. 5+♥️ and 5+♠️ [TODO] review or delete        |
|          |                     |       |                                                              |
|          | 2NT<sup>A RF</sup>  |       | Unusual 2NT. At least 5♥️ and 5 of the unbid minor suit       |
| 1♥️/♠️     |                     |       |                                                              |
|          | X                   | 12+   | [Take-out double](#take-out-double), 2- in suite **or**<br />Power double 16+ HCP. |
|          | 2NT                 |       | 5+♣️ and 5+♦️                                                  |
|          |                     |       | 1                                                            |
| 1NT      |                     |       |                                                              |
|          | X                   | 16-18 | Balanced.                                                    |
|          | 2♣️/♦️/♥️/♠️/NT         |       | [Multi-Landy](#multi-landy)                               |
| ...      |                     |       |                                                              |

## Doubles

- All doubles up to 3♠️ are round forcing <sup>RF</sup>.

- Any double coming as a first bid by the player is also round forcing <sup>RF</sup>.

#### Take-out double

12+ HCP. Shortness (2-) in doubled suit. 3+ in other suits. With no shortness, do a trap pass instead. With 16-18HCP and a stopper bid 1NT, instead.

May later turn out to be a [Power double](#power-double).

Responses to take-out double up to level 2:

| Partner | Responder                         | Description                                                  |
| ------- | :-------------------------------- | :----------------------------------------------------------- |
| X       |                                   |                                                              |
|         | New suit, non-jump                | 0-8 HCP. 3+ (usually 4+) cards in suit                       |
|         | New suit, jump                    | 9-12 HCP. 4+ cards in suit. Invite                           |
|         | NT, non-jump                      | 7-10 HCP, stopper in doubled suit                            |
|         | NT, jump                          | 10-12 HCP if 2NT, Invite.                                    |
|         | 3NT                               | 13+ HCP. To play.                                            |
|         | Cue bid, non-jump <sup>A RF</sup> | 10+ HCP.                                                     |
|         | Cue bid, jump<sup>A RF</sup>      | 13+ HCP, no stopper in doubled suit. Asking partner to bid 3NT with a stopper |

#### Balancing double

Only used by 4th seat player to prevent opponents from playing too low. 10+ HCP<sup>VUL</sup> and 8+ HCP<sup>NONVUL</sup>. Shortness (2-) in doubled suit.

Most frequently used when opponent's suit is passed at level 1.

Also possible by a previously passed hand<sup>PASSED</sup> at level 2 when partner has shown a higher suit than opponent's.

#### Negative double

6+ HCP. Over 1 from partner and 1 overcall from opponent, shows exactly 4 cards in all unbid majors. Might have a 5-card ♥️only in 1♣️/♦️ - 1♠️ scenario with 9- HCP, since bidding 2♥️ requires 10HCP.

May later turn out to be a [Power double](#power-double).

#### Power double

16+ HCP. Any take-out, balancing or negative double can transform into a power double if the player bids again (incl. a second double). Showing a power-double invalidates any previous assumptions for hand's distribution.

#### Penalty double

A penalty double shows enough values and distribution to fail the contract. Penalty doubles are only used at 3NT and above (this doesn't necessarily mean that all doubles 4♣️ and above are for penalty).

Responder may also transform any take-out or power double into penalty double, when at level 3+ (preferably 4+) by passing.

## Conventions

#### Stayman

After 1NT - 2♣️, opener's rebids are as follows:

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
|                      | 3NT                   | 10+ HCP, 4-♥️, 3-♠️          |

#### Smolen

Convention is used after [Stayman](#stayman), only when holding enough values for a game and two major suits (5-4 or 6-4).
After 1NT - 2♣️ - 2♦️, with 10+ HCP responder shows 5-4 in majors by bidding the four-card major with a jump-shift, effectively promising 5 in the other one. In case of a 6-4 in majors, responder makes a transfer at level 4. 

| Weak hand (2♣️)    | Strong hand (1NT-2♦️) | Description              |
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

Opener then completes the transfer at level 2 (default), or at level 3 (invite) when holding 17 HCP and 4+ fit. Responder raises to game when holding enough values.

#### Texas Transfer

After 1NT, responder shows a 6+ major suite and asks opener to bid it.

| Opener | Responder         | Description |
| ------ | :---------------- | :---------- |
| 1NT    |                   |             |
|        | 4♦️<sup>A GF</sup> | 6+ ♥️        |
|        | 4♥️<sup>A GF</sup> | 6+ ♠️        |

Opener then completes the transfer at level 4 or initiates [slam exploration](#slam-exploration).

#### Puppet Stayman

After 3NT - 3♣️, opener's rebids are as follows:

[TODO] Expand.

#### Splinter

A double jump-shift response to 1♥️/♠️ shows 4+ fit and shortness (1-) in bid suit. Always a game forcing <sup>GF</sup>

| Opening Bid | Response        | Description |
| ----------- | --------------- | ----------- |
| 1♥️          |                 |             |
|             | 3♠️<sup>GF</sup> | 4+♥️, 1-♠️    |
|             | 4♣️<sup>GF</sup> | 4+♥️, 1-♣️    |
|             | 4♦️<sup>GF</sup> | 4+♥️, 1-♦️    |
| 1♠️          |                 |             |
|             | 4♣️<sup>GF</sup> | 4+♠️, 1-♣️    |
|             | 4♦️<sup>GF</sup> | 4+♠️, 1-♦️    |
|             | 4♥️<sup>GF</sup> | 4+♠️, 1-♥️    |

#### Jacoby 2NT

Over 1♥️/♠️ show 12HCP, 4+ fit by bidding 2NT<sup>A GF</sup>. Game forcing.

#### Gambling

9-15 HCP. AKQxxxx (7+) in ♣️/♦️. No outside A or K

If partner already passed, bid may be done with 21- HCP.

#### RKCB

Roman Key Card Blackwood. Used when partners agreed to a trump suit and is interested in slam. 4NT<sup>A RF</sup> bids asks partner how many key cards he holds. Key cards consist of all Aces plus the King of trumps. Responses:

| Asking bid         | Response       | Description                           |
| ------------------ | -------------- | ------------------------------------- |
| 4NT<sup>A RF</sup> |                |                                       |
|                    | 5♣️<sup>A</sup> | 0 or 3 key cards                      |
|                    | 5♦️<sup>A</sup> | 1 or 4 key cards                      |
|                    | 5♥️<sup>A</sup> | 2 or 5 key cards. No Q in trump suit  |
|                    | 5♠️<sup>A</sup> | 2 or 5 key cards. Has Q in trump suit |

##### Kings Ask

After any RKCB response, 5NT rebid asks for Kings. Partner then answers how many kings he holds:

| Asking bid         | Response       | Description     |
| ------------------ | -------------- | --------------- |
| 5NT<sup>A RF</sup> |                |                 |
|                    | 6♣️<sup>A</sup> | 0 Kings in hand |
|                    | 6♦️<sup>A</sup> | 1 King          |
|                    | 6♥️<sup>A</sup> | 2 Kings         |
|                    | 6♠️<sup>A</sup> | 3 Kings         |

##### Queen Ask

After a standard 0/3 or 1/4 response, the 4NT bidder may ask for Queen of trumps by bidding at the cheapest non-trump suit.

| Asking bid                                                   | Response       | Description               |
| ------------------------------------------------------------ | -------------- | ------------------------- |
| Relay - any non-trump suite at the lowest possible level<sup>A RF</sup> | Trump suit     | No Q                      |
|                                                              | 5NT            | Has Q, no side-suit K     |
|                                                              | Non-trump suit | Has Q, has K in that suit |

#### Multi-Landy

Multi-Landy utilizes an artificial overcall bid at the 2nd level after opponents open 1NT.
All bids are artificial and shall be alerted <sup>A</sup>.
Overcalls and responses are described in the table:

| Overcall            | Description                 |
| :------------------ | :-------------------------- |
| 2♣️ <sup>A RF</sup>  | At least 5-4 in majors      |
| 2♦️ <sup>A RF</sup>  | 6+ major, 3- in other suits |
| 2♥️ <sup>A</sup>     | 5+♥️ and 4+ minor            |
| 2♠️ <sup>A</sup>     | 5+♠️ and 4+ minor            |
| 2NT <sup>A RF</sup> | 5+♣️ and 5+♦️                 |

