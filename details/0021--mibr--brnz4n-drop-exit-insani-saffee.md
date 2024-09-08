### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1329.4<br />
<br />
Final Rank Value (1329.4) = Starting Rank Value (1377.7) + Head To Head Adjustments (-48.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.553[<sup>1</sup>](#table2)
- Bounty Collected: 0.574[<sup>2</sup>](#table1)
- Opponent Network: 0.317[<sup>2</sup>](#table1)
- LAN Wins: 0.575[<sup>2</sup>](#table1)

The average of these factors is 0.505<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1377.7
- 400 + ( ( 0.505 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1377.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           85 |       90 | 2024-09-05 | Spirit         | W   | 1.000      | 0.889        | 1.000 (0.889)    | 0.557 (0.495)    | 1 (1.000) |    30.56 | brnz4n, drop, exit, insani, saffee |
|           84 |      143 | 2024-09-03 | 9z             | W   | 1.000      | 0.889        | 0.362 (0.322)    | 0.530 (0.471)    | 1 (1.000) |    20.72 | brnz4n, drop, exit, insani, saffee |
|           83 |      607 | 2024-08-21 | Hype           | W   | 1.000      | -            | -                | -                | -         |     2.11 | brnz4n, drop, exit, insani, saffee |
|           82 |      610 | 2024-08-21 | Hype           | W   | 1.000      | -            | -                | -                | -         |     2.15 | brnz4n, drop, exit, insani, saffee |
|           81 |      858 | 2024-08-13 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |   -26.36 | brnz4n, drop, exit, insani, saffee |
|           80 |      862 | 2024-08-13 | BESTIA         | W   | 1.000      | 0.450        | -                | 0.807 (0.363)    | -         |     4.66 | brnz4n, drop, exit, insani, saffee |
|           79 |      995 | 2024-08-09 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -6.68 | brnz4n, drop, exit, insani, saffee |
|           78 |     1008 | 2024-08-09 | 9z             | L   | 1.000      | -            | -                | -                | -         |   -10.35 | brnz4n, drop, exit, insani, saffee |
|           77 |     1077 | 2024-08-07 | HEROIC         | W   | 0.986      | -            | -                | -                | 1 (0.986) |    19.82 | brnz4n, drop, exit, insani, saffee |
|           76 |     1223 | 2024-08-02 | paiN           | L   | 0.956      | -            | -                | -                | -         |    -6.39 | brnz4n, drop, exit, insani, saffee |
|           75 |     1225 | 2024-08-02 | ODDIK          | L   | 0.955      | -            | -                | -                | -         |   -24.09 | brnz4n, drop, exit, insani, saffee |
|           74 |     1239 | 2024-08-02 | Fluxo          | W   | 0.954      | 0.371        | -                | 0.649 (0.229)    | -         |     6.99 | brnz4n, drop, exit, insani, saffee |
|           73 |     1266 | 2024-08-01 | ODDIK          | W   | 0.949      | 0.371        | 0.190 (0.067)    | 0.839 (0.295)    | -         |     5.50 | brnz4n, drop, exit, insani, saffee |
|           72 |     1313 | 2024-07-31 | Sharks         | W   | 0.942      | -            | -                | -                | -         |     4.71 | brnz4n, drop, exit, insani, saffee |
|           71 |     1319 | 2024-07-31 | ODDIK          | W   | 0.941      | 0.450        | 0.190 (0.080)    | 0.839 (0.355)    | -         |     5.93 | brnz4n, drop, exit, insani, saffee |
|           70 |     1324 | 2024-07-31 | ODDIK          | W   | 0.941      | 0.450        | 0.190 (0.080)    | 0.839 (0.355)    | -         |     6.25 | brnz4n, drop, exit, insani, saffee |
|           69 |     1352 | 2024-07-30 | Dusty Roots    | L   | 0.936      | -            | -                | -                | -         |   -28.19 | brnz4n, drop, exit, insani, saffee |
|           68 |     1357 | 2024-07-30 | Dusty Roots    | W   | 0.936      | -            | -                | -                | -         |     1.15 | brnz4n, drop, exit, insani, saffee |
|           67 |     1361 | 2024-07-30 | 9z Academy     | W   | 0.935      | -            | -                | -                | -         |     0.29 | brnz4n, drop, exit, insani, saffee |
|           66 |     1397 | 2024-07-29 | Imperial       | L   | 0.928      | -            | -                | -                | -         |   -22.00 | brnz4n, drop, exit, insani, saffee |
|           65 |     1422 | 2024-07-28 | RED Canids     | W   | 0.923      | -            | -                | -                | -         |     5.66 | brnz4n, drop, exit, insani, saffee |
|           64 |     1428 | 2024-07-28 | Imperial       | L   | 0.922      | -            | -                | -                | -         |   -22.89 | brnz4n, drop, exit, insani, saffee |
|           63 |     1518 | 2024-07-25 | Galorys        | W   | 0.902      | -            | -                | -                | -         |     1.06 | brnz4n, drop, exit, insani, saffee |
|           62 |     1519 | 2024-07-25 | Galorys        | W   | 0.902      | -            | -                | -                | -         |     1.07 | brnz4n, drop, exit, insani, saffee |
|           61 |     1782 | 2024-07-18 | The MongolZ    | L   | 0.853      | -            | -                | -                | -         |    -2.45 | brnz4n, drop, exit, insani, saffee |
|           60 |     1834 | 2024-07-17 | Spirit         | L   | 0.848      | -            | -                | -                | -         |    -0.85 | brnz4n, drop, exit, insani, saffee |
|           59 |     2207 | 2024-06-15 | Complexity     | L   | 0.633      | -            | -                | -                | -         |    -6.57 | brnz4n, drop, exit, insani, saffee |
|           58 |     2233 | 2024-06-14 | Alliance       | W   | 0.628      | -            | -                | -                | 1 (0.628) |     0.92 | brnz4n, drop, exit, insani, saffee |
|           57 |     2246 | 2024-06-14 | ENCE           | L   | 0.627      | -            | -                | -                | -         |   -14.60 | brnz4n, drop, exit, insani, saffee |
|           56 |     2488 | 2024-06-07 | Bounty Hunters | L   | 0.583      | -            | -                | -                | -         |   -17.55 | brnz4n, drop, exit, insani, saffee |
|           55 |     2549 | 2024-06-06 | 9z             | L   | 0.576      | -            | -                | -                | -         |    -8.42 | brnz4n, drop, exit, insani, saffee |
|           54 |     2617 | 2024-06-05 | BESTIA         | W   | 0.569      | 0.450        | -                | 0.807 (0.207)    | -         |     1.67 | brnz4n, drop, exit, insani, saffee |
|           53 |     2671 | 2024-06-04 | Galorys        | W   | 0.563      | -            | -                | -                | -         |     0.49 | brnz4n, drop, exit, insani, saffee |
|           52 |     2995 | 2024-05-22 | paiN           | W   | 0.475      | 0.450        | 0.420 (0.090)    | 0.935 (0.200)    | -         |    11.09 | brnz4n, drop, exit, insani, saffee |
|           51 |     2999 | 2024-05-22 | paiN           | W   | 0.475      | 0.450        | 0.420 (0.090)    | -                | -         |    11.44 | brnz4n, drop, exit, insani, saffee |
|           50 |     3073 | 2024-05-20 | BetBoom        | L   | 0.462      | -            | -                | -                | -         |   -10.33 | brnz4n, drop, exit, insani, saffee |
|           49 |     3084 | 2024-05-20 | BIG            | W   | 0.460      | 0.769        | 0.146 (0.052)    | -                | -         |     3.65 | brnz4n, drop, exit, insani, saffee |
|           48 |     3093 | 2024-05-20 | BetBoom        | L   | 0.459      | -            | -                | -                | -         |   -10.51 | brnz4n, drop, exit, insani, saffee |
|           47 |     3170 | 2024-05-17 | HEROIC         | L   | 0.441      | -            | -                | -                | -         |    -7.05 | brnz4n, drop, exit, insani, saffee |
|           46 |     3203 | 2024-05-16 | Aurora         | W   | 0.435      | 0.769        | 0.290 (0.097)    | 0.603 (0.201)    | 1 (0.435) |     6.27 | brnz4n, drop, exit, insani, saffee |
|           45 |     3261 | 2024-05-15 | HEROIC         | L   | 0.427      | -            | -                | -                | -         |    -6.96 | brnz4n, drop, exit, insani, saffee |
|           44 |     3667 | 2024-04-28 | Aurora         | W   | 0.312      | -            | -                | -                | 1 (0.312) |     4.78 | brnz4n, drop, exit, insani, saffee |
|           43 |     3670 | 2024-04-27 | Apeks          | W   | 0.311      | -            | -                | -                | 1 (0.311) |     0.31 | brnz4n, drop, exit, insani, saffee |
|           42 |     3696 | 2024-04-26 | Rooster        | W   | 0.305      | -            | -                | -                | 1 (0.305) |     0.22 | brnz4n, drop, exit, insani, saffee |
|           41 |     3719 | 2024-04-26 | Rebels         | L   | 0.299      | -            | -                | -                | -         |    -8.82 | brnz4n, drop, exit, insani, saffee |
|           40 |     3722 | 2024-04-25 | KZG            | W   | 0.297      | -            | -                | -                | 1 (0.297) |     0.13 | brnz4n, drop, exit, insani, saffee |
|           39 |     3832 | 2024-04-20 | paiN           | L   | 0.261      | -            | -                | -                | -         |    -1.73 | brnz4n, drop, exit, insani, saffee |
|           38 |     3841 | 2024-04-20 | OG             | W   | 0.260      | -            | -                | -                | 1 (0.260) |     0.67 | brnz4n, drop, exit, insani, saffee |
|           37 |     3854 | 2024-04-19 | paiN           | W   | 0.257      | -            | -                | -                | -         |     6.54 | brnz4n, drop, exit, insani, saffee |
|           36 |     3861 | 2024-04-19 | FURIA          | W   | 0.256      | 0.589        | 0.319 (0.048)    | -                | -         |     6.26 | brnz4n, drop, exit, insani, saffee |
|           35 |     3880 | 2024-04-19 | paiN           | L   | 0.254      | -            | -                | -                | -         |    -1.51 | brnz4n, drop, exit, insani, saffee |
|           34 |     3902 | 2024-04-18 | Imperial       | W   | 0.250      | -            | -                | -                | -         |     1.14 | brnz4n, drop, exit, insani, saffee |
|           33 |     3907 | 2024-04-18 | paiN           | W   | 0.249      | -            | -                | -                | -         |     6.45 | brnz4n, drop, exit, insani, saffee |
|           32 |     3911 | 2024-04-18 | OG             | W   | 0.249      | -            | -                | -                | -         |     0.67 | brnz4n, drop, exit, insani, saffee |
|           31 |     3956 | 2024-04-17 | RED Canids     | W   | 0.243      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           30 |     3962 | 2024-04-17 | Case           | W   | 0.242      | -            | -                | -                | -         |     0.59 | brnz4n, drop, exit, insani, saffee |
|           29 |     4001 | 2024-04-16 | Bounty Hunters | W   | 0.236      | -            | -                | -                | -         |     0.32 | brnz4n, drop, exit, insani, saffee |
|           28 |     4022 | 2024-04-15 | Imperial       | W   | 0.229      | -            | -                | -                | -         |     1.05 | brnz4n, drop, exit, insani, saffee |
|           27 |     4036 | 2024-04-14 | Galorys        | W   | 0.222      | -            | -                | -                | -         |     0.18 | brnz4n, drop, exit, insani, saffee |
|           26 |     4050 | 2024-04-13 | Case           | W   | 0.214      | -            | -                | -                | -         |     0.52 | brnz4n, drop, exit, insani, saffee |
|           25 |     4081 | 2024-04-11 | paiN           | W   | 0.203      | -            | -                | -                | -         |     5.36 | brnz4n, drop, exit, insani, saffee |
|           24 |     4119 | 2024-04-10 | Galorys        | W   | 0.196      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           23 |     4123 | 2024-04-10 | Galorys        | W   | 0.196      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           22 |     4140 | 2024-04-10 | Imperial       | W   | 0.194      | -            | -                | -                | -         |     0.91 | brnz4n, drop, exit, insani, saffee |
|           21 |     4171 | 2024-04-09 | adalYamigos    | W   | 0.190      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|           20 |     4176 | 2024-04-09 | adalYamigos    | W   | 0.189      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|           19 |     4183 | 2024-04-09 | RED Canids     | W   | 0.188      | -            | -                | -                | -         |     0.55 | brnz4n, drop, exit, insani, saffee |
|           18 |     4213 | 2024-04-08 | W7M            | W   | 0.183      | -            | -                | -                | -         |     0.20 | brnz4n, drop, exit, insani, saffee |
|           17 |     4247 | 2024-04-07 | paiN           | W   | 0.176      | -            | -                | -                | -         |     4.73 | brnz4n, drop, exit, insani, saffee |
|           16 |     4264 | 2024-04-06 | Bounty Hunters | W   | 0.169      | -            | -                | -                | -         |     0.25 | brnz4n, drop, exit, insani, saffee |
|           15 |     4281 | 2024-04-05 | Fluxo          | W   | 0.163      | -            | -                | -                | -         |     0.14 | brnz4n, drop, exit, insani, saffee |
|           14 |     4282 | 2024-04-05 | Fluxo          | L   | 0.163      | -            | -                | -                | -         |    -4.99 | brnz4n, drop, exit, insani, saffee |
|           13 |     4285 | 2024-04-05 | ODDIK          | W   | 0.162      | -            | -                | -                | -         |     1.00 | brnz4n, drop, exit, insani, saffee |
|           12 |     4306 | 2024-04-04 | Solid          | W   | 0.156      | -            | -                | -                | -         |     0.23 | brnz4n, drop, exit, insani, saffee |
|           11 |     4312 | 2024-04-04 | Solid          | W   | 0.156      | -            | -                | -                | -         |     0.23 | brnz4n, drop, exit, insani, saffee |
|           10 |     4345 | 2024-04-03 | Fluxo          | W   | 0.150      | -            | -                | -                | -         |     0.12 | brnz4n, drop, exit, insani, saffee |
|            9 |     4393 | 2024-04-02 | Fluxo          | W   | 0.143      | -            | -                | -                | -         |     0.11 | brnz4n, drop, exit, insani, saffee |
|            8 |     4396 | 2024-04-02 | Sharks         | W   | 0.142      | -            | -                | -                | -         |     0.11 | brnz4n, drop, exit, insani, saffee |
|            7 |     4482 | 2024-03-27 | Case           | W   | 0.103      | -            | -                | -                | -         |     0.28 | brnz4n, drop, exit, insani, saffee |
|            6 |     4488 | 2024-03-27 | Case           | W   | 0.103      | -            | -                | -                | -         |     0.28 | brnz4n, drop, exit, insani, saffee |
|            5 |     4528 | 2024-03-26 | ODDIK          | W   | 0.096      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|            4 |     4530 | 2024-03-26 | ODDIK          | W   | 0.096      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|            3 |     4722 | 2024-03-14 | Sharks         | W   | 0.016      | -            | -                | -                | -         |     0.07 | brnz4n, drop, exit, insani, saffee |
|            2 |     4724 | 2024-03-14 | Sharks         | W   | 0.016      | -            | -                | -                | -         |     0.07 | brnz4n, drop, exit, insani, saffee |
|            1 |     4796 | 2024-03-12 | Fluxo          | L   | 0.002      | -            | -                | -                | -         |    -0.06 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($47,349.44)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-09 |      1.000 | $4,500.00      | $4,500.00       |
| 2024-08-02 |      0.956 | $4,000.00      | $3,823.70       |
| 2024-07-21 |      0.875 | $10,000.00     | $8,747.22       |
| 2024-06-16 |      0.640 | $3,000.00      | $1,920.83       |
| 2024-06-09 |      0.595 | $3,000.00      | $1,786.39       |
| 2024-04-28 |      0.312 | $50,000.00     | $15,613.43      |
| 2024-04-20 |      0.262 | $20,000.00     | $5,242.59       |
| 2024-04-15 |      0.229 | $25,000.00     | $5,715.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
