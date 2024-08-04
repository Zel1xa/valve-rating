### Roster Details<br />
Team Name: Revenant<br />
Roster: HS, lauNX, NBK-, Nivera, reiko<br />
Global Rank: [115](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [82]( ../standings_europe.md)<br />
<br />
Final Rank Value:  828.6<br />
<br />
Final Rank Value (828.6) = Starting Rank Value (803.7) + Head To Head Adjustments (24.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.083[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.197<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 803.7
- 400 + ( ( 0.197 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 803.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |        3 | 2024-08-04 | Monte Gen       | L   | 1.000      | -            | -                | -                | -         |   -26.92 | HS, lauNX, NBK-, Nivera, reiko   |
|           19 |      339 | 2024-07-26 | DMS             | L   | 1.000      | -            | -                | -                | -         |   -13.92 | adeX, Jeebs, NBK-, Nivera, reiko |
|           18 |      365 | 2024-07-25 | 3DMAX           | L   | 1.000      | -            | -                | -                | -         |    -1.86 | adeX, Jeebs, NBK-, Nivera, reiko |
|           17 |      395 | 2024-07-24 | AMKAL           | L   | 1.000      | -            | -                | -                | -         |    -4.23 | adeX, lauNX, NBK-, Nivera, reiko |
|           16 |      410 | 2024-07-24 | Eternal Fire    | L   | 1.000      | -            | -                | -                | -         |    -0.47 | adeX, lauNX, NBK-, Nivera, reiko |
|           15 |      835 | 2024-07-12 | Verdant         | W   | 1.000      | 0.371        | 0.015 (0.005)    | 0.299 (0.111)    | 0 (0.000) |    14.58 | adeX, lauNX, NBK-, Nivera, reiko |
|           14 |      895 | 2024-07-09 | Johnny Speeds   | W   | 1.000      | 0.333        | 0.122 (0.041)    | 0.941 (0.314)    | 0 (0.000) |    28.45 | adeX, lauNX, NBK-, Nivera, reiko |
|           13 |      912 | 2024-07-08 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -11.08 | adeX, lauNX, NBK-, Nivera, reiko |
|           12 |      915 | 2024-07-08 | lajtbitexe      | W   | 1.000      | 0.333        | 0.007 (0.002)    | 0.113 (0.038)    | 0 (0.000) |    10.81 | adeX, lauNX, NBK-, Nivera, reiko |
|           11 |      919 | 2024-07-07 | kONO            | W   | 1.000      | 0.333        | 0.028 (0.009)    | 0.536 (0.179)    | 0 (0.000) |    17.32 | adeX, lauNX, NBK-, Nivera, reiko |
|           10 |      922 | 2024-07-06 | 777             | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.181 (0.060)    | 0 (0.000) |    11.51 | adeX, lauNX, NBK-, Nivera, reiko |
|            9 |      927 | 2024-07-05 | lajtbitexe      | L   | 0.998      | -            | -                | -                | -         |   -19.80 | adeX, lauNX, NBK-, Nivera, reiko |
|            8 |      958 | 2024-06-27 | Johnny Speeds   | L   | 0.944      | -            | -                | -                | -         |    -2.51 | adeX, lauNX, NBK-, Nivera, reiko |
|            7 |      961 | 2024-06-26 | lajtbitexe      | W   | 0.938      | 0.333        | 0.007 (0.002)    | 0.113 (0.035)    | 0 (0.000) |    10.52 | adeX, lauNX, NBK-, Nivera, reiko |
|            6 |      962 | 2024-06-25 | Johnny Speeds   | L   | 0.932      | -            | -                | -                | -         |    -2.41 | adeX, lauNX, NBK-, Nivera, reiko |
|            5 |      970 | 2024-06-23 | Heimo           | W   | 0.918      | 0.333        | 0.006 (0.002)    | 0.107 (0.033)    | 0 (0.000) |     8.84 | adeX, lauNX, NBK-, Nivera, reiko |
|            4 |      993 | 2024-06-16 | CYBERSHOKE      | L   | 0.874      | -            | -                | -                | -         |   -11.12 | adeX, lauNX, NBK-, Nivera, reiko |
|            3 |     1022 | 2024-06-15 | Verdant         | W   | 0.867      | 0.143        | 0.015 (0.002)    | 0.299 (0.037)    | 0 (0.000) |    16.19 | adeX, lauNX, NBK-, Nivera, reiko |
|            2 |     1080 | 2024-06-14 | Astralis Talent | W   | 0.859      | 0.143        | 0.009 (0.001)    | 0.162 (0.020)    | 0 (0.000) |    10.75 | adeX, lauNX, NBK-, Nivera, reiko |
|            1 |     1107 | 2024-06-13 | Verdant         | L   | 0.853      | -            | -                | -                | -         |    -9.77 | adeX, lauNX, NBK-, Nivera, reiko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,832.99)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-09 |      1.000 | $6,000.00      | $6,000.00       |
| 2024-06-27 |      0.944 | $3,000.00      | $2,832.99       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
