### Roster Details<br />
Team Name: Portugal<br />
Roster: Ag1l, aragornN, Icarus, NOPEEJ, rafaxF<br />
Global Rank: [171](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [109]( ../standings_europe.md)<br />
<br />
Final Rank Value:  663.7<br />
<br />
Final Rank Value (663.7) = Starting Rank Value (683.3) + Head To Head Adjustments (-19.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.280[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.036[<sup>2</sup>](#table1)

The average of these factors is 0.138<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 683.3
- 400 + ( ( 0.138 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 683.3


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
|           16 |      835 | 2024-07-14 | Sampi            | L   | 1.000      | -            | -                | -                | -         |    -6.55 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           15 |      846 | 2024-07-13 | The Suspect      | L   | 1.000      | -            | -                | -                | -         |    -9.04 | Ag1l, aragornN, Icarus, NOPEEJ, rafaxF |
|           14 |      937 | 2024-07-08 | Norway           | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.106 (0.015)    | 0 (0.000) |    16.34 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|           13 |     1619 | 2024-06-01 | FLuffy Gangsters | L   | 0.762      | -            | -                | -                | -         |   -15.31 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           12 |     1680 | 2024-05-30 | RUBY             | L   | 0.749      | -            | -                | -                | -         |    -4.53 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           11 |     1717 | 2024-05-29 | TNL              | W   | 0.742      | 0.372        | 0.000 (0.000)    | 0.039 (0.011)    | 0 (0.000) |     6.32 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|           10 |     2258 | 2024-05-11 | AL QATRAO        | L   | 0.621      | -            | -                | -                | -         |    -9.71 | Ag1l, aragornN, fox, pr, rafaxF        |
|            9 |     2699 | 2024-04-20 | 1WIN             | L   | 0.482      | -            | -                | -                | -         |    -2.84 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            8 |     2742 | 2024-04-19 | Secret           | W   | 0.475      | 0.143        | 0.000 (0.000)    | 0.056 (0.004)    | 0 (0.000) |     4.81 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            7 |     2785 | 2024-04-18 | Illuminar        | L   | 0.469      | -            | -                | -                | -         |   -10.57 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            6 |     2833 | 2024-04-17 | 500              | W   | 0.461      | 0.143        | 0.001 (0.000)    | 0.093 (0.006)    | 0 (0.000) |     8.43 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF   |
|            5 |     3902 | 2024-03-03 | Rhyno            | W   | 0.161      | 0.314        | 0.071 (0.004)    | 0.437 (0.022)    | 1 (0.161) |     4.21 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            4 |     3923 | 2024-03-02 | OVERFRAG         | W   | 0.154      | 0.314        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.154) |     1.38 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            3 |     4055 | 2024-02-24 | 500              | L   | 0.108      | -            | -                | -                | -         |    -1.62 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            2 |     4195 | 2024-02-18 | Alliance         | L   | 0.067      | -            | -                | -                | -         |    -0.60 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |
|            1 |     4363 | 2024-02-11 | Young Ninjas     | L   | 0.022      | -            | -                | -                | -         |    -0.27 | Ag1l, aragornN, NOPEEJ, pr, rafaxF     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($862.14)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.628 | $539.00        | $338.37         |
| 2024-03-03 |      0.161 | $3,251.00      | $523.77         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
