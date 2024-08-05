### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1705.4<br />
<br />
Final Rank Value (1705.4) = Starting Rank Value (1730.0) + Head To Head Adjustments (-24.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.709[<sup>1</sup>](#table2)
- Bounty Collected: 0.621[<sup>2</sup>](#table1)
- Opponent Network: 0.322[<sup>2</sup>](#table1)
- LAN Wins: 0.942[<sup>2</sup>](#table1)

The average of these factors is 0.649<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1730.0
- 400 + ( ( 0.649 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1730.0


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
|           34 |       37 | 2024-08-04 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | 0.254 (0.148)    | 0.544 (0.316)    | 1 (1.000) |    10.62 | br0, device, jabbi, Staehr, stavn    |
|           33 |       69 | 2024-08-03 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.51 | br0, device, jabbi, Staehr, stavn    |
|           32 |      108 | 2024-08-02 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.73 | br0, device, jabbi, Staehr, stavn    |
|           31 |      233 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |   -10.03 | br0, device, jabbi, Staehr, stavn    |
|           30 |      261 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.63 | br0, device, jabbi, Staehr, stavn    |
|           29 |     1084 | 2024-06-14 | Virtus.pro        | L   | 0.853      | -            | -                | -                | -         |   -15.27 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1143 | 2024-06-13 | SAW               | W   | 0.845      | 0.729        | -                | 0.530 (0.326)    | 1 (0.845) |     1.16 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1166 | 2024-06-12 | Natus Vincere     | L   | 0.839      | -            | -                | -                | -         |    -6.65 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1327 | 2024-06-08 | The MongolZ       | L   | 0.812      | -            | -                | -                | -         |    -7.30 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1382 | 2024-06-07 | BetBoom           | W   | 0.805      | 0.715        | 0.249 (0.143)    | 0.529 (0.305)    | 1 (0.805) |     3.83 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1429 | 2024-06-06 | The MongolZ       | W   | 0.800      | 0.715        | 1.000 (0.572)    | 0.710 (0.406)    | 1 (0.800) |    18.57 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1449 | 2024-06-06 | ENCE              | W   | 0.798      | 0.715        | -                | 0.432 (0.247)    | 1 (0.798) |     3.04 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1459 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.798      | -            | -                | -                | -         |   -17.19 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1505 | 2024-06-05 | Sashi             | L   | 0.792      | -            | -                | -                | -         |   -23.78 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1518 | 2024-06-05 | HEROIC            | W   | 0.790      | 0.715        | -                | 0.365 (0.206)    | 1 (0.790) |     6.90 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1867 | 2024-05-22 | Liquid            | L   | 0.698      | -            | -                | -                | -         |   -15.35 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1908 | 2024-05-21 | Aurora            | W   | 0.692      | 0.769        | 0.422 (0.224)    | 0.778 (0.414)    | -         |     5.37 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1938 | 2024-05-20 | BetBoom           | W   | 0.686      | 0.769        | 0.249 (0.131)    | 0.529 (0.279)    | -         |     2.33 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1958 | 2024-05-19 | BIG               | W   | 0.680      | -            | -                | -                | -         |     1.63 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2254 | 2024-05-11 | Vitality          | L   | 0.625      | -            | -                | -                | -         |    -6.80 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2273 | 2024-05-10 | Liquid            | W   | 0.619      | 0.889        | 0.383 (0.211)    | 0.450 (0.247)    | 1 (0.619) |     5.68 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2540 | 2024-04-27 | 3DMAX             | W   | 0.532      | 0.889        | 0.508 (0.240)    | 1.000 (0.473)    | 1 (0.532) |     5.83 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2611 | 2024-04-24 | FaZe              | W   | 0.513      | 0.889        | 0.630 (0.288)    | -                | -         |     7.58 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2631 | 2024-04-23 | Eternal Fire      | W   | 0.506      | 0.889        | 0.740 (0.333)    | -                | -         |     7.22 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2918 | 2024-04-13 | FaZe              | L   | 0.438      | -            | -                | -                | -         |    -7.55 | br0, device, jabbi, Staehr, stavn    |
|            9 |     3018 | 2024-04-10 | Virtus.pro        | W   | 0.417      | -            | -                | -                | -         |     5.95 | br0, device, jabbi, Staehr, stavn    |
|            8 |     3066 | 2024-04-09 | FaZe              | W   | 0.411      | 0.624        | 0.630 (0.162)    | -                | -         |     5.96 | br0, device, jabbi, Staehr, stavn    |
|            7 |     3098 | 2024-04-08 | Steel Helmet      | W   | 0.404      | -            | -                | -                | -         |     0.02 | br0, device, jabbi, Staehr, stavn    |
|            6 |     4069 | 2024-02-23 | 9 Pandas          | L   | 0.105      | -            | -                | -                | -         |    -3.24 | blameF, device, jabbi, Staehr, stavn |
|            5 |     4088 | 2024-02-22 | ENCE              | L   | 0.098      | -            | -                | -                | -         |    -2.48 | blameF, device, jabbi, Staehr, stavn |
|            4 |     4115 | 2024-02-21 | Monte             | W   | 0.091      | -            | -                | -                | -         |     0.05 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4141 | 2024-02-20 | HEROIC            | L   | 0.085      | -            | -                | -                | -         |    -1.92 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4156 | 2024-02-19 | Spirit            | L   | 0.080      | -            | -                | -                | -         |    -0.69 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4166 | 2024-02-19 | Nexus             | W   | 0.079      | -            | -                | -                | -         |     0.02 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($125,350.60)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.39) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-16 |      0.865 | $20,000.00     | $17,308.33      |
| 2024-06-09 |      0.819 | $28,000.00     | $22,932.78      |
| 2024-05-23 |      0.705 | $50,000.00     | $35,263.89      |
| 2024-05-12 |      0.632 | $45,000.00     | $28,456.25      |
| 2024-04-14 |      0.444 | $20,000.00     | $8,889.35       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
