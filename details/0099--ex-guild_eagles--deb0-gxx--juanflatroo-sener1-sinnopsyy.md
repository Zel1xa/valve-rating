### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: deb0, gxx-, juanflatroo, SENER1, sinnopsyy<br />
Global Rank: [99](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [72]( ../standings_europe.md)<br />
<br />
Final Rank Value:  862.6<br />
<br />
Final Rank Value (862.6) = Starting Rank Value (822.4) + Head To Head Adjustments (40.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.317[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.101[<sup>2</sup>](#table1)
- LAN Wins: 0.042[<sup>2</sup>](#table1)

The average of these factors is 0.205<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 822.4
- 400 + ( ( 0.205 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 822.4


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
|           38 |     1054 | 2024-06-11 | SINNERS           | L   | 0.858      | -            | -                | -                | -         |    -8.88 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           37 |     1668 | 2024-05-25 | Zero Tenacity     | L   | 0.747      | -            | -                | -                | -         |    -5.57 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           36 |     1677 | 2024-05-25 | The Suspect       | W   | 0.745      | 0.143        | 0.008 (0.001)    | 0.186 (0.020)    | 0 (0.000) |    10.03 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     1686 | 2024-05-24 | Zero Tenacity     | W   | 0.740      | 0.273        | 0.139 (0.028)    | 1.000 (0.202)    | 0 (0.000) |    18.16 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     1691 | 2024-05-24 | Serbia            | W   | 0.739      | 0.273        | 0.013 (0.003)    | 0.226 (0.046)    | 0 (0.000) |     9.45 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     1947 | 2024-05-17 | Sashi             | L   | 0.691      | -            | -                | -                | -         |    -2.50 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     2301 | 2024-05-05 | 1WIN              | L   | 0.612      | -            | -                | -                | -         |    -7.63 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     2418 | 2024-04-29 | EYEBALLERS        | L   | 0.573      | -            | -                | -                | -         |    -7.97 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     2459 | 2024-04-27 | Insilio           | L   | 0.560      | -            | -                | -                | -         |    -7.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     2486 | 2024-04-26 | BLEED             | L   | 0.553      | -            | -                | -                | -         |    -4.34 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     2520 | 2024-04-25 | PARIVISION        | L   | 0.546      | -            | -                | -                | -         |    -4.36 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     2544 | 2024-04-24 | Zero Tenacity     | W   | 0.538      | 0.435        | 0.139 (0.032)    | 1.000 (0.234)    | 0 (0.000) |    12.78 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     2574 | 2024-04-22 | 3DMAX             | L   | 0.526      | -            | -                | -                | -         |    -0.23 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2587 | 2024-04-22 | Sangal            | W   | 0.524      | 0.435        | 0.221 (0.050)    | 0.823 (0.188)    | 0 (0.000) |    13.63 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2704 | 2024-04-18 | Sashi             | L   | 0.500      | -            | -                | -                | -         |    -2.72 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2709 | 2024-04-18 | KOI               | W   | 0.500      | 0.143        | 0.040 (0.003)    | 0.313 (0.022)    | 0 (0.000) |    10.37 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     2721 | 2024-04-18 | FRAGMATIC         | W   | 0.500      | -            | -                | -                | 0 (0.000) |     1.24 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     2728 | 2024-04-18 | AMKAL             | L   | 0.499      | -            | -                | -                | -         |    -2.41 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     2800 | 2024-04-16 | Sashi             | W   | 0.486      | 0.384        | 0.187 (0.035)    | 0.970 (0.181)    | -         |    12.94 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     2994 | 2024-04-09 | Metizport         | W   | 0.439      | 0.384        | 0.038 (0.006)    | 0.425 (0.072)    | -         |     9.31 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3163 | 2024-04-03 | AMKAL             | L   | 0.399      | -            | -                | -                | -         |    -1.88 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3199 | 2024-04-02 | Insilio           | L   | 0.394      | -            | -                | -                | -         |    -4.70 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3208 | 2024-04-02 | AMKAL             | W   | 0.393      | 0.143        | 0.132 (0.007)    | 0.482 (0.027)    | -         |    10.54 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3218 | 2024-04-02 | 500               | L   | 0.391      | -            | -                | -                | -         |    -7.40 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3223 | 2024-04-01 | 500               | W   | 0.387      | 0.384        | -                | 0.126 (0.019)    | -         |     4.96 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3305 | 2024-03-27 | ALTERNATE aTTaX   | L   | 0.354      | -            | -                | -                | -         |    -3.21 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3379 | 2024-03-22 | VP.Prodigy        | L   | 0.318      | -            | -                | -                | -         |    -4.33 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3933 | 2024-02-27 | Croatia           | L   | 0.160      | -            | -                | -                | -         |    -4.38 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3940 | 2024-02-27 | Metizport         | W   | 0.160      | -            | -                | -                | -         |     3.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     4023 | 2024-02-24 | GamerLegion       | L   | 0.138      | -            | -                | -                | -         |    -2.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     4033 | 2024-02-23 | BetBoom           | W   | 0.132      | 0.143        | 0.257 (0.005)    | -                | 1 (0.132) |     4.04 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     4053 | 2024-02-22 | Gaimin Gladiators | L   | 0.126      | -            | -                | -                | -         |    -1.16 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     4077 | 2024-02-21 | ex-Preasy         | W   | 0.120      | -            | -                | -                | 1 (0.120) |     1.70 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4107 | 2024-02-20 | Nexus             | W   | 0.112      | -            | -                | -                | 1 (0.112) |     1.87 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4131 | 2024-02-19 | ENCE              | L   | 0.107      | -            | -                | -                | -         |    -0.08 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4140 | 2024-02-19 | MOUZ              | L   | 0.105      | -            | -                | -                | -         |    -0.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4371 | 2024-02-08 | Insilio           | L   | 0.034      | -            | -                | -                | -         |    -0.42 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4375 | 2024-02-08 | RUBY              | L   | 0.033      | -            | -                | -                | -         |    -0.35 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,297.52)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.740 | $2,158.00      | $1,597.52       |
| 2024-05-18 |      0.700 | $1,000.00      | $700.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
