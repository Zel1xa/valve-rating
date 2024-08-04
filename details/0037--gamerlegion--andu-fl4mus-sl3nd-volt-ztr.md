### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1146.4<br />
<br />
Final Rank Value (1146.4) = Starting Rank Value (1137.0) + Head To Head Adjustments (9.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.452[<sup>2</sup>](#table1)
- Opponent Network: 0.226[<sup>2</sup>](#table1)
- LAN Wins: 0.196[<sup>2</sup>](#table1)

The average of these factors is 0.360<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1137.0
- 400 + ( ( 0.360 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1137.0


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
|           24 |      178 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.29 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      216 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.67 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |     1006 | 2024-06-15 | 5W                | L   | 0.867      | -            | -                | -                | -         |   -19.77 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |     1048 | 2024-06-14 | Endpoint          | W   | 0.861      | 0.450        | -                | 0.522 (0.202)    | 0 (0.000) |     4.33 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |     1078 | 2024-06-13 | Illuminar         | L   | 0.855      | -            | -                | -                | -         |   -22.24 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1253 | 2024-06-08 | 5W                | W   | 0.822      | 0.450        | 0.081 (0.030)    | -                | 0 (0.000) |     5.51 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1310 | 2024-06-07 | MOUZ NXT          | W   | 0.815      | 0.450        | 0.139 (0.051)    | 1.000 (0.367)    | 0 (0.000) |    10.37 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1373 | 2024-06-06 | ECLOT             | W   | 0.808      | 0.450        | 0.062 (0.023)    | 0.559 (0.203)    | 0 (0.000) |    12.12 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1607 | 2024-05-31 | GUN5              | L   | 0.767      | -            | -                | -                | -         |   -19.24 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1814 | 2024-05-22 | Eternal Fire      | L   | 0.707      | -            | -                | -                | -         |    -1.30 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1847 | 2024-05-21 | AMKAL             | W   | 0.702      | 0.769        | 0.130 (0.070)    | 0.475 (0.256)    | 0 (0.000) |    11.89 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     1956 | 2024-05-18 | fnatic            | W   | 0.679      | 0.769        | 0.371 (0.193)    | 0.708 (0.370)    | 0 (0.000) |    18.47 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     1977 | 2024-05-17 | Gaimin Gladiators | W   | 0.674      | 0.769        | 0.038 (0.020)    | 0.351 (0.182)    | 0 (0.000) |     6.46 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2280 | 2024-05-07 | Virtus.pro        | L   | 0.608      | -            | -                | -                | -         |    -0.93 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2354 | 2024-05-03 | ENCE              | W   | 0.581      | 0.889        | 0.169 (0.087)    | 0.400 (0.207)    | 1 (0.581) |    14.82 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2372 | 2024-05-02 | FORZE             | W   | 0.575      | 0.889        | 0.058 (0.030)    | 0.177 (0.090)    | 1 (0.575) |     4.77 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2403 | 2024-05-01 | MOUZ              | L   | 0.567      | -            | -                | -                | -         |    -0.30 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2433 | 2024-04-30 | ENCE              | W   | 0.560      | 0.889        | 0.169 (0.084)    | 0.400 (0.199)    | 1 (0.560) |    14.75 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2648 | 2024-04-20 | BIG               | L   | 0.494      | -            | -                | -                | -         |    -4.19 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2736 | 2024-04-18 | Sashi             | L   | 0.481      | -            | -                | -                | -         |    -7.74 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2816 | 2024-04-16 | MOUZ NXT          | W   | 0.467      | 0.384        | 0.139 (0.025)    | 1.000 (0.179)    | -         |     5.90 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3209 | 2024-04-02 | Monte             | L   | 0.375      | -            | -                | -                | -         |    -8.15 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3217 | 2024-04-02 | FAVBET            | L   | 0.374      | -            | -                | -                | -         |   -10.35 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3237 | 2024-04-01 | GUN5              | W   | 0.367      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($56,288.95)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.880 | $5,000.00      | $4,397.80       |
| 2024-05-23 |      0.714 | $50,000.00     | $35,679.40      |
| 2024-05-12 |      0.641 | $17,500.00     | $11,211.75      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
