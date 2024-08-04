### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [79](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
<br />
Final Rank Value:  941.7<br />
<br />
Final Rank Value (941.7) = Starting Rank Value (891.5) + Head To Head Adjustments (50.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.379[<sup>1</sup>](#table2)
- Bounty Collected: 0.368[<sup>2</sup>](#table1)
- Opponent Network: 0.215[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 891.5
- 400 + ( ( 0.240 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 891.5


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
|           54 |       15 | 2024-08-04 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|           53 |       55 | 2024-08-03 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|           52 |       84 | 2024-08-02 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -15.32 | faydett, FpSSS, Pipw, Polt, sugaR |
|           51 |      123 | 2024-08-01 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.72 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |      168 | 2024-07-31 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -6.78 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |      208 | 2024-07-30 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.90 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |      273 | 2024-07-28 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.68 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |      399 | 2024-07-24 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |    -8.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |      469 | 2024-07-22 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.74 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |      534 | 2024-07-20 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    15.20 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |      572 | 2024-07-19 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -17.14 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |      612 | 2024-07-18 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.509 (0.255)    | 0 (0.000) |    10.07 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |      732 | 2024-07-16 | KOI               | L   | 1.000      | -            | -                | -                | -         |    -9.89 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |      809 | 2024-07-14 | Permitta          | W   | 1.000      | 0.371        | 0.024 (0.009)    | 0.876 (0.325)    | 0 (0.000) |    15.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |      872 | 2024-07-10 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.80 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |      894 | 2024-07-09 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.57 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |      913 | 2024-07-08 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -27.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     1170 | 2024-06-10 | ARCRED            | W   | 0.834      | 0.372        | 0.041 (0.013)    | -                | 0 (0.000) |    10.87 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     1217 | 2024-06-09 | RUBY              | W   | 0.827      | 0.372        | 0.095 (0.029)    | 0.501 (0.154)    | 0 (0.000) |    10.63 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     1273 | 2024-06-08 | Zero Tenacity     | W   | 0.821      | 0.372        | 0.137 (0.042)    | 1.000 (0.305)    | 0 (0.000) |    17.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     1339 | 2024-06-07 | Aurora Young Blud | W   | 0.814      | 0.372        | -                | 0.460 (0.139)    | -         |     9.54 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     1542 | 2024-06-03 | RUBY              | L   | 0.787      | -            | -                | -                | -         |   -12.50 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     1599 | 2024-06-01 | 1WIN              | W   | 0.773      | 0.372        | 0.027 (0.008)    | 0.707 (0.203)    | -         |    14.58 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     1652 | 2024-05-30 | VP.Prodigy        | W   | 0.760      | 0.372        | 0.025 (0.007)    | -                | -         |    11.74 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     2308 | 2024-05-07 | RUBY              | L   | 0.607      | -            | -                | -                | -         |    -9.75 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     2327 | 2024-05-06 | Zero Tenacity     | L   | 0.600      | -            | -                | -                | -         |    -6.64 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     2331 | 2024-05-06 | BLEED             | L   | 0.598      | -            | -                | -                | -         |    -6.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     2376 | 2024-05-03 | Permitta          | W   | 0.580      | 0.435        | -                | 0.876 (0.221)    | -         |     8.72 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     2388 | 2024-05-03 | BetBoom           | L   | 0.578      | -            | -                | -                | -         |    -1.22 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     2423 | 2024-05-01 | OG                | W   | 0.567      | 0.435        | 0.139 (0.034)    | -                | -         |    12.04 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     2432 | 2024-05-01 | Nexus             | W   | 0.565      | -            | -                | -                | -         |     6.55 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     2474 | 2024-04-29 | HAVU              | L   | 0.552      | -            | -                | -                | -         |   -13.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     2510 | 2024-04-27 | ex-Guild Eagles   | W   | 0.540      | -            | -                | -                | -         |     6.69 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     2519 | 2024-04-27 | Permitta          | W   | 0.539      | 0.396        | -                | 0.876 (0.187)    | -         |     9.22 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     2538 | 2024-04-26 | ARCRED            | L   | 0.533      | -            | -                | -                | -         |    -9.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     2543 | 2024-04-26 | Enterprise        | W   | 0.532      | 0.396        | 0.039 (0.008)    | 0.625 (0.132)    | -         |     7.92 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     2579 | 2024-04-25 | MOUZ NXT          | W   | 0.524      | 0.435        | 0.139 (0.032)    | 1.000 (0.228)    | -         |    10.97 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     2604 | 2024-04-23 | EYEBALLERS        | W   | 0.513      | -            | -                | -                | -         |     7.48 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     2653 | 2024-04-21 | Permitta          | L   | 0.498      | -            | -                | -                | -         |    -6.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     3190 | 2024-04-03 | AMKAL             | L   | 0.381      | -            | -                | -                | -         |    -2.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     3231 | 2024-04-02 | ex-Guild Eagles   | W   | 0.374      | -            | -                | -                | -         |     4.35 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     3246 | 2024-04-02 | PARIVISION        | W   | 0.372      | -            | -                | -                | -         |     8.99 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     3473 | 2024-03-18 | Sashi             | L   | 0.273      | -            | -                | -                | -         |    -1.85 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     3532 | 2024-03-15 | CYBERSHOKE        | W   | 0.254      | -            | -                | -                | -         |     1.75 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     3604 | 2024-03-13 | INGLORIOUS        | W   | 0.240      | -            | -                | -                | -         |     0.91 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     3656 | 2024-03-11 | 1WIN              | W   | 0.227      | -            | -                | -                | -         |     3.82 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     3700 | 2024-03-09 | Fraud5            | W   | 0.213      | -            | -                | -                | -         |     1.35 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     3740 | 2024-03-07 | Sashi             | L   | 0.201      | -            | -                | -                | -         |    -1.26 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     3775 | 2024-03-06 | The Chosen Few    | W   | 0.194      | -            | -                | -                | -         |     1.38 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     3814 | 2024-03-05 | Johnny Speeds     | L   | 0.187      | -            | -                | -                | -         |    -0.54 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     3821 | 2024-03-05 | Betera            | W   | 0.187      | -            | -                | -                | -         |     1.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     4358 | 2024-02-09 | Sashi             | L   | 0.019      | -            | -                | -                | -         |    -0.11 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     4367 | 2024-02-08 | ex-Guild Eagles   | W   | 0.014      | -            | -                | -                | -         |     0.17 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     4373 | 2024-02-08 | AMKAL             | L   | 0.013      | -            | -                | -                | -         |    -0.08 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,410.34)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.834 | $7,000.00      | $5,837.38       |
| 2024-05-04 |      0.587 | $2,000.00      | $1,173.10       |
| 2024-03-25 |      0.320 | $1,250.00      | $399.86         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
