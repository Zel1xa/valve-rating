### Roster Details<br />
Team Name: Patins da Ferrari<br />
Roster: CSO, CutzMeretz, Leomonster, Misfit, zede<br />
Global Rank: [142](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [38]( ../standings_americas.md)<br />
<br />
Final Rank Value:  743.8<br />
<br />
Final Rank Value (743.8) = Starting Rank Value (790.0) + Head To Head Adjustments (-46.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.312[<sup>2</sup>](#table1)
- Opponent Network: 0.107[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 790.0
- 400 + ( ( 0.191 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 790.0


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
|           24 |      238 | 2024-07-27 | Case           | L   | 1.000      | -            | -                | -                | -         |    -9.49 | CSO, CutzMeretz, Leomonster, Misfit, zede |
|           23 |      254 | 2024-07-26 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -6.24 | CSO, CutzMeretz, Leomonster, Misfit, zede |
|           22 |      266 | 2024-07-26 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -7.29 | CSO, CutzMeretz, Leomonster, Misfit, zede |
|           21 |      290 | 2024-07-25 | Sharks         | L   | 1.000      | -            | -                | -                | -         |    -7.61 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           20 |      369 | 2024-07-23 | Galorys        | L   | 1.000      | -            | -                | -                | -         |   -15.01 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           19 |      396 | 2024-07-22 | paiN Academy   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.04 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           18 |      405 | 2024-07-22 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -7.18 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           17 |      431 | 2024-07-21 | FURIA Academy  | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.108 (0.040)    | 0 (0.000) |     5.98 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           16 |      470 | 2024-07-20 | KRÜ            | L   | 1.000      | -            | -                | -                | -         |   -13.16 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           15 |      597 | 2024-07-17 | Hawks          | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.030 (0.011)    | 0 (0.000) |     5.81 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           14 |      657 | 2024-07-16 | Vikings KR     | L   | 1.000      | -            | -                | -                | -         |   -14.95 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           13 |      791 | 2024-07-10 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -9.02 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|           12 |      813 | 2024-07-09 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -14.54 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|           11 |      831 | 2024-07-08 | Sharks         | L   | 1.000      | -            | -                | -                | -         |    -9.38 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|           10 |      854 | 2024-07-06 | 9z Academy     | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.072 (0.024)    | 0 (0.000) |     4.08 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|            9 |      864 | 2024-07-01 | Vikings KR     | L   | 0.981      | -            | -                | -                | -         |   -16.23 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            8 |      867 | 2024-06-30 | Sharks         | W   | 0.974      | 0.333        | 0.031 (0.010)    | 0.583 (0.189)    | 0 (0.000) |    21.59 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            7 |      877 | 2024-06-29 | Bounty Hunters | L   | 0.966      | -            | -                | -                | -         |   -10.77 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            6 |      893 | 2024-06-26 | Dusty Roots    | W   | 0.947      | 0.333        | 0.006 (0.002)    | 0.299 (0.094)    | 0 (0.000) |    14.46 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            5 |      980 | 2024-06-14 | inSanitY       | L   | 0.867      | -            | -                | -                | -         |    -8.55 | CutzMeretz, desh, Leomonster, roz, zede   |
|            4 |     1140 | 2024-06-09 | Vikings KR     | W   | 0.833      | 0.450        | 0.008 (0.003)    | 0.479 (0.179)    | 0 (0.000) |    12.24 | CutzMeretz, desh, Leomonster, roz, zede   |
|            3 |     1202 | 2024-06-08 | Sharks         | W   | 0.826      | 0.450        | 0.031 (0.011)    | 0.583 (0.217)    | 0 (0.000) |    19.90 | CutzMeretz, desh, Leomonster, roz, zede   |
|            2 |     1226 | 2024-06-07 | paiN           | L   | 0.822      | -            | -                | -                | -         |    -1.51 | CutzMeretz, desh, Leomonster, roz, zede   |
|            1 |     1310 | 2024-06-06 | ODDIK          | W   | 0.813      | 0.450        | 0.098 (0.036)    | 0.857 (0.314)    | 0 (0.000) |    17.59 | CutzMeretz, desh, Leomonster, roz, zede   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,000.81)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $1,800.00      | $1,800.00       |
| 2024-06-16 |      0.880 | $2,500.00      | $2,200.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
