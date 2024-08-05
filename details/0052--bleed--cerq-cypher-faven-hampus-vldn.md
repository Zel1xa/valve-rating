### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1056.2<br />
<br />
Final Rank Value (1056.2) = Starting Rank Value (957.8) + Head To Head Adjustments (98.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.490[<sup>1</sup>](#table2)
- Bounty Collected: 0.392[<sup>2</sup>](#table1)
- Opponent Network: 0.209[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 957.8
- 400 + ( ( 0.273 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 957.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           43 |     2241 | 2024-05-11 | B8                | L   | 0.629      | -            | -                | -                | -         |    -9.88 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           42 |     2269 | 2024-05-09 | Sampi             | W   | 0.618      | 0.435        | -                | 1.000 (0.269)    | 0 (0.000) |     6.17 | CYPHER, draken, faveN, hampus, VLDN |
|           41 |     2311 | 2024-05-07 | 1WIN              | L   | 0.604      | -            | -                | -                | -         |   -12.56 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2335 | 2024-05-06 | Insilio           | W   | 0.596      | -            | -                | -                | 0 (0.000) |     6.27 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2399 | 2024-05-02 | AMKAL             | L   | 0.571      | -            | -                | -                | -         |    -7.15 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2435 | 2024-05-01 | MOUZ NXT          | L   | 0.563      | -            | -                | -                | -         |    -9.58 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2467 | 2024-04-30 | Permitta          | W   | 0.556      | 0.384        | -                | 0.876 (0.187)    | 0 (0.000) |     5.67 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2490 | 2024-04-28 | B8                | W   | 0.545      | 0.500        | 0.165 (0.045)    | 0.951 (0.259)    | 0 (0.000) |     7.80 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2540 | 2024-04-26 | ex-Guild Eagles   | W   | 0.531      | -            | -                | -                | 0 (0.000) |     3.94 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2548 | 2024-04-26 | DMS               | W   | 0.530      | -            | -                | -                | 0 (0.000) |     4.84 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2590 | 2024-04-24 | Permitta          | W   | 0.518      | 0.435        | -                | 0.876 (0.197)    | 0 (0.000) |     6.25 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2591 | 2024-04-24 | Nemiga            | L   | 0.517      | -            | -                | -                | -         |    -5.54 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2610 | 2024-04-23 | B8                | W   | 0.511      | 0.500        | 0.165 (0.042)    | 0.951 (0.243)    | 0 (0.000) |     7.77 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2619 | 2024-04-23 | Sashi             | L   | 0.509      | -            | -                | -                | -         |    -5.82 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2627 | 2024-04-22 | Sangal            | W   | 0.504      | 0.500        | 0.219 (0.055)    | 0.861 (0.217)    | 0 (0.000) |     9.59 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2629 | 2024-04-22 | Gaimin Gladiators | W   | 0.503      | -            | -                | -                | 0 (0.000) |     7.75 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2644 | 2024-04-21 | Illuminar         | W   | 0.498      | -            | -                | -                | -         |     0.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2650 | 2024-04-21 | BIG               | W   | 0.496      | 0.384        | 0.155 (0.030)    | -                | -         |    12.71 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2673 | 2024-04-20 | MOUZ NXT          | W   | 0.491      | 0.500        | 0.139 (0.034)    | 1.000 (0.245)    | -         |     8.38 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2730 | 2024-04-19 | Sampi             | W   | 0.483      | 0.384        | -                | 1.000 (0.185)    | -         |     5.57 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2787 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.476      | 0.500        | 0.031 (0.007)    | -                | -         |     6.73 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2822 | 2024-04-17 | 3DMAX             | L   | 0.469      | -            | -                | -                | -         |    -0.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2841 | 2024-04-16 | KOI               | W   | 0.464      | 0.384        | 0.058 (0.010)    | -                | -         |     8.90 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2851 | 2024-04-16 | SINNERS           | W   | 0.462      | 0.384        | -                | 0.797 (0.142)    | -         |    10.70 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     3031 | 2024-04-09 | Alliance          | W   | 0.417      | -            | -                | -                | -         |     4.27 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3039 | 2024-04-09 | HAVU              | W   | 0.416      | -            | -                | -                | -         |     2.23 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3123 | 2024-04-05 | BetBoom           | L   | 0.391      | -            | -                | -                | -         |    -1.09 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3126 | 2024-04-05 | Alliance          | W   | 0.390      | -            | -                | -                | -         |     4.15 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3165 | 2024-04-04 | Benched Heroes    | W   | 0.384      | -            | -                | -                | -         |     0.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3172 | 2024-04-04 | BetBoom           | L   | 0.383      | -            | -                | -                | -         |    -1.06 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3242 | 2024-04-02 | Passion UA        | W   | 0.371      | 0.384        | 0.172 (0.025)    | 1.000 (0.142)    | -         |     6.88 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3264 | 2024-04-01 | Enterprise        | L   | 0.363      | -            | -                | -                | -         |    -6.85 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3619 | 2024-03-13 | Sashi             | W   | 0.236      | -            | -                | -                | -         |     5.25 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3717 | 2024-03-09 | Endpoint          | W   | 0.209      | -            | -                | -                | -         |     2.56 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3784 | 2024-03-06 | fnatic            | L   | 0.191      | -            | -                | -                | -         |    -0.23 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3830 | 2024-03-05 | BetBoom           | W   | 0.183      | 0.500        | 0.250 (0.023)    | -                | -         |     5.34 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3838 | 2024-03-04 | Rebels            | W   | 0.178      | -            | -                | -                | -         |     3.08 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3847 | 2024-03-04 | AURA              | W   | 0.176      | -            | -                | -                | -         |     0.38 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3911 | 2024-03-01 | Young Ninjas      | W   | 0.158      | -            | -                | -                | -         |     1.18 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3926 | 2024-02-29 | AURA              | W   | 0.149      | -            | -                | -                | -         |     0.33 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     3942 | 2024-02-28 | BIG               | W   | 0.142      | 0.500        | 0.155 (0.011)    | -                | -         |     3.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     3977 | 2024-02-26 | MOUZ NXT          | L   | 0.130      | -            | -                | -                | -         |    -1.56 | CeRq, faveN, hampus, lauNX, VLDN    |
|            1 |     4378 | 2024-02-08 | Passion UA        | W   | 0.009      | -            | -                | -                | -         |     0.20 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,379.58)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.678 | $500.00        | $338.89         |
| 2024-05-12 |      0.638 | $2,000.00      | $1,275.42       |
| 2024-04-24 |      0.517 | $25,000.00     | $12,930.56      |
| 2024-04-22 |      0.503 | $20,000.00     | $10,063.89      |
| 2024-03-06 |      0.191 | $25,000.00     | $4,770.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
