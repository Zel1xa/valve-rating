### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1176.2<br />
<br />
Final Rank Value (1176.2) = Starting Rank Value (1149.8) + Head To Head Adjustments (26.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.504[<sup>1</sup>](#table2)
- Bounty Collected: 0.416[<sup>2</sup>](#table1)
- Opponent Network: 0.135[<sup>2</sup>](#table1)
- LAN Wins: 0.403[<sup>2</sup>](#table1)

The average of these factors is 0.364<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1149.8
- 400 + ( ( 0.364 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1149.8


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
|           48 |      668 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -2.90 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |      735 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.51 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1303 | 2024-06-08 | Rooster            | W   | 0.811      | 0.333        | 0.010 (0.003)    | 0.241 (0.065)    | 0 (0.000) |     3.66 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1358 | 2024-06-08 | Mindfreak          | W   | 0.805      | 0.333        | 0.004 (0.001)    | 0.218 (0.059)    | -         |     2.08 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1413 | 2024-06-07 | Rooster            | L   | 0.798      | -            | -                | -                | -         |   -21.91 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1741 | 2024-05-28 | BIG                | L   | 0.735      | -            | -                | -                | -         |    -8.66 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1762 | 2024-05-27 | Spirit             | L   | 0.729      | -            | -                | -                | -         |    -0.47 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1889 | 2024-05-22 | Mindfreak          | W   | 0.692      | 0.333        | 0.004 (0.001)    | 0.218 (0.050)    | -         |     1.39 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1894 | 2024-05-22 | Mindfreak          | W   | 0.692      | 0.333        | -                | 0.218 (0.050)    | -         |     1.41 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     1964 | 2024-05-20 | Canon Event        | W   | 0.679      | -            | -                | -                | -         |     0.37 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     1966 | 2024-05-20 | Canon Event        | W   | 0.679      | -            | -                | -                | -         |     0.37 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2335 | 2024-05-08 | Liquid             | L   | 0.600      | -            | -                | -                | -         |    -1.95 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2353 | 2024-05-07 | BetBoom            | W   | 0.593      | 0.889        | 0.248 (0.131)    | 0.513 (0.271)    | 1 (0.593) |    14.00 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2397 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.579      | 0.889        | 0.253 (0.131)    | 0.531 (0.274)    | 1 (0.579) |    16.70 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2413 | 2024-05-04 | PERA               | W   | 0.573      | 0.889        | 0.047 (0.024)    | 0.435 (0.222)    | 1 (0.573) |     3.57 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2429 | 2024-05-03 | HEROIC             | L   | 0.566      | -            | -                | -                | -         |    -1.76 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2456 | 2024-05-02 | BOSS               | W   | 0.559      | 0.889        | 0.014 (0.007)    | 0.319 (0.158)    | 1 (0.559) |     2.17 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2478 | 2024-05-01 | Natus Vincere      | L   | 0.553      | -            | -                | -                | -         |    -0.19 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2725 | 2024-04-20 | Bad News Kangaroos | W   | 0.479      | 0.143        | 0.016 (0.001)    | -                | -         |     1.68 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2771 | 2024-04-19 | Rooster            | W   | 0.472      | -            | -                | -                | -         |     1.73 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2778 | 2024-04-18 | Mindfreak          | W   | 0.471      | -            | -                | -                | -         |     1.04 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     3023 | 2024-04-10 | FaZe               | L   | 0.413      | -            | -                | -                | -         |    -0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     3038 | 2024-04-09 | Nemiga             | W   | 0.411      | 0.624        | 0.314 (0.081)    | 0.704 (0.181)    | 1 (0.411) |     6.54 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     3088 | 2024-04-08 | Virtus.pro         | L   | 0.404      | -            | -                | -                | -         |    -0.61 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3119 | 2024-04-08 | Cloud9             | W   | 0.398      | 0.624        | 0.061 (0.015)    | 0.102 (0.025)    | 1 (0.398) |     4.69 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3260 | 2024-04-03 | Arcade             | W   | 0.365      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3265 | 2024-04-03 | Arcade             | W   | 0.365      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3388 | 2024-03-27 | KZG                | W   | 0.319      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3393 | 2024-03-27 | KZG                | W   | 0.319      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3658 | 2024-03-13 | Rooster            | W   | 0.226      | -            | -                | -                | -         |     0.81 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3666 | 2024-03-13 | Rooster            | W   | 0.225      | -            | -                | -                | -         |     0.81 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3835 | 2024-03-06 | DXA                | W   | 0.179      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3837 | 2024-03-06 | DXA                | W   | 0.179      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3985 | 2024-02-27 | Lynn Vision        | L   | 0.132      | -            | -                | -                | -         |    -2.62 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3986 | 2024-02-27 | ATOX               | W   | 0.130      | -            | -                | -                | 1 (0.130) |     0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     4007 | 2024-02-27 | JiJieHao           | W   | 0.125      | -            | -                | -                | 1 (0.125) |     0.06 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     4023 | 2024-02-25 | The MongolZ        | L   | 0.118      | -            | -                | -                | -         |    -0.04 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     4026 | 2024-02-25 | ATOX               | W   | 0.117      | -            | -                | -                | 1 (0.117) |     0.61 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     4088 | 2024-02-23 | Rooster            | W   | 0.099      | -            | -                | -                | -         |     0.35 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     4107 | 2024-02-22 | Rooster            | W   | 0.092      | -            | -                | -                | -         |     0.33 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     4111 | 2024-02-21 | Bad News Kangaroos | W   | 0.091      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     4134 | 2024-02-21 | Bad News Kangaroos | W   | 0.086      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     4138 | 2024-02-21 | Bad News Kangaroos | W   | 0.085      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4193 | 2024-02-18 | Mindfreak          | W   | 0.071      | -            | -                | -                | -         |     0.16 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4211 | 2024-02-18 | Arcade             | W   | 0.065      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4215 | 2024-02-18 | MANTRA             | W   | 0.065      | -            | -                | -                | -         |     0.03 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4216 | 2024-02-17 | Arcade             | W   | 0.063      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4238 | 2024-02-16 | GR                 | W   | 0.057      | -            | -                | -                | -         |     0.12 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,244.47)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.811 | $3,250.00      | $2,635.81       |
| 2024-06-02 |      0.768 | $4,000.00      | $3,070.74       |
| 2024-05-12 |      0.627 | $23,500.00     | $14,731.02      |
| 2024-04-14 |      0.439 | $6,000.00      | $2,633.75       |
| 2024-02-17 |      0.063 | $2,750.00      | $173.15         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
