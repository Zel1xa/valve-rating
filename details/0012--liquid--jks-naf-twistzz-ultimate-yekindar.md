### Roster Details<br />
Team Name: Liquid<br />
Roster: jks, NAF, Twistzz, ultimate, YEKINDAR<br />
Global Rank: [12](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1583.2<br />
<br />
Final Rank Value (1583.2) = Starting Rank Value (1500.6) + Head To Head Adjustments (82.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.666[<sup>1</sup>](#table2)
- Bounty Collected: 0.585[<sup>2</sup>](#table1)
- Opponent Network: 0.189[<sup>2</sup>](#table1)
- LAN Wins: 0.715[<sup>2</sup>](#table1)

The average of these factors is 0.539<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1500.6
- 400 + ( ( 0.539 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1500.6


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
|           37 |       79 | 2024-08-01 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.331 (0.192)    | 1 (1.000) |    28.05 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           36 |      121 | 2024-07-31 | Virtus.pro       | W   | 1.000      | 0.581        | 0.496 (0.288)    | 0.324 (0.188)    | 1 (1.000) |    21.58 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |     1633 | 2024-05-29 | G2               | L   | 0.760      | -            | -                | -                | -         |    -2.32 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     1658 | 2024-05-28 | Falcons          | W   | 0.753      | 0.624        | 0.225 (0.106)    | 0.247 (0.116)    | 1 (0.753) |     8.48 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     1676 | 2024-05-27 | 9z               | L   | 0.747      | -            | -                | -                | -         |   -14.65 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1687 | 2024-05-27 | Complexity       | W   | 0.746      | 0.624        | 0.311 (0.145)    | 0.380 (0.177)    | 1 (0.746) |    15.74 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1761 | 2024-05-23 | Eternal Fire     | L   | 0.717      | -            | -                | -                | -         |    -6.80 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1805 | 2024-05-22 | Astralis         | W   | 0.710      | 0.769        | 0.353 (0.192)    | 0.382 (0.209)    | -         |    16.64 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1850 | 2024-05-21 | ENCE             | W   | 0.703      | 0.769        | 0.170 (0.092)    | 0.401 (0.217)    | -         |     7.32 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     1906 | 2024-05-19 | AMKAL            | W   | 0.691      | 0.769        | 0.130 (0.069)    | 0.477 (0.253)    | -         |     3.18 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     1921 | 2024-05-18 | OG               | W   | 0.686      | 0.769        | 0.140 (0.074)    | -                | -         |     1.59 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2211 | 2024-05-10 | Astralis         | L   | 0.631      | -            | -                | -                | -         |    -4.83 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2255 | 2024-05-08 | FlyQuest         | W   | 0.618      | 0.889        | -                | 0.291 (0.160)    | 1 (0.618) |     3.11 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2323 | 2024-05-04 | MOUZ             | L   | 0.592      | -            | -                | -                | -         |    -2.35 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     2385 | 2024-05-01 | Monte            | W   | 0.572      | -            | -                | -                | 1 (0.572) |     1.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2408 | 2024-04-30 | FURIA            | W   | 0.565      | 0.889        | 0.284 (0.143)    | 0.491 (0.247)    | 1 (0.565) |    12.53 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2651 | 2024-04-19 | M80              | L   | 0.494      | -            | -                | -                | -         |   -12.85 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2701 | 2024-04-18 | M80              | W   | 0.487      | -            | -                | -                | -         |     2.60 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2704 | 2024-04-18 | Legacy           | W   | 0.486      | -            | -                | -                | -         |     0.97 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     2751 | 2024-04-17 | Akimbo           | W   | 0.480      | -            | -                | -                | -         |     0.24 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     2756 | 2024-04-17 | straykids        | W   | 0.480      | -            | -                | -                | -         |     0.13 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     2869 | 2024-04-12 | FaZe             | L   | 0.443      | -            | -                | -                | -         |    -3.58 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     2954 | 2024-04-10 | MOUZ             | L   | 0.429      | -            | -                | -                | -         |    -1.73 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     3032 | 2024-04-08 | G2               | W   | 0.416      | 0.624        | 1.000 (0.260)    | 0.498 (0.129)    | 1 (0.416) |    12.30 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     3042 | 2024-04-07 | HEROIC           | W   | 0.415      | -            | -                | -                | 1 (0.415) |     7.75 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3713 | 2024-03-07 | SAW              | L   | 0.204      | -            | -                | -                | -         |    -5.54 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3795 | 2024-03-04 | Complexity       | L   | 0.186      | -            | -                | -                | -         |    -1.79 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3831 | 2024-03-03 | BOSS             | W   | 0.178      | -            | -                | -                | 1 (0.178) |     0.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3844 | 2024-03-02 | FURIA            | L   | 0.172      | -            | -                | -                | -         |    -1.22 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3859 | 2024-03-01 | BESTIA           | W   | 0.166      | -            | -                | -                | -         |     0.35 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     3930 | 2024-02-26 | Nouns            | W   | 0.141      | -            | -                | -                | -         |     0.16 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     3932 | 2024-02-26 | BOSS             | W   | 0.140      | -            | -                | -                | -         |     0.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     3945 | 2024-02-25 | Wildcard         | W   | 0.134      | -            | -                | -                | -         |     0.15 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     3950 | 2024-02-25 | Nouns            | L   | 0.133      | -            | -                | -                | -         |    -4.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     4009 | 2024-02-22 | Party Astronauts | W   | 0.114      | -            | -                | -                | -         |     0.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     4011 | 2024-02-22 | MIGHT            | W   | 0.114      | -            | -                | -                | -         |     0.02 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     4017 | 2024-02-22 | ex-CatEvil       | W   | 0.113      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($102,763.63)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.785 | $6,000.00      | $4,711.67       |
| 2024-05-23 |      0.717 | $100,000.00    | $71,736.11      |
| 2024-05-12 |      0.644 | $32,000.00     | $20,622.22      |
| 2024-04-14 |      0.457 | $10,000.00     | $4,565.51       |
| 2024-03-10 |      0.226 | $5,000.00      | $1,128.13       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
