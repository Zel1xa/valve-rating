### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1146.4<br />
<br />
Final Rank Value (1146.4) = Starting Rank Value (1136.6) + Head To Head Adjustments (9.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.452[<sup>2</sup>](#table1)
- Opponent Network: 0.225[<sup>2</sup>](#table1)
- LAN Wins: 0.196[<sup>2</sup>](#table1)

The average of these factors is 0.360<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1136.6
- 400 + ( ( 0.360 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1136.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      202 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.29 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      240 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.67 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |     1030 | 2024-06-15 | 5W                | L   | 0.866      | -            | -                | -                | -         |   -19.75 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |     1072 | 2024-06-14 | Endpoint          | W   | 0.860      | 0.450        | -                | 0.522 (0.202)    | 0 (0.000) |     4.35 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |     1102 | 2024-06-13 | Illuminar         | L   | 0.854      | -            | -                | -                | -         |   -22.19 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1277 | 2024-06-08 | 5W                | W   | 0.820      | 0.450        | 0.081 (0.030)    | -                | 0 (0.000) |     5.50 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1334 | 2024-06-07 | MOUZ NXT          | W   | 0.814      | 0.450        | 0.139 (0.051)    | 1.000 (0.366)    | 0 (0.000) |    10.39 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1397 | 2024-06-06 | ECLOT             | W   | 0.807      | 0.450        | 0.062 (0.023)    | 0.558 (0.203)    | 0 (0.000) |    12.20 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1631 | 2024-05-31 | GUN5              | L   | 0.766      | -            | -                | -                | -         |   -19.18 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1838 | 2024-05-22 | Eternal Fire      | L   | 0.706      | -            | -                | -                | -         |    -1.29 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1871 | 2024-05-21 | AMKAL             | W   | 0.701      | 0.769        | 0.130 (0.070)    | 0.475 (0.256)    | 0 (0.000) |    11.86 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     1980 | 2024-05-18 | fnatic            | W   | 0.678      | 0.769        | 0.371 (0.193)    | 0.708 (0.369)    | 0 (0.000) |    18.46 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     2001 | 2024-05-17 | Gaimin Gladiators | W   | 0.673      | 0.769        | 0.038 (0.020)    | 0.350 (0.181)    | 0 (0.000) |     6.52 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2304 | 2024-05-07 | Virtus.pro        | L   | 0.607      | -            | -                | -                | -         |    -0.92 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2378 | 2024-05-03 | ENCE              | W   | 0.579      | 0.889        | 0.169 (0.087)    | 0.400 (0.206)    | 1 (0.579) |    14.81 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2396 | 2024-05-02 | FORZE             | W   | 0.574      | 0.889        | 0.058 (0.030)    | 0.176 (0.090)    | 1 (0.574) |     4.75 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2427 | 2024-05-01 | MOUZ              | L   | 0.566      | -            | -                | -                | -         |    -0.30 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2457 | 2024-04-30 | ENCE              | W   | 0.559      | 0.889        | 0.169 (0.084)    | 0.400 (0.199)    | 1 (0.559) |    14.73 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2672 | 2024-04-20 | BIG               | L   | 0.493      | -            | -                | -                | -         |    -4.18 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2760 | 2024-04-18 | Sashi             | L   | 0.480      | -            | -                | -                | -         |    -7.70 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2840 | 2024-04-16 | MOUZ NXT          | W   | 0.466      | 0.384        | 0.139 (0.025)    | 1.000 (0.179)    | -         |     5.90 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3233 | 2024-04-02 | Monte             | L   | 0.374      | -            | -                | -                | -         |    -8.14 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3241 | 2024-04-02 | FAVBET            | L   | 0.373      | -            | -                | -                | -         |   -10.31 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3261 | 2024-04-01 | GUN5              | W   | 0.366      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($56,211.75)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.878 | $5,000.00      | $4,392.48       |
| 2024-05-23 |      0.713 | $50,000.00     | $35,626.16      |
| 2024-05-12 |      0.640 | $17,500.00     | $11,193.11      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />