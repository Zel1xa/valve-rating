### Roster Details<br />
Team Name: Patins da Ferrari<br />
Roster: CSO, CutzMeretz, Leomonster, Misfit, zede<br />
Global Rank: [144](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [39]( ../standings_americas.md)<br />
<br />
Final Rank Value:  747.5<br />
<br />
Final Rank Value (747.5) = Starting Rank Value (789.3) + Head To Head Adjustments (-41.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.311[<sup>2</sup>](#table1)
- Opponent Network: 0.102[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 789.3
- 400 + ( ( 0.189 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 789.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      347 | 2024-07-27 | Case           | L   | 1.000      | -            | -                | -                | -         |    -9.41 | CSO, CutzMeretz, Leomonster, Misfit, zede |
|           23 |      363 | 2024-07-26 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -5.61 | CSO, CutzMeretz, Leomonster, Misfit, zede |
|           22 |      375 | 2024-07-26 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -6.56 | CSO, CutzMeretz, Leomonster, Misfit, zede |
|           21 |      399 | 2024-07-25 | Sharks         | L   | 1.000      | -            | -                | -                | -         |    -7.26 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           20 |      478 | 2024-07-23 | Galorys        | L   | 1.000      | -            | -                | -                | -         |   -14.56 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           19 |      505 | 2024-07-22 | paiN Academy   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.03 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           18 |      515 | 2024-07-22 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -6.36 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           17 |      540 | 2024-07-21 | FURIA Academy  | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.102 (0.038)    | 0 (0.000) |     5.98 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           16 |      577 | 2024-07-20 | KRÜ            | L   | 1.000      | -            | -                | -                | -         |   -13.52 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           15 |      706 | 2024-07-17 | Hawks          | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.028 (0.010)    | 0 (0.000) |     5.72 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           14 |      769 | 2024-07-16 | Vikings KR     | L   | 1.000      | -            | -                | -                | -         |   -14.81 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           13 |      908 | 2024-07-10 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -8.59 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|           12 |      930 | 2024-07-09 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -14.78 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|           11 |      948 | 2024-07-08 | Sharks         | L   | 1.000      | -            | -                | -                | -         |    -8.99 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|           10 |      971 | 2024-07-06 | 9z Academy     | W   | 0.994      | 0.333        | 0.000 (0.000)    | 0.067 (0.022)    | 0 (0.000) |     4.08 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|            9 |      981 | 2024-07-01 | Vikings KR     | L   | 0.961      | -            | -                | -                | -         |   -15.72 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            8 |      984 | 2024-06-30 | Sharks         | W   | 0.954      | 0.333        | 0.030 (0.010)    | 0.547 (0.174)    | 0 (0.000) |    21.57 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            7 |      994 | 2024-06-29 | Bounty Hunters | L   | 0.947      | -            | -                | -                | -         |   -10.42 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            6 |     1011 | 2024-06-26 | Dusty Roots    | W   | 0.927      | 0.333        | 0.006 (0.002)    | 0.359 (0.111)    | 0 (0.000) |    14.52 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            5 |     1115 | 2024-06-14 | inSanitY       | L   | 0.847      | -            | -                | -                | -         |    -8.26 | CutzMeretz, desh, Leomonster, roz, zede   |
|            4 |     1282 | 2024-06-09 | Vikings KR     | W   | 0.813      | 0.450        | 0.008 (0.003)    | 0.490 (0.179)    | 0 (0.000) |    12.15 | CutzMeretz, desh, Leomonster, roz, zede   |
|            3 |     1348 | 2024-06-08 | Sharks         | W   | 0.806      | 0.450        | 0.030 (0.011)    | 0.547 (0.198)    | 0 (0.000) |    19.75 | CutzMeretz, desh, Leomonster, roz, zede   |
|            2 |     1373 | 2024-06-07 | paiN           | L   | 0.802      | -            | -                | -                | -         |    -1.25 | CutzMeretz, desh, Leomonster, roz, zede   |
|            1 |     1457 | 2024-06-06 | ODDIK          | W   | 0.793      | 0.450        | 0.099 (0.035)    | 0.805 (0.288)    | 0 (0.000) |    17.50 | CutzMeretz, desh, Leomonster, roz, zede   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,951.04)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $1,800.00      | $1,800.00       |
| 2024-06-16 |      0.860 | $2,500.00      | $2,151.04       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
