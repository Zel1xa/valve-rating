### Roster Details<br />
Team Name: Portugal<br />
Roster: Ag1l, aragornN, Icarus, NOPEEJ, rafaxF<br />
Global Rank: [170](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [108]( ../standings_europe.md)<br />
<br />
Final Rank Value:  664.2<br />
<br />
Final Rank Value (664.2) = Starting Rank Value (683.7) + Head To Head Adjustments (-19.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.280[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.036[<sup>2</sup>](#table1)

The average of these factors is 0.138<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 683.7
- 400 + ( ( 0.138 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 683.7


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
|           16 |      841 | 2024-07-14 | Sampi            | L   | 1.000      | -            | -                | -                | -         |    -6.54 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           15 |      852 | 2024-07-13 | The Suspect      | L   | 1.000      | -            | -                | -                | -         |    -9.04 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           14 |      943 | 2024-07-08 | Norway           | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.103 (0.015)    | 0 (0.000) |    16.34 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|           13 |     1625 | 2024-06-01 | FLuffy Gangsters | L   | 0.762      | -            | -                | -                | -         |   -15.32 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           12 |     1686 | 2024-05-30 | RUBY             | L   | 0.748      | -            | -                | -                | -         |    -4.45 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           11 |     1723 | 2024-05-29 | TNL              | W   | 0.741      | 0.372        | 0.000 (0.000)    | 0.038 (0.011)    | 0 (0.000) |     6.31 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           10 |     2264 | 2024-05-11 | AL QATRAO        | L   | 0.621      | -            | -                | -                | -         |    -9.70 | Ag1l, aragornN, fox, pr, rafaxF        |
|            9 |     2705 | 2024-04-20 | 1WIN             | L   | 0.481      | -            | -                | -                | -         |    -2.85 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            8 |     2748 | 2024-04-19 | Secret           | W   | 0.475      | 0.143        | 0.000 (0.000)    | 0.055 (0.004)    | 0 (0.000) |     4.80 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            7 |     2791 | 2024-04-18 | Illuminar        | L   | 0.468      | -            | -                | -                | -         |   -10.56 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            6 |     2839 | 2024-04-17 | 500              | W   | 0.461      | 0.143        | 0.001 (0.000)    | 0.090 (0.006)    | 0 (0.000) |     8.43 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            5 |     3908 | 2024-03-03 | Rhyno            | W   | 0.160      | 0.314        | 0.071 (0.004)    | 0.427 (0.022)    | 1 (0.160) |     4.19 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            4 |     3929 | 2024-03-02 | OVERFRAG         | W   | 0.153      | 0.314        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.153) |     1.37 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            3 |     4061 | 2024-02-24 | 500              | L   | 0.108      | -            | -                | -                | -         |    -1.61 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            2 |     4201 | 2024-02-18 | Alliance         | L   | 0.067      | -            | -                | -                | -         |    -0.59 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            1 |     4369 | 2024-02-11 | Young Ninjas     | L   | 0.021      | -            | -                | -                | -         |    -0.27 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($859.69)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.627 | $539.00        | $338.02         |
| 2024-03-03 |      0.160 | $3,251.00      | $521.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
