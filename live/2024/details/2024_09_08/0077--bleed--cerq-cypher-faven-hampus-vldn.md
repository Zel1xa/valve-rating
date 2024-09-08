### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [77](../../standings_global_2024_09_08.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_08.md)<br />
Regional Rank: [56]( ../../standings_europe_2024_09_08.md)<br />
<br />
Final Rank Value:  913.5<br />
<br />
Final Rank Value (913.5) = Starting Rank Value (838.0) + Head To Head Adjustments (75.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.426[<sup>1</sup>](#table2)
- Bounty Collected: 0.356[<sup>2</sup>](#table1)
- Opponent Network: 0.123[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.226<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 838.0
- 400 + ( ( 0.226 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 838.0


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
|           33 |     3404 | 2024-05-11 | B8                | L   | 0.399      | -            | -                | -                | -         |    -4.08 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     3432 | 2024-05-09 | Sampi             | W   | 0.388      | 0.435        | 0.032 (0.005)    | 1.000 (0.169)    | 0 (0.000) |     6.08 | CYPHER, draken, faveN, hampus, VLDN |
|           31 |     3474 | 2024-05-07 | 1WIN              | L   | 0.374      | -            | -                | -                | -         |    -6.30 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     3498 | 2024-05-06 | Insilio           | W   | 0.366      | 0.396        | -                | 0.654 (0.095)    | 0 (0.000) |     5.82 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     3562 | 2024-05-02 | AMKAL             | L   | 0.341      | -            | -                | -                | -         |    -2.84 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     3598 | 2024-05-01 | MOUZ NXT          | L   | 0.333      | -            | -                | -                | -         |    -4.28 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     3630 | 2024-04-30 | Permitta          | W   | 0.326      | 0.384        | -                | 0.968 (0.121)    | 0 (0.000) |     5.43 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     3653 | 2024-04-28 | B8                | W   | 0.315      | 0.500        | 0.176 (0.028)    | 1.000 (0.157)    | 0 (0.000) |     6.69 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     3703 | 2024-04-26 | ex-Guild Eagles   | W   | 0.301      | -            | -                | -                | 0 (0.000) |     2.91 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     3711 | 2024-04-26 | DMS               | W   | 0.300      | -            | -                | -                | 0 (0.000) |     4.23 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     3753 | 2024-04-24 | Permitta          | W   | 0.288      | 0.435        | -                | 0.968 (0.121)    | 0 (0.000) |     5.24 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     3754 | 2024-04-24 | Nemiga            | L   | 0.287      | -            | -                | -                | -         |    -1.63 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     3773 | 2024-04-23 | B8                | W   | 0.281      | 0.500        | 0.176 (0.025)    | 1.000 (0.140)    | 0 (0.000) |     6.19 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     3782 | 2024-04-23 | Sashi             | L   | 0.279      | -            | -                | -                | -         |    -2.32 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     3790 | 2024-04-22 | Sangal            | W   | 0.274      | 0.500        | 0.248 (0.034)    | 0.878 (0.120)    | 0 (0.000) |     7.85 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3792 | 2024-04-22 | Gaimin Gladiators | W   | 0.273      | -            | -                | -                | 0 (0.000) |     4.78 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3807 | 2024-04-21 | Illuminar         | W   | 0.268      | -            | -                | -                | -         |     0.96 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3813 | 2024-04-21 | BIG               | W   | 0.266      | 0.384        | 0.146 (0.015)    | -                | -         |     7.19 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3836 | 2024-04-20 | MOUZ NXT          | W   | 0.261      | 0.500        | 0.111 (0.014)    | 0.813 (0.106)    | -         |     5.40 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3893 | 2024-04-19 | Sampi             | W   | 0.253      | 0.384        | -                | 1.000 (0.097)    | -         |     4.47 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3950 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.246      | 0.500        | 0.102 (0.012)    | 0.837 (0.103)    | -         |     5.70 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3985 | 2024-04-17 | 3DMAX             | L   | 0.239      | -            | -                | -                | -         |    -0.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     4004 | 2024-04-16 | KOI               | W   | 0.234      | 0.384        | 0.053 (0.005)    | -                | -         |     4.71 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     4014 | 2024-04-16 | SINNERS           | W   | 0.232      | 0.384        | 0.081 (0.007)    | -                | -         |     6.23 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     4194 | 2024-04-09 | Alliance          | W   | 0.188      | -            | -                | -                | -         |     2.83 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     4202 | 2024-04-09 | HAVU              | W   | 0.186      | -            | -                | -                | -         |     1.01 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     4286 | 2024-04-05 | BetBoom           | L   | 0.161      | -            | -                | -                | -         |    -0.54 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     4289 | 2024-04-05 | Alliance          | W   | 0.160      | -            | -                | -                | -         |     2.48 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     4328 | 2024-04-04 | Benched Heroes    | W   | 0.154      | -            | -                | -                | -         |     0.38 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     4335 | 2024-04-04 | BetBoom           | L   | 0.153      | -            | -                | -                | -         |    -0.51 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            3 |     4405 | 2024-04-02 | Passion UA        | W   | 0.141      | 0.384        | 0.164 (0.009)    | -                | -         |     3.24 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     4427 | 2024-04-01 | Enterprise        | L   | 0.133      | -            | -                | -                | -         |    -1.90 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            1 |     4782 | 2024-03-13 | Sashi             | W   | 0.006      | -            | -                | -                | -         |     0.14 | CeRq, CYPHER, faveN, hampus, VLDN   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,683.75)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.448 | $500.00        | $223.89         |
| 2024-05-12 |      0.408 | $2,000.00      | $815.42         |
| 2024-04-24 |      0.287 | $25,000.00     | $7,180.56       |
| 2024-04-22 |      0.273 | $20,000.00     | $5,463.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
