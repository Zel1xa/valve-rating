### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1704.1<br />
<br />
Final Rank Value (1704.1) = Starting Rank Value (1727.6) + Head To Head Adjustments (-23.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.709[<sup>1</sup>](#table2)
- Bounty Collected: 0.619[<sup>2</sup>](#table1)
- Opponent Network: 0.312[<sup>2</sup>](#table1)
- LAN Wins: 0.941[<sup>2</sup>](#table1)

The average of these factors is 0.645<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1727.6
- 400 + ( ( 0.645 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1727.6


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
|           34 |       61 | 2024-08-04 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | 0.253 (0.147)    | 0.531 (0.309)    | 1 (1.000) |    10.66 | br0, device, jabbi, Staehr, stavn    |
|           33 |       93 | 2024-08-03 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.51 | br0, device, jabbi, Staehr, stavn    |
|           32 |      132 | 2024-08-02 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.73 | br0, device, jabbi, Staehr, stavn    |
|           31 |      257 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |   -10.03 | br0, device, jabbi, Staehr, stavn    |
|           30 |      285 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.62 | br0, device, jabbi, Staehr, stavn    |
|           29 |     1108 | 2024-06-14 | Virtus.pro        | L   | 0.847      | -            | -                | -                | -         |   -15.18 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1167 | 2024-06-13 | SAW               | W   | 0.838      | 0.729        | -                | 0.516 (0.316)    | 1 (0.838) |     1.18 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1190 | 2024-06-12 | Natus Vincere     | L   | 0.832      | -            | -                | -                | -         |    -6.57 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1351 | 2024-06-08 | The MongolZ       | L   | 0.806      | -            | -                | -                | -         |    -7.21 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1406 | 2024-06-07 | BetBoom           | W   | 0.799      | 0.715        | 0.248 (0.141)    | 0.513 (0.293)    | 1 (0.799) |     3.82 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1453 | 2024-06-06 | The MongolZ       | W   | 0.793      | 0.715        | 1.000 (0.568)    | 0.694 (0.394)    | 1 (0.793) |    18.46 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1473 | 2024-06-06 | ENCE              | W   | 0.792      | 0.715        | -                | 0.422 (0.239)    | 1 (0.792) |     3.09 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1483 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.791      | -            | -                | -                | -         |   -17.02 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1529 | 2024-06-05 | Sashi             | L   | 0.786      | -            | -                | -                | -         |   -23.58 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1542 | 2024-06-05 | HEROIC            | W   | 0.784      | 0.715        | -                | 0.354 (0.199)    | 1 (0.784) |     6.83 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1891 | 2024-05-22 | Liquid            | L   | 0.692      | -            | -                | -                | -         |   -15.19 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1932 | 2024-05-21 | Aurora            | W   | 0.686      | 0.769        | 0.420 (0.221)    | 0.758 (0.400)    | -         |     5.48 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1962 | 2024-05-20 | BetBoom           | W   | 0.680      | 0.769        | 0.248 (0.129)    | 0.513 (0.268)    | -         |     2.33 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1982 | 2024-05-19 | BIG               | W   | 0.674      | -            | -                | -                | -         |     1.63 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2278 | 2024-05-11 | Vitality          | L   | 0.619      | -            | -                | -                | -         |    -6.71 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2297 | 2024-05-10 | Liquid            | W   | 0.613      | 0.889        | 0.383 (0.208)    | 0.437 (0.238)    | 1 (0.613) |     5.66 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2564 | 2024-04-27 | 3DMAX             | W   | 0.526      | 0.889        | 0.510 (0.239)    | 1.000 (0.468)    | 1 (0.526) |     5.89 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2635 | 2024-04-24 | FaZe              | W   | 0.507      | 0.889        | 0.624 (0.281)    | -                | -         |     7.45 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2655 | 2024-04-23 | Eternal Fire      | W   | 0.500      | 0.889        | 0.738 (0.328)    | -                | -         |     7.16 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2942 | 2024-04-13 | FaZe              | L   | 0.432      | -            | -                | -                | -         |    -7.48 | br0, device, jabbi, Staehr, stavn    |
|            9 |     3042 | 2024-04-10 | Virtus.pro        | W   | 0.411      | -            | -                | -                | -         |     5.86 | br0, device, jabbi, Staehr, stavn    |
|            8 |     3090 | 2024-04-09 | FaZe              | W   | 0.405      | 0.624        | 0.624 (0.158)    | -                | -         |     5.84 | br0, device, jabbi, Staehr, stavn    |
|            7 |     3122 | 2024-04-08 | Steel Helmet      | W   | 0.398      | -            | -                | -                | -         |     0.02 | br0, device, jabbi, Staehr, stavn    |
|            6 |     4093 | 2024-02-23 | 9 Pandas          | L   | 0.098      | -            | -                | -                | -         |    -3.05 | blameF, device, jabbi, Staehr, stavn |
|            5 |     4112 | 2024-02-22 | ENCE              | L   | 0.092      | -            | -                | -                | -         |    -2.31 | blameF, device, jabbi, Staehr, stavn |
|            4 |     4139 | 2024-02-21 | Monte             | W   | 0.085      | -            | -                | -                | -         |     0.04 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4165 | 2024-02-20 | HEROIC            | L   | 0.079      | -            | -                | -                | -         |    -1.79 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4180 | 2024-02-19 | Spirit            | L   | 0.074      | -            | -                | -                | -         |    -0.63 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4190 | 2024-02-19 | Nexus             | W   | 0.072      | -            | -                | -                | -         |     0.02 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($124,354.49)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.39) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-16 |      0.859 | $20,000.00     | $17,186.11      |
| 2024-06-09 |      0.813 | $28,000.00     | $22,761.67      |
| 2024-05-23 |      0.699 | $50,000.00     | $34,958.33      |
| 2024-05-12 |      0.626 | $45,000.00     | $28,181.25      |
| 2024-04-14 |      0.438 | $20,000.00     | $8,767.13       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
