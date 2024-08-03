### Roster Details<br />
Team Name: panelinha<br />
Roster: annaEX, goddess, josi, Le, yungher<br />
Global Rank: [105](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [25]( ../standings_americas.md)<br />
<br />
Final Rank Value:  843.9<br />
<br />
Final Rank Value (843.9) = Starting Rank Value (845.4) + Head To Head Adjustments (-1.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.401[<sup>1</sup>](#table2)
- Bounty Collected: 0.273[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.177[<sup>2</sup>](#table1)

The average of these factors is 0.218<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 845.4
- 400 + ( ( 0.218 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 845.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |      233 | 2024-07-27 | MIBR fe       | L   | 1.000      | -            | -                | -                | -         |   -21.89 | annaEX, goddess, josi, Le, yungher       |
|           11 |     1468 | 2024-06-02 | Imperial fe   | L   | 0.786      | -            | -                | -                | -         |    -6.63 | annaEX, goddess, julih, poppins, yungher |
|           10 |     1486 | 2024-06-01 | NAVI Javelins | W   | 0.781      | 0.524        | 0.027 (0.011)    | 0.196 (0.080)    | 1 (0.781) |    12.32 | annaEX, goddess, julih, poppins, yungher |
|            9 |     1518 | 2024-05-31 | Let Her Cook  | L   | 0.775      | -            | -                | -                | -         |   -10.41 | annaEX, goddess, julih, poppins, yungher |
|            8 |     1522 | 2024-05-31 | TSM Shimmer   | W   | 0.774      | 0.524        | 0.020 (0.008)    | 0.206 (0.084)    | 1 (0.774) |     7.82 | annaEX, goddess, julih, poppins, yungher |
|            7 |     2593 | 2024-04-19 | FURIA fe      | W   | 0.494      | 0.332        | 0.003 (0.001)    | 0.078 (0.013)    | 0 (0.000) |     4.26 | annaEX, goddess, julih, poppins, yungher |
|            6 |     2856 | 2024-04-10 | GENKID4M4     | W   | 0.434      | 0.332        | 0.002 (0.000)    | 0.012 (0.002)    | 0 (0.000) |     2.74 | annaEX, goddess, julih, poppins, yungher |
|            5 |     3048 | 2024-04-04 | KG fe         | W   | 0.394      | 0.332        | 0.002 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     1.67 | annaEX, goddess, julih, poppins, yungher |
|            4 |     3220 | 2024-03-27 | Divina fe     | W   | 0.341      | 0.332        | 0.002 (0.000)    | 0.022 (0.002)    | 0 (0.000) |     2.46 | annaEX, goddess, julih, poppins, yungher |
|            3 |     3334 | 2024-03-20 | MIBR fe       | W   | 0.295      | 0.332        | 0.007 (0.001)    | 0.111 (0.011)    | 0 (0.000) |     2.72 | annaEX, goddess, julih, poppins, yungher |
|            2 |     3451 | 2024-03-14 | W7M fe        | W   | 0.255      | 0.332        | 0.002 (0.000)    | 0.034 (0.003)    | 0 (0.000) |     1.84 | annaEX, goddess, julih, poppins, yungher |
|            1 |     3655 | 2024-03-06 | Atrix         | W   | 0.201      | 0.332        | 0.003 (0.000)    | 0.062 (0.004)    | 0 (0.000) |     1.56 | annaEX, goddess, julih, poppins, yungher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,491.71)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $250.00        | $250.00         |
| 2024-06-02 |      0.788 | $13,000.00     | $10,241.71      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
