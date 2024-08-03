### Roster Details<br />
Team Name: Portugal<br />
Roster: Ag1l, aragornN, Icarus, NOPEEJ, rafaxF<br />
Global Rank: [170](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [108]( ../standings_europe.md)<br />
<br />
Final Rank Value:  665.3<br />
<br />
Final Rank Value (665.3) = Starting Rank Value (686.7) + Head To Head Adjustments (-21.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.282[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.040[<sup>2</sup>](#table1)

The average of these factors is 0.140<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 686.7
- 400 + ( ( 0.140 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 686.7


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
|           16 |      741 | 2024-07-14 | Sampi            | L   | 1.000      | -            | -                | -                | -         |    -6.81 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           15 |      751 | 2024-07-13 | The Suspect      | L   | 1.000      | -            | -                | -                | -         |    -9.17 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           14 |      839 | 2024-07-08 | Norway           | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.110 (0.016)    | 0 (0.000) |    16.26 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|           13 |     1489 | 2024-06-01 | FLuffy Gangsters | L   | 0.780      | -            | -                | -                | -         |   -15.79 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           12 |     1549 | 2024-05-30 | RUBY             | L   | 0.767      | -            | -                | -                | -         |    -4.59 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           11 |     1586 | 2024-05-29 | TNL              | W   | 0.760      | 0.372        | 0.000 (0.000)    | 0.040 (0.011)    | 0 (0.000) |     6.41 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           10 |     2125 | 2024-05-11 | AL QATRAO        | L   | 0.639      | -            | -                | -                | -         |   -10.04 | Ag1l, aragornN, fox, pr, rafaxF        |
|            9 |     2564 | 2024-04-20 | 1WIN             | L   | 0.500      | -            | -                | -                | -         |    -3.47 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            8 |     2607 | 2024-04-19 | Secret           | W   | 0.493      | 0.143        | 0.000 (0.000)    | 0.061 (0.004)    | 0 (0.000) |     4.96 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            7 |     2650 | 2024-04-18 | Illuminar        | L   | 0.487      | -            | -                | -                | -         |   -11.03 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            6 |     2698 | 2024-04-17 | 500              | W   | 0.480      | 0.143        | 0.001 (0.000)    | 0.103 (0.007)    | 0 (0.000) |     8.78 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            5 |     3759 | 2024-03-03 | Rhyno            | W   | 0.179      | 0.314        | 0.071 (0.004)    | 0.418 (0.023)    | 1 (0.179) |     4.68 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            4 |     3780 | 2024-03-02 | OVERFRAG         | W   | 0.172      | 0.314        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.172) |     1.53 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            3 |     3912 | 2024-02-24 | 500              | L   | 0.126      | -            | -                | -                | -         |    -1.90 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            2 |     4052 | 2024-02-18 | Alliance         | L   | 0.085      | -            | -                | -                | -         |    -0.76 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            1 |     4219 | 2024-02-11 | Young Ninjas     | L   | 0.040      | -            | -                | -                | -         |    -0.52 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($930.75)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.646 | $539.00        | $348.13         |
| 2024-03-03 |      0.179 | $3,251.00      | $582.62         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
