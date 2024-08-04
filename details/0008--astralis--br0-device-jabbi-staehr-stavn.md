### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1667.1<br />
<br />
Final Rank Value (1667.1) = Starting Rank Value (1687.0) + Head To Head Adjustments (-19.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.688[<sup>1</sup>](#table2)
- Bounty Collected: 0.621[<sup>2</sup>](#table1)
- Opponent Network: 0.320[<sup>2</sup>](#table1)
- LAN Wins: 0.890[<sup>2</sup>](#table1)

The average of these factors is 0.630<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1687.0
- 400 + ( ( 0.630 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1687.0


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
|           33 |       10 | 2024-08-03 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -8.65 | br0, device, jabbi, Staehr, stavn    |
|           32 |       49 | 2024-08-02 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     6.52 | br0, device, jabbi, Staehr, stavn    |
|           31 |      172 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.04 | br0, device, jabbi, Staehr, stavn    |
|           30 |      200 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     6.48 | br0, device, jabbi, Staehr, stavn    |
|           29 |     1022 | 2024-06-14 | Virtus.pro        | L   | 0.865      | -            | -                | -                | -         |   -14.34 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1081 | 2024-06-13 | SAW               | W   | 0.857      | 0.729        | -                | 0.541 (0.338)    | 1 (0.857) |     1.40 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1104 | 2024-06-12 | Natus Vincere     | L   | 0.851      | -            | -                | -                | -         |    -5.96 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1265 | 2024-06-08 | The MongolZ       | L   | 0.824      | -            | -                | -                | -         |    -6.65 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1320 | 2024-06-07 | BetBoom           | W   | 0.817      | 0.715        | 0.252 (0.147)    | 0.543 (0.318)    | 1 (0.817) |     4.61 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1367 | 2024-06-06 | The MongolZ       | W   | 0.812      | 0.715        | 1.000 (0.581)    | 0.720 (0.418)    | 1 (0.812) |    19.62 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1387 | 2024-06-06 | ENCE              | W   | 0.810      | 0.715        | -                | 0.401 (0.232)    | 1 (0.810) |     3.45 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1397 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.810      | -            | -                | -                | -         |   -16.70 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1443 | 2024-06-05 | Sashi             | L   | 0.804      | -            | -                | -                | -         |   -23.91 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1456 | 2024-06-05 | HEROIC            | W   | 0.803      | 0.715        | -                | 0.375 (0.215)    | 1 (0.803) |     8.07 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1805 | 2024-05-22 | Liquid            | L   | 0.710      | -            | -                | -                | -         |   -16.64 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1846 | 2024-05-21 | Aurora            | W   | 0.704      | 0.769        | 0.424 (0.230)    | 0.794 (0.430)    | -         |     6.15 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1876 | 2024-05-20 | BetBoom           | W   | 0.698      | 0.769        | 0.252 (0.135)    | 0.543 (0.292)    | -         |     2.89 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1896 | 2024-05-19 | BIG               | W   | 0.692      | -            | -                | -                | -         |     2.03 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2192 | 2024-05-11 | Vitality          | L   | 0.638      | -            | -                | -                | -         |    -6.05 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2211 | 2024-05-10 | Liquid            | W   | 0.631      | 0.889        | 0.316 (0.177)    | 0.461 (0.259)    | 1 (0.631) |     4.83 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2478 | 2024-04-27 | 3DMAX             | W   | 0.544      | 0.889        | 0.505 (0.244)    | 1.000 (0.484)    | 1 (0.544) |     6.65 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2548 | 2024-04-24 | FaZe              | W   | 0.525      | 0.889        | 0.643 (0.300)    | -                | 1 (0.525) |     8.73 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2568 | 2024-04-23 | Eternal Fire      | W   | 0.518      | 0.889        | 0.743 (0.342)    | 0.458 (0.211)    | -         |     8.34 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2855 | 2024-04-13 | FaZe              | L   | 0.450      | -            | -                | -                | -         |    -6.88 | br0, device, jabbi, Staehr, stavn    |
|            9 |     2955 | 2024-04-10 | Virtus.pro        | W   | 0.429      | 0.624        | 0.496 (0.133)    | -                | -         |     6.93 | br0, device, jabbi, Staehr, stavn    |
|            8 |     3003 | 2024-04-09 | FaZe              | W   | 0.423      | 0.624        | 0.643 (0.170)    | -                | -         |     7.05 | br0, device, jabbi, Staehr, stavn    |
|            7 |     3035 | 2024-04-08 | Steel Helmet      | W   | 0.416      | -            | -                | -                | -         |     0.03 | br0, device, jabbi, Staehr, stavn    |
|            6 |     4005 | 2024-02-23 | 9 Pandas          | L   | 0.117      | -            | -                | -                | -         |    -3.60 | blameF, device, jabbi, Staehr, stavn |
|            5 |     4024 | 2024-02-22 | ENCE              | L   | 0.110      | -            | -                | -                | -         |    -2.68 | blameF, device, jabbi, Staehr, stavn |
|            4 |     4051 | 2024-02-21 | Monte             | W   | 0.103      | -            | -                | -                | -         |     0.07 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4077 | 2024-02-20 | HEROIC            | L   | 0.097      | -            | -                | -                | -         |    -2.03 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4092 | 2024-02-19 | Spirit            | L   | 0.092      | -            | -                | -                | -         |    -0.67 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4102 | 2024-02-19 | Nexus             | W   | 0.091      | -            | -                | -                | -         |     0.02 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($114,820.19)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.35) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.877 | $20,000.00     | $17,550.00      |
| 2024-06-09 |      0.831 | $28,000.00     | $23,271.11      |
| 2024-05-23 |      0.717 | $50,000.00     | $35,868.06      |
| 2024-05-12 |      0.644 | $45,000.00     | $29,000.00      |
| 2024-04-14 |      0.457 | $20,000.00     | $9,131.02       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
