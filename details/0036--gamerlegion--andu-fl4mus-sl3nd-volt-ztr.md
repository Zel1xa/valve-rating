### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1146.3<br />
<br />
Final Rank Value (1146.3) = Starting Rank Value (1136.3) + Head To Head Adjustments (10.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.451[<sup>2</sup>](#table1)
- Opponent Network: 0.223[<sup>2</sup>](#table1)
- LAN Wins: 0.195[<sup>2</sup>](#table1)

The average of these factors is 0.359<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1136.3
- 400 + ( ( 0.359 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1136.3


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
|           24 |      227 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.32 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      265 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.68 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |     1055 | 2024-06-15 | 5W                | L   | 0.859      | -            | -                | -                | -         |   -19.61 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |     1097 | 2024-06-14 | Endpoint          | W   | 0.853      | 0.450        | -                | 0.514 (0.197)    | 0 (0.000) |     4.33 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |     1127 | 2024-06-13 | Illuminar         | L   | 0.847      | -            | -                | -                | -         |   -21.97 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1302 | 2024-06-08 | 5W                | W   | 0.814      | 0.450        | 0.081 (0.030)    | -                | 0 (0.000) |     5.46 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1359 | 2024-06-07 | MOUZ NXT          | W   | 0.807      | 0.450        | 0.139 (0.050)    | 0.987 (0.359)    | 0 (0.000) |    10.43 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1422 | 2024-06-06 | ECLOT             | W   | 0.800      | 0.450        | 0.062 (0.022)    | 0.550 (0.198)    | 0 (0.000) |    12.14 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1656 | 2024-05-31 | GUN5              | L   | 0.760      | -            | -                | -                | -         |   -18.99 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1863 | 2024-05-22 | Eternal Fire      | L   | 0.699      | -            | -                | -                | -         |    -1.28 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1896 | 2024-05-21 | AMKAL             | W   | 0.694      | 0.769        | 0.130 (0.069)    | 0.465 (0.248)    | 0 (0.000) |    11.69 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     2005 | 2024-05-18 | fnatic            | W   | 0.671      | 0.769        | 0.371 (0.191)    | 0.697 (0.360)    | 0 (0.000) |    18.29 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     2026 | 2024-05-17 | Gaimin Gladiators | W   | 0.666      | 0.769        | 0.037 (0.019)    | 0.342 (0.175)    | 0 (0.000) |     6.38 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2329 | 2024-05-07 | Virtus.pro        | L   | 0.600      | -            | -                | -                | -         |    -0.92 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2403 | 2024-05-03 | ENCE              | W   | 0.573      | 0.889        | 0.174 (0.089)    | 0.432 (0.220)    | 1 (0.573) |    14.78 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2421 | 2024-05-02 | FORZE             | W   | 0.567      | 0.889        | 0.058 (0.029)    | 0.171 (0.086)    | 1 (0.567) |     4.67 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2452 | 2024-05-01 | MOUZ              | L   | 0.559      | -            | -                | -                | -         |    -0.30 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2482 | 2024-04-30 | ENCE              | W   | 0.552      | 0.889        | 0.174 (0.085)    | 0.432 (0.212)    | 1 (0.552) |    14.68 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2697 | 2024-04-20 | BIG               | L   | 0.486      | -            | -                | -                | -         |    -4.13 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2785 | 2024-04-18 | Sashi             | L   | 0.473      | -            | -                | -                | -         |    -7.57 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2865 | 2024-04-16 | MOUZ NXT          | W   | 0.459      | 0.384        | 0.139 (0.024)    | 0.987 (0.174)    | -         |     5.87 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3258 | 2024-04-02 | Monte             | L   | 0.367      | -            | -                | -                | -         |    -8.02 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3266 | 2024-04-02 | FAVBET            | L   | 0.366      | -            | -                | -                | -         |   -10.12 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3286 | 2024-04-01 | GUN5              | W   | 0.359      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,716.67)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.872 | $5,000.00      | $4,358.33       |
| 2024-05-23 |      0.706 | $50,000.00     | $35,284.72      |
| 2024-05-12 |      0.633 | $17,500.00     | $11,073.61      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
