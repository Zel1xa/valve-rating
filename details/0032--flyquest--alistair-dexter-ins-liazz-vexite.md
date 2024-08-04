### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1182.1<br />
<br />
Final Rank Value (1182.1) = Starting Rank Value (1156.4) + Head To Head Adjustments (25.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.504[<sup>1</sup>](#table2)
- Bounty Collected: 0.418[<sup>2</sup>](#table1)
- Opponent Network: 0.144[<sup>2</sup>](#table1)
- LAN Wins: 0.413[<sup>2</sup>](#table1)

The average of these factors is 0.370<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1156.4
- 400 + ( ( 0.370 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1156.4


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
|           48 |      600 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -3.04 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |      667 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.51 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1235 | 2024-06-08 | Rooster            | W   | 0.825      | 0.333        | 0.010 (0.003)    | 0.251 (0.069)    | 0 (0.000) |     3.65 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1290 | 2024-06-08 | Mindfreak          | W   | 0.819      | 0.333        | 0.004 (0.001)    | 0.227 (0.062)    | -         |     2.07 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1345 | 2024-06-07 | Rooster            | L   | 0.812      | -            | -                | -                | -         |   -22.35 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1673 | 2024-05-28 | BIG                | L   | 0.749      | -            | -                | -                | -         |    -8.97 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1694 | 2024-05-27 | Spirit             | L   | 0.742      | -            | -                | -                | -         |    -0.49 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1821 | 2024-05-22 | Mindfreak          | W   | 0.706      | 0.333        | 0.004 (0.001)    | 0.227 (0.053)    | -         |     1.38 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1826 | 2024-05-22 | Mindfreak          | W   | 0.706      | 0.333        | -                | 0.227 (0.053)    | -         |     1.40 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     1896 | 2024-05-20 | Canon Event        | W   | 0.693      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     1898 | 2024-05-20 | Canon Event        | W   | 0.693      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2267 | 2024-05-08 | Liquid             | L   | 0.614      | -            | -                | -                | -         |    -2.09 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2285 | 2024-05-07 | BetBoom            | W   | 0.607      | 0.889        | 0.251 (0.135)    | 0.541 (0.292)    | 1 (0.607) |    14.25 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2329 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.593      | 0.889        | 0.255 (0.134)    | 0.553 (0.292)    | 1 (0.593) |    17.04 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2345 | 2024-05-04 | PERA               | W   | 0.586      | 0.889        | 0.048 (0.025)    | 0.453 (0.236)    | 1 (0.586) |     3.55 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2361 | 2024-05-03 | HEROIC             | L   | 0.580      | -            | -                | -                | -         |    -1.83 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2388 | 2024-05-02 | BOSS               | W   | 0.573      | 0.889        | 0.014 (0.007)    | 0.333 (0.169)    | 1 (0.573) |     2.15 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2410 | 2024-05-01 | Natus Vincere      | L   | 0.566      | -            | -                | -                | -         |    -0.20 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2657 | 2024-04-20 | Bad News Kangaroos | W   | 0.493      | 0.143        | 0.017 (0.001)    | -                | -         |     1.69 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2703 | 2024-04-19 | Rooster            | W   | 0.486      | -            | -                | -                | -         |     1.74 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2710 | 2024-04-18 | Mindfreak          | W   | 0.485      | -            | -                | -                | -         |     1.04 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     2955 | 2024-04-10 | FaZe               | L   | 0.426      | -            | -                | -                | -         |    -0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     2970 | 2024-04-09 | Nemiga             | W   | 0.425      | 0.624        | 0.317 (0.084)    | 0.695 (0.184)    | 1 (0.425) |     6.30 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     3020 | 2024-04-08 | Virtus.pro         | L   | 0.418      | -            | -                | -                | -         |    -0.64 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3051 | 2024-04-08 | Cloud9             | W   | 0.412      | 0.624        | 0.062 (0.016)    | 0.111 (0.028)    | 1 (0.412) |     4.81 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3192 | 2024-04-03 | Arcade             | W   | 0.379      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3197 | 2024-04-03 | Arcade             | W   | 0.379      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3320 | 2024-03-27 | KZG                | W   | 0.333      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3325 | 2024-03-27 | KZG                | W   | 0.333      | -            | -                | -                | -         |     0.71 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3590 | 2024-03-13 | Rooster            | W   | 0.239      | -            | -                | -                | -         |     0.83 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3598 | 2024-03-13 | Rooster            | W   | 0.239      | -            | -                | -                | -         |     0.84 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3767 | 2024-03-06 | DXA                | W   | 0.193      | -            | -                | -                | -         |     0.42 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3769 | 2024-03-06 | DXA                | W   | 0.193      | -            | -                | -                | -         |     0.42 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3917 | 2024-02-27 | Lynn Vision        | L   | 0.145      | -            | -                | -                | -         |    -3.00 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3918 | 2024-02-27 | ATOX               | W   | 0.144      | -            | -                | -                | 1 (0.144) |     0.74 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     3939 | 2024-02-27 | JiJieHao           | W   | 0.139      | -            | -                | -                | 1 (0.139) |     0.07 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     3955 | 2024-02-25 | The MongolZ        | L   | 0.132      | -            | -                | -                | -         |    -0.05 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     3958 | 2024-02-25 | ATOX               | W   | 0.131      | -            | -                | -                | 1 (0.131) |     0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     4020 | 2024-02-23 | Rooster            | W   | 0.112      | -            | -                | -                | -         |     0.39 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     4039 | 2024-02-22 | Rooster            | W   | 0.106      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     4043 | 2024-02-21 | Bad News Kangaroos | W   | 0.105      | -            | -                | -                | -         |     0.16 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     4066 | 2024-02-21 | Bad News Kangaroos | W   | 0.100      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     4070 | 2024-02-21 | Bad News Kangaroos | W   | 0.099      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4125 | 2024-02-18 | Mindfreak          | W   | 0.085      | -            | -                | -                | -         |     0.18 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4143 | 2024-02-18 | Arcade             | W   | 0.079      | -            | -                | -                | -         |     0.16 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4147 | 2024-02-18 | MANTRA             | W   | 0.079      | -            | -                | -                | -         |     0.04 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4148 | 2024-02-17 | Arcade             | W   | 0.077      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4170 | 2024-02-16 | GR                 | W   | 0.071      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,790.34)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.825 | $3,250.00      | $2,680.72       |
| 2024-06-02 |      0.782 | $4,000.00      | $3,126.02       |
| 2024-05-12 |      0.641 | $23,500.00     | $15,055.78      |
| 2024-04-14 |      0.453 | $6,000.00      | $2,716.67       |
| 2024-02-17 |      0.077 | $2,750.00      | $211.15         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
