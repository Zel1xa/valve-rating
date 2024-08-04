### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: deb0, gxx-, juanflatroo, SENER1, sinnopsyy<br />
Global Rank: [96](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [70]( ../standings_europe.md)<br />
<br />
Final Rank Value:  856.8<br />
<br />
Final Rank Value (856.8) = Starting Rank Value (813.5) + Head To Head Adjustments (43.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.359[<sup>2</sup>](#table1)
- Opponent Network: 0.098[<sup>2</sup>](#table1)
- LAN Wins: 0.035[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 813.5
- 400 + ( ( 0.202 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 813.5


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
|           38 |     1131 | 2024-06-11 | SINNERS           | L   | 0.840      | -            | -                | -                | -         |    -8.44 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           37 |     1727 | 2024-05-25 | Zero Tenacity     | L   | 0.729      | -            | -                | -                | -         |    -4.83 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           36 |     1736 | 2024-05-25 | The Suspect       | W   | 0.727      | 0.143        | 0.008 (0.001)    | 0.189 (0.020)    | 0 (0.000) |     9.83 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     1745 | 2024-05-24 | Zero Tenacity     | W   | 0.722      | 0.273        | 0.137 (0.027)    | 1.000 (0.197)    | 0 (0.000) |    18.34 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     1750 | 2024-05-24 | Serbia            | W   | 0.721      | 0.273        | 0.012 (0.002)    | 0.227 (0.045)    | 0 (0.000) |     9.31 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     1980 | 2024-05-17 | Sashi             | L   | 0.673      | -            | -                | -                | -         |    -2.43 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     2323 | 2024-05-05 | 1WIN              | L   | 0.593      | -            | -                | -                | -         |    -7.37 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     2437 | 2024-04-29 | EYEBALLERS        | L   | 0.555      | -            | -                | -                | -         |    -7.64 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     2478 | 2024-04-27 | Insilio           | L   | 0.542      | -            | -                | -                | -         |    -6.80 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     2504 | 2024-04-26 | BLEED             | L   | 0.535      | -            | -                | -                | -         |    -4.04 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     2539 | 2024-04-25 | PARIVISION        | L   | 0.528      | -            | -                | -                | -         |    -4.17 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     2563 | 2024-04-24 | Zero Tenacity     | W   | 0.520      | 0.435        | 0.137 (0.031)    | 1.000 (0.226)    | 0 (0.000) |    12.51 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     2590 | 2024-04-22 | 3DMAX             | L   | 0.508      | -            | -                | -                | -         |    -0.22 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2602 | 2024-04-22 | Sangal            | W   | 0.506      | 0.435        | 0.219 (0.048)    | 0.862 (0.189)    | 0 (0.000) |    13.34 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2715 | 2024-04-18 | Sashi             | L   | 0.482      | -            | -                | -                | -         |    -2.59 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2720 | 2024-04-18 | KOI               | W   | 0.482      | 0.143        | 0.058 (0.004)    | 0.375 (0.026)    | 0 (0.000) |    12.19 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     2732 | 2024-04-18 | FRAGMATIC         | W   | 0.482      | -            | -                | -                | 0 (0.000) |     1.26 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     2739 | 2024-04-18 | AMKAL             | L   | 0.481      | -            | -                | -                | -         |    -2.26 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     2809 | 2024-04-16 | Sashi             | W   | 0.468      | 0.384        | 0.184 (0.033)    | 0.962 (0.173)    | -         |    12.51 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     3002 | 2024-04-09 | Metizport         | W   | 0.421      | 0.384        | 0.037 (0.006)    | 0.417 (0.067)    | -         |     9.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3169 | 2024-04-03 | AMKAL             | L   | 0.381      | -            | -                | -                | -         |    -1.74 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3199 | 2024-04-02 | Insilio           | L   | 0.376      | -            | -                | -                | -         |    -4.43 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3208 | 2024-04-02 | AMKAL             | W   | 0.374      | 0.143        | 0.130 (0.007)    | 0.476 (0.025)    | -         |    10.11 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3218 | 2024-04-02 | 500               | L   | 0.373      | -            | -                | -                | -         |    -7.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3223 | 2024-04-01 | 500               | W   | 0.369      | 0.384        | -                | 0.098 (0.014)    | -         |     4.43 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3304 | 2024-03-27 | ALTERNATE aTTaX   | L   | 0.336      | -            | -                | -                | -         |    -2.98 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3374 | 2024-03-22 | VP.Prodigy        | L   | 0.300      | -            | -                | -                | -         |    -4.04 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3915 | 2024-02-27 | Croatia           | L   | 0.142      | -            | -                | -                | -         |    -3.87 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3922 | 2024-02-27 | Metizport         | W   | 0.142      | -            | -                | -                | -         |     2.77 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     4001 | 2024-02-24 | GamerLegion       | L   | 0.120      | -            | -                | -                | -         |    -2.08 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     4010 | 2024-02-23 | BetBoom           | W   | 0.114      | 0.143        | 0.251 (0.004)    | -                | 1 (0.114) |     3.48 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     4028 | 2024-02-22 | Gaimin Gladiators | L   | 0.108      | -            | -                | -                | -         |    -1.03 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     4051 | 2024-02-21 | ex-Preasy         | W   | 0.102      | -            | -                | -                | 1 (0.102) |     1.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4081 | 2024-02-20 | Nexus             | W   | 0.094      | -            | -                | -                | 1 (0.094) |     1.58 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4105 | 2024-02-19 | ENCE              | L   | 0.088      | -            | -                | -                | -         |    -0.07 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4114 | 2024-02-19 | MOUZ              | L   | 0.087      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4335 | 2024-02-08 | Insilio           | L   | 0.016      | -            | -                | -                | -         |    -0.20 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4339 | 2024-02-08 | RUBY              | L   | 0.015      | -            | -                | -                | -         |    -0.16 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,240.50)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.722 | $2,158.00      | $1,558.56       |
| 2024-05-18 |      0.682 | $1,000.00      | $681.94         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
