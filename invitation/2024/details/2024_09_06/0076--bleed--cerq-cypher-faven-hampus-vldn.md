### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [76](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [56]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  924.6<br />
<br />
Final Rank Value (924.6) = Starting Rank Value (847.1) + Head To Head Adjustments (77.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.428[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.129[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 847.1
- 400 + ( ( 0.229 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 847.1


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
|           33 |     3367 | 2024-05-11 | B8                | L   | 0.411      | -            | -                | -                | -         |    -4.44 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     3395 | 2024-05-09 | Sampi             | W   | 0.400      | 0.435        | 0.033 (0.006)    | 1.000 (0.174)    | 0 (0.000) |     6.22 | CYPHER, draken, faveN, hampus, VLDN |
|           31 |     3437 | 2024-05-07 | 1WIN              | L   | 0.386      | -            | -                | -                | -         |    -6.53 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     3461 | 2024-05-06 | Insilio           | W   | 0.378      | 0.396        | -                | 0.636 (0.095)    | 0 (0.000) |     5.77 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     3525 | 2024-05-02 | AMKAL             | L   | 0.353      | -            | -                | -                | -         |    -2.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     3561 | 2024-05-01 | MOUZ NXT          | L   | 0.345      | -            | -                | -                | -         |    -4.49 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     3593 | 2024-04-30 | Permitta          | W   | 0.337      | 0.384        | -                | 0.998 (0.130)    | 0 (0.000) |     5.53 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     3616 | 2024-04-28 | B8                | W   | 0.327      | 0.500        | 0.176 (0.029)    | 1.000 (0.163)    | 0 (0.000) |     6.73 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     3666 | 2024-04-26 | ex-Guild Eagles   | W   | 0.313      | -            | -                | -                | 0 (0.000) |     2.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     3674 | 2024-04-26 | DMS               | W   | 0.312      | -            | -                | -                | 0 (0.000) |     4.35 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     3716 | 2024-04-24 | Permitta          | W   | 0.300      | 0.435        | -                | 0.998 (0.130)    | 0 (0.000) |     5.39 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     3717 | 2024-04-24 | Nemiga            | L   | 0.299      | -            | -                | -                | -         |    -1.74 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     3736 | 2024-04-23 | B8                | W   | 0.292      | 0.500        | 0.176 (0.026)    | 1.000 (0.146)    | 0 (0.000) |     6.27 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     3745 | 2024-04-23 | Sashi             | L   | 0.291      | -            | -                | -                | -         |    -2.42 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     3753 | 2024-04-22 | Sangal            | W   | 0.286      | 0.500        | 0.248 (0.035)    | 0.869 (0.124)    | 0 (0.000) |     7.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3755 | 2024-04-22 | Gaimin Gladiators | W   | 0.285      | -            | -                | -                | 0 (0.000) |     4.99 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3770 | 2024-04-21 | Illuminar         | W   | 0.280      | -            | -                | -                | -         |     0.96 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3776 | 2024-04-21 | BIG               | W   | 0.278      | 0.384        | 0.147 (0.016)    | -                | -         |     7.53 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3799 | 2024-04-20 | MOUZ NXT          | W   | 0.272      | 0.500        | 0.111 (0.015)    | 0.845 (0.115)    | -         |     5.62 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3856 | 2024-04-19 | Sampi             | W   | 0.265      | 0.384        | -                | 1.000 (0.102)    | -         |     4.66 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3913 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.257      | 0.500        | 0.101 (0.013)    | 0.861 (0.111)    | -         |     5.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3948 | 2024-04-17 | 3DMAX             | L   | 0.251      | -            | -                | -                | -         |    -0.09 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3967 | 2024-04-16 | KOI               | W   | 0.246      | 0.384        | 0.053 (0.005)    | -                | -         |     4.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3977 | 2024-04-16 | SINNERS           | W   | 0.244      | 0.384        | 0.081 (0.008)    | -                | -         |     6.54 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     4157 | 2024-04-09 | Alliance          | W   | 0.199      | -            | -                | -                | -         |     2.99 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     4165 | 2024-04-09 | HAVU              | W   | 0.198      | -            | -                | -                | -         |     1.05 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     4249 | 2024-04-05 | BetBoom           | L   | 0.173      | -            | -                | -                | -         |    -0.55 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     4252 | 2024-04-05 | Alliance          | W   | 0.172      | -            | -                | -                | -         |     2.64 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     4291 | 2024-04-04 | Benched Heroes    | W   | 0.166      | -            | -                | -                | -         |     0.39 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     4298 | 2024-04-04 | BetBoom           | L   | 0.165      | -            | -                | -                | -         |    -0.53 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            3 |     4368 | 2024-04-02 | Passion UA        | W   | 0.153      | 0.384        | 0.147 (0.009)    | -                | -         |     3.44 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     4390 | 2024-04-01 | Enterprise        | L   | 0.145      | -            | -                | -                | -         |    -2.08 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            1 |     4745 | 2024-03-13 | Sashi             | W   | 0.018      | -            | -                | -                | -         |     0.44 | CeRq, CYPHER, faveN, hampus, VLDN   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($14,250.01)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.460 | $500.00        | $229.85         |
| 2024-05-12 |      0.420 | $2,000.00      | $839.26         |
| 2024-04-24 |      0.299 | $25,000.00     | $7,478.59       |
| 2024-04-22 |      0.285 | $20,000.00     | $5,702.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
