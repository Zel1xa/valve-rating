### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: deb0, gxx-, juanflatroo, SENER1, sinnopsyy<br />
Global Rank: [103](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  856.8<br />
<br />
Final Rank Value (856.8) = Starting Rank Value (811.6) + Head To Head Adjustments (45.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.095[<sup>2</sup>](#table1)
- LAN Wins: 0.031[<sup>2</sup>](#table1)

The average of these factors is 0.200<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 811.6
- 400 + ( ( 0.200 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 811.6


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
|           38 |     1201 | 2024-06-11 | SINNERS           | L   | 0.826      | -            | -                | -                | -         |    -7.54 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           37 |     1797 | 2024-05-25 | Zero Tenacity     | L   | 0.715      | -            | -                | -                | -         |    -4.66 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           36 |     1806 | 2024-05-25 | The Suspect       | W   | 0.713      | 0.143        | 0.008 (0.001)    | 0.223 (0.023)    | 0 (0.000) |     9.79 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     1815 | 2024-05-24 | Zero Tenacity     | W   | 0.708      | 0.273        | 0.143 (0.028)    | 1.000 (0.193)    | 0 (0.000) |    18.07 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     1820 | 2024-05-24 | Serbia            | W   | 0.707      | 0.273        | 0.012 (0.002)    | 0.219 (0.042)    | 0 (0.000) |     9.20 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     2050 | 2024-05-17 | Sashi             | L   | 0.659      | -            | -                | -                | -         |    -2.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     2393 | 2024-05-05 | 1WIN              | L   | 0.579      | -            | -                | -                | -         |    -6.39 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     2507 | 2024-04-29 | EYEBALLERS        | L   | 0.541      | -            | -                | -                | -         |    -7.37 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     2548 | 2024-04-27 | Insilio           | L   | 0.528      | -            | -                | -                | -         |    -6.48 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     2574 | 2024-04-26 | BLEED             | L   | 0.521      | -            | -                | -                | -         |    -3.93 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     2609 | 2024-04-25 | PARIVISION        | L   | 0.514      | -            | -                | -                | -         |    -3.86 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     2633 | 2024-04-24 | Zero Tenacity     | W   | 0.506      | 0.435        | 0.143 (0.031)    | 1.000 (0.220)    | 0 (0.000) |    12.29 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     2660 | 2024-04-22 | 3DMAX             | L   | 0.494      | -            | -                | -                | -         |    -0.20 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2672 | 2024-04-22 | Sangal            | W   | 0.492      | 0.435        | 0.219 (0.047)    | 0.846 (0.181)    | 0 (0.000) |    13.08 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2785 | 2024-04-18 | Sashi             | L   | 0.468      | -            | -                | -                | -         |    -2.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2790 | 2024-04-18 | KOI               | W   | 0.468      | 0.143        | 0.058 (0.004)    | 0.357 (0.024)    | 0 (0.000) |    11.81 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     2802 | 2024-04-18 | FRAGMATIC         | W   | 0.468      | -            | -                | -                | 0 (0.000) |     1.23 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     2809 | 2024-04-18 | AMKAL             | L   | 0.467      | -            | -                | -                | -         |    -2.18 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     2879 | 2024-04-16 | Sashi             | W   | 0.454      | 0.384        | 0.184 (0.032)    | 0.958 (0.167)    | -         |    12.20 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     3072 | 2024-04-09 | Metizport         | W   | 0.407      | 0.384        | 0.036 (0.006)    | 0.434 (0.068)    | -         |     8.72 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3239 | 2024-04-03 | AMKAL             | L   | 0.367      | -            | -                | -                | -         |    -1.67 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3269 | 2024-04-02 | Insilio           | L   | 0.362      | -            | -                | -                | -         |    -4.18 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3278 | 2024-04-02 | AMKAL             | W   | 0.360      | 0.143        | 0.130 (0.007)    | 0.453 (0.023)    | -         |     9.75 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3288 | 2024-04-02 | 500               | L   | 0.359      | -            | -                | -                | -         |    -7.07 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3293 | 2024-04-01 | 500               | W   | 0.355      | 0.384        | -                | 0.090 (0.012)    | -         |     4.27 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3374 | 2024-03-27 | ALTERNATE aTTaX   | L   | 0.322      | -            | -                | -                | -         |    -2.83 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3444 | 2024-03-22 | VP.Prodigy        | L   | 0.286      | -            | -                | -                | -         |    -3.81 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3985 | 2024-02-27 | Croatia           | L   | 0.128      | -            | -                | -                | -         |    -3.48 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3992 | 2024-02-27 | Metizport         | W   | 0.128      | -            | -                | -                | -         |     2.50 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     4071 | 2024-02-24 | GamerLegion       | L   | 0.106      | -            | -                | -                | -         |    -1.87 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     4080 | 2024-02-23 | BetBoom           | W   | 0.100      | 0.143        | 0.248 (0.004)    | -                | 1 (0.100) |     3.05 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     4098 | 2024-02-22 | Gaimin Gladiators | L   | 0.094      | -            | -                | -                | -         |    -0.91 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     4121 | 2024-02-21 | ex-Preasy         | W   | 0.088      | -            | -                | -                | 1 (0.088) |     1.24 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4151 | 2024-02-20 | Nexus             | W   | 0.080      | -            | -                | -                | 1 (0.080) |     1.36 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4175 | 2024-02-19 | ENCE              | L   | 0.074      | -            | -                | -                | -         |    -0.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4184 | 2024-02-19 | MOUZ              | L   | 0.073      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4405 | 2024-02-08 | Insilio           | L   | 0.002      | -            | -                | -                | -         |    -0.02 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4409 | 2024-02-08 | RUBY              | L   | 0.001      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,196.35)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.708 | $2,158.00      | $1,528.38       |
| 2024-05-18 |      0.668 | $1,000.00      | $667.96         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
