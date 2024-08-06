### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  954.3<br />
<br />
Final Rank Value (954.3) = Starting Rank Value (894.4) + Head To Head Adjustments (60.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.378[<sup>1</sup>](#table2)
- Bounty Collected: 0.368[<sup>2</sup>](#table1)
- Opponent Network: 0.215[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 894.4
- 400 + ( ( 0.240 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 894.4


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
|           54 |       54 | 2024-08-04 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.91 | faydett, FpSSS, Pipw, Polt, sugaR |
|           53 |       93 | 2024-08-03 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.91 | faydett, FpSSS, Pipw, Polt, sugaR |
|           52 |      122 | 2024-08-02 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -14.69 | faydett, FpSSS, Pipw, Polt, sugaR |
|           51 |      161 | 2024-08-01 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.04 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |      206 | 2024-07-31 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -7.00 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |      246 | 2024-07-30 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -11.30 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |      311 | 2024-07-28 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |      437 | 2024-07-24 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |    -8.42 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |      507 | 2024-07-22 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.89 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |      572 | 2024-07-20 | UNiTY             | W   | 1.000      | 0.371        | 0.024 (0.009)    | -                | 0 (0.000) |    15.06 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |      610 | 2024-07-19 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -17.24 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |      650 | 2024-07-18 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.488 (0.244)    | 0 (0.000) |    10.08 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |      770 | 2024-07-16 | KOI               | L   | 1.000      | -            | -                | -                | -         |   -10.20 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |      847 | 2024-07-14 | Permitta          | W   | 1.000      | 0.371        | 0.023 (0.009)    | 0.919 (0.340)    | 0 (0.000) |    15.76 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |      910 | 2024-07-10 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |      932 | 2024-07-09 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.44 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |      951 | 2024-07-08 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -27.85 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     1208 | 2024-06-10 | ARCRED            | W   | 0.822      | 0.372        | 0.041 (0.013)    | -                | 0 (0.000) |    11.88 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     1255 | 2024-06-09 | RUBY              | W   | 0.814      | 0.372        | 0.095 (0.029)    | 0.480 (0.145)    | 0 (0.000) |    10.67 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     1311 | 2024-06-08 | Zero Tenacity     | W   | 0.808      | 0.372        | 0.143 (0.043)    | 1.000 (0.301)    | 0 (0.000) |    17.57 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     1377 | 2024-06-07 | Aurora Young Blud | W   | 0.801      | 0.372        | -                | 0.521 (0.156)    | -         |    11.11 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     1580 | 2024-06-03 | RUBY              | L   | 0.775      | -            | -                | -                | -         |   -12.24 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     1637 | 2024-06-01 | 1WIN              | W   | 0.761      | 0.372        | 0.033 (0.009)    | 0.718 (0.203)    | -         |    14.46 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     1690 | 2024-05-30 | VP.Prodigy        | W   | 0.748      | 0.372        | 0.025 (0.007)    | -                | -         |    11.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     2346 | 2024-05-07 | RUBY              | L   | 0.594      | -            | -                | -                | -         |    -9.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     2365 | 2024-05-06 | Zero Tenacity     | L   | 0.588      | -            | -                | -                | -         |    -6.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     2369 | 2024-05-06 | BLEED             | L   | 0.586      | -            | -                | -                | -         |    -6.29 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     2414 | 2024-05-03 | Permitta          | W   | 0.567      | 0.435        | -                | 0.919 (0.227)    | -         |     8.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     2426 | 2024-05-03 | BetBoom           | L   | 0.565      | -            | -                | -                | -         |    -1.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     2461 | 2024-05-01 | OG                | W   | 0.555      | 0.435        | 0.137 (0.033)    | -                | -         |    11.63 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     2470 | 2024-05-01 | Nexus             | W   | 0.553      | -            | -                | -                | -         |     6.42 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     2512 | 2024-04-29 | HAVU              | L   | 0.540      | -            | -                | -                | -         |   -13.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     2548 | 2024-04-27 | ex-Guild Eagles   | W   | 0.528      | -            | -                | -                | -         |     6.48 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     2557 | 2024-04-27 | Permitta          | W   | 0.527      | 0.396        | -                | 0.919 (0.192)    | -         |     9.19 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     2576 | 2024-04-26 | ARCRED            | L   | 0.521      | -            | -                | -                | -         |    -8.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     2581 | 2024-04-26 | Enterprise        | W   | 0.520      | 0.396        | 0.039 (0.008)    | 0.641 (0.132)    | -         |     7.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     2617 | 2024-04-25 | MOUZ NXT          | W   | 0.512      | 0.435        | 0.139 (0.031)    | 0.962 (0.214)    | -         |    10.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     2642 | 2024-04-23 | EYEBALLERS        | W   | 0.501      | -            | -                | -                | -         |     7.31 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     2691 | 2024-04-21 | Permitta          | L   | 0.485      | -            | -                | -                | -         |    -6.42 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     3228 | 2024-04-03 | AMKAL             | L   | 0.368      | -            | -                | -                | -         |    -2.67 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     3269 | 2024-04-02 | ex-Guild Eagles   | W   | 0.362      | -            | -                | -                | -         |     4.18 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     3284 | 2024-04-02 | PARIVISION        | W   | 0.360      | -            | -                | -                | -         |     8.76 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     3511 | 2024-03-18 | Sashi             | L   | 0.260      | -            | -                | -                | -         |    -1.78 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     3570 | 2024-03-15 | CYBERSHOKE        | W   | 0.242      | -            | -                | -                | -         |     1.65 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     3642 | 2024-03-13 | INGLORIOUS        | W   | 0.228      | -            | -                | -                | -         |     0.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     3694 | 2024-03-11 | 1WIN              | W   | 0.214      | -            | -                | -                | -         |     3.67 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     3738 | 2024-03-09 | Fraud5            | W   | 0.201      | -            | -                | -                | -         |     1.25 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     3778 | 2024-03-07 | Sashi             | L   | 0.189      | -            | -                | -                | -         |    -1.20 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     3813 | 2024-03-06 | The Chosen Few    | W   | 0.182      | -            | -                | -                | -         |     1.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     3852 | 2024-03-05 | Johnny Speeds     | L   | 0.175      | -            | -                | -                | -         |    -0.50 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     3859 | 2024-03-05 | Betera            | W   | 0.175      | -            | -                | -                | -         |     1.36 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     4396 | 2024-02-09 | Sashi             | L   | 0.007      | -            | -                | -                | -         |    -0.04 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     4405 | 2024-02-08 | ex-Guild Eagles   | W   | 0.002      | -            | -                | -                | -         |     0.02 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     4411 | 2024-02-08 | AMKAL             | L   | 0.001      | -            | -                | -                | -         |    -0.00 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,285.30)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.822 | $7,000.00      | $5,751.99       |
| 2024-05-04 |      0.574 | $2,000.00      | $1,148.70       |
| 2024-03-25 |      0.308 | $1,250.00      | $384.61         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
