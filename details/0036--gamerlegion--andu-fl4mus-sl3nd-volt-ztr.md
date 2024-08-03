### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1144.2<br />
<br />
Final Rank Value (1144.2) = Starting Rank Value (1136.8) + Head To Head Adjustments (7.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.447[<sup>2</sup>](#table1)
- Opponent Network: 0.228[<sup>2</sup>](#table1)
- LAN Wins: 0.197[<sup>2</sup>](#table1)

The average of these factors is 0.360<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1136.8
- 400 + ( ( 0.360 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1136.8


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
|           24 |      144 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.19 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      182 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.67 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |      952 | 2024-06-15 | 5W                | L   | 0.873      | -            | -                | -                | -         |   -19.76 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |      985 | 2024-06-14 | Endpoint          | W   | 0.866      | 0.450        | -                | 0.540 (0.211)    | 0 (0.000) |     4.43 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |     1016 | 2024-06-13 | Illuminar         | L   | 0.860      | -            | -                | -                | -         |   -22.29 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1184 | 2024-06-08 | 5W                | W   | 0.827      | 0.450        | 0.081 (0.030)    | -                | 0 (0.000) |     5.65 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1238 | 2024-06-07 | MOUZ NXT          | W   | 0.820      | 0.450        | 0.139 (0.051)    | 1.000 (0.369)    | 0 (0.000) |    10.45 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1301 | 2024-06-06 | ECLOT             | W   | 0.814      | 0.450        | 0.063 (0.023)    | 0.578 (0.212)    | 0 (0.000) |    12.34 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1532 | 2024-05-31 | GUN5              | L   | 0.773      | -            | -                | -                | -         |   -19.24 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1738 | 2024-05-22 | Eternal Fire      | L   | 0.713      | -            | -                | -                | -         |    -1.30 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1771 | 2024-05-21 | AMKAL             | W   | 0.707      | 0.769        | 0.130 (0.071)    | 0.494 (0.268)    | 0 (0.000) |    12.01 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     1879 | 2024-05-18 | fnatic            | W   | 0.685      | 0.769        | 0.290 (0.152)    | 0.627 (0.330)    | 0 (0.000) |    15.54 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     1900 | 2024-05-17 | Gaimin Gladiators | W   | 0.680      | 0.769        | 0.038 (0.020)    | 0.366 (0.191)    | 0 (0.000) |     6.61 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2202 | 2024-05-07 | Virtus.pro        | L   | 0.614      | -            | -                | -                | -         |    -0.96 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2276 | 2024-05-03 | ENCE              | W   | 0.586      | 0.889        | 0.170 (0.089)    | 0.415 (0.216)    | 1 (0.586) |    14.93 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2294 | 2024-05-02 | FORZE             | W   | 0.580      | 0.889        | 0.059 (0.030)    | 0.186 (0.096)    | 1 (0.580) |     4.86 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2325 | 2024-05-01 | MOUZ              | L   | 0.573      | -            | -                | -                | -         |    -0.41 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2355 | 2024-04-30 | ENCE              | W   | 0.565      | 0.889        | 0.170 (0.085)    | 0.415 (0.208)    | 1 (0.565) |    14.87 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2569 | 2024-04-20 | BIG               | L   | 0.499      | -            | -                | -                | -         |    -4.15 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2657 | 2024-04-18 | Sashi             | L   | 0.486      | -            | -                | -                | -         |    -7.68 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2737 | 2024-04-16 | MOUZ NXT          | W   | 0.472      | 0.384        | 0.139 (0.025)    | 1.000 (0.182)    | -         |     5.86 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3130 | 2024-04-02 | Monte             | L   | 0.380      | -            | -                | -                | -         |    -8.21 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3138 | 2024-04-02 | FAVBET            | L   | 0.379      | -            | -                | -                | -         |   -10.49 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3158 | 2024-04-01 | GUN5              | W   | 0.372      | -            | -                | -                | -         |     0.19 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($56,686.69)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.885 | $5,000.00      | $4,425.23       |
| 2024-05-23 |      0.719 | $50,000.00     | $35,953.70      |
| 2024-05-12 |      0.646 | $17,500.00     | $11,307.75      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
