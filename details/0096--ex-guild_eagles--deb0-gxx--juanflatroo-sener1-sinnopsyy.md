### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: deb0, gxx-, juanflatroo, SENER1, sinnopsyy<br />
Global Rank: [96](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [70]( ../standings_europe.md)<br />
<br />
Final Rank Value:  857.7<br />
<br />
Final Rank Value (857.7) = Starting Rank Value (814.3) + Head To Head Adjustments (43.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.359[<sup>2</sup>](#table1)
- Opponent Network: 0.099[<sup>2</sup>](#table1)
- LAN Wins: 0.036[<sup>2</sup>](#table1)

The average of these factors is 0.203<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 814.3
- 400 + ( ( 0.203 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 814.3


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
|           38 |     1127 | 2024-06-11 | SINNERS           | L   | 0.843      | -            | -                | -                | -         |    -8.48 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           37 |     1723 | 2024-05-25 | Zero Tenacity     | L   | 0.732      | -            | -                | -                | -         |    -4.86 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           36 |     1732 | 2024-05-25 | The Suspect       | W   | 0.730      | 0.143        | 0.008 (0.001)    | 0.189 (0.020)    | 0 (0.000) |     9.84 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     1741 | 2024-05-24 | Zero Tenacity     | W   | 0.725      | 0.273        | 0.137 (0.027)    | 1.000 (0.198)    | 0 (0.000) |    18.41 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     1746 | 2024-05-24 | Serbia            | W   | 0.724      | 0.273        | 0.012 (0.002)    | 0.227 (0.045)    | 0 (0.000) |     9.33 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     1976 | 2024-05-17 | Sashi             | L   | 0.676      | -            | -                | -                | -         |    -2.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     2319 | 2024-05-05 | 1WIN              | L   | 0.597      | -            | -                | -                | -         |    -7.41 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     2433 | 2024-04-29 | EYEBALLERS        | L   | 0.558      | -            | -                | -                | -         |    -7.70 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     2474 | 2024-04-27 | Insilio           | L   | 0.545      | -            | -                | -                | -         |    -6.84 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     2500 | 2024-04-26 | BLEED             | L   | 0.538      | -            | -                | -                | -         |    -4.05 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     2534 | 2024-04-25 | PARIVISION        | L   | 0.531      | -            | -                | -                | -         |    -4.22 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     2558 | 2024-04-24 | Zero Tenacity     | W   | 0.523      | 0.435        | 0.137 (0.031)    | 1.000 (0.227)    | 0 (0.000) |    12.56 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     2585 | 2024-04-22 | 3DMAX             | L   | 0.511      | -            | -                | -                | -         |    -0.22 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2597 | 2024-04-22 | Sangal            | W   | 0.509      | 0.435        | 0.219 (0.048)    | 0.862 (0.191)    | 0 (0.000) |    13.40 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2710 | 2024-04-18 | Sashi             | L   | 0.485      | -            | -                | -                | -         |    -2.62 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2715 | 2024-04-18 | KOI               | W   | 0.485      | 0.143        | 0.059 (0.004)    | 0.376 (0.026)    | 0 (0.000) |    12.27 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     2727 | 2024-04-18 | FRAGMATIC         | W   | 0.485      | -            | -                | -                | 0 (0.000) |     1.26 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     2734 | 2024-04-18 | AMKAL             | L   | 0.484      | -            | -                | -                | -         |    -2.28 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     2804 | 2024-04-16 | Sashi             | W   | 0.471      | 0.384        | 0.184 (0.033)    | 0.964 (0.174)    | -         |    12.58 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     2997 | 2024-04-09 | Metizport         | W   | 0.424      | 0.384        | 0.037 (0.006)    | 0.418 (0.068)    | -         |     9.08 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3164 | 2024-04-03 | AMKAL             | L   | 0.384      | -            | -                | -                | -         |    -1.76 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3194 | 2024-04-02 | Insilio           | L   | 0.379      | -            | -                | -                | -         |    -4.47 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3203 | 2024-04-02 | AMKAL             | W   | 0.378      | 0.143        | 0.130 (0.007)    | 0.477 (0.026)    | -         |    10.19 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3213 | 2024-04-02 | 500               | L   | 0.376      | -            | -                | -                | -         |    -7.41 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3218 | 2024-04-01 | 500               | W   | 0.372      | 0.384        | -                | 0.099 (0.014)    | -         |     4.46 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3299 | 2024-03-27 | ALTERNATE aTTaX   | L   | 0.339      | -            | -                | -                | -         |    -3.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3369 | 2024-03-22 | VP.Prodigy        | L   | 0.303      | -            | -                | -                | -         |    -4.09 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3909 | 2024-02-27 | Croatia           | L   | 0.145      | -            | -                | -                | -         |    -3.95 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3916 | 2024-02-27 | Metizport         | W   | 0.145      | -            | -                | -                | -         |     2.82 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     3995 | 2024-02-24 | GamerLegion       | L   | 0.123      | -            | -                | -                | -         |    -2.12 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     4004 | 2024-02-23 | BetBoom           | W   | 0.117      | 0.143        | 0.252 (0.004)    | -                | 1 (0.117) |     3.58 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     4022 | 2024-02-22 | Gaimin Gladiators | L   | 0.111      | -            | -                | -                | -         |    -1.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     4045 | 2024-02-21 | ex-Preasy         | W   | 0.105      | -            | -                | -                | 1 (0.105) |     1.49 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4075 | 2024-02-20 | Nexus             | W   | 0.097      | -            | -                | -                | 1 (0.097) |     1.63 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4099 | 2024-02-19 | ENCE              | L   | 0.092      | -            | -                | -                | -         |    -0.07 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4108 | 2024-02-19 | MOUZ              | L   | 0.090      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4328 | 2024-02-08 | Insilio           | L   | 0.019      | -            | -                | -                | -         |    -0.23 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4332 | 2024-02-08 | RUBY              | L   | 0.018      | -            | -                | -                | -         |    -0.19 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,250.15)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.725 | $2,158.00      | $1,565.15       |
| 2024-05-18 |      0.685 | $1,000.00      | $685.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
