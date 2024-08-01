### Roster Details<br />
Team Name: Portugal<br />
Roster: Ag1l, aragornN, Icarus, NOPEEJ, rafaxF<br />
Global Rank: [169](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [108]( ../standings_europe.md)<br />
<br />
Final Rank Value:  670.1<br />
<br />
Final Rank Value (670.1) = Starting Rank Value (692.1) + Head To Head Adjustments (-22.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.284[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.044[<sup>2</sup>](#table1)

The average of these factors is 0.142<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 692.1
- 400 + ( ( 0.142 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 692.1


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
|           17 |      704 | 2024-07-14 | Sampi            | L   | 1.000      | -            | -                | -                | -         |    -6.98 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           16 |      717 | 2024-07-13 | The Suspect      | L   | 1.000      | -            | -                | -                | -         |    -9.22 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           15 |      808 | 2024-07-08 | Norway           | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.106 (0.015)    | 0 (0.000) |    16.22 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|           14 |     1496 | 2024-06-01 | FLuffy Gangsters | L   | 0.793      | -            | -                | -                | -         |   -16.20 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           13 |     1557 | 2024-05-30 | RUBY             | L   | 0.780      | -            | -                | -                | -         |    -4.64 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           12 |     1594 | 2024-05-29 | TNL              | W   | 0.773      | 0.372        | 0.000 (0.000)    | 0.039 (0.011)    | 0 (0.000) |     6.38 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           11 |     2172 | 2024-05-11 | AL QATRAO        | L   | 0.652      | -            | -                | -                | -         |   -10.29 | Ag1l, aragornN, fox, pr, rafaxF        |
|           10 |     2624 | 2024-04-20 | 1WIN             | L   | 0.513      | -            | -                | -                | -         |    -3.62 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            9 |     2668 | 2024-04-19 | Secret           | W   | 0.507      | 0.143        | 0.000 (0.000)    | 0.060 (0.004)    | 0 (0.000) |     5.02 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            8 |     2712 | 2024-04-18 | Illuminar        | L   | 0.500      | -            | -                | -                | -         |   -11.39 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            7 |     2761 | 2024-04-17 | 500              | W   | 0.493      | 0.143        | 0.001 (0.000)    | 0.126 (0.009)    | 0 (0.000) |     9.43 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            6 |     3856 | 2024-03-03 | Rhyno            | W   | 0.192      | 0.314        | 0.072 (0.004)    | 0.403 (0.024)    | 1 (0.192) |     5.06 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            5 |     3877 | 2024-03-02 | OVERFRAG         | W   | 0.185      | 0.314        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.185) |     1.62 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            4 |     4013 | 2024-02-24 | 500              | L   | 0.139      | -            | -                | -                | -         |    -1.97 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            3 |     4159 | 2024-02-18 | Alliance         | L   | 0.098      | -            | -                | -                | -         |    -0.90 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            2 |     4336 | 2024-02-11 | Young Ninjas     | L   | 0.053      | -            | -                | -                | -         |    -0.69 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            1 |     4428 | 2024-02-04 | ARCRED           | W   | 0.005      | 0.358        | 0.038 (0.000)    | 0.327 (0.001)    | 0 (0.000) |     0.11 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($980.06)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.659 | $539.00        | $355.14         |
| 2024-03-03 |      0.192 | $3,251.00      | $624.91         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
