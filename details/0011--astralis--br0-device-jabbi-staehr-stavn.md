### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [11](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1565.5<br />
<br />
Final Rank Value (1565.5) = Starting Rank Value (1510.3) + Head To Head Adjustments (55.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.683[<sup>1</sup>](#table2)
- Bounty Collected: 0.587[<sup>2</sup>](#table1)
- Opponent Network: 0.280[<sup>2</sup>](#table1)
- LAN Wins: 0.743[<sup>2</sup>](#table1)

The average of these factors is 0.573<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1510.3
- 400 + ( ( 0.573 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1510.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |      924 | 2024-08-12 | G2                | L   | 1.000      | -            | -                | -                | -         |    -3.21 | br0, device, jabbi, Staehr, stavn |
|           30 |      954 | 2024-08-11 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -3.48 | br0, device, jabbi, Staehr, stavn |
|           29 |      974 | 2024-08-10 | 9z                | W   | 1.000      | 1.000        | 0.362 (0.362)    | 0.530 (0.530)    | 1 (1.000) |    10.16 | br0, device, jabbi, Staehr, stavn |
|           28 |     1175 | 2024-08-04 | Ninjas in Pyjamas | W   | 0.967      | 0.581        | 0.232 (0.131)    | 0.428 (0.240)    | 1 (0.967) |    10.21 | br0, device, jabbi, Staehr, stavn |
|           27 |     1207 | 2024-08-03 | Vitality          | L   | 0.960      | -            | -                | -                | -         |    -4.11 | br0, device, jabbi, Staehr, stavn |
|           26 |     1246 | 2024-08-02 | Falcons           | W   | 0.953      | 0.581        | 0.297 (0.165)    | 0.477 (0.264)    | 1 (0.953) |    12.15 | br0, device, jabbi, Staehr, stavn |
|           25 |     1371 | 2024-07-30 | Vitality          | L   | 0.934      | -            | -                | -                | -         |    -3.92 | br0, device, jabbi, Staehr, stavn |
|           24 |     1399 | 2024-07-29 | Falcons           | W   | 0.928      | 0.581        | 0.297 (0.160)    | 0.477 (0.257)    | 1 (0.928) |    12.56 | br0, device, jabbi, Staehr, stavn |
|           23 |     2225 | 2024-06-14 | Virtus.pro        | L   | 0.628      | -            | -                | -                | -         |   -10.32 | br0, device, jabbi, Staehr, stavn |
|           22 |     2284 | 2024-06-13 | SAW               | W   | 0.619      | 0.729        | 0.330 (0.149)    | 0.747 (0.337)    | 1 (0.619) |     6.44 | br0, device, jabbi, Staehr, stavn |
|           21 |     2307 | 2024-06-12 | Natus Vincere     | L   | 0.613      | -            | -                | -                | -         |    -1.70 | br0, device, jabbi, Staehr, stavn |
|           20 |     2468 | 2024-06-08 | The MongolZ       | L   | 0.587      | -            | -                | -                | -         |    -2.68 | br0, device, jabbi, Staehr, stavn |
|           19 |     2523 | 2024-06-07 | BetBoom           | W   | 0.580      | 0.715        | -                | 0.535 (0.222)    | 1 (0.580) |     3.38 | br0, device, jabbi, Staehr, stavn |
|           18 |     2570 | 2024-06-06 | The MongolZ       | W   | 0.574      | 0.715        | 0.864 (0.355)    | 0.695 (0.285)    | 1 (0.574) |    15.77 | br0, device, jabbi, Staehr, stavn |
|           17 |     2590 | 2024-06-06 | ENCE              | W   | 0.573      | -            | -                | -                | 1 (0.573) |     2.45 | br0, device, jabbi, Staehr, stavn |
|           16 |     2600 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.572      | -            | -                | -                | -         |   -12.19 | br0, device, jabbi, Staehr, stavn |
|           15 |     2646 | 2024-06-05 | Sashi             | L   | 0.567      | -            | -                | -                | -         |   -16.41 | br0, device, jabbi, Staehr, stavn |
|           14 |     2659 | 2024-06-05 | HEROIC            | W   | 0.565      | -            | -                | -                | 1 (0.565) |     5.85 | br0, device, jabbi, Staehr, stavn |
|           13 |     3008 | 2024-05-22 | Liquid            | L   | 0.473      | -            | -                | -                | -         |    -7.09 | br0, device, jabbi, Staehr, stavn |
|           12 |     3049 | 2024-05-21 | Aurora            | W   | 0.467      | 0.769        | -                | 0.603 (0.216)    | -         |     4.07 | br0, device, jabbi, Staehr, stavn |
|           11 |     3079 | 2024-05-20 | BetBoom           | W   | 0.461      | 0.769        | -                | 0.535 (0.189)    | -         |     2.11 | br0, device, jabbi, Staehr, stavn |
|           10 |     3099 | 2024-05-19 | BIG               | W   | 0.455      | -            | -                | -                | -         |     1.81 | br0, device, jabbi, Staehr, stavn |
|            9 |     3395 | 2024-05-11 | Vitality          | L   | 0.400      | -            | -                | -                | -         |    -1.37 | br0, device, jabbi, Staehr, stavn |
|            8 |     3414 | 2024-05-10 | Liquid            | W   | 0.394      | 0.889        | 0.370 (0.129)    | -                | 1 (0.394) |     6.67 | br0, device, jabbi, Staehr, stavn |
|            7 |     3681 | 2024-04-27 | 3DMAX             | W   | 0.307      | 0.889        | 0.509 (0.139)    | 0.951 (0.260)    | -         |     7.02 | br0, device, jabbi, Staehr, stavn |
|            6 |     3752 | 2024-04-24 | FaZe              | W   | 0.288      | 0.889        | 0.587 (0.150)    | -                | -         |     7.10 | br0, device, jabbi, Staehr, stavn |
|            5 |     3772 | 2024-04-23 | Eternal Fire      | W   | 0.281      | 0.889        | 0.972 (0.242)    | -                | -         |     7.71 | br0, device, jabbi, Staehr, stavn |
|            4 |     4059 | 2024-04-13 | FaZe              | L   | 0.213      | -            | -                | -                | -         |    -1.44 | br0, device, jabbi, Staehr, stavn |
|            3 |     4159 | 2024-04-10 | Virtus.pro        | W   | 0.192      | -            | -                | -                | -         |     3.04 | br0, device, jabbi, Staehr, stavn |
|            2 |     4207 | 2024-04-09 | FaZe              | W   | 0.186      | -            | -                | -                | -         |     4.64 | br0, device, jabbi, Staehr, stavn |
|            1 |     4239 | 2024-04-08 | Steel Helmet      | W   | 0.179      | -            | -                | -                | -         |     0.02 | br0, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($104,241.79)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.34) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-18 |      1.000 | $16,000.00     | $16,000.00      |
| 2024-08-04 |      0.967 | $12,500.00     | $12,088.83      |
| 2024-06-16 |      0.640 | $20,000.00     | $12,805.56      |
| 2024-06-09 |      0.594 | $28,000.00     | $16,628.89      |
| 2024-05-23 |      0.480 | $50,000.00     | $24,006.94      |
| 2024-05-12 |      0.407 | $45,000.00     | $18,325.00      |
| 2024-04-14 |      0.219 | $20,000.00     | $4,386.57       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
