### Roster Details<br />
Team Name: Portugal<br />
Roster: Ag1l, aragornN, Icarus, NOPEEJ, rafaxF<br />
Global Rank: [170](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [108]( ../standings_europe.md)<br />
<br />
Final Rank Value:  664.4<br />
<br />
Final Rank Value (664.4) = Starting Rank Value (685.2) + Head To Head Adjustments (-20.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.282[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.039[<sup>2</sup>](#table1)

The average of these factors is 0.139<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 685.2
- 400 + ( ( 0.139 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 685.2


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
|           16 |      779 | 2024-07-14 | Sampi            | L   | 1.000      | -            | -                | -                | -         |    -6.75 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           15 |      790 | 2024-07-13 | The Suspect      | L   | 1.000      | -            | -                | -                | -         |    -9.18 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           14 |      881 | 2024-07-08 | Norway           | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.107 (0.015)    | 0 (0.000) |    16.30 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|           13 |     1563 | 2024-06-01 | FLuffy Gangsters | L   | 0.775      | -            | -                | -                | -         |   -15.67 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           12 |     1624 | 2024-05-30 | RUBY             | L   | 0.762      | -            | -                | -                | -         |    -4.58 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           11 |     1661 | 2024-05-29 | TNL              | W   | 0.754      | 0.372        | 0.000 (0.000)    | 0.039 (0.011)    | 0 (0.000) |     6.38 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           10 |     2202 | 2024-05-11 | AL QATRAO        | L   | 0.634      | -            | -                | -                | -         |    -9.94 | Ag1l, aragornN, fox, pr, rafaxF        |
|            9 |     2643 | 2024-04-20 | 1WIN             | L   | 0.495      | -            | -                | -                | -         |    -3.13 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            8 |     2686 | 2024-04-19 | Secret           | W   | 0.488      | 0.143        | 0.000 (0.000)    | 0.058 (0.004)    | 0 (0.000) |     4.92 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            7 |     2729 | 2024-04-18 | Illuminar        | L   | 0.481      | -            | -                | -                | -         |   -10.88 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            6 |     2777 | 2024-04-17 | 500              | W   | 0.474      | 0.143        | 0.001 (0.000)    | 0.098 (0.007)    | 0 (0.000) |     8.67 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            5 |     3846 | 2024-03-03 | Rhyno            | W   | 0.174      | 0.314        | 0.071 (0.004)    | 0.404 (0.022)    | 1 (0.174) |     4.54 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            4 |     3867 | 2024-03-02 | OVERFRAG         | W   | 0.166      | 0.314        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.166) |     1.49 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            3 |     3999 | 2024-02-24 | 500              | L   | 0.121      | -            | -                | -                | -         |    -1.81 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            2 |     4139 | 2024-02-18 | Alliance         | L   | 0.080      | -            | -                | -                | -         |    -0.71 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            1 |     4307 | 2024-02-11 | Young Ninjas     | L   | 0.034      | -            | -                | -                | -         |    -0.45 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($909.96)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.640 | $539.00        | $345.17         |
| 2024-03-03 |      0.174 | $3,251.00      | $564.79         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
