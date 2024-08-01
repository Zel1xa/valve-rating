### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1194.6<br />
<br />
Final Rank Value (1194.6) = Starting Rank Value (1173.5) + Head To Head Adjustments (21.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.506[<sup>1</sup>](#table2)
- Bounty Collected: 0.418[<sup>2</sup>](#table1)
- Opponent Network: 0.144[<sup>2</sup>](#table1)
- LAN Wins: 0.436[<sup>2</sup>](#table1)

The average of these factors is 0.376<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1173.5
- 400 + ( ( 0.376 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1173.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           50 |      517 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -3.31 | aliStair, dexter, INS, Liazz, Vexite |
|           49 |      584 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.46 | aliStair, dexter, INS, Liazz, Vexite |
|           48 |     1152 | 2024-06-08 | Rooster            | W   | 0.844      | 0.333        | 0.010 (0.003)    | 0.281 (0.079)    | 0 (0.000) |     3.58 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |     1210 | 2024-06-08 | Mindfreak          | W   | 0.838      | 0.333        | 0.004 (0.001)    | 0.227 (0.063)    | -         |     1.92 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1270 | 2024-06-07 | Rooster            | L   | 0.831      | -            | -                | -                | -         |   -23.01 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1604 | 2024-05-28 | BIG                | L   | 0.767      | -            | -                | -                | -         |   -11.78 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1625 | 2024-05-27 | Spirit             | L   | 0.761      | -            | -                | -                | -         |    -0.53 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1764 | 2024-05-22 | Mindfreak          | W   | 0.725      | 0.333        | -                | 0.227 (0.055)    | -         |     1.27 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1769 | 2024-05-22 | Mindfreak          | W   | 0.724      | 0.333        | -                | 0.227 (0.055)    | -         |     1.29 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1849 | 2024-05-20 | Canon Event        | W   | 0.712      | -            | -                | -                | -         |     0.33 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1851 | 2024-05-20 | Canon Event        | W   | 0.712      | -            | -                | -                | -         |     0.33 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     2047 | 2024-05-15 | Vantage            | W   | 0.678      | -            | -                | -                | -         |     0.86 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     2048 | 2024-05-15 | Vantage            | W   | 0.678      | -            | -                | -                | -         |     0.87 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2237 | 2024-05-08 | Liquid             | L   | 0.633      | -            | -                | -                | -         |    -3.08 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2255 | 2024-05-07 | BetBoom            | W   | 0.626      | 0.889        | 0.257 (0.143)    | 0.551 (0.306)    | 1 (0.626) |    14.50 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2299 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.612      | 0.889        | 0.207 (0.113)    | 0.447 (0.243)    | 1 (0.612) |    15.95 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2315 | 2024-05-04 | PERA               | W   | 0.605      | 0.889        | 0.048 (0.026)    | 0.452 (0.243)    | 1 (0.605) |     3.36 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2331 | 2024-05-03 | HEROIC             | L   | 0.598      | -            | -                | -                | -         |    -2.03 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2359 | 2024-05-02 | BOSS               | W   | 0.592      | 0.889        | 0.014 (0.008)    | 0.334 (0.176)    | 1 (0.592) |     2.15 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2382 | 2024-05-01 | Natus Vincere      | L   | 0.585      | -            | -                | -                | -         |    -0.21 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2636 | 2024-04-20 | Bad News Kangaroos | W   | 0.512      | 0.143        | 0.017 (0.001)    | -                | -         |     1.56 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2683 | 2024-04-19 | Rooster            | W   | 0.505      | -            | -                | -                | -         |     1.72 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2690 | 2024-04-18 | Mindfreak          | W   | 0.504      | -            | -                | -                | -         |     0.96 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     2939 | 2024-04-10 | FaZe               | L   | 0.445      | -            | -                | -                | -         |    -0.68 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     2954 | 2024-04-09 | Nemiga             | W   | 0.443      | 0.624        | 0.324 (0.090)    | 0.697 (0.193)    | 1 (0.443) |     6.47 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     3004 | 2024-04-08 | Virtus.pro         | L   | 0.437      | -            | -                | -                | -         |    -0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3035 | 2024-04-08 | Cloud9             | W   | 0.431      | 0.624        | 0.067 (0.018)    | 0.117 (0.031)    | 1 (0.431) |     5.19 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3182 | 2024-04-03 | Arcade             | W   | 0.398      | -            | -                | -                | -         |     0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3187 | 2024-04-03 | Arcade             | W   | 0.398      | -            | -                | -                | -         |     0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3313 | 2024-03-27 | KZG                | W   | 0.352      | -            | -                | -                | -         |     0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3318 | 2024-03-27 | KZG                | W   | 0.351      | -            | -                | -                | -         |     0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3591 | 2024-03-13 | Rooster            | W   | 0.258      | 0.333        | 0.010 (0.001)    | -                | -         |     0.84 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3599 | 2024-03-13 | Rooster            | W   | 0.258      | -            | -                | -                | -         |     0.85 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3770 | 2024-03-06 | DXA                | W   | 0.212      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3772 | 2024-03-06 | DXA                | W   | 0.211      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3927 | 2024-02-27 | Lynn Vision        | L   | 0.164      | -            | -                | -                | -         |    -3.82 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3928 | 2024-02-27 | ATOX               | W   | 0.163      | -            | -                | -                | 1 (0.163) |     0.80 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     3951 | 2024-02-27 | JiJieHao           | W   | 0.158      | -            | -                | -                | 1 (0.158) |     0.07 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     3966 | 2024-02-25 | The MongolZ        | L   | 0.150      | -            | -                | -                | -         |    -0.06 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     3969 | 2024-02-25 | ATOX               | W   | 0.149      | -            | -                | -                | 1 (0.149) |     0.73 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     4036 | 2024-02-23 | Rooster            | W   | 0.131      | -            | -                | -                | -         |     0.42 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     4056 | 2024-02-22 | Rooster            | W   | 0.125      | -            | -                | -                | -         |     0.40 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     4060 | 2024-02-21 | Bad News Kangaroos | W   | 0.123      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     4082 | 2024-02-21 | Bad News Kangaroos | W   | 0.118      | -            | -                | -                | -         |     0.35 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     4088 | 2024-02-21 | Bad News Kangaroos | W   | 0.118      | -            | -                | -                | -         |     0.35 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4143 | 2024-02-18 | Mindfreak          | W   | 0.104      | -            | -                | -                | -         |     0.20 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4160 | 2024-02-18 | Arcade             | W   | 0.098      | -            | -                | -                | -         |     0.17 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4164 | 2024-02-18 | MANTRA             | W   | 0.098      | -            | -                | -                | -         |     0.07 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4165 | 2024-02-17 | Arcade             | W   | 0.096      | -            | -                | -                | -         |     0.17 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4187 | 2024-02-16 | GR                 | W   | 0.090      | -            | -                | -                | -         |     0.16 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($34,531.88)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.844 | $3,250.00      | $2,741.74       |
| 2024-06-02 |      0.800 | $4,000.00      | $3,201.11       |
| 2024-05-12 |      0.659 | $23,500.00     | $15,496.94      |
| 2024-04-14 |      0.472 | $6,000.00      | $2,829.31       |
| 2024-02-17 |      0.096 | $2,750.00      | $262.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
