### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: deb0, gxx-, juanflatroo, SENER1, sinnopsyy<br />
Global Rank: [103](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  854.5<br />
<br />
Final Rank Value (854.5) = Starting Rank Value (809.7) + Head To Head Adjustments (44.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.093[<sup>2</sup>](#table1)
- LAN Wins: 0.031[<sup>2</sup>](#table1)

The average of these factors is 0.200<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 809.7
- 400 + ( ( 0.200 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 809.7


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
|           38 |     1195 | 2024-06-11 | SINNERS           | L   | 0.827      | -            | -                | -                | -         |    -7.49 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           37 |     1791 | 2024-05-25 | Zero Tenacity     | L   | 0.715      | -            | -                | -                | -         |    -4.69 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           36 |     1800 | 2024-05-25 | The Suspect       | W   | 0.714      | 0.143        | 0.008 (0.001)    | 0.228 (0.023)    | 0 (0.000) |     9.85 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     1809 | 2024-05-24 | Zero Tenacity     | W   | 0.709      | 0.273        | 0.143 (0.028)    | 1.000 (0.193)    | 0 (0.000) |    18.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     1814 | 2024-05-24 | Serbia            | W   | 0.707      | 0.273        | 0.012 (0.002)    | 0.224 (0.043)    | 0 (0.000) |     9.26 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     2044 | 2024-05-17 | Sashi             | L   | 0.660      | -            | -                | -                | -         |    -2.32 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     2387 | 2024-05-05 | 1WIN              | L   | 0.580      | -            | -                | -                | -         |    -6.32 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     2501 | 2024-04-29 | EYEBALLERS        | L   | 0.542      | -            | -                | -                | -         |    -7.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     2542 | 2024-04-27 | Insilio           | L   | 0.528      | -            | -                | -                | -         |    -6.43 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     2568 | 2024-04-26 | BLEED             | L   | 0.522      | -            | -                | -                | -         |    -3.89 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     2603 | 2024-04-25 | PARIVISION        | L   | 0.514      | -            | -                | -                | -         |    -3.85 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     2627 | 2024-04-24 | Zero Tenacity     | W   | 0.507      | 0.435        | 0.143 (0.031)    | 1.000 (0.220)    | 0 (0.000) |    12.36 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     2654 | 2024-04-22 | 3DMAX             | L   | 0.495      | -            | -                | -                | -         |    -0.20 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2666 | 2024-04-22 | Sangal            | W   | 0.493      | 0.435        | 0.219 (0.047)    | 0.865 (0.185)    | 0 (0.000) |    13.13 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2779 | 2024-04-18 | Sashi             | L   | 0.469      | -            | -                | -                | -         |    -2.42 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2784 | 2024-04-18 | KOI               | W   | 0.469      | 0.143        | 0.058 (0.004)    | 0.365 (0.024)    | 0 (0.000) |    11.88 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     2796 | 2024-04-18 | FRAGMATIC         | W   | 0.468      | -            | -                | -                | 0 (0.000) |     1.25 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     2803 | 2024-04-18 | AMKAL             | L   | 0.467      | -            | -                | -                | -         |    -2.15 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     2873 | 2024-04-16 | Sashi             | W   | 0.454      | 0.384        | 0.184 (0.032)    | 0.980 (0.171)    | -         |    12.24 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     3066 | 2024-04-09 | Metizport         | W   | 0.407      | 0.384        | 0.032 (0.005)    | 0.237 (0.037)    | -         |     7.85 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3233 | 2024-04-03 | AMKAL             | L   | 0.368      | -            | -                | -                | -         |    -1.65 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3263 | 2024-04-02 | Insilio           | L   | 0.362      | -            | -                | -                | -         |    -4.15 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3272 | 2024-04-02 | AMKAL             | W   | 0.361      | 0.143        | 0.130 (0.007)    | 0.463 (0.024)    | -         |     9.78 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3282 | 2024-04-02 | 500               | L   | 0.360      | -            | -                | -                | -         |    -7.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3287 | 2024-04-01 | 500               | W   | 0.356      | 0.384        | -                | 0.093 (0.013)    | -         |     4.30 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3368 | 2024-03-27 | ALTERNATE aTTaX   | L   | 0.322      | -            | -                | -                | -         |    -2.83 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3438 | 2024-03-22 | VP.Prodigy        | L   | 0.287      | -            | -                | -                | -         |    -3.79 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3979 | 2024-02-27 | Croatia           | L   | 0.129      | -            | -                | -                | -         |    -3.50 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3986 | 2024-02-27 | Metizport         | W   | 0.129      | -            | -                | -                | -         |     2.14 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     4065 | 2024-02-24 | GamerLegion       | L   | 0.107      | -            | -                | -                | -         |    -1.87 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     4074 | 2024-02-23 | BetBoom           | W   | 0.101      | 0.143        | 0.248 (0.004)    | -                | 1 (0.101) |     3.08 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     4092 | 2024-02-22 | Gaimin Gladiators | L   | 0.094      | -            | -                | -                | -         |    -0.91 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     4115 | 2024-02-21 | ex-Preasy         | W   | 0.088      | -            | -                | -                | 1 (0.088) |     1.25 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4145 | 2024-02-20 | Nexus             | W   | 0.081      | -            | -                | -                | 1 (0.081) |     1.37 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4169 | 2024-02-19 | ENCE              | L   | 0.075      | -            | -                | -                | -         |    -0.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4178 | 2024-02-19 | MOUZ              | L   | 0.074      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4399 | 2024-02-08 | Insilio           | L   | 0.002      | -            | -                | -                | -         |    -0.03 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4403 | 2024-02-08 | RUBY              | L   | 0.001      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,198.39)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.709 | $2,158.00      | $1,529.78       |
| 2024-05-18 |      0.669 | $1,000.00      | $668.61         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
