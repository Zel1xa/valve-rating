### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: deb0, gxx-, juanflatroo, SENER1, sinnopsyy<br />
Global Rank: [99](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [72]( ../standings_europe.md)<br />
<br />
Final Rank Value:  856.0<br />
<br />
Final Rank Value (856.0) = Starting Rank Value (811.8) + Head To Head Adjustments (44.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.035[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 811.8
- 400 + ( ( 0.201 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 811.8


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
|           38 |     1162 | 2024-06-11 | SINNERS           | L   | 0.839      | -            | -                | -                | -         |    -7.83 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           37 |     1758 | 2024-05-25 | Zero Tenacity     | L   | 0.727      | -            | -                | -                | -         |    -4.82 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           36 |     1767 | 2024-05-25 | The Suspect       | W   | 0.726      | 0.143        | 0.008 (0.001)    | 0.229 (0.024)    | 0 (0.000) |     9.94 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     1776 | 2024-05-24 | Zero Tenacity     | W   | 0.721      | 0.273        | 0.137 (0.027)    | 1.000 (0.197)    | 0 (0.000) |    18.30 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     1781 | 2024-05-24 | Serbia            | W   | 0.719      | 0.273        | 0.012 (0.002)    | 0.227 (0.045)    | 0 (0.000) |     9.33 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     2011 | 2024-05-17 | Sashi             | L   | 0.672      | -            | -                | -                | -         |    -2.37 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     2354 | 2024-05-05 | 1WIN              | L   | 0.592      | -            | -                | -                | -         |    -6.68 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     2468 | 2024-04-29 | EYEBALLERS        | L   | 0.554      | -            | -                | -                | -         |    -7.58 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     2509 | 2024-04-27 | Insilio           | L   | 0.540      | -            | -                | -                | -         |    -6.69 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     2535 | 2024-04-26 | BLEED             | L   | 0.534      | -            | -                | -                | -         |    -3.97 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     2570 | 2024-04-25 | PARIVISION        | L   | 0.526      | -            | -                | -                | -         |    -4.10 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     2594 | 2024-04-24 | Zero Tenacity     | W   | 0.519      | 0.435        | 0.137 (0.031)    | 1.000 (0.225)    | 0 (0.000) |    12.53 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     2621 | 2024-04-22 | 3DMAX             | L   | 0.507      | -            | -                | -                | -         |    -0.21 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2633 | 2024-04-22 | Sangal            | W   | 0.505      | 0.435        | 0.219 (0.048)    | 0.861 (0.189)    | 0 (0.000) |    13.36 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2746 | 2024-04-18 | Sashi             | L   | 0.481      | -            | -                | -                | -         |    -2.52 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2751 | 2024-04-18 | KOI               | W   | 0.481      | 0.143        | 0.058 (0.004)    | 0.375 (0.026)    | 0 (0.000) |    12.20 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     2763 | 2024-04-18 | FRAGMATIC         | W   | 0.480      | -            | -                | -                | 0 (0.000) |     1.27 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     2770 | 2024-04-18 | AMKAL             | L   | 0.479      | -            | -                | -                | -         |    -2.23 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     2840 | 2024-04-16 | Sashi             | W   | 0.466      | 0.384        | 0.184 (0.033)    | 0.962 (0.172)    | -         |    12.53 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     3033 | 2024-04-09 | Metizport         | W   | 0.419      | 0.384        | 0.033 (0.005)    | 0.248 (0.040)    | -         |     8.11 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3200 | 2024-04-03 | AMKAL             | L   | 0.380      | -            | -                | -                | -         |    -1.73 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3230 | 2024-04-02 | Insilio           | L   | 0.374      | -            | -                | -                | -         |    -4.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3239 | 2024-04-02 | AMKAL             | W   | 0.373      | 0.143        | 0.130 (0.007)    | 0.475 (0.025)    | -         |    10.08 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3249 | 2024-04-02 | 500               | L   | 0.372      | -            | -                | -                | -         |    -7.29 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3254 | 2024-04-01 | 500               | W   | 0.368      | 0.384        | -                | 0.098 (0.014)    | -         |     4.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3335 | 2024-03-27 | ALTERNATE aTTaX   | L   | 0.334      | -            | -                | -                | -         |    -2.95 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3405 | 2024-03-22 | VP.Prodigy        | L   | 0.299      | -            | -                | -                | -         |    -3.98 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3946 | 2024-02-27 | Croatia           | L   | 0.141      | -            | -                | -                | -         |    -3.82 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3953 | 2024-02-27 | Metizport         | W   | 0.140      | -            | -                | -                | -         |     2.33 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     4032 | 2024-02-24 | GamerLegion       | L   | 0.119      | -            | -                | -                | -         |    -2.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     4041 | 2024-02-23 | BetBoom           | W   | 0.113      | 0.143        | 0.251 (0.004)    | -                | 1 (0.113) |     3.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     4059 | 2024-02-22 | Gaimin Gladiators | L   | 0.106      | -            | -                | -                | -         |    -1.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     4082 | 2024-02-21 | ex-Preasy         | W   | 0.100      | -            | -                | -                | 1 (0.100) |     1.43 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4112 | 2024-02-20 | Nexus             | W   | 0.093      | -            | -                | -                | 1 (0.093) |     1.56 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4136 | 2024-02-19 | ENCE              | L   | 0.087      | -            | -                | -                | -         |    -0.07 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4145 | 2024-02-19 | MOUZ              | L   | 0.085      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4366 | 2024-02-08 | Insilio           | L   | 0.014      | -            | -                | -                | -         |    -0.17 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4370 | 2024-02-08 | RUBY              | L   | 0.013      | -            | -                | -                | -         |    -0.14 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,235.82)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.721 | $2,158.00      | $1,555.36       |
| 2024-05-18 |      0.680 | $1,000.00      | $680.46         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
