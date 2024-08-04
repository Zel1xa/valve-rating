### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1181.1<br />
<br />
Final Rank Value (1181.1) = Starting Rank Value (1156.9) + Head To Head Adjustments (24.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.505[<sup>1</sup>](#table2)
- Bounty Collected: 0.416[<sup>2</sup>](#table1)
- Opponent Network: 0.145[<sup>2</sup>](#table1)
- LAN Wins: 0.416[<sup>2</sup>](#table1)

The average of these factors is 0.370<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1156.9
- 400 + ( ( 0.370 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1156.9


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
|           48 |      589 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -3.07 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |      656 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.51 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1223 | 2024-06-08 | Rooster            | W   | 0.829      | 0.333        | 0.010 (0.003)    | 0.266 (0.073)    | 0 (0.000) |     3.58 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1278 | 2024-06-08 | Mindfreak          | W   | 0.823      | 0.333        | 0.004 (0.001)    | 0.227 (0.062)    | -         |     1.97 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1333 | 2024-06-07 | Rooster            | L   | 0.816      | -            | -                | -                | -         |   -22.54 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1661 | 2024-05-28 | BIG                | L   | 0.752      | -            | -                | -                | -         |    -8.99 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1682 | 2024-05-27 | Spirit             | L   | 0.746      | -            | -                | -                | -         |    -0.50 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1809 | 2024-05-22 | Mindfreak          | W   | 0.710      | 0.333        | 0.004 (0.001)    | 0.227 (0.054)    | -         |     1.33 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1814 | 2024-05-22 | Mindfreak          | W   | 0.709      | 0.333        | -                | 0.227 (0.054)    | -         |     1.35 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     1884 | 2024-05-20 | Canon Event        | W   | 0.697      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     1886 | 2024-05-20 | Canon Event        | W   | 0.697      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2255 | 2024-05-08 | Liquid             | L   | 0.618      | -            | -                | -                | -         |    -3.11 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2273 | 2024-05-07 | BetBoom            | W   | 0.611      | 0.889        | 0.252 (0.137)    | 0.543 (0.295)    | 1 (0.611) |    14.34 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2317 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.597      | 0.889        | 0.223 (0.118)    | 0.553 (0.294)    | 1 (0.597) |    17.05 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2333 | 2024-05-04 | PERA               | W   | 0.590      | 0.889        | 0.048 (0.025)    | 0.453 (0.237)    | 1 (0.590) |     3.52 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2349 | 2024-05-03 | HEROIC             | L   | 0.583      | -            | -                | -                | -         |    -1.85 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2376 | 2024-05-02 | BOSS               | W   | 0.577      | 0.889        | 0.014 (0.007)    | 0.333 (0.171)    | 1 (0.577) |     2.16 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2398 | 2024-05-01 | Natus Vincere      | L   | 0.570      | -            | -                | -                | -         |    -0.20 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2644 | 2024-04-20 | Bad News Kangaroos | W   | 0.497      | 0.143        | 0.017 (0.001)    | -                | -         |     1.58 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2690 | 2024-04-19 | Rooster            | W   | 0.490      | -            | -                | -                | -         |     1.72 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2697 | 2024-04-18 | Mindfreak          | W   | 0.489      | -            | -                | -                | -         |     1.00 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     2942 | 2024-04-10 | FaZe               | L   | 0.430      | -            | -                | -                | -         |    -0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     2957 | 2024-04-09 | Nemiga             | W   | 0.428      | 0.624        | 0.318 (0.085)    | 0.695 (0.186)    | 1 (0.428) |     6.36 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     3007 | 2024-04-08 | Virtus.pro         | L   | 0.422      | -            | -                | -                | -         |    -0.65 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3038 | 2024-04-08 | Cloud9             | W   | 0.416      | 0.624        | 0.063 (0.016)    | 0.112 (0.029)    | 1 (0.416) |     4.90 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3179 | 2024-04-03 | Arcade             | W   | 0.383      | -            | -                | -                | -         |     0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3184 | 2024-04-03 | Arcade             | W   | 0.383      | -            | -                | -                | -         |     0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3307 | 2024-03-27 | KZG                | W   | 0.337      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3312 | 2024-03-27 | KZG                | W   | 0.336      | -            | -                | -                | -         |     0.71 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3576 | 2024-03-13 | Rooster            | W   | 0.243      | -            | -                | -                | -         |     0.83 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3584 | 2024-03-13 | Rooster            | W   | 0.243      | -            | -                | -                | -         |     0.84 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3753 | 2024-03-06 | DXA                | W   | 0.197      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3755 | 2024-03-06 | DXA                | W   | 0.196      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3903 | 2024-02-27 | Lynn Vision        | L   | 0.149      | -            | -                | -                | -         |    -3.44 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3904 | 2024-02-27 | ATOX               | W   | 0.148      | -            | -                | -                | 1 (0.148) |     0.75 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     3925 | 2024-02-27 | JiJieHao           | W   | 0.143      | -            | -                | -                | 1 (0.143) |     0.07 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     3941 | 2024-02-25 | The MongolZ        | L   | 0.135      | -            | -                | -                | -         |    -0.05 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     3944 | 2024-02-25 | ATOX               | W   | 0.134      | -            | -                | -                | 1 (0.134) |     0.68 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     4006 | 2024-02-23 | Rooster            | W   | 0.116      | -            | -                | -                | -         |     0.39 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     4025 | 2024-02-22 | Rooster            | W   | 0.110      | -            | -                | -                | -         |     0.37 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     4029 | 2024-02-21 | Bad News Kangaroos | W   | 0.108      | -            | -                | -                | -         |     0.33 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     4052 | 2024-02-21 | Bad News Kangaroos | W   | 0.103      | -            | -                | -                | -         |     0.32 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     4056 | 2024-02-21 | Bad News Kangaroos | W   | 0.103      | -            | -                | -                | -         |     0.32 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4111 | 2024-02-18 | Mindfreak          | W   | 0.089      | -            | -                | -                | -         |     0.18 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4128 | 2024-02-18 | Arcade             | W   | 0.083      | -            | -                | -                | -         |     0.16 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4132 | 2024-02-18 | MANTRA             | W   | 0.083      | -            | -                | -                | -         |     0.04 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4133 | 2024-02-17 | Arcade             | W   | 0.081      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4155 | 2024-02-16 | GR                 | W   | 0.075      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,939.38)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.829 | $3,250.00      | $2,692.99       |
| 2024-06-02 |      0.785 | $4,000.00      | $3,141.11       |
| 2024-05-12 |      0.644 | $23,500.00     | $15,144.44      |
| 2024-04-14 |      0.457 | $6,000.00      | $2,739.31       |
| 2024-02-17 |      0.081 | $2,750.00      | $221.53         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
