### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1145.2<br />
<br />
Final Rank Value (1145.2) = Starting Rank Value (1134.7) + Head To Head Adjustments (10.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.567[<sup>1</sup>](#table2)
- Bounty Collected: 0.451[<sup>2</sup>](#table1)
- Opponent Network: 0.220[<sup>2</sup>](#table1)
- LAN Wins: 0.194[<sup>2</sup>](#table1)

The average of these factors is 0.358<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1134.7
- 400 + ( ( 0.358 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1134.7


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
|           24 |      234 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.33 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      272 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.68 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |     1062 | 2024-06-15 | 5W                | L   | 0.855      | -            | -                | -                | -         |   -19.48 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |     1104 | 2024-06-14 | Endpoint          | W   | 0.848      | 0.450        | -                | 0.513 (0.196)    | 0 (0.000) |     4.36 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |     1134 | 2024-06-13 | Illuminar         | L   | 0.842      | -            | -                | -                | -         |   -21.81 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1309 | 2024-06-08 | 5W                | W   | 0.809      | 0.450        | 0.081 (0.030)    | -                | 0 (0.000) |     5.46 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1366 | 2024-06-07 | MOUZ NXT          | W   | 0.802      | 0.450        | 0.139 (0.050)    | 0.984 (0.355)    | 0 (0.000) |    10.44 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1429 | 2024-06-06 | ECLOT             | W   | 0.796      | 0.450        | 0.061 (0.022)    | 0.549 (0.196)    | 0 (0.000) |    12.15 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1663 | 2024-05-31 | GUN5              | L   | 0.755      | -            | -                | -                | -         |   -18.84 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1870 | 2024-05-22 | Eternal Fire      | L   | 0.695      | -            | -                | -                | -         |    -1.27 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1903 | 2024-05-21 | AMKAL             | W   | 0.689      | 0.769        | 0.130 (0.069)    | 0.463 (0.245)    | 0 (0.000) |    11.72 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     2012 | 2024-05-18 | fnatic            | W   | 0.667      | 0.769        | 0.371 (0.190)    | 0.695 (0.356)    | 0 (0.000) |    18.18 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     2033 | 2024-05-17 | Gaimin Gladiators | W   | 0.662      | 0.769        | 0.037 (0.019)    | 0.339 (0.172)    | 0 (0.000) |     6.34 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2336 | 2024-05-07 | Virtus.pro        | L   | 0.596      | -            | -                | -                | -         |    -0.91 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2410 | 2024-05-03 | ENCE              | W   | 0.568      | 0.889        | 0.173 (0.087)    | 0.431 (0.218)    | 1 (0.568) |    14.70 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2428 | 2024-05-02 | FORZE             | W   | 0.562      | 0.889        | 0.057 (0.029)    | 0.168 (0.084)    | 1 (0.562) |     4.62 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2459 | 2024-05-01 | MOUZ              | L   | 0.555      | -            | -                | -                | -         |    -0.29 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2489 | 2024-04-30 | ENCE              | W   | 0.547      | 0.889        | 0.173 (0.084)    | 0.431 (0.210)    | 1 (0.547) |    14.59 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2704 | 2024-04-20 | BIG               | L   | 0.481      | -            | -                | -                | -         |    -4.09 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2792 | 2024-04-18 | Sashi             | L   | 0.468      | -            | -                | -                | -         |    -7.45 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2872 | 2024-04-16 | MOUZ NXT          | W   | 0.454      | 0.384        | 0.139 (0.024)    | 0.984 (0.172)    | -         |     5.85 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3265 | 2024-04-02 | Monte             | L   | 0.362      | -            | -                | -                | -         |    -7.91 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3273 | 2024-04-02 | FAVBET            | L   | 0.361      | -            | -                | -                | -         |    -9.98 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3293 | 2024-04-01 | GUN5              | W   | 0.354      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,374.31)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.867 | $5,000.00      | $4,334.72       |
| 2024-05-23 |      0.701 | $50,000.00     | $35,048.61      |
| 2024-05-12 |      0.628 | $17,500.00     | $10,990.97      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
