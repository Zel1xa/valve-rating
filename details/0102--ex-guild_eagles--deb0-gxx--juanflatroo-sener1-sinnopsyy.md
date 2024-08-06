### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: deb0, gxx-, juanflatroo, SENER1, sinnopsyy<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.1<br />
<br />
Final Rank Value (855.1) = Starting Rank Value (810.4) + Head To Head Adjustments (44.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.094[<sup>2</sup>](#table1)
- LAN Wins: 0.032[<sup>2</sup>](#table1)

The average of these factors is 0.200<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 810.4
- 400 + ( ( 0.200 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 810.4


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
|           38 |     1191 | 2024-06-11 | SINNERS           | L   | 0.829      | -            | -                | -                | -         |    -7.54 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           37 |     1787 | 2024-05-25 | Zero Tenacity     | L   | 0.718      | -            | -                | -                | -         |    -4.72 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           36 |     1796 | 2024-05-25 | The Suspect       | W   | 0.716      | 0.143        | 0.008 (0.001)    | 0.227 (0.023)    | 0 (0.000) |     9.87 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     1805 | 2024-05-24 | Zero Tenacity     | W   | 0.711      | 0.273        | 0.143 (0.028)    | 1.000 (0.194)    | 0 (0.000) |    18.11 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     1810 | 2024-05-24 | Serbia            | W   | 0.710      | 0.273        | 0.012 (0.002)    | 0.224 (0.043)    | 0 (0.000) |     9.26 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     2040 | 2024-05-17 | Sashi             | L   | 0.662      | -            | -                | -                | -         |    -2.33 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     2383 | 2024-05-05 | 1WIN              | L   | 0.583      | -            | -                | -                | -         |    -6.38 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     2497 | 2024-04-29 | EYEBALLERS        | L   | 0.544      | -            | -                | -                | -         |    -7.40 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     2538 | 2024-04-27 | Insilio           | L   | 0.531      | -            | -                | -                | -         |    -6.49 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     2564 | 2024-04-26 | BLEED             | L   | 0.524      | -            | -                | -                | -         |    -3.91 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     2599 | 2024-04-25 | PARIVISION        | L   | 0.517      | -            | -                | -                | -         |    -3.90 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     2623 | 2024-04-24 | Zero Tenacity     | W   | 0.509      | 0.435        | 0.143 (0.032)    | 1.000 (0.221)    | 0 (0.000) |    12.40 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     2650 | 2024-04-22 | 3DMAX             | L   | 0.497      | -            | -                | -                | -         |    -0.20 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2662 | 2024-04-22 | Sangal            | W   | 0.495      | 0.435        | 0.219 (0.047)    | 0.866 (0.186)    | 0 (0.000) |    13.18 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2775 | 2024-04-18 | Sashi             | L   | 0.472      | -            | -                | -                | -         |    -2.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2780 | 2024-04-18 | KOI               | W   | 0.471      | 0.143        | 0.058 (0.004)    | 0.366 (0.025)    | 0 (0.000) |    11.94 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     2792 | 2024-04-18 | FRAGMATIC         | W   | 0.471      | -            | -                | -                | 0 (0.000) |     1.26 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     2799 | 2024-04-18 | AMKAL             | L   | 0.470      | -            | -                | -                | -         |    -2.17 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     2869 | 2024-04-16 | Sashi             | W   | 0.457      | 0.384        | 0.184 (0.032)    | 0.982 (0.172)    | -         |    12.30 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     3062 | 2024-04-09 | Metizport         | W   | 0.410      | 0.384        | 0.032 (0.005)    | 0.239 (0.038)    | -         |     7.91 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3229 | 2024-04-03 | AMKAL             | L   | 0.370      | -            | -                | -                | -         |    -1.67 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3259 | 2024-04-02 | Insilio           | L   | 0.365      | -            | -                | -                | -         |    -4.21 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3268 | 2024-04-02 | AMKAL             | W   | 0.364      | 0.143        | 0.130 (0.007)    | 0.464 (0.024)    | -         |     9.84 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3278 | 2024-04-02 | 500               | L   | 0.362      | -            | -                | -                | -         |    -7.11 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3283 | 2024-04-01 | 500               | W   | 0.358      | 0.384        | -                | 0.093 (0.013)    | -         |     4.33 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3364 | 2024-03-27 | ALTERNATE aTTaX   | L   | 0.325      | -            | -                | -                | -         |    -2.85 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3434 | 2024-03-22 | VP.Prodigy        | L   | 0.289      | -            | -                | -                | -         |    -3.83 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3975 | 2024-02-27 | Croatia           | L   | 0.131      | -            | -                | -                | -         |    -3.56 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3982 | 2024-02-27 | Metizport         | W   | 0.131      | -            | -                | -                | -         |     2.18 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     4061 | 2024-02-24 | GamerLegion       | L   | 0.109      | -            | -                | -                | -         |    -1.92 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     4070 | 2024-02-23 | BetBoom           | W   | 0.103      | 0.143        | 0.249 (0.004)    | -                | 1 (0.103) |     3.15 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     4088 | 2024-02-22 | Gaimin Gladiators | L   | 0.097      | -            | -                | -                | -         |    -0.93 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     4111 | 2024-02-21 | ex-Preasy         | W   | 0.091      | -            | -                | -                | 1 (0.091) |     1.29 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4141 | 2024-02-20 | Nexus             | W   | 0.083      | -            | -                | -                | 1 (0.083) |     1.41 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4165 | 2024-02-19 | ENCE              | L   | 0.078      | -            | -                | -                | -         |    -0.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4174 | 2024-02-19 | MOUZ              | L   | 0.076      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4395 | 2024-02-08 | Insilio           | L   | 0.005      | -            | -                | -                | -         |    -0.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4399 | 2024-02-08 | RUBY              | L   | 0.004      | -            | -                | -                | -         |    -0.04 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,206.29)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.711 | $2,158.00      | $1,535.18       |
| 2024-05-18 |      0.671 | $1,000.00      | $671.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
