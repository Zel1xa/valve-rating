### Roster Details<br />
Team Name: Portugal<br />
Roster: Ag1l, aragornN, Icarus, NOPEEJ, rafaxF<br />
Global Rank: [166](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [107]( ../standings_europe.md)<br />
<br />
Final Rank Value:  671.2<br />
<br />
Final Rank Value (671.2) = Starting Rank Value (694.0) + Head To Head Adjustments (-22.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.284[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.045[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 694.0
- 400 + ( ( 0.143 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 694.0


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
|           18 |      654 | 2024-07-14 | Sampi            | L   | 1.000      | -            | -                | -                | -         |    -6.95 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           17 |      665 | 2024-07-13 | Kosovo           | L   | 1.000      | -            | -                | -                | -         |    -9.16 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           16 |      756 | 2024-07-08 | Norway           | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.106 (0.015)    | 0 (0.000) |    16.22 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|           15 |     1438 | 2024-06-01 | FLuffy Gangsters | L   | 0.799      | -            | -                | -                | -         |   -16.35 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           14 |     1499 | 2024-05-30 | RUBY             | L   | 0.786      | -            | -                | -                | -         |    -4.75 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           13 |     1536 | 2024-05-29 | TNL              | W   | 0.779      | 0.372        | 0.000 (0.000)    | 0.038 (0.011)    | 0 (0.000) |     6.41 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           12 |     2077 | 2024-05-11 | AL QATRAO        | L   | 0.659      | -            | -                | -                | -         |   -10.39 | Ag1l, aragornN, fox, pr, rafaxF        |
|           11 |     2518 | 2024-04-20 | 1WIN             | L   | 0.519      | -            | -                | -                | -         |    -3.71 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           10 |     2561 | 2024-04-19 | Secret           | W   | 0.513      | 0.143        | 0.000 (0.000)    | 0.061 (0.004)    | 0 (0.000) |     5.07 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            9 |     2604 | 2024-04-18 | Illuminar        | L   | 0.506      | -            | -                | -                | -         |   -11.55 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            8 |     2652 | 2024-04-17 | 500              | W   | 0.499      | 0.143        | 0.001 (0.000)    | 0.106 (0.008)    | 0 (0.000) |     9.13 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            7 |     3721 | 2024-03-03 | Rhyno            | W   | 0.198      | 0.314        | 0.072 (0.004)    | 0.403 (0.025)    | 1 (0.198) |     5.20 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            6 |     3742 | 2024-03-02 | OVERFRAG         | W   | 0.191      | 0.314        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.191) |     1.67 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            5 |     3874 | 2024-02-24 | 500              | L   | 0.145      | -            | -                | -                | -         |    -2.20 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            4 |     4014 | 2024-02-18 | Alliance         | L   | 0.104      | -            | -                | -                | -         |    -0.97 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            3 |     4182 | 2024-02-11 | Young Ninjas     | L   | 0.059      | -            | -                | -                | -         |    -0.76 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            2 |     4273 | 2024-02-04 | ARCRED           | W   | 0.011      | 0.358        | 0.038 (0.000)    | 0.328 (0.001)    | 0 (0.000) |     0.25 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            1 |     4292 | 2024-02-03 | Rhyno            | L   | 0.006      | -            | -                | -                | -         |    -0.03 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,002.81)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.665 | $539.00        | $358.38         |
| 2024-03-03 |      0.198 | $3,251.00      | $644.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
