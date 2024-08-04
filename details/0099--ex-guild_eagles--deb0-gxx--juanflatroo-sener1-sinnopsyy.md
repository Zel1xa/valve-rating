### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: deb0, gxx-, juanflatroo, SENER1, sinnopsyy<br />
Global Rank: [99](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [72]( ../standings_europe.md)<br />
<br />
Final Rank Value:  856.1<br />
<br />
Final Rank Value (856.1) = Starting Rank Value (811.7) + Head To Head Adjustments (44.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.035[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 811.7
- 400 + ( ( 0.201 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 811.7


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
|           38 |     1163 | 2024-06-11 | SINNERS           | L   | 0.838      | -            | -                | -                | -         |    -7.82 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           37 |     1759 | 2024-05-25 | Zero Tenacity     | L   | 0.727      | -            | -                | -                | -         |    -4.81 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           36 |     1768 | 2024-05-25 | The Suspect       | W   | 0.725      | 0.143        | 0.008 (0.001)    | 0.229 (0.024)    | 0 (0.000) |     9.94 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     1777 | 2024-05-24 | Zero Tenacity     | W   | 0.720      | 0.273        | 0.137 (0.027)    | 1.000 (0.197)    | 0 (0.000) |    18.31 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     1782 | 2024-05-24 | Serbia            | W   | 0.719      | 0.273        | 0.012 (0.002)    | 0.227 (0.045)    | 0 (0.000) |     9.33 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     2012 | 2024-05-17 | Sashi             | L   | 0.672      | -            | -                | -                | -         |    -2.37 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     2355 | 2024-05-05 | 1WIN              | L   | 0.592      | -            | -                | -                | -         |    -6.67 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     2469 | 2024-04-29 | EYEBALLERS        | L   | 0.553      | -            | -                | -                | -         |    -7.58 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     2510 | 2024-04-27 | Insilio           | L   | 0.540      | -            | -                | -                | -         |    -6.69 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     2536 | 2024-04-26 | BLEED             | L   | 0.533      | -            | -                | -                | -         |    -3.95 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     2571 | 2024-04-25 | PARIVISION        | L   | 0.526      | -            | -                | -                | -         |    -4.09 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     2595 | 2024-04-24 | Zero Tenacity     | W   | 0.518      | 0.435        | 0.137 (0.031)    | 1.000 (0.225)    | 0 (0.000) |    12.54 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     2622 | 2024-04-22 | 3DMAX             | L   | 0.507      | -            | -                | -                | -         |    -0.21 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2634 | 2024-04-22 | Sangal            | W   | 0.504      | 0.435        | 0.219 (0.048)    | 0.861 (0.189)    | 0 (0.000) |    13.37 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2747 | 2024-04-18 | Sashi             | L   | 0.481      | -            | -                | -                | -         |    -2.52 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2752 | 2024-04-18 | KOI               | W   | 0.480      | 0.143        | 0.058 (0.004)    | 0.375 (0.026)    | 0 (0.000) |    12.19 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     2764 | 2024-04-18 | FRAGMATIC         | W   | 0.480      | -            | -                | -                | 0 (0.000) |     1.27 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     2771 | 2024-04-18 | AMKAL             | L   | 0.479      | -            | -                | -                | -         |    -2.22 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     2841 | 2024-04-16 | Sashi             | W   | 0.466      | 0.384        | 0.184 (0.033)    | 0.962 (0.172)    | -         |    12.52 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     3034 | 2024-04-09 | Metizport         | W   | 0.419      | 0.384        | 0.033 (0.005)    | 0.248 (0.040)    | -         |     8.11 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3201 | 2024-04-03 | AMKAL             | L   | 0.379      | -            | -                | -                | -         |    -1.72 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3231 | 2024-04-02 | Insilio           | L   | 0.374      | -            | -                | -                | -         |    -4.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3240 | 2024-04-02 | AMKAL             | W   | 0.373      | 0.143        | 0.130 (0.007)    | 0.475 (0.025)    | -         |    10.08 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3250 | 2024-04-02 | 500               | L   | 0.372      | -            | -                | -                | -         |    -7.29 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3255 | 2024-04-01 | 500               | W   | 0.367      | 0.384        | -                | 0.097 (0.014)    | -         |     4.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3336 | 2024-03-27 | ALTERNATE aTTaX   | L   | 0.334      | -            | -                | -                | -         |    -2.94 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3406 | 2024-03-22 | VP.Prodigy        | L   | 0.298      | -            | -                | -                | -         |    -3.98 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3947 | 2024-02-27 | Croatia           | L   | 0.141      | -            | -                | -                | -         |    -3.81 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3954 | 2024-02-27 | Metizport         | W   | 0.140      | -            | -                | -                | -         |     2.33 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     4033 | 2024-02-24 | GamerLegion       | L   | 0.118      | -            | -                | -                | -         |    -2.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     4042 | 2024-02-23 | BetBoom           | W   | 0.112      | 0.143        | 0.251 (0.004)    | -                | 1 (0.112) |     3.43 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     4060 | 2024-02-22 | Gaimin Gladiators | L   | 0.106      | -            | -                | -                | -         |    -1.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     4083 | 2024-02-21 | ex-Preasy         | W   | 0.100      | -            | -                | -                | 1 (0.100) |     1.42 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4113 | 2024-02-20 | Nexus             | W   | 0.092      | -            | -                | -                | 1 (0.092) |     1.56 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4137 | 2024-02-19 | ENCE              | L   | 0.087      | -            | -                | -                | -         |    -0.07 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4146 | 2024-02-19 | MOUZ              | L   | 0.085      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4367 | 2024-02-08 | Insilio           | L   | 0.014      | -            | -                | -                | -         |    -0.17 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4371 | 2024-02-08 | RUBY              | L   | 0.013      | -            | -                | -                | -         |    -0.14 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,234.87)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.720 | $2,158.00      | $1,554.71       |
| 2024-05-18 |      0.680 | $1,000.00      | $680.16         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
