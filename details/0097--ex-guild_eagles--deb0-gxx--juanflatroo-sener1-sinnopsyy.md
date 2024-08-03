### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: deb0, gxx-, juanflatroo, SENER1, sinnopsyy<br />
Global Rank: [97](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [71]( ../standings_europe.md)<br />
<br />
Final Rank Value:  857.1<br />
<br />
Final Rank Value (857.1) = Starting Rank Value (815.2) + Head To Head Adjustments (41.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.359[<sup>2</sup>](#table1)
- Opponent Network: 0.099[<sup>2</sup>](#table1)
- LAN Wins: 0.037[<sup>2</sup>](#table1)

The average of these factors is 0.203<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 815.2
- 400 + ( ( 0.203 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 815.2


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
|           38 |     1073 | 2024-06-11 | SINNERS           | L   | 0.845      | -            | -                | -                | -         |    -8.56 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           37 |     1659 | 2024-05-25 | Zero Tenacity     | L   | 0.734      | -            | -                | -                | -         |    -4.90 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           36 |     1668 | 2024-05-25 | The Suspect       | W   | 0.732      | 0.143        | 0.008 (0.001)    | 0.195 (0.020)    | 0 (0.000) |     9.92 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     1677 | 2024-05-24 | Zero Tenacity     | W   | 0.727      | 0.273        | 0.137 (0.027)    | 1.000 (0.198)    | 0 (0.000) |    18.42 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     1682 | 2024-05-24 | Serbia            | W   | 0.725      | 0.273        | 0.012 (0.002)    | 0.234 (0.046)    | 0 (0.000) |     9.40 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     1911 | 2024-05-17 | Sashi             | L   | 0.678      | -            | -                | -                | -         |    -2.40 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     2253 | 2024-05-05 | 1WIN              | L   | 0.598      | -            | -                | -                | -         |    -7.34 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     2367 | 2024-04-29 | EYEBALLERS        | L   | 0.560      | -            | -                | -                | -         |    -7.70 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     2408 | 2024-04-27 | Insilio           | L   | 0.547      | -            | -                | -                | -         |    -6.79 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     2434 | 2024-04-26 | BLEED             | L   | 0.540      | -            | -                | -                | -         |    -4.05 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     2468 | 2024-04-25 | PARIVISION        | L   | 0.533      | -            | -                | -                | -         |    -4.17 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     2492 | 2024-04-24 | Zero Tenacity     | W   | 0.525      | 0.435        | 0.137 (0.031)    | 1.000 (0.228)    | 0 (0.000) |    12.62 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     2519 | 2024-04-22 | 3DMAX             | L   | 0.513      | -            | -                | -                | -         |    -0.22 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2531 | 2024-04-22 | Sangal            | W   | 0.511      | 0.435        | 0.219 (0.049)    | 0.823 (0.183)    | 0 (0.000) |    13.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2644 | 2024-04-18 | Sashi             | L   | 0.487      | -            | -                | -                | -         |    -2.52 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2649 | 2024-04-18 | KOI               | W   | 0.487      | 0.143        | 0.040 (0.003)    | 0.319 (0.022)    | 0 (0.000) |    10.11 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     2661 | 2024-04-18 | FRAGMATIC         | W   | 0.486      | -            | -                | -                | 0 (0.000) |     1.26 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     2668 | 2024-04-18 | AMKAL             | L   | 0.485      | -            | -                | -                | -         |    -2.27 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     2738 | 2024-04-16 | Sashi             | W   | 0.472      | 0.384        | 0.184 (0.033)    | 0.998 (0.181)    | -         |    12.71 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     2931 | 2024-04-09 | Metizport         | W   | 0.426      | 0.384        | 0.037 (0.006)    | 0.433 (0.071)    | -         |     9.11 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3098 | 2024-04-03 | AMKAL             | L   | 0.386      | -            | -                | -                | -         |    -1.76 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3128 | 2024-04-02 | Insilio           | L   | 0.380      | -            | -                | -                | -         |    -4.46 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3137 | 2024-04-02 | AMKAL             | W   | 0.379      | 0.143        | 0.130 (0.007)    | 0.494 (0.027)    | -         |    10.25 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3147 | 2024-04-02 | 500               | L   | 0.378      | -            | -                | -                | -         |    -7.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3152 | 2024-04-01 | 500               | W   | 0.374      | 0.384        | -                | 0.103 (0.015)    | -         |     4.49 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3232 | 2024-03-27 | ALTERNATE aTTaX   | L   | 0.340      | -            | -                | -                | -         |    -3.03 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3298 | 2024-03-22 | VP.Prodigy        | L   | 0.305      | -            | -                | -                | -         |    -4.10 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3836 | 2024-02-27 | Croatia           | L   | 0.147      | -            | -                | -                | -         |    -4.00 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3843 | 2024-02-27 | Metizport         | W   | 0.147      | -            | -                | -                | -         |     2.85 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     3922 | 2024-02-24 | GamerLegion       | L   | 0.125      | -            | -                | -                | -         |    -2.16 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     3931 | 2024-02-23 | BetBoom           | W   | 0.119      | 0.143        | 0.252 (0.004)    | -                | 1 (0.119) |     3.63 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     3949 | 2024-02-22 | Gaimin Gladiators | L   | 0.112      | -            | -                | -                | -         |    -1.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     3972 | 2024-02-21 | ex-Preasy         | W   | 0.106      | -            | -                | -                | 1 (0.106) |     1.51 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4002 | 2024-02-20 | Nexus             | W   | 0.099      | -            | -                | -                | 1 (0.099) |     1.67 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4026 | 2024-02-19 | ENCE              | L   | 0.093      | -            | -                | -                | -         |    -0.07 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4035 | 2024-02-19 | MOUZ              | L   | 0.092      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4255 | 2024-02-08 | Insilio           | L   | 0.020      | -            | -                | -                | -         |    -0.25 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4259 | 2024-02-08 | RUBY              | L   | 0.019      | -            | -                | -                | -         |    -0.21 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,255.56)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.727 | $2,158.00      | $1,568.85       |
| 2024-05-18 |      0.687 | $1,000.00      | $686.71         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
