### Roster Details<br />
Team Name: Portugal<br />
Roster: Ag1l, aragornN, Icarus, NOPEEJ, rafaxF<br />
Global Rank: [172](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [110]( ../standings_europe.md)<br />
<br />
Final Rank Value:  664.1<br />
<br />
Final Rank Value (664.1) = Starting Rank Value (684.5) + Head To Head Adjustments (-20.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.281[<sup>1</sup>](#table2)
- Bounty Collected: 0.231[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.038[<sup>2</sup>](#table1)

The average of these factors is 0.139<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 684.5
- 400 + ( ( 0.139 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 684.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |      807 | 2024-07-14 | Sampi            | L   | 1.000      | -            | -                | -                | -         |    -6.69 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           15 |      818 | 2024-07-13 | The Suspect      | L   | 1.000      | -            | -                | -                | -         |    -9.07 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           14 |      909 | 2024-07-08 | Norway           | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.107 (0.015)    | 0 (0.000) |    16.31 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|           13 |     1591 | 2024-06-01 | FLuffy Gangsters | L   | 0.772      | -            | -                | -                | -         |   -15.56 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           12 |     1652 | 2024-05-30 | RUBY             | L   | 0.758      | -            | -                | -                | -         |    -4.63 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           11 |     1689 | 2024-05-29 | TNL              | W   | 0.751      | 0.372        | 0.000 (0.000)    | 0.040 (0.011)    | 0 (0.000) |     6.37 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           10 |     2230 | 2024-05-11 | AL QATRAO        | L   | 0.631      | -            | -                | -                | -         |    -9.88 | Ag1l, aragornN, fox, pr, rafaxF        |
|            9 |     2671 | 2024-04-20 | 1WIN             | L   | 0.491      | -            | -                | -                | -         |    -3.03 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            8 |     2714 | 2024-04-19 | Secret           | W   | 0.485      | 0.143        | 0.000 (0.000)    | 0.058 (0.004)    | 0 (0.000) |     4.88 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            7 |     2757 | 2024-04-18 | Illuminar        | L   | 0.478      | -            | -                | -                | -         |   -10.80 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            6 |     2805 | 2024-04-17 | 500              | W   | 0.471      | 0.143        | 0.001 (0.000)    | 0.097 (0.007)    | 0 (0.000) |     8.61 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            5 |     3874 | 2024-03-03 | Rhyno            | W   | 0.170      | 0.314        | 0.071 (0.004)    | 0.404 (0.022)    | 1 (0.170) |     4.45 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            4 |     3895 | 2024-03-02 | OVERFRAG         | W   | 0.163      | 0.314        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.163) |     1.46 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            3 |     4027 | 2024-02-24 | 500              | L   | 0.117      | -            | -                | -                | -         |    -1.76 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            2 |     4167 | 2024-02-18 | Alliance         | L   | 0.076      | -            | -                | -                | -         |    -0.68 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            1 |     4335 | 2024-02-11 | Young Ninjas     | L   | 0.031      | -            | -                | -                | -         |    -0.40 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($896.89)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.637 | $539.00        | $343.31         |
| 2024-03-03 |      0.170 | $3,251.00      | $553.57         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
