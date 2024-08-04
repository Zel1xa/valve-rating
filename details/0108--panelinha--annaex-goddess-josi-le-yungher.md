### Roster Details<br />
Team Name: panelinha<br />
Roster: annaEX, goddess, josi, Le, yungher<br />
Global Rank: [108](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [27]( ../standings_americas.md)<br />
<br />
Final Rank Value:  842.3<br />
<br />
Final Rank Value (842.3) = Starting Rank Value (844.1) + Head To Head Adjustments (-1.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.401[<sup>1</sup>](#table2)
- Bounty Collected: 0.272[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.176[<sup>2</sup>](#table1)

The average of these factors is 0.217<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 844.1
- 400 + ( ( 0.217 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 844.1


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
|           12 |      291 | 2024-07-27 | MIBR fe       | L   | 1.000      | -            | -                | -                | -         |   -21.85 | annaEX, goddess, josi, Le, yungher       |
|           11 |     1564 | 2024-06-02 | Imperial fe   | L   | 0.780      | -            | -                | -                | -         |    -6.59 | annaEX, goddess, julih, poppins, yungher |
|           10 |     1584 | 2024-06-01 | NAVI Javelins | W   | 0.774      | 0.524        | 0.026 (0.011)    | 0.189 (0.076)    | 1 (0.774) |    12.21 | annaEX, goddess, julih, poppins, yungher |
|            9 |     1617 | 2024-05-31 | Let Her Cook  | L   | 0.769      | -            | -                | -                | -         |   -10.26 | annaEX, goddess, julih, poppins, yungher |
|            8 |     1621 | 2024-05-31 | TSM Shimmer   | W   | 0.768      | 0.524        | 0.020 (0.008)    | 0.199 (0.080)    | 1 (0.768) |     7.78 | annaEX, goddess, julih, poppins, yungher |
|            7 |     2696 | 2024-04-19 | FURIA fe      | W   | 0.488      | 0.332        | 0.003 (0.001)    | 0.074 (0.012)    | 0 (0.000) |     4.21 | annaEX, goddess, julih, poppins, yungher |
|            6 |     2959 | 2024-04-10 | GENKID4M4     | W   | 0.428      | 0.332        | 0.002 (0.000)    | 0.011 (0.002)    | 0 (0.000) |     2.71 | annaEX, goddess, julih, poppins, yungher |
|            5 |     3151 | 2024-04-04 | KG fe         | W   | 0.388      | 0.332        | 0.002 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     1.66 | annaEX, goddess, julih, poppins, yungher |
|            4 |     3324 | 2024-03-27 | Divina fe     | W   | 0.335      | 0.332        | 0.002 (0.000)    | 0.021 (0.002)    | 0 (0.000) |     2.42 | annaEX, goddess, julih, poppins, yungher |
|            3 |     3442 | 2024-03-20 | MIBR fe       | W   | 0.288      | 0.332        | 0.007 (0.001)    | 0.107 (0.010)    | 0 (0.000) |     2.67 | annaEX, goddess, julih, poppins, yungher |
|            2 |     3560 | 2024-03-14 | W7M fe        | W   | 0.248      | 0.332        | 0.002 (0.000)    | 0.033 (0.003)    | 0 (0.000) |     1.80 | annaEX, goddess, julih, poppins, yungher |
|            1 |     3766 | 2024-03-06 | Atrix         | W   | 0.195      | 0.332        | 0.003 (0.000)    | 0.059 (0.004)    | 0 (0.000) |     1.52 | annaEX, goddess, julih, poppins, yungher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,406.55)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $250.00        | $250.00         |
| 2024-06-02 |      0.781 | $13,000.00     | $10,156.55      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
