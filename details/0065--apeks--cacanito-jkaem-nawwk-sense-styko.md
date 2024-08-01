### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [65](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [45]( ../standings_europe.md)<br />
<br />
Final Rank Value:  972.8<br />
<br />
Final Rank Value (972.8) = Starting Rank Value (915.8) + Head To Head Adjustments (57.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.395[<sup>1</sup>](#table2)
- Bounty Collected: 0.362[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.199[<sup>2</sup>](#table1)

The average of these factors is 0.251<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 915.8
- 400 + ( ( 0.251 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 915.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |     2452 | 2024-04-27 | MIBR              | L   | 0.563      | -            | -                | -                | -         |    -1.26 | CacaNito, jkaem, nawwk, sense, STYKO |
|           37 |     2502 | 2024-04-25 | Aurora            | W   | 0.550      | 0.500        | 0.431 (0.119)    | 0.798 (0.220)    | 1 (0.550) |    16.93 | CacaNito, jkaem, nawwk, sense, STYKO |
|           36 |     2508 | 2024-04-25 | sunday school     | W   | 0.549      | -            | -                | -                | 1 (0.549) |     2.50 | CacaNito, jkaem, nawwk, sense, STYKO |
|           35 |     2699 | 2024-04-18 | ex-Sprout         | W   | 0.501      | -            | -                | -                | 0 (0.000) |     0.67 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2703 | 2024-04-18 | BetBoom           | L   | 0.500      | -            | -                | -                | -         |    -1.10 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2706 | 2024-04-18 | DMS               | W   | 0.500      | 0.143        | -                | 0.447 (0.032)    | 0 (0.000) |     7.07 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2719 | 2024-04-18 | AMKAL             | W   | 0.500      | 0.143        | 0.132 (0.009)    | 0.482 (0.034)    | 0 (0.000) |    11.95 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2888 | 2024-04-11 | Aurora            | L   | 0.453      | -            | -                | -                | -         |    -0.27 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2927 | 2024-04-10 | AMKAL             | L   | 0.447      | -            | -                | -                | -         |    -3.68 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2977 | 2024-04-09 | fnatic            | W   | 0.440      | 0.143        | 0.292 (0.018)    | 0.529 (0.033)    | 0 (0.000) |    12.73 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     2989 | 2024-04-09 | KOI               | W   | 0.439      | 0.143        | 0.040 (0.003)    | 0.313 (0.020)    | -         |     7.29 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     3011 | 2024-04-08 | fnatic            | L   | 0.434      | -            | -                | -                | -         |    -1.06 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     3023 | 2024-04-08 | GUN5              | W   | 0.432      | -            | -                | -                | -         |     0.70 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     3171 | 2024-04-03 | Monte             | L   | 0.399      | -            | -                | -                | -         |    -4.87 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     3203 | 2024-04-02 | Aurora            | L   | 0.393      | -            | -                | -                | -         |    -0.19 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3211 | 2024-04-02 | B8                | W   | 0.392      | 0.143        | 0.168 (0.009)    | 0.878 (0.049)    | -         |     9.06 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3236 | 2024-03-31 | B8                | L   | 0.379      | -            | -                | -                | -         |    -3.21 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3268 | 2024-03-28 | 3DMAX             | L   | 0.359      | -            | -                | -                | -         |    -0.18 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3338 | 2024-03-26 | FORZE             | L   | 0.346      | -            | -                | -                | -         |    -5.30 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3438 | 2024-03-19 | Legacy            | L   | 0.299      | -            | -                | -                | -         |    -3.42 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3451 | 2024-03-18 | Imperial          | L   | 0.292      | -            | -                | -                | -         |    -1.12 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3464 | 2024-03-17 | AMKAL             | W   | 0.287      | 0.143        | 0.132 (0.005)    | 0.482 (0.020)    | 1 (0.287) |     6.92 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3480 | 2024-03-17 | paiN              | L   | 0.286      | -            | -                | -                | -         |    -0.72 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3616 | 2024-03-12 | Metizport         | L   | 0.253      | -            | -                | -                | -         |    -4.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3625 | 2024-03-11 | Virtus.pro        | L   | 0.247      | -            | -                | -                | -         |    -0.09 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3635 | 2024-03-11 | KOI               | W   | 0.246      | 0.143        | 0.040 (0.001)    | 0.313 (0.011)    | -         |     4.12 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3729 | 2024-03-07 | Space             | W   | 0.220      | 0.500        | -                | 0.406 (0.045)    | -         |     2.50 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3757 | 2024-03-06 | PARIVISION        | L   | 0.213      | -            | -                | -                | -         |    -1.87 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     4083 | 2024-02-21 | Gaimin Gladiators | W   | 0.118      | -            | -                | -                | 1 (0.118) |     2.19 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     4113 | 2024-02-20 | Monte             | W   | 0.112      | 0.143        | 0.062 (0.001)    | -                | 1 (0.112) |     2.22 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     4126 | 2024-02-19 | Cloud9            | L   | 0.107      | -            | -                | -                | -         |    -1.07 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     4136 | 2024-02-19 | OG                | W   | 0.105      | 0.143        | 0.143 (0.002)    | -                | 1 (0.105) |     2.04 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4329 | 2024-02-11 | Metizport         | L   | 0.054      | -            | -                | -                | -         |    -0.88 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4332 | 2024-02-11 | 3DMAX             | W   | 0.053      | 0.143        | 0.505 (0.004)    | 1.000 (0.008)    | -         |     1.65 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4345 | 2024-02-10 | Metizport         | W   | 0.046      | -            | -                | -                | -         |     0.70 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4348 | 2024-02-10 | ex-Anonymo        | W   | 0.046      | -            | -                | -                | -         |     0.13 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4417 | 2024-02-04 | Natus Vincere     | L   | 0.007      | -            | -                | -                | -         |    -0.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4438 | 2024-02-03 | Complexity        | L   | 0.000      | -            | -                | -                | -         |     0.00 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,666.68)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $500.00        | $423.16         |
| 2024-04-28 |      0.564 | $10,000.00     | $5,644.91       |
| 2024-03-20 |      0.307 | $10,000.00     | $3,068.06       |
| 2024-02-11 |      0.053 | $10,000.00     | $530.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
