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
Final Rank Value (857.4) = Starting Rank Value (811.9) + Head To Head Adjustments (45.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.031[<sup>2</sup>](#table1)

The average of these factors is 0.200<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 811.9
- 400 + ( ( 0.200 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 811.9


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
|           37 |     1212 | 2024-06-11 | SINNERS           | L   | 0.825      | -            | -                | -                | -         |    -7.50 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           36 |     1808 | 2024-05-25 | Zero Tenacity     | L   | 0.714      | -            | -                | -                | -         |    -4.64 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     1817 | 2024-05-25 | The Suspect       | W   | 0.712      | 0.143        | 0.008 (0.001)    | 0.223 (0.023)    | 0 (0.000) |     9.76 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     1826 | 2024-05-24 | Zero Tenacity     | W   | 0.707      | 0.273        | 0.143 (0.028)    | 1.000 (0.193)    | 0 (0.000) |    18.05 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     1831 | 2024-05-24 | Serbia            | W   | 0.706      | 0.273        | 0.012 (0.002)    | 0.219 (0.042)    | 0 (0.000) |     9.25 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     2061 | 2024-05-17 | Sashi             | L   | 0.658      | -            | -                | -                | -         |    -2.34 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     2404 | 2024-05-05 | 1WIN              | L   | 0.578      | -            | -                | -                | -         |    -6.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     2518 | 2024-04-29 | EYEBALLERS        | L   | 0.540      | -            | -                | -                | -         |    -7.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     2559 | 2024-04-27 | Insilio           | L   | 0.527      | -            | -                | -                | -         |    -6.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     2585 | 2024-04-26 | BLEED             | L   | 0.520      | -            | -                | -                | -         |    -3.93 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     2620 | 2024-04-25 | PARIVISION        | L   | 0.513      | -            | -                | -                | -         |    -3.83 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     2644 | 2024-04-24 | Zero Tenacity     | W   | 0.505      | 0.435        | 0.143 (0.031)    | 1.000 (0.220)    | 0 (0.000) |    12.27 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2671 | 2024-04-22 | 3DMAX             | L   | 0.493      | -            | -                | -                | -         |    -0.20 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2683 | 2024-04-22 | Sangal            | W   | 0.491      | 0.435        | 0.219 (0.047)    | 0.846 (0.181)    | 0 (0.000) |    13.11 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2796 | 2024-04-18 | Sashi             | L   | 0.467      | -            | -                | -                | -         |    -2.43 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     2801 | 2024-04-18 | KOI               | W   | 0.467      | 0.143        | 0.058 (0.004)    | 0.356 (0.024)    | 0 (0.000) |    11.78 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     2813 | 2024-04-18 | FRAGMATIC         | W   | 0.467      | -            | -                | -                | 0 (0.000) |     1.23 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     2820 | 2024-04-18 | AMKAL             | L   | 0.466      | -            | -                | -                | -         |    -2.17 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     2890 | 2024-04-16 | Sashi             | W   | 0.453      | 0.384        | 0.184 (0.032)    | 0.958 (0.167)    | -         |    12.18 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3083 | 2024-04-09 | Metizport         | W   | 0.406      | 0.384        | 0.036 (0.006)    | 0.510 (0.080)    | -         |     8.73 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3250 | 2024-04-03 | AMKAL             | L   | 0.366      | -            | -                | -                | -         |    -1.66 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3280 | 2024-04-02 | Insilio           | L   | 0.361      | -            | -                | -                | -         |    -4.16 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3289 | 2024-04-02 | AMKAL             | W   | 0.359      | 0.143        | 0.130 (0.007)    | 0.452 (0.023)    | -         |     9.72 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3299 | 2024-04-02 | 500               | L   | 0.358      | -            | -                | -                | -         |    -7.05 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3304 | 2024-04-01 | 500               | W   | 0.354      | 0.384        | -                | 0.090 (0.012)    | -         |     4.25 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3385 | 2024-03-27 | ALTERNATE aTTaX   | L   | 0.321      | -            | -                | -                | -         |    -2.82 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3455 | 2024-03-22 | VP.Prodigy        | L   | 0.285      | -            | -                | -                | -         |    -3.78 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3996 | 2024-02-27 | Croatia           | L   | 0.127      | -            | -                | -                | -         |    -3.46 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     4003 | 2024-02-27 | Metizport         | W   | 0.127      | -            | -                | -                | -         |     2.50 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     4082 | 2024-02-24 | GamerLegion       | L   | 0.105      | -            | -                | -                | -         |    -1.85 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     4091 | 2024-02-23 | BetBoom           | W   | 0.099      | 0.143        | 0.248 (0.004)    | -                | 1 (0.099) |     3.02 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     4109 | 2024-02-22 | Gaimin Gladiators | L   | 0.093      | -            | -                | -                | -         |    -0.90 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4132 | 2024-02-21 | ex-Preasy         | W   | 0.087      | -            | -                | -                | 1 (0.087) |     1.22 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4162 | 2024-02-20 | Nexus             | W   | 0.079      | -            | -                | -                | 1 (0.079) |     1.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4186 | 2024-02-19 | ENCE              | L   | 0.073      | -            | -                | -                | -         |    -0.05 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4195 | 2024-02-19 | MOUZ              | L   | 0.072      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4416 | 2024-02-08 | Insilio           | L   | 0.001      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,193.13)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.707 | $2,158.00      | $1,526.19       |
| 2024-05-18 |      0.667 | $1,000.00      | $666.94         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
