### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: deb0, gxx-, juanflatroo, SENER1, sinnopsyy<br />
Global Rank: [101](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  863.5<br />
<br />
Final Rank Value (863.5) = Starting Rank Value (823.4) + Head To Head Adjustments (40.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.317[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.101[<sup>2</sup>](#table1)
- LAN Wins: 0.042[<sup>2</sup>](#table1)

The average of these factors is 0.206<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 823.4
- 400 + ( ( 0.206 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 823.4


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
|           38 |     1050 | 2024-06-11 | SINNERS           | L   | 0.860      | -            | -                | -                | -         |    -8.90 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           37 |     1664 | 2024-05-25 | Zero Tenacity     | L   | 0.748      | -            | -                | -                | -         |    -5.58 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           36 |     1673 | 2024-05-25 | The Suspect       | W   | 0.747      | 0.143        | 0.008 (0.001)    | 0.186 (0.020)    | 0 (0.000) |    10.03 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     1682 | 2024-05-24 | Zero Tenacity     | W   | 0.742      | 0.273        | 0.139 (0.028)    | 1.000 (0.202)    | 0 (0.000) |    18.19 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     1687 | 2024-05-24 | Serbia            | W   | 0.740      | 0.273        | 0.013 (0.003)    | 0.226 (0.046)    | 0 (0.000) |     9.46 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     1943 | 2024-05-17 | Sashi             | L   | 0.693      | -            | -                | -                | -         |    -2.51 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     2297 | 2024-05-05 | 1WIN              | L   | 0.613      | -            | -                | -                | -         |    -7.69 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     2414 | 2024-04-29 | EYEBALLERS        | L   | 0.574      | -            | -                | -                | -         |    -8.00 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     2455 | 2024-04-27 | Insilio           | L   | 0.561      | -            | -                | -                | -         |    -7.08 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     2482 | 2024-04-26 | BLEED             | L   | 0.555      | -            | -                | -                | -         |    -4.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     2516 | 2024-04-25 | PARIVISION        | L   | 0.547      | -            | -                | -                | -         |    -4.37 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     2540 | 2024-04-24 | Zero Tenacity     | W   | 0.540      | 0.435        | 0.139 (0.033)    | 1.000 (0.235)    | 0 (0.000) |    12.80 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     2570 | 2024-04-22 | 3DMAX             | L   | 0.528      | -            | -                | -                | -         |    -0.23 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2583 | 2024-04-22 | Sangal            | W   | 0.526      | 0.435        | 0.221 (0.050)    | 0.823 (0.188)    | 0 (0.000) |    13.66 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2700 | 2024-04-18 | Sashi             | L   | 0.502      | -            | -                | -                | -         |    -2.73 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2705 | 2024-04-18 | KOI               | W   | 0.501      | 0.143        | 0.040 (0.003)    | 0.313 (0.022)    | 0 (0.000) |    10.40 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     2717 | 2024-04-18 | FRAGMATIC         | W   | 0.501      | -            | -                | -                | 0 (0.000) |     1.24 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     2724 | 2024-04-18 | AMKAL             | L   | 0.500      | -            | -                | -                | -         |    -2.41 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     2796 | 2024-04-16 | Sashi             | W   | 0.487      | 0.384        | 0.187 (0.035)    | 0.971 (0.182)    | -         |    12.98 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     2990 | 2024-04-09 | Metizport         | W   | 0.440      | 0.384        | 0.038 (0.007)    | 0.425 (0.072)    | -         |     9.34 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3159 | 2024-04-03 | AMKAL             | L   | 0.401      | -            | -                | -                | -         |    -1.88 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3195 | 2024-04-02 | Insilio           | L   | 0.395      | -            | -                | -                | -         |    -4.71 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3204 | 2024-04-02 | AMKAL             | W   | 0.394      | 0.143        | 0.132 (0.007)    | 0.482 (0.027)    | -         |    10.59 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3214 | 2024-04-02 | 500               | L   | 0.393      | -            | -                | -                | -         |    -7.43 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3219 | 2024-04-01 | 500               | W   | 0.388      | 0.384        | -                | 0.127 (0.019)    | -         |     4.97 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3301 | 2024-03-27 | ALTERNATE aTTaX   | L   | 0.355      | -            | -                | -                | -         |    -3.22 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3375 | 2024-03-22 | VP.Prodigy        | L   | 0.320      | -            | -                | -                | -         |    -4.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3929 | 2024-02-27 | Croatia           | L   | 0.162      | -            | -                | -                | -         |    -4.42 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3936 | 2024-02-27 | Metizport         | W   | 0.161      | -            | -                | -                | -         |     3.08 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     4019 | 2024-02-24 | GamerLegion       | L   | 0.140      | -            | -                | -                | -         |    -2.38 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     4029 | 2024-02-23 | BetBoom           | W   | 0.134      | 0.143        | 0.257 (0.005)    | -                | 1 (0.134) |     4.08 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     4049 | 2024-02-22 | Gaimin Gladiators | L   | 0.127      | -            | -                | -                | -         |    -1.17 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     4073 | 2024-02-21 | ex-Preasy         | W   | 0.121      | -            | -                | -                | 1 (0.121) |     1.72 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4103 | 2024-02-20 | Nexus             | W   | 0.114      | -            | -                | -                | 1 (0.114) |     1.89 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4127 | 2024-02-19 | ENCE              | L   | 0.108      | -            | -                | -                | -         |    -0.08 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4136 | 2024-02-19 | MOUZ              | L   | 0.106      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4367 | 2024-02-08 | Insilio           | L   | 0.035      | -            | -                | -                | -         |    -0.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4371 | 2024-02-08 | RUBY              | L   | 0.034      | -            | -                | -                | -         |    -0.36 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,301.91)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.742 | $2,158.00      | $1,600.52       |
| 2024-05-18 |      0.701 | $1,000.00      | $701.39         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
