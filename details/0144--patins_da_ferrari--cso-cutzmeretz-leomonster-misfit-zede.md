### Roster Details<br />
Team Name: Patins da Ferrari<br />
Roster: CSO, CutzMeretz, Leomonster, Misfit, zede<br />
Global Rank: [144](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [39]( ../standings_americas.md)<br />
<br />
Final Rank Value:  748.3<br />
<br />
Final Rank Value (748.3) = Starting Rank Value (789.6) + Head To Head Adjustments (-41.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.311[<sup>2</sup>](#table1)
- Opponent Network: 0.104[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.190<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 789.6
- 400 + ( ( 0.190 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 789.6


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
|           24 |      328 | 2024-07-27 | Case           | L   | 1.000      | -            | -                | -                | -         |    -9.40 | CSO, CutzMeretz, Leomonster, Misfit, zede |
|           23 |      344 | 2024-07-26 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -5.60 | CSO, CutzMeretz, Leomonster, Misfit, zede |
|           22 |      356 | 2024-07-26 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -6.55 | CSO, CutzMeretz, Leomonster, Misfit, zede |
|           21 |      380 | 2024-07-25 | Sharks         | L   | 1.000      | -            | -                | -                | -         |    -7.23 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           20 |      459 | 2024-07-23 | Galorys        | L   | 1.000      | -            | -                | -                | -         |   -14.55 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           19 |      486 | 2024-07-22 | paiN Academy   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.02 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           18 |      496 | 2024-07-22 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -6.34 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           17 |      521 | 2024-07-21 | FURIA Academy  | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.104 (0.039)    | 0 (0.000) |     5.96 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           16 |      558 | 2024-07-20 | KRÜ            | L   | 1.000      | -            | -                | -                | -         |   -13.49 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           15 |      687 | 2024-07-17 | Hawks          | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.029 (0.011)    | 0 (0.000) |     5.71 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           14 |      750 | 2024-07-16 | Vikings KR     | L   | 1.000      | -            | -                | -                | -         |   -14.79 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           13 |      889 | 2024-07-10 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -8.57 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|           12 |      911 | 2024-07-09 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -14.75 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|           11 |      929 | 2024-07-08 | Sharks         | L   | 1.000      | -            | -                | -                | -         |    -8.95 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|           10 |      952 | 2024-07-06 | 9z Academy     | W   | 0.996      | 0.333        | 0.000 (0.000)    | 0.069 (0.023)    | 0 (0.000) |     4.07 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|            9 |      962 | 2024-07-01 | Vikings KR     | L   | 0.963      | -            | -                | -                | -         |   -15.73 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            8 |      965 | 2024-06-30 | Sharks         | W   | 0.956      | 0.333        | 0.030 (0.010)    | 0.558 (0.178)    | 0 (0.000) |    21.64 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            7 |      975 | 2024-06-29 | Bounty Hunters | L   | 0.948      | -            | -                | -                | -         |   -10.40 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            6 |      992 | 2024-06-26 | Dusty Roots    | W   | 0.929      | 0.333        | 0.006 (0.002)    | 0.366 (0.113)    | 0 (0.000) |    14.54 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            5 |     1096 | 2024-06-14 | inSanitY       | L   | 0.849      | -            | -                | -                | -         |    -8.24 | CutzMeretz, desh, Leomonster, roz, zede   |
|            4 |     1263 | 2024-06-09 | Vikings KR     | W   | 0.814      | 0.450        | 0.008 (0.003)    | 0.501 (0.184)    | 0 (0.000) |    12.20 | CutzMeretz, desh, Leomonster, roz, zede   |
|            3 |     1329 | 2024-06-08 | Sharks         | W   | 0.808      | 0.450        | 0.030 (0.011)    | 0.558 (0.203)    | 0 (0.000) |    19.83 | CutzMeretz, desh, Leomonster, roz, zede   |
|            2 |     1354 | 2024-06-07 | paiN           | L   | 0.804      | -            | -                | -                | -         |    -1.25 | CutzMeretz, desh, Leomonster, roz, zede   |
|            1 |     1438 | 2024-06-06 | ODDIK          | W   | 0.795      | 0.450        | 0.099 (0.035)    | 0.823 (0.294)    | 0 (0.000) |    17.57 | CutzMeretz, desh, Leomonster, roz, zede   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,955.56)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $1,800.00      | $1,800.00       |
| 2024-06-16 |      0.862 | $2,500.00      | $2,155.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />