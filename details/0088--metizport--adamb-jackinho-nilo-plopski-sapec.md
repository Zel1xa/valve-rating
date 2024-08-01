### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, Plopski, Sapec<br />
Global Rank: [88](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  904.0<br />
<br />
Final Rank Value (904.0) = Starting Rank Value (905.2) + Head To Head Adjustments (-1.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.414[<sup>1</sup>](#table2)
- Bounty Collected: 0.384[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 905.2
- 400 + ( ( 0.246 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 905.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           67 |        4 | 2024-08-01 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.14 | adamb, Jackinho, nilo, Plopski, Sapec |
|           66 |      110 | 2024-07-30 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.63 | adamb, Jackinho, nilo, Plopski, Sapec |
|           65 |      157 | 2024-07-28 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.55 | adamb, Jackinho, nilo, Plopski, Sapec |
|           64 |      325 | 2024-07-23 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -16.66 | adamb, Jackinho, nilo, Plopski, Sapec |
|           63 |      344 | 2024-07-22 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.76 | adamb, Jackinho, nilo, Plopski, Sapec |
|           62 |      449 | 2024-07-19 | Sampi             | W   | 1.000      | 0.435        | 0.028 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.72 | adamb, Jackinho, nilo, Plopski, Sapec |
|           61 |      512 | 2024-07-18 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -25.74 | adamb, Jackinho, nilo, Plopski, Sapec |
|           60 |      633 | 2024-07-16 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.555 (0.241)    | 0 (0.000) |    12.65 | adamb, Jackinho, nilo, Plopski, Sapec |
|           59 |     1711 | 2024-05-23 | Space             | L   | 0.731      | -            | -                | -                | -         |   -14.74 | abdi, adamb, Jackinho, nilo, Plopski  |
|           58 |     1834 | 2024-05-20 | Zero Tenacity     | L   | 0.714      | -            | -                | -                | -         |    -8.74 | adamb, Jackinho, nilo, Plopski, ztr   |
|           57 |     1894 | 2024-05-18 | Ninjas in Pyjamas | W   | 0.700      | 0.500        | 0.207 (0.072)    | 0.447 (0.157)    | 0 (0.000) |    20.73 | adamb, Jackinho, nilo, Plopski, ztr   |
|           56 |     1981 | 2024-05-16 | Rare Atom         | W   | 0.685      | 0.500        | -                | 0.437 (0.150)    | 0 (0.000) |     3.40 | adamb, Jackinho, nilo, Plopski, ztr   |
|           55 |     2176 | 2024-05-11 | BetBoom           | L   | 0.652      | -            | -                | -                | -         |    -1.73 | adamb, Jackinho, nilo, Plopski, ztr   |
|           54 |     2190 | 2024-05-10 | EYEBALLERS        | W   | 0.646      | 0.435        | -                | 0.512 (0.144)    | 0 (0.000) |     8.91 | adamb, Jackinho, nilo, Plopski, ztr   |
|           53 |     2316 | 2024-05-04 | AMKAL             | L   | 0.605      | -            | -                | -                | -         |    -4.67 | adamb, Jackinho, nilo, susp, ztr      |
|           52 |     2332 | 2024-05-03 | Zero Tenacity     | W   | 0.598      | 0.435        | 0.139 (0.036)    | 1.000 (0.260)    | 0 (0.000) |    12.18 | adamb, Jackinho, nilo, susp, ztr      |
|           51 |     2353 | 2024-05-02 | Sangal            | W   | 0.593      | 0.435        | 0.221 (0.057)    | 0.823 (0.212)    | 0 (0.000) |    13.52 | adamb, Jackinho, nilo, susp, ztr      |
|           50 |     2516 | 2024-04-25 | Nexus             | L   | 0.547      | -            | -                | -                | -         |   -11.17 | adamb, Jackinho, nilo, susp, ztr      |
|           49 |     2560 | 2024-04-23 | Alliance          | W   | 0.532      | 0.384        | -                | 0.319 (0.065)    | 0 (0.000) |     6.76 | adamb, Jackinho, nilo, p1ke, susp     |
|           48 |     2675 | 2024-04-19 | FURIA             | L   | 0.506      | -            | -                | -                | -         |    -0.25 | adamb, Jackinho, Plopski, susp, ztr   |
|           47 |     2711 | 2024-04-18 | Imperial          | L   | 0.500      | -            | -                | -                | -         |    -1.91 | adamb, Jackinho, Plopski, susp, ztr   |
|           46 |     2994 | 2024-04-09 | ex-Guild Eagles   | L   | 0.439      | -            | -                | -                | -         |    -9.31 | adamb, Jackinho, nilo, susp, ztr      |
|           45 |     3009 | 2024-04-08 | Aurora            | L   | 0.434      | -            | -                | -                | -         |    -0.25 | adamb, Jackinho, nilo, susp, ztr      |
|           44 |     3020 | 2024-04-08 | 9 Pandas          | L   | 0.432      | -            | -                | -                | -         |    -5.86 | adamb, Jackinho, nilo, susp, ztr      |
|           43 |     3047 | 2024-04-07 | EYEBALLERS        | W   | 0.427      | 0.330        | -                | 0.512 (0.072)    | 0 (0.000) |     5.82 | adamb, Jackinho, nilo, susp, ztr      |
|           42 |     3056 | 2024-04-07 | Johnny Speeds     | W   | 0.425      | 0.330        | 0.124 (0.017)    | 0.819 (0.115)    | -         |    11.72 | adamb, Jackinho, nilo, susp, ztr      |
|           41 |     3072 | 2024-04-06 | Young Gods        | W   | 0.418      | -            | -                | -                | -         |     3.07 | adamb, Jackinho, nilo, susp, ztr      |
|           40 |     3127 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.406      | -            | -                | -                | -         |    -0.42 | adamb, Jackinho, nilo, susp, ztr      |
|           39 |     3157 | 2024-04-03 | Monte             | W   | 0.400      | -            | -                | -                | -         |     7.64 | adamb, Jackinho, nilo, susp, ztr      |
|           38 |     3170 | 2024-04-03 | FAVBET            | W   | 0.399      | -            | -                | -                | -         |     4.04 | adamb, Jackinho, nilo, susp, ztr      |
|           37 |     3204 | 2024-04-02 | B8                | W   | 0.393      | 0.143        | 0.168 (0.009)    | -                | -         |     8.95 | adamb, Jackinho, nilo, susp, ztr      |
|           36 |     3212 | 2024-04-02 | Aurora            | L   | 0.392      | -            | -                | -                | -         |    -0.18 | adamb, Jackinho, nilo, susp, ztr      |
|           35 |     3226 | 2024-04-01 | PARIVISION        | L   | 0.386      | -            | -                | -                | -         |    -3.14 | adamb, Jackinho, nilo, susp, ztr      |
|           34 |     3295 | 2024-03-27 | Aurora            | L   | 0.354      | -            | -                | -                | -         |    -0.16 | adamb, Jackinho, nilo, susp, ztr      |
|           33 |     3301 | 2024-03-27 | NAVI Junior       | W   | 0.354      | -            | -                | -                | -         |     2.48 | adamb, Jackinho, nilo, susp, ztr      |
|           32 |     3508 | 2024-03-15 | kONO              | L   | 0.273      | -            | -                | -                | -         |    -5.59 | adamb, Jackinho, nilo, susp, ztr      |
|           31 |     3549 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.266      | -            | -                | -                | -         |    -3.61 | adamb, Jackinho, nilo, susp, ztr      |
|           30 |     3584 | 2024-03-13 | HEROIC            | L   | 0.259      | -            | -                | -                | -         |    -0.22 | adamb, Jackinho, nilo, susp, ztr      |
|           29 |     3608 | 2024-03-12 | B8                | W   | 0.254      | 0.143        | 0.168 (0.006)    | -                | -         |     5.87 | adamb, Jackinho, nilo, susp, ztr      |
|           28 |     3616 | 2024-03-12 | Apeks             | W   | 0.253      | -            | -                | -                | -         |     4.08 | adamb, Jackinho, nilo, susp, ztr      |
|           27 |     3627 | 2024-03-11 | ex-Preasy         | W   | 0.247      | -            | -                | -                | -         |     2.80 | adamb, Jackinho, nilo, susp, ztr      |
|           26 |     3638 | 2024-03-11 | ENCE              | L   | 0.246      | -            | -                | -                | -         |    -0.31 | adamb, Jackinho, nilo, susp, ztr      |
|           25 |     3648 | 2024-03-10 | Spirit            | L   | 0.241      | -            | -                | -                | -         |    -0.03 | adamb, Jackinho, nilo, susp, ztr      |
|           24 |     3676 | 2024-03-09 | Monte             | W   | 0.233      | 0.535        | 0.062 (0.008)    | -                | -         |     4.71 | adamb, Jackinho, nilo, susp, ztr      |
|           23 |     3681 | 2024-03-09 | EYEBALLERS        | L   | 0.233      | -            | -                | -                | -         |    -3.70 | adamb, Jackinho, nilo, susp, ztr      |
|           22 |     3686 | 2024-03-09 | Lemondogs         | W   | 0.232      | -            | -                | -                | -         |     0.39 | adamb, Jackinho, nilo, susp, ztr      |
|           21 |     3706 | 2024-03-08 | Secret            | W   | 0.226      | -            | -                | -                | -         |     0.78 | adamb, Jackinho, nilo, susp, ztr      |
|           20 |     3747 | 2024-03-06 | Falcons           | W   | 0.214      | 0.535        | 0.205 (0.024)    | -                | -         |     6.41 | adamb, Jackinho, nilo, susp, ztr      |
|           19 |     3833 | 2024-03-03 | The Chosen Few    | W   | 0.194      | -            | -                | -                | -         |     1.34 | adamb, Jackinho, nilo, susp, ztr      |
|           18 |     3839 | 2024-03-03 | ILIN              | W   | 0.194      | -            | -                | -                | -         |     0.35 | adamb, Jackinho, nilo, susp, ztr      |
|           17 |     3844 | 2024-03-03 | RUSH B            | W   | 0.193      | -            | -                | -                | -         |     2.56 | adamb, Jackinho, nilo, susp, ztr      |
|           16 |     3855 | 2024-03-03 | ECLOT             | L   | 0.192      | -            | -                | -                | -         |    -1.44 | adamb, Jackinho, nilo, susp, ztr      |
|           15 |     3904 | 2024-02-29 | Endpoint          | W   | 0.172      | -            | -                | -                | -         |     2.79 | adamb, Jackinho, nilo, susp, ztr      |
|           14 |     3940 | 2024-02-27 | ex-Guild Eagles   | L   | 0.160      | -            | -                | -                | -         |    -3.06 | adamb, Jackinho, nilo, susp, ztr      |
|           13 |     4188 | 2024-02-16 | ex-Anonymo        | L   | 0.090      | -            | -                | -                | -         |    -2.56 | adamb, Jackinho, nilo, susp, ztr      |
|           12 |     4329 | 2024-02-11 | Apeks             | W   | 0.054      | -            | -                | -                | -         |     0.88 | adamb, Jackinho, nilo, susp, ztr      |
|           11 |     4330 | 2024-02-11 | Alliance          | L   | 0.054      | -            | -                | -                | -         |    -0.98 | adamb, Jackinho, nilo, susp, ztr      |
|           10 |     4335 | 2024-02-11 | ex-Sprout         | W   | 0.052      | -            | -                | -                | -         |     0.17 | adamb, Jackinho, nilo, susp, ztr      |
|            9 |     4342 | 2024-02-10 | FURIA             | W   | 0.047      | -            | -                | -                | -         |     1.46 | adamb, Jackinho, nilo, susp, ztr      |
|            8 |     4345 | 2024-02-10 | Apeks             | L   | 0.046      | -            | -                | -                | -         |    -0.70 | adamb, Jackinho, nilo, susp, ztr      |
|            7 |     4347 | 2024-02-10 | FURIA             | W   | 0.046      | -            | -                | -                | -         |     1.43 | adamb, Jackinho, nilo, susp, ztr      |
|            6 |     4383 | 2024-02-07 | ex-Sprout         | W   | 0.026      | -            | -                | -                | -         |     0.09 | adamb, Jackinho, nilo, susp, ztr      |
|            5 |     4391 | 2024-02-06 | Into the Breach   | L   | 0.019      | -            | -                | -                | -         |    -0.52 | adamb, Jackinho, nilo, susp, ztr      |
|            4 |     4404 | 2024-02-05 | TSM               | L   | 0.012      | -            | -                | -                | -         |    -0.30 | adamb, Jackinho, nilo, susp, ztr      |
|            3 |     4411 | 2024-02-04 | 500               | L   | 0.007      | -            | -                | -                | -         |    -0.17 | adamb, Jackinho, nilo, susp, ztr      |
|            2 |     4415 | 2024-02-04 | TMVG              | W   | 0.007      | -            | -                | -                | -         |     0.02 | adamb, Jackinho, nilo, susp, ztr      |
|            1 |     4428 | 2024-02-04 | DUSTY             | W   | 0.005      | -            | -                | -                | -         |     0.03 | adamb, Jackinho, nilo, susp, ztr      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,538.31)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.660 | $2,000.00      | $1,319.86       |
| 2024-05-04 |      0.606 | $5,000.00      | $3,031.94       |
| 2024-04-20 |      0.514 | $5,000.00      | $2,571.76       |
| 2024-04-07 |      0.427 | $6,110.00      | $2,606.93       |
| 2024-03-10 |      0.241 | $12,500.00     | $3,007.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
