### Roster Details<br />
Team Name: Liquid<br />
Roster: jks, NAF, Twistzz, ultimate, YEKINDAR<br />
Global Rank: [9](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [1]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1672.0<br />
<br />
Final Rank Value (1672.0) = Starting Rank Value (1595.2) + Head To Head Adjustments (76.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.706[<sup>1</sup>](#table2)
- Bounty Collected: 0.622[<sup>2</sup>](#table1)
- Opponent Network: 0.193[<sup>2</sup>](#table1)
- LAN Wins: 0.804[<sup>2</sup>](#table1)

The average of these factors is 0.581<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1595.2
- 400 + ( ( 0.581 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1595.2


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
|           38 |       72 | 2024-08-03 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.357 (0.207)    | 1 (1.000) |    25.60 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           37 |      151 | 2024-08-01 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.357 (0.207)    | 1 (1.000) |    26.86 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           36 |      195 | 2024-07-31 | Virtus.pro       | W   | 1.000      | 0.581        | 0.498 (0.290)    | 0.309 (0.179)    | 1 (1.000) |    19.01 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |     1708 | 2024-05-29 | G2               | L   | 0.743      | -            | -                | -                | -         |    -3.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     1733 | 2024-05-28 | Falcons          | W   | 0.736      | 0.624        | 0.220 (0.101)    | -                | 1 (0.736) |     6.24 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     1751 | 2024-05-27 | 9z               | L   | 0.730      | -            | -                | -                | -         |   -16.37 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1762 | 2024-05-27 | Complexity       | W   | 0.728      | 0.624        | 0.341 (0.155)    | 0.364 (0.166)    | 1 (0.728) |    13.38 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1836 | 2024-05-23 | Eternal Fire     | L   | 0.700      | -            | -                | -                | -         |    -8.74 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1880 | 2024-05-22 | Astralis         | W   | 0.693      | 0.769        | 0.389 (0.207)    | 0.403 (0.215)    | -         |    15.22 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1925 | 2024-05-21 | ENCE             | W   | 0.686      | 0.769        | 0.173 (0.091)    | 0.422 (0.222)    | -         |     5.51 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     1981 | 2024-05-19 | AMKAL            | W   | 0.674      | 0.769        | -                | 0.453 (0.234)    | -         |     2.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     1996 | 2024-05-18 | OG               | W   | 0.669      | 0.769        | 0.137 (0.070)    | -                | -         |     0.99 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2286 | 2024-05-10 | Astralis         | L   | 0.614      | -            | -                | -                | -         |    -5.66 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2330 | 2024-05-08 | FlyQuest         | W   | 0.601      | 0.889        | -                | 0.278 (0.148)    | 1 (0.601) |     1.96 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2398 | 2024-05-04 | MOUZ             | L   | 0.575      | -            | -                | -                | -         |    -3.41 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     2460 | 2024-05-01 | Monte            | W   | 0.555      | -            | -                | -                | 1 (0.555) |     0.60 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2483 | 2024-04-30 | FURIA            | W   | 0.548      | 0.889        | 0.284 (0.138)    | 0.469 (0.228)    | 1 (0.548) |    10.36 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2727 | 2024-04-19 | M80              | L   | 0.477      | -            | -                | -                | -         |   -13.33 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2777 | 2024-04-18 | M80              | W   | 0.470      | -            | -                | -                | -         |     1.61 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2780 | 2024-04-18 | Legacy           | W   | 0.469      | -            | -                | -                | -         |     0.57 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     2827 | 2024-04-17 | Akimbo           | W   | 0.463      | -            | -                | -                | -         |     0.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     2832 | 2024-04-17 | straykids        | W   | 0.463      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     2945 | 2024-04-12 | FaZe             | L   | 0.426      | -            | -                | -                | -         |    -5.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     3030 | 2024-04-10 | MOUZ             | L   | 0.412      | -            | -                | -                | -         |    -2.57 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     3108 | 2024-04-08 | G2               | W   | 0.399      | 0.624        | 1.000 (0.249)    | 0.478 (0.119)    | 1 (0.399) |    11.33 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     3118 | 2024-04-07 | HEROIC           | W   | 0.398      | -            | -                | -                | 1 (0.398) |     5.75 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3790 | 2024-03-07 | SAW              | L   | 0.187      | -            | -                | -                | -         |    -5.40 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3872 | 2024-03-04 | Complexity       | L   | 0.169      | -            | -                | -                | -         |    -2.23 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3908 | 2024-03-03 | BOSS             | W   | 0.161      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3921 | 2024-03-02 | FURIA            | L   | 0.155      | -            | -                | -                | -         |    -1.61 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3936 | 2024-03-01 | BESTIA           | W   | 0.149      | -            | -                | -                | -         |     0.18 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     4007 | 2024-02-26 | Nouns            | W   | 0.124      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     4009 | 2024-02-26 | BOSS             | W   | 0.123      | -            | -                | -                | -         |     0.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     4022 | 2024-02-25 | Wildcard         | W   | 0.117      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     4027 | 2024-02-25 | Nouns            | L   | 0.116      | -            | -                | -                | -         |    -3.58 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     4086 | 2024-02-22 | Party Astronauts | W   | 0.097      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     4088 | 2024-02-22 | MIGHT            | W   | 0.097      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     4094 | 2024-02-22 | ex-CatEvil       | W   | 0.096      | -            | -                | -                | -         |     0.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($122,656.97)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.38) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-06-02 |      0.768 | $6,000.00      | $4,609.44       |
| 2024-05-23 |      0.700 | $100,000.00    | $70,032.41      |
| 2024-05-12 |      0.627 | $32,000.00     | $20,077.04      |
| 2024-04-14 |      0.440 | $10,000.00     | $4,395.14       |
| 2024-03-10 |      0.209 | $5,000.00      | $1,042.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
