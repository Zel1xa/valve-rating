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
Final Rank Value (1146.4) = Starting Rank Value (1136.7) + Head To Head Adjustments (9.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.451[<sup>2</sup>](#table1)
- Opponent Network: 0.226[<sup>2</sup>](#table1)
- LAN Wins: 0.195[<sup>2</sup>](#table1)

The average of these factors is 0.360<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1136.7
- 400 + ( ( 0.360 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1136.7


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
|           24 |      219 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.32 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      257 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.68 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |     1047 | 2024-06-15 | 5W                | L   | 0.861      | -            | -                | -                | -         |   -19.64 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |     1089 | 2024-06-14 | Endpoint          | W   | 0.854      | 0.450        | -                | 0.520 (0.200)    | 0 (0.000) |     4.33 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |     1119 | 2024-06-13 | Illuminar         | L   | 0.848      | -            | -                | -                | -         |   -22.04 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1294 | 2024-06-08 | 5W                | W   | 0.815      | 0.450        | 0.081 (0.030)    | -                | 0 (0.000) |     5.45 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1351 | 2024-06-07 | MOUZ NXT          | W   | 0.808      | 0.450        | 0.139 (0.050)    | 1.000 (0.364)    | 0 (0.000) |    10.41 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1414 | 2024-06-06 | ECLOT             | W   | 0.802      | 0.450        | 0.062 (0.022)    | 0.557 (0.201)    | 0 (0.000) |    12.12 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1648 | 2024-05-31 | GUN5              | L   | 0.761      | -            | -                | -                | -         |   -19.04 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1855 | 2024-05-22 | Eternal Fire      | L   | 0.700      | -            | -                | -                | -         |    -1.29 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1888 | 2024-05-21 | AMKAL             | W   | 0.695      | 0.769        | 0.130 (0.069)    | 0.472 (0.252)    | 0 (0.000) |    11.71 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     1997 | 2024-05-18 | fnatic            | W   | 0.672      | 0.769        | 0.371 (0.192)    | 0.706 (0.365)    | 0 (0.000) |    18.32 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     2018 | 2024-05-17 | Gaimin Gladiators | W   | 0.667      | 0.769        | 0.037 (0.019)    | 0.346 (0.178)    | 0 (0.000) |     6.38 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2321 | 2024-05-07 | Virtus.pro        | L   | 0.601      | -            | -                | -                | -         |    -0.92 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2395 | 2024-05-03 | ENCE              | W   | 0.574      | 0.889        | 0.168 (0.086)    | 0.438 (0.223)    | 1 (0.574) |    14.76 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2413 | 2024-05-02 | FORZE             | W   | 0.568      | 0.889        | 0.058 (0.029)    | 0.173 (0.087)    | 1 (0.568) |     4.67 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2444 | 2024-05-01 | MOUZ              | L   | 0.560      | -            | -                | -                | -         |    -0.30 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2474 | 2024-04-30 | ENCE              | W   | 0.553      | 0.889        | 0.168 (0.083)    | 0.438 (0.215)    | 1 (0.553) |    14.66 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2689 | 2024-04-20 | BIG               | L   | 0.487      | -            | -                | -                | -         |    -4.15 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2777 | 2024-04-18 | Sashi             | L   | 0.474      | -            | -                | -                | -         |    -7.60 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2857 | 2024-04-16 | MOUZ NXT          | W   | 0.460      | 0.384        | 0.139 (0.025)    | 1.000 (0.177)    | -         |     5.86 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3250 | 2024-04-02 | Monte             | L   | 0.368      | -            | -                | -                | -         |    -8.04 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3258 | 2024-04-02 | FAVBET            | L   | 0.367      | -            | -                | -                | -         |   -10.15 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3278 | 2024-04-01 | GUN5              | W   | 0.360      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,797.22)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.873 | $5,000.00      | $4,363.89       |
| 2024-05-23 |      0.707 | $50,000.00     | $35,340.28      |
| 2024-05-12 |      0.634 | $17,500.00     | $11,093.06      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
