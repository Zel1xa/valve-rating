### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: deb0, gxx-, juanflatroo, SENER1, sinnopsyy<br />
Global Rank: [100](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.4<br />
<br />
Final Rank Value (855.4) = Starting Rank Value (811.0) + Head To Head Adjustments (44.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.095[<sup>2</sup>](#table1)
- LAN Wins: 0.034[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 811.0
- 400 + ( ( 0.201 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 811.0


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
|           38 |     1167 | 2024-06-11 | SINNERS           | L   | 0.836      | -            | -                | -                | -         |    -7.78 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           37 |     1763 | 2024-05-25 | Zero Tenacity     | L   | 0.725      | -            | -                | -                | -         |    -4.78 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           36 |     1772 | 2024-05-25 | The Suspect       | W   | 0.723      | 0.143        | 0.008 (0.001)    | 0.230 (0.024)    | 0 (0.000) |     9.93 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     1781 | 2024-05-24 | Zero Tenacity     | W   | 0.718      | 0.273        | 0.137 (0.027)    | 1.000 (0.196)    | 0 (0.000) |    18.26 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     1786 | 2024-05-24 | Serbia            | W   | 0.716      | 0.273        | 0.012 (0.002)    | 0.227 (0.044)    | 0 (0.000) |     9.31 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     2016 | 2024-05-17 | Sashi             | L   | 0.669      | -            | -                | -                | -         |    -2.36 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     2359 | 2024-05-05 | 1WIN              | L   | 0.589      | -            | -                | -                | -         |    -6.64 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     2473 | 2024-04-29 | EYEBALLERS        | L   | 0.551      | -            | -                | -                | -         |    -7.53 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     2514 | 2024-04-27 | Insilio           | L   | 0.538      | -            | -                | -                | -         |    -6.65 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     2540 | 2024-04-26 | BLEED             | L   | 0.531      | -            | -                | -                | -         |    -3.94 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     2575 | 2024-04-25 | PARIVISION        | L   | 0.524      | -            | -                | -                | -         |    -4.05 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     2599 | 2024-04-24 | Zero Tenacity     | W   | 0.516      | 0.435        | 0.137 (0.031)    | 1.000 (0.224)    | 0 (0.000) |    12.50 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     2626 | 2024-04-22 | 3DMAX             | L   | 0.504      | -            | -                | -                | -         |    -0.21 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2638 | 2024-04-22 | Sangal            | W   | 0.502      | 0.435        | 0.219 (0.048)    | 0.861 (0.188)    | 0 (0.000) |    13.32 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2751 | 2024-04-18 | Sashi             | L   | 0.478      | -            | -                | -                | -         |    -2.50 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2756 | 2024-04-18 | KOI               | W   | 0.478      | 0.143        | 0.058 (0.004)    | 0.374 (0.026)    | 0 (0.000) |    12.13 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     2768 | 2024-04-18 | FRAGMATIC         | W   | 0.477      | -            | -                | -                | 0 (0.000) |     1.27 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     2775 | 2024-04-18 | AMKAL             | L   | 0.477      | -            | -                | -                | -         |    -2.21 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     2845 | 2024-04-16 | Sashi             | W   | 0.463      | 0.384        | 0.184 (0.033)    | 0.961 (0.171)    | -         |    12.46 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     3038 | 2024-04-09 | Metizport         | W   | 0.417      | 0.384        | 0.033 (0.005)    | 0.246 (0.039)    | -         |     8.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3205 | 2024-04-03 | AMKAL             | L   | 0.377      | -            | -                | -                | -         |    -1.71 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3235 | 2024-04-02 | Insilio           | L   | 0.371      | -            | -                | -                | -         |    -4.32 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3244 | 2024-04-02 | AMKAL             | W   | 0.370      | 0.143        | 0.130 (0.007)    | 0.474 (0.025)    | -         |    10.02 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3254 | 2024-04-02 | 500               | L   | 0.369      | -            | -                | -                | -         |    -7.24 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3259 | 2024-04-01 | 500               | W   | 0.365      | 0.384        | -                | 0.097 (0.014)    | -         |     4.41 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3340 | 2024-03-27 | ALTERNATE aTTaX   | L   | 0.331      | -            | -                | -                | -         |    -2.92 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3410 | 2024-03-22 | VP.Prodigy        | L   | 0.296      | -            | -                | -                | -         |    -3.94 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3951 | 2024-02-27 | Croatia           | L   | 0.138      | -            | -                | -                | -         |    -3.75 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3958 | 2024-02-27 | Metizport         | W   | 0.138      | -            | -                | -                | -         |     2.29 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     4037 | 2024-02-24 | GamerLegion       | L   | 0.116      | -            | -                | -                | -         |    -2.02 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     4046 | 2024-02-23 | BetBoom           | W   | 0.110      | 0.143        | 0.250 (0.004)    | -                | 1 (0.110) |     3.36 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     4064 | 2024-02-22 | Gaimin Gladiators | L   | 0.103      | -            | -                | -                | -         |    -0.99 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     4087 | 2024-02-21 | ex-Preasy         | W   | 0.098      | -            | -                | -                | 1 (0.098) |     1.39 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4117 | 2024-02-20 | Nexus             | W   | 0.090      | -            | -                | -                | 1 (0.090) |     1.52 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4141 | 2024-02-19 | ENCE              | L   | 0.084      | -            | -                | -                | -         |    -0.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4150 | 2024-02-19 | MOUZ              | L   | 0.083      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4371 | 2024-02-08 | Insilio           | L   | 0.012      | -            | -                | -                | -         |    -0.14 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4375 | 2024-02-08 | RUBY              | L   | 0.010      | -            | -                | -                | -         |    -0.11 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,227.34)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.718 | $2,158.00      | $1,549.56       |
| 2024-05-18 |      0.678 | $1,000.00      | $677.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
