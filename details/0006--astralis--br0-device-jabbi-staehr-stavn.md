### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1705.0<br />
<br />
Final Rank Value (1705.0) = Starting Rank Value (1729.4) + Head To Head Adjustments (-24.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.709[<sup>1</sup>](#table2)
- Bounty Collected: 0.620[<sup>2</sup>](#table1)
- Opponent Network: 0.321[<sup>2</sup>](#table1)
- LAN Wins: 0.942[<sup>2</sup>](#table1)

The average of these factors is 0.648<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1729.4
- 400 + ( ( 0.648 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1729.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |       39 | 2024-08-04 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | 0.254 (0.147)    | 0.544 (0.316)    | 1 (1.000) |    10.63 | br0, device, jabbi, Staehr, stavn    |
|           33 |       71 | 2024-08-03 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.51 | br0, device, jabbi, Staehr, stavn    |
|           32 |      110 | 2024-08-02 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.73 | br0, device, jabbi, Staehr, stavn    |
|           31 |      235 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |   -10.03 | br0, device, jabbi, Staehr, stavn    |
|           30 |      263 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.62 | br0, device, jabbi, Staehr, stavn    |
|           29 |     1086 | 2024-06-14 | Virtus.pro        | L   | 0.852      | -            | -                | -                | -         |   -15.24 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1145 | 2024-06-13 | SAW               | W   | 0.843      | 0.729        | -                | 0.529 (0.325)    | 1 (0.843) |     1.16 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1168 | 2024-06-12 | Natus Vincere     | L   | 0.837      | -            | -                | -                | -         |    -6.63 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1329 | 2024-06-08 | The MongolZ       | L   | 0.810      | -            | -                | -                | -         |    -7.27 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1384 | 2024-06-07 | BetBoom           | W   | 0.803      | 0.715        | 0.249 (0.143)    | 0.527 (0.303)    | 1 (0.803) |     3.82 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1431 | 2024-06-06 | The MongolZ       | W   | 0.798      | 0.715        | 1.000 (0.571)    | 0.710 (0.405)    | 1 (0.798) |    18.54 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1451 | 2024-06-06 | ENCE              | W   | 0.797      | 0.715        | -                | 0.432 (0.246)    | 1 (0.797) |     3.04 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1461 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.796      | -            | -                | -                | -         |   -17.14 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1507 | 2024-06-05 | Sashi             | L   | 0.790      | -            | -                | -                | -         |   -23.73 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1520 | 2024-06-05 | HEROIC            | W   | 0.789      | 0.715        | -                | 0.364 (0.205)    | 1 (0.789) |     6.88 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1869 | 2024-05-22 | Liquid            | L   | 0.696      | -            | -                | -                | -         |   -15.31 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1910 | 2024-05-21 | Aurora            | W   | 0.690      | 0.769        | 0.421 (0.223)    | 0.777 (0.412)    | -         |     5.37 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1940 | 2024-05-20 | BetBoom           | W   | 0.684      | 0.769        | 0.249 (0.131)    | 0.527 (0.277)    | -         |     2.33 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1960 | 2024-05-19 | BIG               | W   | 0.678      | -            | -                | -                | -         |     1.63 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2256 | 2024-05-11 | Vitality          | L   | 0.624      | -            | -                | -                | -         |    -6.77 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2275 | 2024-05-10 | Liquid            | W   | 0.617      | 0.889        | 0.383 (0.210)    | 0.449 (0.246)    | 1 (0.617) |     5.67 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2542 | 2024-04-27 | 3DMAX             | W   | 0.530      | 0.889        | 0.509 (0.240)    | 1.000 (0.472)    | 1 (0.530) |     5.84 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2613 | 2024-04-24 | FaZe              | W   | 0.511      | 0.889        | 0.629 (0.286)    | -                | -         |     7.54 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2633 | 2024-04-23 | Eternal Fire      | W   | 0.504      | 0.889        | 0.739 (0.331)    | -                | -         |     7.20 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2920 | 2024-04-13 | FaZe              | L   | 0.436      | -            | -                | -                | -         |    -7.53 | br0, device, jabbi, Staehr, stavn    |
|            9 |     3020 | 2024-04-10 | Virtus.pro        | W   | 0.415      | -            | -                | -                | -         |     5.93 | br0, device, jabbi, Staehr, stavn    |
|            8 |     3068 | 2024-04-09 | FaZe              | W   | 0.409      | 0.624        | 0.629 (0.160)    | -                | -         |     5.92 | br0, device, jabbi, Staehr, stavn    |
|            7 |     3100 | 2024-04-08 | Steel Helmet      | W   | 0.402      | -            | -                | -                | -         |     0.02 | br0, device, jabbi, Staehr, stavn    |
|            6 |     4071 | 2024-02-23 | 9 Pandas          | L   | 0.103      | -            | -                | -                | -         |    -3.18 | blameF, device, jabbi, Staehr, stavn |
|            5 |     4090 | 2024-02-22 | ENCE              | L   | 0.096      | -            | -                | -                | -         |    -2.43 | blameF, device, jabbi, Staehr, stavn |
|            4 |     4117 | 2024-02-21 | Monte             | W   | 0.089      | -            | -                | -                | -         |     0.04 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4143 | 2024-02-20 | HEROIC            | L   | 0.083      | -            | -                | -                | -         |    -1.88 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4158 | 2024-02-19 | Spirit            | L   | 0.079      | -            | -                | -                | -         |    -0.68 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4168 | 2024-02-19 | Nexus             | W   | 0.077      | -            | -                | -                | -         |     0.02 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($125,056.30)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.39) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-16 |      0.864 | $20,000.00     | $17,272.22      |
| 2024-06-09 |      0.817 | $28,000.00     | $22,882.22      |
| 2024-05-23 |      0.703 | $50,000.00     | $35,173.61      |
| 2024-05-12 |      0.631 | $45,000.00     | $28,375.00      |
| 2024-04-14 |      0.443 | $20,000.00     | $8,853.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
