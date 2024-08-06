### Roster Details<br />
Team Name: Patins da Ferrari<br />
Roster: CSO, CutzMeretz, Leomonster, Misfit, zede<br />
Global Rank: [144](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [39]( ../standings_americas.md)<br />
<br />
Final Rank Value:  748.4<br />
<br />
Final Rank Value (748.4) = Starting Rank Value (789.6) + Head To Head Adjustments (-41.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.311[<sup>2</sup>](#table1)
- Opponent Network: 0.105[<sup>2</sup>](#table1)
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
|           24 |      324 | 2024-07-27 | Case           | L   | 1.000      | -            | -                | -                | -         |    -9.40 | CSO, CutzMeretz, Leomonster, Misfit, zede |
|           23 |      340 | 2024-07-26 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -5.60 | CSO, CutzMeretz, Leomonster, Misfit, zede |
|           22 |      352 | 2024-07-26 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -6.54 | CSO, CutzMeretz, Leomonster, Misfit, zede |
|           21 |      376 | 2024-07-25 | Sharks         | L   | 1.000      | -            | -                | -                | -         |    -7.23 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           20 |      455 | 2024-07-23 | Galorys        | L   | 1.000      | -            | -                | -                | -         |   -14.56 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           19 |      482 | 2024-07-22 | paiN Academy   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.01 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           18 |      492 | 2024-07-22 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -6.34 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           17 |      517 | 2024-07-21 | FURIA Academy  | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.104 (0.039)    | 0 (0.000) |     5.96 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           16 |      554 | 2024-07-20 | KRÜ            | L   | 1.000      | -            | -                | -                | -         |   -13.50 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           15 |      683 | 2024-07-17 | Hawks          | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.029 (0.011)    | 0 (0.000) |     5.71 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           14 |      746 | 2024-07-16 | Vikings KR     | L   | 1.000      | -            | -                | -                | -         |   -14.80 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           13 |      885 | 2024-07-10 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -8.57 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|           12 |      907 | 2024-07-09 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -14.76 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|           11 |      925 | 2024-07-08 | Sharks         | L   | 1.000      | -            | -                | -                | -         |    -8.95 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|           10 |      948 | 2024-07-06 | 9z Academy     | W   | 0.999      | 0.333        | 0.000 (0.000)    | 0.069 (0.023)    | 0 (0.000) |     4.07 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|            9 |      958 | 2024-07-01 | Vikings KR     | L   | 0.965      | -            | -                | -                | -         |   -15.78 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            8 |      961 | 2024-06-30 | Sharks         | W   | 0.959      | 0.333        | 0.030 (0.010)    | 0.558 (0.178)    | 0 (0.000) |    21.70 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            7 |      971 | 2024-06-29 | Bounty Hunters | L   | 0.951      | -            | -                | -                | -         |   -10.42 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            6 |      988 | 2024-06-26 | Dusty Roots    | W   | 0.931      | 0.333        | 0.006 (0.002)    | 0.366 (0.114)    | 0 (0.000) |    14.57 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            5 |     1092 | 2024-06-14 | inSanitY       | L   | 0.851      | -            | -                | -                | -         |    -8.26 | CutzMeretz, desh, Leomonster, roz, zede   |
|            4 |     1259 | 2024-06-09 | Vikings KR     | W   | 0.817      | 0.450        | 0.008 (0.003)    | 0.500 (0.184)    | 0 (0.000) |    12.23 | CutzMeretz, desh, Leomonster, roz, zede   |
|            3 |     1325 | 2024-06-08 | Sharks         | W   | 0.810      | 0.450        | 0.030 (0.011)    | 0.558 (0.204)    | 0 (0.000) |    19.90 | CutzMeretz, desh, Leomonster, roz, zede   |
|            2 |     1350 | 2024-06-07 | paiN           | L   | 0.806      | -            | -                | -                | -         |    -1.25 | CutzMeretz, desh, Leomonster, roz, zede   |
|            1 |     1434 | 2024-06-06 | ODDIK          | W   | 0.798      | 0.450        | 0.099 (0.036)    | 0.822 (0.295)    | 0 (0.000) |    17.62 | CutzMeretz, desh, Leomonster, roz, zede   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,961.81)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $1,800.00      | $1,800.00       |
| 2024-06-16 |      0.865 | $2,500.00      | $2,161.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
