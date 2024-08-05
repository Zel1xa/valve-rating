### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1705.5<br />
<br />
Final Rank Value (1705.5) = Starting Rank Value (1730.2) + Head To Head Adjustments (-24.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.709[<sup>1</sup>](#table2)
- Bounty Collected: 0.621[<sup>2</sup>](#table1)
- Opponent Network: 0.322[<sup>2</sup>](#table1)
- LAN Wins: 0.942[<sup>2</sup>](#table1)

The average of these factors is 0.649<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1730.2
- 400 + ( ( 0.649 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1730.2


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
|           34 |       36 | 2024-08-04 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | 0.254 (0.148)    | 0.544 (0.316)    | 1 (1.000) |    10.62 | br0, device, jabbi, Staehr, stavn    |
|           33 |       68 | 2024-08-03 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.51 | br0, device, jabbi, Staehr, stavn    |
|           32 |      107 | 2024-08-02 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.74 | br0, device, jabbi, Staehr, stavn    |
|           31 |      232 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |   -10.03 | br0, device, jabbi, Staehr, stavn    |
|           30 |      260 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.63 | br0, device, jabbi, Staehr, stavn    |
|           29 |     1083 | 2024-06-14 | Virtus.pro        | L   | 0.854      | -            | -                | -                | -         |   -15.28 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1142 | 2024-06-13 | SAW               | W   | 0.845      | 0.729        | -                | 0.530 (0.327)    | 1 (0.845) |     1.16 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1165 | 2024-06-12 | Natus Vincere     | L   | 0.839      | -            | -                | -                | -         |    -6.66 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1326 | 2024-06-08 | The MongolZ       | L   | 0.812      | -            | -                | -                | -         |    -7.31 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1381 | 2024-06-07 | BetBoom           | W   | 0.806      | 0.715        | 0.249 (0.144)    | 0.529 (0.305)    | 1 (0.806) |     3.84 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1428 | 2024-06-06 | The MongolZ       | W   | 0.800      | 0.715        | 1.000 (0.572)    | 0.710 (0.406)    | 1 (0.800) |    18.57 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1448 | 2024-06-06 | ENCE              | W   | 0.799      | 0.715        | -                | 0.432 (0.247)    | 1 (0.799) |     3.04 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1458 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.798      | -            | -                | -                | -         |   -17.20 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1504 | 2024-06-05 | Sashi             | L   | 0.792      | -            | -                | -                | -         |   -23.80 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1517 | 2024-06-05 | HEROIC            | W   | 0.791      | 0.715        | -                | 0.365 (0.206)    | 1 (0.791) |     6.91 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1866 | 2024-05-22 | Liquid            | L   | 0.698      | -            | -                | -                | -         |   -15.36 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1907 | 2024-05-21 | Aurora            | W   | 0.692      | 0.769        | 0.422 (0.224)    | 0.779 (0.414)    | -         |     5.36 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1937 | 2024-05-20 | BetBoom           | W   | 0.686      | 0.769        | 0.249 (0.131)    | 0.529 (0.279)    | -         |     2.33 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1957 | 2024-05-19 | BIG               | W   | 0.680      | -            | -                | -                | -         |     1.63 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2253 | 2024-05-11 | Vitality          | L   | 0.626      | -            | -                | -                | -         |    -6.80 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2272 | 2024-05-10 | Liquid            | W   | 0.619      | 0.889        | 0.383 (0.211)    | 0.450 (0.248)    | 1 (0.619) |     5.68 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2539 | 2024-04-27 | 3DMAX             | W   | 0.533      | 0.889        | 0.508 (0.241)    | 1.000 (0.474)    | 1 (0.533) |     5.82 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2610 | 2024-04-24 | FaZe              | W   | 0.513      | 0.889        | 0.631 (0.288)    | -                | -         |     7.59 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2630 | 2024-04-23 | Eternal Fire      | W   | 0.506      | 0.889        | 0.740 (0.333)    | -                | -         |     7.23 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2917 | 2024-04-13 | FaZe              | L   | 0.438      | -            | -                | -                | -         |    -7.55 | br0, device, jabbi, Staehr, stavn    |
|            9 |     3017 | 2024-04-10 | Virtus.pro        | W   | 0.418      | -            | -                | -                | -         |     5.96 | br0, device, jabbi, Staehr, stavn    |
|            8 |     3065 | 2024-04-09 | FaZe              | W   | 0.411      | 0.624        | 0.631 (0.162)    | -                | -         |     5.97 | br0, device, jabbi, Staehr, stavn    |
|            7 |     3097 | 2024-04-08 | Steel Helmet      | W   | 0.404      | -            | -                | -                | -         |     0.02 | br0, device, jabbi, Staehr, stavn    |
|            6 |     4068 | 2024-02-23 | 9 Pandas          | L   | 0.105      | -            | -                | -                | -         |    -3.25 | blameF, device, jabbi, Staehr, stavn |
|            5 |     4087 | 2024-02-22 | ENCE              | L   | 0.098      | -            | -                | -                | -         |    -2.49 | blameF, device, jabbi, Staehr, stavn |
|            4 |     4114 | 2024-02-21 | Monte             | W   | 0.092      | -            | -                | -                | -         |     0.05 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4140 | 2024-02-20 | HEROIC            | L   | 0.085      | -            | -                | -                | -         |    -1.93 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4155 | 2024-02-19 | Spirit            | L   | 0.081      | -            | -                | -                | -         |    -0.70 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4165 | 2024-02-19 | Nexus             | W   | 0.079      | -            | -                | -                | -         |     0.02 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($125,418.52)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.39) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-16 |      0.866 | $20,000.00     | $17,316.67      |
| 2024-06-09 |      0.819 | $28,000.00     | $22,944.44      |
| 2024-05-23 |      0.706 | $50,000.00     | $35,284.72      |
| 2024-05-12 |      0.633 | $45,000.00     | $28,475.00      |
| 2024-04-14 |      0.445 | $20,000.00     | $8,897.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
