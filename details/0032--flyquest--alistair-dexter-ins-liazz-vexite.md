### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1181.2<br />
<br />
Final Rank Value (1181.2) = Starting Rank Value (1155.1) + Head To Head Adjustments (26.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.504[<sup>1</sup>](#table2)
- Bounty Collected: 0.418[<sup>2</sup>](#table1)
- Opponent Network: 0.144[<sup>2</sup>](#table1)
- LAN Wins: 0.410[<sup>2</sup>](#table1)

The average of these factors is 0.369<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1155.1
- 400 + ( ( 0.369 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1155.1


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
|           48 |      628 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -3.00 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |      695 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.50 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1263 | 2024-06-08 | Rooster            | W   | 0.821      | 0.333        | 0.010 (0.003)    | 0.251 (0.069)    | 0 (0.000) |     3.64 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1318 | 2024-06-08 | Mindfreak          | W   | 0.815      | 0.333        | 0.004 (0.001)    | 0.227 (0.062)    | -         |     2.07 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1373 | 2024-06-07 | Rooster            | L   | 0.809      | -            | -                | -                | -         |   -22.25 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1701 | 2024-05-28 | BIG                | L   | 0.745      | -            | -                | -                | -         |    -8.91 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1722 | 2024-05-27 | Spirit             | L   | 0.739      | -            | -                | -                | -         |    -0.49 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1849 | 2024-05-22 | Mindfreak          | W   | 0.702      | 0.333        | 0.004 (0.001)    | 0.227 (0.053)    | -         |     1.37 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1854 | 2024-05-22 | Mindfreak          | W   | 0.702      | 0.333        | -                | 0.227 (0.053)    | -         |     1.39 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     1924 | 2024-05-20 | Canon Event        | W   | 0.690      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     1926 | 2024-05-20 | Canon Event        | W   | 0.689      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2295 | 2024-05-08 | Liquid             | L   | 0.610      | -            | -                | -                | -         |    -2.04 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2313 | 2024-05-07 | BetBoom            | W   | 0.604      | 0.889        | 0.250 (0.134)    | 0.540 (0.290)    | 1 (0.604) |    14.18 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2357 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.590      | 0.889        | 0.254 (0.133)    | 0.553 (0.290)    | 1 (0.590) |    16.95 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2373 | 2024-05-04 | PERA               | W   | 0.583      | 0.889        | 0.048 (0.025)    | 0.453 (0.235)    | 1 (0.583) |     3.55 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2389 | 2024-05-03 | HEROIC             | L   | 0.576      | -            | -                | -                | -         |    -1.80 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2416 | 2024-05-02 | BOSS               | W   | 0.570      | 0.889        | 0.014 (0.007)    | 0.332 (0.168)    | 1 (0.570) |     2.15 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2438 | 2024-05-01 | Natus Vincere      | L   | 0.563      | -            | -                | -                | -         |    -0.20 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2685 | 2024-04-20 | Bad News Kangaroos | W   | 0.489      | 0.143        | 0.017 (0.001)    | -                | -         |     1.68 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2731 | 2024-04-19 | Rooster            | W   | 0.483      | -            | -                | -                | -         |     1.73 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2738 | 2024-04-18 | Mindfreak          | W   | 0.482      | -            | -                | -                | -         |     1.04 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     2983 | 2024-04-10 | FaZe               | L   | 0.423      | -            | -                | -                | -         |    -0.68 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     2998 | 2024-04-09 | Nemiga             | W   | 0.421      | 0.624        | 0.317 (0.083)    | 0.733 (0.193)    | 1 (0.421) |     6.65 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     3048 | 2024-04-08 | Virtus.pro         | L   | 0.415      | -            | -                | -                | -         |    -0.63 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3079 | 2024-04-08 | Cloud9             | W   | 0.408      | 0.624        | 0.062 (0.016)    | 0.110 (0.028)    | 1 (0.408) |     4.85 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3220 | 2024-04-03 | Arcade             | W   | 0.376      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3225 | 2024-04-03 | Arcade             | W   | 0.376      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3348 | 2024-03-27 | KZG                | W   | 0.329      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3353 | 2024-03-27 | KZG                | W   | 0.329      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3618 | 2024-03-13 | Rooster            | W   | 0.236      | -            | -                | -                | -         |     0.82 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3626 | 2024-03-13 | Rooster            | W   | 0.236      | -            | -                | -                | -         |     0.83 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3795 | 2024-03-06 | DXA                | W   | 0.189      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3797 | 2024-03-06 | DXA                | W   | 0.189      | -            | -                | -                | -         |     0.42 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3945 | 2024-02-27 | Lynn Vision        | L   | 0.142      | -            | -                | -                | -         |    -2.92 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3946 | 2024-02-27 | ATOX               | W   | 0.141      | -            | -                | -                | 1 (0.141) |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     3967 | 2024-02-27 | JiJieHao           | W   | 0.136      | -            | -                | -                | 1 (0.136) |     0.06 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     3983 | 2024-02-25 | The MongolZ        | L   | 0.128      | -            | -                | -                | -         |    -0.05 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     3986 | 2024-02-25 | ATOX               | W   | 0.127      | -            | -                | -                | 1 (0.127) |     0.65 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     4048 | 2024-02-23 | Rooster            | W   | 0.109      | -            | -                | -                | -         |     0.38 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     4067 | 2024-02-22 | Rooster            | W   | 0.102      | -            | -                | -                | -         |     0.35 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     4071 | 2024-02-21 | Bad News Kangaroos | W   | 0.101      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     4094 | 2024-02-21 | Bad News Kangaroos | W   | 0.096      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     4098 | 2024-02-21 | Bad News Kangaroos | W   | 0.096      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4153 | 2024-02-18 | Mindfreak          | W   | 0.082      | -            | -                | -                | -         |     0.18 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4171 | 2024-02-18 | Arcade             | W   | 0.076      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4175 | 2024-02-18 | MANTRA             | W   | 0.075      | -            | -                | -                | -         |     0.03 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4176 | 2024-02-17 | Arcade             | W   | 0.073      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4198 | 2024-02-16 | GR                 | W   | 0.068      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,654.10)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.821 | $3,250.00      | $2,669.51       |
| 2024-06-02 |      0.778 | $4,000.00      | $3,112.22       |
| 2024-05-12 |      0.637 | $23,500.00     | $14,974.72      |
| 2024-04-14 |      0.449 | $6,000.00      | $2,695.97       |
| 2024-02-17 |      0.073 | $2,750.00      | $201.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
