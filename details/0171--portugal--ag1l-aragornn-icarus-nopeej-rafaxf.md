### Roster Details<br />
Team Name: Portugal<br />
Roster: Ag1l, aragornN, Icarus, NOPEEJ, rafaxF<br />
Global Rank: [171](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [109]( ../standings_europe.md)<br />
<br />
Final Rank Value:  664.4<br />
<br />
Final Rank Value (664.4) = Starting Rank Value (685.0) + Head To Head Adjustments (-20.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.281[<sup>1</sup>](#table2)
- Bounty Collected: 0.231[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.039[<sup>2</sup>](#table1)

The average of these factors is 0.139<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 685.0
- 400 + ( ( 0.139 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 685.0


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
|           16 |      802 | 2024-07-14 | Sampi            | L   | 1.000      | -            | -                | -                | -         |    -6.70 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           15 |      813 | 2024-07-13 | The Suspect      | L   | 1.000      | -            | -                | -                | -         |    -9.08 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           14 |      904 | 2024-07-08 | Norway           | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.107 (0.015)    | 0 (0.000) |    16.30 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|           13 |     1586 | 2024-06-01 | FLuffy Gangsters | L   | 0.774      | -            | -                | -                | -         |   -15.63 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           12 |     1647 | 2024-05-30 | RUBY             | L   | 0.761      | -            | -                | -                | -         |    -4.65 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           11 |     1684 | 2024-05-29 | TNL              | W   | 0.754      | 0.372        | 0.000 (0.000)    | 0.039 (0.011)    | 0 (0.000) |     6.38 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           10 |     2225 | 2024-05-11 | AL QATRAO        | L   | 0.633      | -            | -                | -                | -         |    -9.93 | Ag1l, aragornN, fox, pr, rafaxF        |
|            9 |     2666 | 2024-04-20 | 1WIN             | L   | 0.494      | -            | -                | -                | -         |    -3.05 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            8 |     2709 | 2024-04-19 | Secret           | W   | 0.487      | 0.143        | 0.000 (0.000)    | 0.058 (0.004)    | 0 (0.000) |     4.91 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            7 |     2752 | 2024-04-18 | Illuminar        | L   | 0.480      | -            | -                | -                | -         |   -10.86 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            6 |     2800 | 2024-04-17 | 500              | W   | 0.473      | 0.143        | 0.001 (0.000)    | 0.098 (0.007)    | 0 (0.000) |     8.66 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            5 |     3869 | 2024-03-03 | Rhyno            | W   | 0.173      | 0.314        | 0.071 (0.004)    | 0.404 (0.022)    | 1 (0.173) |     4.52 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            4 |     3890 | 2024-03-02 | OVERFRAG         | W   | 0.166      | 0.314        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.166) |     1.48 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            3 |     4022 | 2024-02-24 | 500              | L   | 0.120      | -            | -                | -                | -         |    -1.80 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            2 |     4162 | 2024-02-18 | Alliance         | L   | 0.079      | -            | -                | -                | -         |    -0.71 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            1 |     4330 | 2024-02-11 | Young Ninjas     | L   | 0.033      | -            | -                | -                | -         |    -0.44 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($907.06)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.640 | $539.00        | $344.76         |
| 2024-03-03 |      0.173 | $3,251.00      | $562.30         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
