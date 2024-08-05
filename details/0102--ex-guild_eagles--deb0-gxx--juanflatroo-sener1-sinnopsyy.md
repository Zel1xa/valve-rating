### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: deb0, gxx-, juanflatroo, SENER1, sinnopsyy<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.5<br />
<br />
Final Rank Value (855.5) = Starting Rank Value (811.0) + Head To Head Adjustments (44.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.094[<sup>2</sup>](#table1)
- LAN Wins: 0.033[<sup>2</sup>](#table1)

The average of these factors is 0.200<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 811.0
- 400 + ( ( 0.200 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 811.0


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
|           38 |     1188 | 2024-06-11 | SINNERS           | L   | 0.832      | -            | -                | -                | -         |    -7.58 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           37 |     1784 | 2024-05-25 | Zero Tenacity     | L   | 0.720      | -            | -                | -                | -         |    -4.75 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           36 |     1793 | 2024-05-25 | The Suspect       | W   | 0.719      | 0.143        | 0.008 (0.001)    | 0.227 (0.023)    | 0 (0.000) |     9.88 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     1802 | 2024-05-24 | Zero Tenacity     | W   | 0.714      | 0.273        | 0.143 (0.028)    | 1.000 (0.195)    | 0 (0.000) |    18.16 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     1807 | 2024-05-24 | Serbia            | W   | 0.712      | 0.273        | 0.012 (0.002)    | 0.224 (0.043)    | 0 (0.000) |     9.27 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     2037 | 2024-05-17 | Sashi             | L   | 0.665      | -            | -                | -                | -         |    -2.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     2380 | 2024-05-05 | 1WIN              | L   | 0.585      | -            | -                | -                | -         |    -6.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     2494 | 2024-04-29 | EYEBALLERS        | L   | 0.546      | -            | -                | -                | -         |    -7.46 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     2535 | 2024-04-27 | Insilio           | L   | 0.533      | -            | -                | -                | -         |    -6.56 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     2561 | 2024-04-26 | BLEED             | L   | 0.527      | -            | -                | -                | -         |    -3.93 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     2596 | 2024-04-25 | PARIVISION        | L   | 0.519      | -            | -                | -                | -         |    -3.93 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     2620 | 2024-04-24 | Zero Tenacity     | W   | 0.512      | 0.435        | 0.143 (0.032)    | 1.000 (0.222)    | 0 (0.000) |    12.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     2647 | 2024-04-22 | 3DMAX             | L   | 0.500      | -            | -                | -                | -         |    -0.20 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2659 | 2024-04-22 | Sangal            | W   | 0.497      | 0.435        | 0.219 (0.047)    | 0.866 (0.187)    | 0 (0.000) |    13.22 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2772 | 2024-04-18 | Sashi             | L   | 0.474      | -            | -                | -                | -         |    -2.46 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2777 | 2024-04-18 | KOI               | W   | 0.473      | 0.143        | 0.058 (0.004)    | 0.367 (0.025)    | 0 (0.000) |    12.00 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     2789 | 2024-04-18 | FRAGMATIC         | W   | 0.473      | -            | -                | -                | 0 (0.000) |     1.26 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     2796 | 2024-04-18 | AMKAL             | L   | 0.472      | -            | -                | -                | -         |    -2.20 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     2866 | 2024-04-16 | Sashi             | W   | 0.459      | 0.384        | 0.184 (0.032)    | 0.983 (0.173)    | -         |    12.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     3059 | 2024-04-09 | Metizport         | W   | 0.412      | 0.384        | 0.032 (0.005)    | 0.240 (0.038)    | -         |     7.96 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3226 | 2024-04-03 | AMKAL             | L   | 0.373      | -            | -                | -                | -         |    -1.69 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3256 | 2024-04-02 | Insilio           | L   | 0.367      | -            | -                | -                | -         |    -4.26 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3265 | 2024-04-02 | AMKAL             | W   | 0.366      | 0.143        | 0.130 (0.007)    | 0.465 (0.024)    | -         |     9.89 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3275 | 2024-04-02 | 500               | L   | 0.365      | -            | -                | -                | -         |    -7.15 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3280 | 2024-04-01 | 500               | W   | 0.360      | 0.384        | -                | 0.094 (0.013)    | -         |     4.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3361 | 2024-03-27 | ALTERNATE aTTaX   | L   | 0.327      | -            | -                | -                | -         |    -2.88 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3431 | 2024-03-22 | VP.Prodigy        | L   | 0.292      | -            | -                | -                | -         |    -3.88 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3972 | 2024-02-27 | Croatia           | L   | 0.134      | -            | -                | -                | -         |    -3.63 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3979 | 2024-02-27 | Metizport         | W   | 0.133      | -            | -                | -                | -         |     2.22 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     4058 | 2024-02-24 | GamerLegion       | L   | 0.112      | -            | -                | -                | -         |    -1.95 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     4067 | 2024-02-23 | BetBoom           | W   | 0.106      | 0.143        | 0.249 (0.004)    | -                | 1 (0.106) |     3.22 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     4085 | 2024-02-22 | Gaimin Gladiators | L   | 0.099      | -            | -                | -                | -         |    -0.95 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     4108 | 2024-02-21 | ex-Preasy         | W   | 0.093      | -            | -                | -                | 1 (0.093) |     1.32 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4138 | 2024-02-20 | Nexus             | W   | 0.086      | -            | -                | -                | 1 (0.086) |     1.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4162 | 2024-02-19 | ENCE              | L   | 0.080      | -            | -                | -                | -         |    -0.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4171 | 2024-02-19 | MOUZ              | L   | 0.078      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4392 | 2024-02-08 | Insilio           | L   | 0.007      | -            | -                | -                | -         |    -0.09 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4396 | 2024-02-08 | RUBY              | L   | 0.006      | -            | -                | -                | -         |    -0.07 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,213.31)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.714 | $2,158.00      | $1,539.97       |
| 2024-05-18 |      0.673 | $1,000.00      | $673.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
