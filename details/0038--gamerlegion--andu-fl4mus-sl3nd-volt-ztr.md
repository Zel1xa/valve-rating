### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1146.2<br />
<br />
Final Rank Value (1146.2) = Starting Rank Value (1137.2) + Head To Head Adjustments (9.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.452[<sup>2</sup>](#table1)
- Opponent Network: 0.226[<sup>2</sup>](#table1)
- LAN Wins: 0.196[<sup>2</sup>](#table1)

The average of these factors is 0.361<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1137.2
- 400 + ( ( 0.361 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1137.2


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
|           24 |      170 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.36 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      208 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.69 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |      998 | 2024-06-15 | 5W                | L   | 0.868      | -            | -                | -                | -         |   -19.79 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |     1040 | 2024-06-14 | Endpoint          | W   | 0.861      | 0.450        | -                | 0.522 (0.202)    | 0 (0.000) |     4.33 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |     1070 | 2024-06-13 | Illuminar         | L   | 0.855      | -            | -                | -                | -         |   -22.27 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1245 | 2024-06-08 | 5W                | W   | 0.822      | 0.450        | 0.081 (0.030)    | -                | 0 (0.000) |     5.51 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1302 | 2024-06-07 | MOUZ NXT          | W   | 0.816      | 0.450        | 0.139 (0.051)    | 1.000 (0.367)    | 0 (0.000) |    10.35 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1365 | 2024-06-06 | ECLOT             | W   | 0.809      | 0.450        | 0.062 (0.023)    | 0.559 (0.203)    | 0 (0.000) |    12.09 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1599 | 2024-05-31 | GUN5              | L   | 0.768      | -            | -                | -                | -         |   -19.26 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1806 | 2024-05-22 | Eternal Fire      | L   | 0.708      | -            | -                | -                | -         |    -1.31 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1839 | 2024-05-21 | AMKAL             | W   | 0.702      | 0.769        | 0.130 (0.070)    | 0.476 (0.257)    | 0 (0.000) |    11.87 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     1948 | 2024-05-18 | fnatic            | W   | 0.680      | 0.769        | 0.371 (0.194)    | 0.708 (0.370)    | 0 (0.000) |    18.48 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     1969 | 2024-05-17 | Gaimin Gladiators | W   | 0.675      | 0.769        | 0.038 (0.020)    | 0.351 (0.182)    | 0 (0.000) |     6.45 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2272 | 2024-05-07 | Virtus.pro        | L   | 0.609      | -            | -                | -                | -         |    -0.94 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2346 | 2024-05-03 | ENCE              | W   | 0.581      | 0.889        | 0.169 (0.087)    | 0.400 (0.207)    | 1 (0.581) |    14.81 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2364 | 2024-05-02 | FORZE             | W   | 0.576      | 0.889        | 0.058 (0.030)    | 0.177 (0.091)    | 1 (0.576) |     4.78 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2395 | 2024-05-01 | MOUZ              | L   | 0.568      | -            | -                | -                | -         |    -0.30 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2425 | 2024-04-30 | ENCE              | W   | 0.560      | 0.889        | 0.169 (0.084)    | 0.400 (0.199)    | 1 (0.560) |    14.74 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2640 | 2024-04-20 | BIG               | L   | 0.494      | -            | -                | -                | -         |    -4.20 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2728 | 2024-04-18 | Sashi             | L   | 0.482      | -            | -                | -                | -         |    -7.80 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2808 | 2024-04-16 | MOUZ NXT          | W   | 0.468      | 0.384        | 0.139 (0.025)    | 1.000 (0.180)    | -         |     5.89 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3201 | 2024-04-02 | Monte             | L   | 0.375      | -            | -                | -                | -         |    -8.16 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3209 | 2024-04-02 | FAVBET            | L   | 0.374      | -            | -                | -                | -         |   -10.38 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3229 | 2024-04-01 | GUN5              | W   | 0.367      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($56,340.97)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.880 | $5,000.00      | $4,401.39       |
| 2024-05-23 |      0.714 | $50,000.00     | $35,715.28      |
| 2024-05-12 |      0.641 | $17,500.00     | $11,224.31      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
