### Roster Details<br />
Team Name: Liquid<br />
Roster: jks, NAF, Twistzz, ultimate, YEKINDAR<br />
Global Rank: [15](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [12]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1546.8<br />
<br />
Final Rank Value (1546.8) = Starting Rank Value (1476.9) + Head To Head Adjustments (69.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.708[<sup>1</sup>](#table2)
- Bounty Collected: 0.550[<sup>2</sup>](#table1)
- Opponent Network: 0.186[<sup>2</sup>](#table1)
- LAN Wins: 0.645[<sup>2</sup>](#table1)

The average of these factors is 0.522<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1476.9
- 400 + ( ( 0.522 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1476.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |        7 | 2024-07-31 | Virtus.pro       | W   | 1.000      | 0.581        | 0.494 (0.287)    | 0.327 (0.190)    | 1 (1.000) |    22.75 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |     1520 | 2024-05-29 | G2               | L   | 0.781      | -            | -                | -                | -         |    -2.25 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     1545 | 2024-05-28 | Falcons          | W   | 0.774      | 0.624        | 0.231 (0.112)    | 0.250 (0.121)    | 1 (0.774) |    10.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     1563 | 2024-05-27 | 9z               | L   | 0.768      | -            | -                | -                | -         |   -14.19 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1574 | 2024-05-27 | Complexity       | W   | 0.766      | 0.624        | 0.348 (0.166)    | 0.367 (0.176)    | 1 (0.766) |    16.88 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1648 | 2024-05-23 | Eternal Fire     | L   | 0.738      | -            | -                | -                | -         |    -5.99 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1692 | 2024-05-22 | Astralis         | W   | 0.731      | 0.769        | 0.394 (0.221)    | 0.386 (0.217)    | -         |    17.90 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1737 | 2024-05-21 | ENCE             | W   | 0.724      | 0.769        | 0.173 (0.096)    | 0.404 (0.225)    | -         |     8.52 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     1793 | 2024-05-19 | AMKAL            | W   | 0.711      | 0.769        | 0.131 (0.071)    | 0.484 (0.264)    | -         |     3.73 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     1808 | 2024-05-18 | OG               | W   | 0.707      | 0.769        | 0.143 (0.078)    | -                | -         |     1.95 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2098 | 2024-05-10 | Astralis         | L   | 0.652      | -            | -                | -                | -         |    -4.23 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2142 | 2024-05-08 | FlyQuest         | W   | 0.638      | 0.889        | -                | 0.298 (0.169)    | 1 (0.638) |     3.91 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2210 | 2024-05-04 | MOUZ             | L   | 0.613      | -            | -                | -                | -         |    -1.90 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     2272 | 2024-05-01 | Monte            | W   | 0.593      | -            | -                | -                | 1 (0.593) |     1.27 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2295 | 2024-04-30 | FURIA            | W   | 0.586      | 0.889        | 0.284 (0.148)    | 0.495 (0.258)    | 1 (0.586) |    13.84 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2539 | 2024-04-19 | M80              | L   | 0.515      | -            | -                | -                | -         |   -12.88 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2589 | 2024-04-18 | M80              | W   | 0.508      | -            | -                | -                | -         |     3.21 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2592 | 2024-04-18 | Legacy           | W   | 0.507      | -            | -                | -                | -         |     1.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     2639 | 2024-04-17 | Akimbo           | W   | 0.501      | -            | -                | -                | -         |     0.29 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     2644 | 2024-04-17 | straykids        | W   | 0.500      | -            | -                | -                | -         |     0.16 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     2757 | 2024-04-12 | FaZe             | L   | 0.464      | -            | -                | -                | -         |    -2.91 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     2842 | 2024-04-10 | MOUZ             | L   | 0.450      | -            | -                | -                | -         |    -1.38 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     2920 | 2024-04-08 | G2               | W   | 0.437      | 0.624        | 1.000 (0.273)    | 0.492 (0.134)    | 1 (0.437) |    13.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     2930 | 2024-04-07 | HEROIC           | W   | 0.436      | 0.624        | 0.234 (0.063)    | 0.382 (0.104)    | 1 (0.436) |     9.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3602 | 2024-03-07 | SAW              | L   | 0.225      | -            | -                | -                | -         |    -5.89 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3684 | 2024-03-04 | Complexity       | L   | 0.207      | -            | -                | -                | -         |    -1.74 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3720 | 2024-03-03 | BOSS             | W   | 0.199      | -            | -                | -                | 1 (0.199) |     0.16 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3733 | 2024-03-02 | FURIA            | L   | 0.192      | -            | -                | -                | -         |    -1.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3748 | 2024-03-01 | BESTIA           | W   | 0.187      | -            | -                | -                | 1 (0.187) |     0.45 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     3819 | 2024-02-26 | Nouns            | W   | 0.162      | -            | -                | -                | -         |     0.22 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     3821 | 2024-02-26 | BOSS             | W   | 0.161      | -            | -                | -                | -         |     0.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     3834 | 2024-02-25 | Wildcard         | W   | 0.155      | -            | -                | -                | -         |     0.20 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     3839 | 2024-02-25 | Nouns            | L   | 0.154      | -            | -                | -                | -         |    -4.65 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     3898 | 2024-02-22 | Party Astronauts | W   | 0.135      | -            | -                | -                | -         |     0.20 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     3900 | 2024-02-22 | MIGHT            | W   | 0.134      | -            | -                | -                | -         |     0.02 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     3906 | 2024-02-22 | ex-CatEvil       | W   | 0.134      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($128,434.84)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.39) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-06-02 |      0.806 | $6,000.00      | $4,836.03       |
| 2024-05-23 |      0.738 | $100,000.00    | $73,808.80      |
| 2024-05-12 |      0.665 | $32,000.00     | $21,285.48      |
| 2024-04-14 |      0.477 | $10,000.00     | $4,772.78       |
| 2024-03-10 |      0.246 | $5,000.00      | $1,231.76       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
