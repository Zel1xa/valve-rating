### Roster Details<br />
Team Name: Portugal<br />
Roster: Ag1l, aragornN, Icarus, NOPEEJ, rafaxF<br />
Global Rank: [170](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [108]( ../standings_europe.md)<br />
<br />
Final Rank Value:  664.1<br />
<br />
Final Rank Value (664.1) = Starting Rank Value (685.3) + Head To Head Adjustments (-21.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.282[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.039[<sup>2</sup>](#table1)

The average of these factors is 0.140<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 685.3
- 400 + ( ( 0.140 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 685.3


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
|           16 |      771 | 2024-07-14 | Sampi            | L   | 1.000      | -            | -                | -                | -         |    -6.77 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           15 |      782 | 2024-07-13 | The Suspect      | L   | 1.000      | -            | -                | -                | -         |    -9.17 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           14 |      873 | 2024-07-08 | Norway           | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.107 (0.015)    | 0 (0.000) |    16.31 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|           13 |     1555 | 2024-06-01 | FLuffy Gangsters | L   | 0.776      | -            | -                | -                | -         |   -15.68 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           12 |     1616 | 2024-05-30 | RUBY             | L   | 0.762      | -            | -                | -                | -         |    -4.59 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           11 |     1653 | 2024-05-29 | TNL              | W   | 0.755      | 0.372        | 0.000 (0.000)    | 0.039 (0.011)    | 0 (0.000) |     6.39 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           10 |     2194 | 2024-05-11 | AL QATRAO        | L   | 0.635      | -            | -                | -                | -         |    -9.95 | Ag1l, aragornN, fox, pr, rafaxF        |
|            9 |     2635 | 2024-04-20 | 1WIN             | L   | 0.495      | -            | -                | -                | -         |    -3.47 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            8 |     2678 | 2024-04-19 | Secret           | W   | 0.489      | 0.143        | 0.000 (0.000)    | 0.058 (0.004)    | 0 (0.000) |     4.92 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            7 |     2721 | 2024-04-18 | Illuminar        | L   | 0.482      | -            | -                | -                | -         |   -10.90 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            6 |     2769 | 2024-04-17 | 500              | W   | 0.475      | 0.143        | 0.001 (0.000)    | 0.098 (0.007)    | 0 (0.000) |     8.69 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            5 |     3838 | 2024-03-03 | Rhyno            | W   | 0.174      | 0.314        | 0.071 (0.004)    | 0.404 (0.022)    | 1 (0.174) |     4.56 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            4 |     3859 | 2024-03-02 | OVERFRAG         | W   | 0.167      | 0.314        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.167) |     1.49 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            3 |     3991 | 2024-02-24 | 500              | L   | 0.122      | -            | -                | -                | -         |    -1.82 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            2 |     4131 | 2024-02-18 | Alliance         | L   | 0.081      | -            | -                | -                | -         |    -0.72 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            1 |     4299 | 2024-02-11 | Young Ninjas     | L   | 0.035      | -            | -                | -                | -         |    -0.46 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($912.68)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.641 | $539.00        | $345.56         |
| 2024-03-03 |      0.174 | $3,251.00      | $567.12         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
