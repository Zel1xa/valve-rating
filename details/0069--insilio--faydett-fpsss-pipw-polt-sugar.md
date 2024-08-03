### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [69](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  954.5<br />
<br />
Final Rank Value (954.5) = Starting Rank Value (893.2) + Head To Head Adjustments (61.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.379[<sup>1</sup>](#table2)
- Bounty Collected: 0.368[<sup>2</sup>](#table1)
- Opponent Network: 0.217[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.241<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 893.2
- 400 + ( ( 0.241 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 893.2


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
|           53 |       19 | 2024-08-03 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.34 | faydett, FpSSS, Pipw, Polt, sugaR |
|           52 |       43 | 2024-08-02 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -15.39 | faydett, FpSSS, Pipw, Polt, sugaR |
|           51 |       66 | 2024-08-01 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.07 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |      110 | 2024-07-31 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -6.82 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |      150 | 2024-07-30 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.92 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |      215 | 2024-07-28 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.48 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |      341 | 2024-07-24 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |    -8.96 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |      411 | 2024-07-22 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.29 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |      476 | 2024-07-20 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    14.92 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |      514 | 2024-07-19 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -16.86 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |      554 | 2024-07-18 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.528 (0.264)    | 0 (0.000) |    10.32 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |      671 | 2024-07-16 | KOI               | L   | 1.000      | -            | -                | -                | -         |   -15.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |      746 | 2024-07-14 | Permitta          | W   | 1.000      | 0.371        | 0.024 (0.009)    | 0.887 (0.328)    | 0 (0.000) |    15.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |      806 | 2024-07-10 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.80 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |      828 | 2024-07-09 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |      847 | 2024-07-08 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -27.80 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     1080 | 2024-06-10 | ARCRED            | W   | 0.840      | 0.372        | 0.041 (0.013)    | -                | 0 (0.000) |    11.03 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     1127 | 2024-06-09 | RUBY              | W   | 0.833      | 0.372        | 0.095 (0.030)    | 0.520 (0.161)    | 0 (0.000) |    10.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     1181 | 2024-06-08 | Zero Tenacity     | W   | 0.827      | 0.372        | 0.137 (0.042)    | 1.000 (0.308)    | 0 (0.000) |    17.69 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     1244 | 2024-06-07 | Aurora Young Blud | W   | 0.820      | 0.372        | -                | 0.433 (0.132)    | -         |     9.04 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     1445 | 2024-06-03 | RUBY              | L   | 0.794      | -            | -                | -                | -         |   -12.45 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     1500 | 2024-06-01 | 1WIN              | W   | 0.779      | 0.372        | 0.027 (0.008)    | 0.650 (0.189)    | -         |    14.05 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     1553 | 2024-05-30 | VP.Prodigy        | W   | 0.767      | 0.372        | 0.026 (0.007)    | -                | -         |    11.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     2206 | 2024-05-07 | RUBY              | L   | 0.613      | -            | -                | -                | -         |    -9.70 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     2225 | 2024-05-06 | Zero Tenacity     | L   | 0.606      | -            | -                | -                | -         |    -6.88 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     2229 | 2024-05-06 | BLEED             | L   | 0.605      | -            | -                | -                | -         |    -6.40 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     2274 | 2024-05-03 | Permitta          | W   | 0.586      | 0.435        | -                | 0.887 (0.226)    | -         |     8.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     2286 | 2024-05-03 | BetBoom           | L   | 0.584      | -            | -                | -                | -         |    -1.25 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     2321 | 2024-05-01 | OG                | W   | 0.573      | 0.435        | 0.140 (0.035)    | -                | -         |    11.94 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     2330 | 2024-05-01 | Nexus             | W   | 0.572      | -            | -                | -                | -         |     6.64 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     2372 | 2024-04-29 | HAVU              | L   | 0.559      | -            | -                | -                | -         |   -13.99 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     2408 | 2024-04-27 | ex-Guild Eagles   | W   | 0.547      | -            | -                | -                | -         |     6.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     2417 | 2024-04-27 | Permitta          | W   | 0.546      | 0.396        | -                | 0.887 (0.192)    | -         |     9.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     2436 | 2024-04-26 | ARCRED            | L   | 0.539      | -            | -                | -                | -         |    -9.76 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     2440 | 2024-04-26 | Enterprise        | W   | 0.539      | 0.396        | 0.039 (0.008)    | 0.646 (0.138)    | -         |     8.01 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     2476 | 2024-04-25 | MOUZ NXT          | W   | 0.531      | 0.435        | 0.139 (0.032)    | 1.000 (0.231)    | -         |    10.95 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     2501 | 2024-04-23 | EYEBALLERS        | W   | 0.520      | -            | -                | -                | -         |     7.55 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     2550 | 2024-04-21 | Permitta          | L   | 0.504      | -            | -                | -                | -         |    -6.88 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     3087 | 2024-04-03 | AMKAL             | L   | 0.387      | -            | -                | -                | -         |    -2.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     3128 | 2024-04-02 | ex-Guild Eagles   | W   | 0.380      | -            | -                | -                | -         |     4.46 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     3143 | 2024-04-02 | PARIVISION        | W   | 0.379      | -            | -                | -                | -         |     9.16 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     3365 | 2024-03-18 | Sashi             | L   | 0.279      | -            | -                | -                | -         |    -1.91 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     3423 | 2024-03-15 | CYBERSHOKE        | W   | 0.260      | -            | -                | -                | -         |     1.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     3494 | 2024-03-13 | INGLORIOUS        | W   | 0.246      | -            | -                | -                | -         |     0.92 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     3545 | 2024-03-11 | 1WIN              | W   | 0.233      | -            | -                | -                | -         |     3.64 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     3589 | 2024-03-09 | Fraud5            | W   | 0.219      | -            | -                | -                | -         |     1.39 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     3629 | 2024-03-07 | Sashi             | L   | 0.207      | -            | -                | -                | -         |    -1.32 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     3664 | 2024-03-06 | The Chosen Few    | W   | 0.200      | -            | -                | -                | -         |     1.42 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     3703 | 2024-03-05 | Johnny Speeds     | L   | 0.194      | -            | -                | -                | -         |    -0.58 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     3710 | 2024-03-05 | Betera            | W   | 0.193      | -            | -                | -                | -         |     1.52 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     4246 | 2024-02-09 | Sashi             | L   | 0.026      | -            | -                | -                | -         |    -0.15 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     4255 | 2024-02-08 | ex-Guild Eagles   | W   | 0.020      | -            | -                | -                | -         |     0.25 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     4261 | 2024-02-08 | AMKAL             | L   | 0.019      | -            | -                | -                | -         |    -0.12 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,477.49)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.840 | $7,000.00      | $5,883.24       |
| 2024-05-04 |      0.593 | $2,000.00      | $1,186.20       |
| 2024-03-25 |      0.326 | $1,250.00      | $408.04         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
