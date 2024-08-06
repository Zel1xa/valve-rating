### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [76](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
<br />
Final Rank Value:  956.1<br />
<br />
Final Rank Value (956.1) = Starting Rank Value (895.5) + Head To Head Adjustments (60.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.378[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.215[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.241<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 895.5
- 400 + ( ( 0.241 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 895.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           53 |       63 | 2024-08-04 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|           52 |      102 | 2024-08-03 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.91 | faydett, FpSSS, Pipw, Polt, sugaR |
|           51 |      131 | 2024-08-02 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -14.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |      170 | 2024-08-01 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.07 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |      215 | 2024-07-31 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -7.02 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |      255 | 2024-07-30 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -11.20 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |      320 | 2024-07-28 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.45 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |      446 | 2024-07-24 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |    -8.44 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |      516 | 2024-07-22 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.92 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |      581 | 2024-07-20 | UNiTY             | W   | 1.000      | 0.371        | 0.024 (0.009)    | -                | 0 (0.000) |    15.02 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |      619 | 2024-07-19 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -17.24 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |      659 | 2024-07-18 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.488 (0.244)    | 0 (0.000) |    10.06 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |      779 | 2024-07-16 | KOI               | L   | 1.000      | -            | -                | -                | -         |   -10.26 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |      856 | 2024-07-14 | Permitta          | W   | 1.000      | 0.371        | 0.039 (0.014)    | 0.919 (0.340)    | 0 (0.000) |    16.03 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |      919 | 2024-07-10 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.62 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |      941 | 2024-07-09 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.43 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |      960 | 2024-07-08 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -27.86 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     1217 | 2024-06-10 | ARCRED            | W   | 0.821      | 0.372        | 0.041 (0.013)    | -                | 0 (0.000) |    11.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     1264 | 2024-06-09 | RUBY              | W   | 0.813      | 0.372        | 0.095 (0.029)    | 0.479 (0.145)    | 0 (0.000) |    10.68 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     1320 | 2024-06-08 | Zero Tenacity     | W   | 0.807      | 0.372        | 0.143 (0.043)    | 1.000 (0.301)    | 0 (0.000) |    17.53 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     1386 | 2024-06-07 | Aurora Young Blud | W   | 0.800      | 0.372        | -                | 0.522 (0.155)    | -         |    11.05 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     1589 | 2024-06-03 | RUBY              | L   | 0.774      | -            | -                | -                | -         |   -12.21 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     1646 | 2024-06-01 | 1WIN              | W   | 0.760      | 0.372        | 0.033 (0.009)    | 0.718 (0.203)    | -         |    14.44 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     1699 | 2024-05-30 | VP.Prodigy        | W   | 0.747      | -            | -                | -                | -         |    11.44 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     2355 | 2024-05-07 | RUBY              | L   | 0.593      | -            | -                | -                | -         |    -9.43 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     2374 | 2024-05-06 | Zero Tenacity     | L   | 0.587      | -            | -                | -                | -         |    -6.49 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     2378 | 2024-05-06 | BLEED             | L   | 0.585      | -            | -                | -                | -         |    -6.30 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     2423 | 2024-05-03 | Permitta          | W   | 0.566      | 0.435        | 0.039 (0.010)    | 0.919 (0.226)    | -         |     8.94 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     2435 | 2024-05-03 | BetBoom           | L   | 0.564      | -            | -                | -                | -         |    -1.24 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     2470 | 2024-05-01 | OG                | W   | 0.554      | 0.435        | 0.137 (0.033)    | -                | -         |    11.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     2479 | 2024-05-01 | Nexus             | W   | 0.552      | -            | -                | -                | -         |     6.42 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     2521 | 2024-04-29 | HAVU              | L   | 0.539      | -            | -                | -                | -         |   -13.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     2557 | 2024-04-27 | ex-Guild Eagles   | W   | 0.527      | -            | -                | -                | -         |     6.44 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     2566 | 2024-04-27 | Permitta          | W   | 0.526      | 0.396        | 0.039 (0.008)    | 0.919 (0.192)    | -         |     9.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     2585 | 2024-04-26 | ARCRED            | L   | 0.520      | -            | -                | -                | -         |    -8.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     2590 | 2024-04-26 | Enterprise        | W   | 0.519      | 0.396        | -                | 0.641 (0.132)    | -         |     7.71 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     2626 | 2024-04-25 | MOUZ NXT          | W   | 0.511      | 0.435        | 0.139 (0.031)    | 0.961 (0.214)    | -         |    10.70 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     2651 | 2024-04-23 | EYEBALLERS        | W   | 0.500      | -            | -                | -                | -         |     7.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     2700 | 2024-04-21 | Permitta          | L   | 0.484      | -            | -                | -                | -         |    -6.13 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     3237 | 2024-04-03 | AMKAL             | L   | 0.367      | -            | -                | -                | -         |    -2.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     3278 | 2024-04-02 | ex-Guild Eagles   | W   | 0.361      | -            | -                | -                | -         |     4.16 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     3293 | 2024-04-02 | PARIVISION        | W   | 0.359      | -            | -                | -                | -         |     8.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     3520 | 2024-03-18 | Sashi             | L   | 0.259      | -            | -                | -                | -         |    -1.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     3579 | 2024-03-15 | CYBERSHOKE        | W   | 0.241      | -            | -                | -                | -         |     1.63 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     3651 | 2024-03-13 | INGLORIOUS        | W   | 0.227      | -            | -                | -                | -         |     0.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     3703 | 2024-03-11 | 1WIN              | W   | 0.213      | -            | -                | -                | -         |     3.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     3747 | 2024-03-09 | Fraud5            | W   | 0.200      | -            | -                | -                | -         |     1.24 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     3787 | 2024-03-07 | Sashi             | L   | 0.188      | -            | -                | -                | -         |    -1.19 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     3822 | 2024-03-06 | The Chosen Few    | W   | 0.181      | -            | -                | -                | -         |     1.27 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     3861 | 2024-03-05 | Johnny Speeds     | L   | 0.174      | -            | -                | -                | -         |    -0.50 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     3868 | 2024-03-05 | Betera            | W   | 0.174      | -            | -                | -                | -         |     1.34 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     4405 | 2024-02-09 | Sashi             | L   | 0.006      | -            | -                | -                | -         |    -0.04 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     4414 | 2024-02-08 | ex-Guild Eagles   | W   | 0.001      | -            | -                | -                | -         |     0.01 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,274.86)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.821 | $7,000.00      | $5,744.86       |
| 2024-05-04 |      0.573 | $2,000.00      | $1,146.67       |
| 2024-03-25 |      0.307 | $1,250.00      | $383.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
