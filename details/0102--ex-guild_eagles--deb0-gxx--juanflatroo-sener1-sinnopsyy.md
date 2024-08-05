### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: deb0, gxx-, juanflatroo, SENER1, sinnopsyy<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.2<br />
<br />
Final Rank Value (855.2) = Starting Rank Value (810.7) + Head To Head Adjustments (44.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.095[<sup>2</sup>](#table1)
- LAN Wins: 0.033[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 810.7
- 400 + ( ( 0.201 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 810.7


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
|           38 |     1180 | 2024-06-11 | SINNERS           | L   | 0.833      | -            | -                | -                | -         |    -7.66 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           37 |     1776 | 2024-05-25 | Zero Tenacity     | L   | 0.721      | -            | -                | -                | -         |    -4.74 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           36 |     1785 | 2024-05-25 | The Suspect       | W   | 0.720      | 0.143        | 0.008 (0.001)    | 0.230 (0.024)    | 0 (0.000) |     9.90 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     1794 | 2024-05-24 | Zero Tenacity     | W   | 0.715      | 0.273        | 0.137 (0.027)    | 1.000 (0.195)    | 0 (0.000) |    18.20 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     1799 | 2024-05-24 | Serbia            | W   | 0.713      | 0.273        | 0.012 (0.002)    | 0.227 (0.044)    | 0 (0.000) |     9.29 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     2029 | 2024-05-17 | Sashi             | L   | 0.666      | -            | -                | -                | -         |    -2.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     2372 | 2024-05-05 | 1WIN              | L   | 0.586      | -            | -                | -                | -         |    -6.45 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     2486 | 2024-04-29 | EYEBALLERS        | L   | 0.547      | -            | -                | -                | -         |    -7.48 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     2527 | 2024-04-27 | Insilio           | L   | 0.534      | -            | -                | -                | -         |    -6.60 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     2553 | 2024-04-26 | BLEED             | L   | 0.528      | -            | -                | -                | -         |    -3.93 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     2588 | 2024-04-25 | PARIVISION        | L   | 0.520      | -            | -                | -                | -         |    -3.98 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     2612 | 2024-04-24 | Zero Tenacity     | W   | 0.513      | 0.435        | 0.137 (0.030)    | 1.000 (0.223)    | 0 (0.000) |    12.45 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     2639 | 2024-04-22 | 3DMAX             | L   | 0.501      | -            | -                | -                | -         |    -0.20 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2651 | 2024-04-22 | Sangal            | W   | 0.499      | 0.435        | 0.219 (0.047)    | 0.877 (0.190)    | 0 (0.000) |    13.24 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2764 | 2024-04-18 | Sashi             | L   | 0.475      | -            | -                | -                | -         |    -2.47 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2769 | 2024-04-18 | KOI               | W   | 0.475      | 0.143        | 0.058 (0.004)    | 0.372 (0.025)    | 0 (0.000) |    12.04 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     2781 | 2024-04-18 | FRAGMATIC         | W   | 0.474      | -            | -                | -                | 0 (0.000) |     1.26 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     2788 | 2024-04-18 | AMKAL             | L   | 0.473      | -            | -                | -                | -         |    -2.19 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     2858 | 2024-04-16 | Sashi             | W   | 0.460      | 0.384        | 0.184 (0.033)    | 0.996 (0.176)    | -         |    12.38 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     3051 | 2024-04-09 | Metizport         | W   | 0.413      | 0.384        | 0.033 (0.005)    | 0.244 (0.039)    | -         |     7.98 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3218 | 2024-04-03 | AMKAL             | L   | 0.374      | -            | -                | -                | -         |    -1.69 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3248 | 2024-04-02 | Insilio           | L   | 0.368      | -            | -                | -                | -         |    -4.27 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3257 | 2024-04-02 | AMKAL             | W   | 0.367      | 0.143        | 0.130 (0.007)    | 0.472 (0.025)    | -         |     9.93 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3267 | 2024-04-02 | 500               | L   | 0.366      | -            | -                | -                | -         |    -7.18 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3272 | 2024-04-01 | 500               | W   | 0.362      | 0.384        | -                | 0.096 (0.013)    | -         |     4.36 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3353 | 2024-03-27 | ALTERNATE aTTaX   | L   | 0.328      | -            | -                | -                | -         |    -2.89 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3423 | 2024-03-22 | VP.Prodigy        | L   | 0.293      | -            | -                | -                | -         |    -3.89 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3964 | 2024-02-27 | Croatia           | L   | 0.135      | -            | -                | -                | -         |    -3.65 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3971 | 2024-02-27 | Metizport         | W   | 0.134      | -            | -                | -                | -         |     2.23 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     4050 | 2024-02-24 | GamerLegion       | L   | 0.113      | -            | -                | -                | -         |    -1.97 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     4059 | 2024-02-23 | BetBoom           | W   | 0.107      | 0.143        | 0.249 (0.004)    | -                | 1 (0.107) |     3.25 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     4077 | 2024-02-22 | Gaimin Gladiators | L   | 0.100      | -            | -                | -                | -         |    -0.96 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     4100 | 2024-02-21 | ex-Preasy         | W   | 0.094      | -            | -                | -                | 1 (0.094) |     1.34 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4130 | 2024-02-20 | Nexus             | W   | 0.087      | -            | -                | -                | 1 (0.087) |     1.47 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4154 | 2024-02-19 | ENCE              | L   | 0.081      | -            | -                | -                | -         |    -0.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4163 | 2024-02-19 | MOUZ              | L   | 0.079      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4384 | 2024-02-08 | Insilio           | L   | 0.008      | -            | -                | -                | -         |    -0.10 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4388 | 2024-02-08 | RUBY              | L   | 0.007      | -            | -                | -                | -         |    -0.08 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,216.82)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.715 | $2,158.00      | $1,542.37       |
| 2024-05-18 |      0.674 | $1,000.00      | $674.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
