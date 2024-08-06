### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: deb0, gxx-, juanflatroo, SENER1, sinnopsyy<br />
Global Rank: [104](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  857.4<br />
<br />
Final Rank Value (857.4) = Starting Rank Value (812.0) + Head To Head Adjustments (45.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.031[<sup>2</sup>](#table1)

The average of these factors is 0.200<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 812.0
- 400 + ( ( 0.200 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 812.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |     1208 | 2024-06-11 | SINNERS           | L   | 0.826      | -            | -                | -                | -         |    -7.52 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           36 |     1804 | 2024-05-25 | Zero Tenacity     | L   | 0.714      | -            | -                | -                | -         |    -4.65 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     1813 | 2024-05-25 | The Suspect       | W   | 0.713      | 0.143        | 0.008 (0.001)    | 0.223 (0.023)    | 0 (0.000) |     9.76 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     1822 | 2024-05-24 | Zero Tenacity     | W   | 0.708      | 0.273        | 0.143 (0.028)    | 1.000 (0.193)    | 0 (0.000) |    18.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     1827 | 2024-05-24 | Serbia            | W   | 0.706      | 0.273        | 0.012 (0.002)    | 0.219 (0.042)    | 0 (0.000) |     9.25 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     2057 | 2024-05-17 | Sashi             | L   | 0.659      | -            | -                | -                | -         |    -2.34 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     2400 | 2024-05-05 | 1WIN              | L   | 0.579      | -            | -                | -                | -         |    -6.37 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     2514 | 2024-04-29 | EYEBALLERS        | L   | 0.540      | -            | -                | -                | -         |    -7.36 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     2555 | 2024-04-27 | Insilio           | L   | 0.527      | -            | -                | -                | -         |    -6.45 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     2581 | 2024-04-26 | BLEED             | L   | 0.521      | -            | -                | -                | -         |    -3.93 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     2616 | 2024-04-25 | PARIVISION        | L   | 0.513      | -            | -                | -                | -         |    -3.85 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     2640 | 2024-04-24 | Zero Tenacity     | W   | 0.506      | 0.435        | 0.143 (0.031)    | 1.000 (0.220)    | 0 (0.000) |    12.27 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2667 | 2024-04-22 | 3DMAX             | L   | 0.494      | -            | -                | -                | -         |    -0.20 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2679 | 2024-04-22 | Sangal            | W   | 0.491      | 0.435        | 0.219 (0.047)    | 0.846 (0.181)    | 0 (0.000) |    13.11 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2792 | 2024-04-18 | Sashi             | L   | 0.468      | -            | -                | -                | -         |    -2.43 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     2797 | 2024-04-18 | KOI               | W   | 0.467      | 0.143        | 0.058 (0.004)    | 0.356 (0.024)    | 0 (0.000) |    11.79 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     2809 | 2024-04-18 | FRAGMATIC         | W   | 0.467      | -            | -                | -                | 0 (0.000) |     1.23 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     2816 | 2024-04-18 | AMKAL             | L   | 0.466      | -            | -                | -                | -         |    -2.17 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     2886 | 2024-04-16 | Sashi             | W   | 0.453      | 0.384        | 0.184 (0.032)    | 0.958 (0.167)    | -         |    12.18 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3079 | 2024-04-09 | Metizport         | W   | 0.406      | 0.384        | 0.036 (0.006)    | 0.510 (0.080)    | -         |     8.74 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3246 | 2024-04-03 | AMKAL             | L   | 0.366      | -            | -                | -                | -         |    -1.66 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3276 | 2024-04-02 | Insilio           | L   | 0.361      | -            | -                | -                | -         |    -4.16 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3285 | 2024-04-02 | AMKAL             | W   | 0.360      | 0.143        | 0.130 (0.007)    | 0.452 (0.023)    | -         |     9.73 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3295 | 2024-04-02 | 500               | L   | 0.359      | -            | -                | -                | -         |    -7.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3300 | 2024-04-01 | 500               | W   | 0.354      | 0.384        | -                | 0.090 (0.012)    | -         |     4.25 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3381 | 2024-03-27 | ALTERNATE aTTaX   | L   | 0.321      | -            | -                | -                | -         |    -2.82 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3451 | 2024-03-22 | VP.Prodigy        | L   | 0.286      | -            | -                | -                | -         |    -3.79 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3992 | 2024-02-27 | Croatia           | L   | 0.128      | -            | -                | -                | -         |    -3.46 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     3999 | 2024-02-27 | Metizport         | W   | 0.127      | -            | -                | -                | -         |     2.50 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     4078 | 2024-02-24 | GamerLegion       | L   | 0.106      | -            | -                | -                | -         |    -1.86 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     4087 | 2024-02-23 | BetBoom           | W   | 0.100      | 0.143        | 0.248 (0.004)    | -                | 1 (0.100) |     3.03 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     4105 | 2024-02-22 | Gaimin Gladiators | L   | 0.093      | -            | -                | -                | -         |    -0.90 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4128 | 2024-02-21 | ex-Preasy         | W   | 0.087      | -            | -                | -                | 1 (0.087) |     1.22 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4158 | 2024-02-20 | Nexus             | W   | 0.080      | -            | -                | -                | 1 (0.080) |     1.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4182 | 2024-02-19 | ENCE              | L   | 0.074      | -            | -                | -                | -         |    -0.05 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4191 | 2024-02-19 | MOUZ              | L   | 0.072      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4412 | 2024-02-08 | Insilio           | L   | 0.001      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,194.01)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.708 | $2,158.00      | $1,526.79       |
| 2024-05-18 |      0.667 | $1,000.00      | $667.22         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
