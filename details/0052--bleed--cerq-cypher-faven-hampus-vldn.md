### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1055.6<br />
<br />
Final Rank Value (1055.6) = Starting Rank Value (957.4) + Head To Head Adjustments (98.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.490[<sup>1</sup>](#table2)
- Bounty Collected: 0.393[<sup>2</sup>](#table1)
- Opponent Network: 0.207[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 957.4
- 400 + ( ( 0.273 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 957.4


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
|           43 |     2213 | 2024-05-11 | B8                | L   | 0.632      | -            | -                | -                | -         |    -9.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           42 |     2241 | 2024-05-09 | Sampi             | W   | 0.622      | 0.435        | -                | 1.000 (0.270)    | 0 (0.000) |     6.22 | CYPHER, draken, faveN, hampus, VLDN |
|           41 |     2283 | 2024-05-07 | 1WIN              | L   | 0.608      | -            | -                | -                | -         |   -12.74 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2307 | 2024-05-06 | Insilio           | W   | 0.599      | -            | -                | -                | 0 (0.000) |     6.33 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2371 | 2024-05-02 | AMKAL             | L   | 0.575      | -            | -                | -                | -         |    -7.18 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2407 | 2024-05-01 | MOUZ NXT          | L   | 0.567      | -            | -                | -                | -         |    -9.65 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2439 | 2024-04-30 | Permitta          | W   | 0.559      | 0.384        | -                | 0.876 (0.188)    | 0 (0.000) |     5.70 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2462 | 2024-04-28 | B8                | W   | 0.548      | 0.500        | 0.165 (0.045)    | 0.912 (0.250)    | 0 (0.000) |     7.86 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2512 | 2024-04-26 | ex-Guild Eagles   | W   | 0.535      | -            | -                | -                | 0 (0.000) |     4.03 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2520 | 2024-04-26 | DMS               | W   | 0.533      | -            | -                | -                | 0 (0.000) |     4.87 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2562 | 2024-04-24 | Permitta          | W   | 0.521      | 0.435        | -                | 0.876 (0.198)    | 0 (0.000) |     6.30 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2563 | 2024-04-24 | Nemiga            | L   | 0.521      | -            | -                | -                | -         |    -5.94 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2582 | 2024-04-23 | B8                | W   | 0.514      | 0.500        | 0.165 (0.042)    | 0.912 (0.234)    | 0 (0.000) |     7.83 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2591 | 2024-04-23 | Sashi             | L   | 0.513      | -            | -                | -                | -         |    -5.87 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2599 | 2024-04-22 | Sangal            | W   | 0.507      | 0.500        | 0.219 (0.056)    | 0.861 (0.219)    | 0 (0.000) |     9.58 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2601 | 2024-04-22 | Gaimin Gladiators | W   | 0.507      | -            | -                | -                | 0 (0.000) |     7.80 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2616 | 2024-04-21 | Illuminar         | W   | 0.501      | -            | -                | -                | -         |     0.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2622 | 2024-04-21 | BIG               | W   | 0.500      | 0.384        | 0.155 (0.030)    | -                | -         |    12.81 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2645 | 2024-04-20 | MOUZ NXT          | W   | 0.494      | 0.500        | 0.139 (0.034)    | 1.000 (0.247)    | -         |     8.44 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2702 | 2024-04-19 | Sampi             | W   | 0.486      | 0.384        | -                | 1.000 (0.187)    | -         |     5.62 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2759 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.479      | 0.500        | 0.031 (0.008)    | -                | -         |     6.78 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2794 | 2024-04-17 | 3DMAX             | L   | 0.473      | -            | -                | -                | -         |    -0.47 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2813 | 2024-04-16 | KOI               | W   | 0.468      | 0.384        | 0.058 (0.011)    | -                | -         |     8.98 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2823 | 2024-04-16 | SINNERS           | W   | 0.466      | 0.384        | -                | 0.757 (0.136)    | -         |     9.94 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     3003 | 2024-04-09 | Alliance          | W   | 0.421      | -            | -                | -                | -         |     4.29 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3011 | 2024-04-09 | HAVU              | W   | 0.420      | -            | -                | -                | -         |     2.25 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3095 | 2024-04-05 | BetBoom           | L   | 0.395      | -            | -                | -                | -         |    -1.09 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3098 | 2024-04-05 | Alliance          | W   | 0.394      | -            | -                | -                | -         |     4.18 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3137 | 2024-04-04 | Benched Heroes    | W   | 0.387      | -            | -                | -                | -         |     0.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3144 | 2024-04-04 | BetBoom           | L   | 0.387      | -            | -                | -                | -         |    -1.06 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3214 | 2024-04-02 | Passion UA        | W   | 0.374      | 0.384        | 0.172 (0.025)    | 1.000 (0.144)    | -         |     6.90 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3236 | 2024-04-01 | Enterprise        | L   | 0.367      | -            | -                | -                | -         |    -6.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3591 | 2024-03-13 | Sashi             | W   | 0.239      | -            | -                | -                | -         |     5.32 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3689 | 2024-03-09 | Endpoint          | W   | 0.213      | -            | -                | -                | -         |     2.61 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3756 | 2024-03-06 | fnatic            | L   | 0.194      | -            | -                | -                | -         |    -0.23 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3802 | 2024-03-05 | BetBoom           | W   | 0.187      | 0.500        | 0.251 (0.023)    | -                | -         |     5.44 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3810 | 2024-03-04 | Rebels            | W   | 0.182      | -            | -                | -                | -         |     3.15 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3819 | 2024-03-04 | AURA              | W   | 0.179      | -            | -                | -                | -         |     0.39 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3883 | 2024-03-01 | Young Ninjas      | W   | 0.161      | -            | -                | -                | -         |     1.21 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3898 | 2024-02-29 | AURA              | W   | 0.153      | -            | -                | -                | -         |     0.34 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     3914 | 2024-02-28 | BIG               | W   | 0.146      | 0.500        | 0.155 (0.011)    | -                | -         |     4.05 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     3949 | 2024-02-26 | MOUZ NXT          | L   | 0.133      | -            | -                | -                | -         |    -1.60 | CeRq, faveN, hampus, lauNX, VLDN    |
|            1 |     4350 | 2024-02-08 | Passion UA        | W   | 0.013      | -            | -                | -                | -         |     0.28 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,629.64)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.681 | $500.00        | $340.61         |
| 2024-05-12 |      0.641 | $2,000.00      | $1,282.31       |
| 2024-04-24 |      0.521 | $25,000.00     | $13,016.78      |
| 2024-04-22 |      0.507 | $20,000.00     | $10,132.87      |
| 2024-03-06 |      0.194 | $25,000.00     | $4,857.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
