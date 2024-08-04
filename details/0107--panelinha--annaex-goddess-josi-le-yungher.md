### Roster Details<br />
Team Name: panelinha<br />
Roster: annaEX, goddess, josi, Le, yungher<br />
Global Rank: [107](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [27]( ../standings_americas.md)<br />
<br />
Final Rank Value:  842.8<br />
<br />
Final Rank Value (842.8) = Starting Rank Value (844.3) + Head To Head Adjustments (-1.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.401[<sup>1</sup>](#table2)
- Bounty Collected: 0.272[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.177[<sup>2</sup>](#table1)

The average of these factors is 0.217<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 844.3
- 400 + ( ( 0.217 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 844.3


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
|           12 |      256 | 2024-07-27 | MIBR fe       | L   | 1.000      | -            | -                | -                | -         |   -21.87 | annaEX, goddess, josi, Le, yungher       |
|           11 |     1528 | 2024-06-02 | Imperial fe   | L   | 0.784      | -            | -                | -                | -         |    -6.63 | annaEX, goddess, julih, poppins, yungher |
|           10 |     1548 | 2024-06-01 | NAVI Javelins | W   | 0.779      | 0.524        | 0.026 (0.011)    | 0.190 (0.077)    | 1 (0.779) |    12.29 | annaEX, goddess, julih, poppins, yungher |
|            9 |     1581 | 2024-05-31 | Let Her Cook  | L   | 0.773      | -            | -                | -                | -         |   -10.39 | annaEX, goddess, julih, poppins, yungher |
|            8 |     1585 | 2024-05-31 | TSM Shimmer   | W   | 0.772      | 0.524        | 0.020 (0.008)    | 0.199 (0.081)    | 1 (0.772) |     7.82 | annaEX, goddess, julih, poppins, yungher |
|            7 |     2659 | 2024-04-19 | FURIA fe      | W   | 0.493      | 0.332        | 0.003 (0.001)    | 0.075 (0.012)    | 0 (0.000) |     4.26 | annaEX, goddess, julih, poppins, yungher |
|            6 |     2922 | 2024-04-10 | GENKID4M4     | W   | 0.433      | 0.332        | 0.002 (0.000)    | 0.011 (0.002)    | 0 (0.000) |     2.73 | annaEX, goddess, julih, poppins, yungher |
|            5 |     3114 | 2024-04-04 | KG fe         | W   | 0.393      | 0.332        | 0.002 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     1.67 | annaEX, goddess, julih, poppins, yungher |
|            4 |     3287 | 2024-03-27 | Divina fe     | W   | 0.340      | 0.332        | 0.002 (0.000)    | 0.021 (0.002)    | 0 (0.000) |     2.45 | annaEX, goddess, julih, poppins, yungher |
|            3 |     3405 | 2024-03-20 | MIBR fe       | W   | 0.293      | 0.332        | 0.007 (0.001)    | 0.107 (0.010)    | 0 (0.000) |     2.71 | annaEX, goddess, julih, poppins, yungher |
|            2 |     3523 | 2024-03-14 | W7M fe        | W   | 0.253      | 0.332        | 0.002 (0.000)    | 0.033 (0.003)    | 0 (0.000) |     1.83 | annaEX, goddess, julih, poppins, yungher |
|            1 |     3728 | 2024-03-06 | Atrix         | W   | 0.200      | 0.332        | 0.003 (0.000)    | 0.060 (0.004)    | 0 (0.000) |     1.55 | annaEX, goddess, julih, poppins, yungher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,469.44)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $250.00        | $250.00         |
| 2024-06-02 |      0.786 | $13,000.00     | $10,219.44      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
