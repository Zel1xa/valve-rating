### Roster Details<br />
Team Name: Revenant<br />
Roster: adeX, Jeebs, NBK-, Nivera, reiko<br />
Global Rank: [114](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
<br />
Final Rank Value:  830.0<br />
<br />
Final Rank Value (830.0) = Starting Rank Value (804.6) + Head To Head Adjustments (25.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.318[<sup>2</sup>](#table1)
- Opponent Network: 0.079[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.197<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 804.6
- 400 + ( ( 0.197 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 804.6


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
|           21 |      223 | 2024-07-26 | DMS             | L   | 1.000      | -            | -                | -                | -         |   -13.63 | adeX, Jeebs, NBK-, Nivera, reiko |
|           20 |      249 | 2024-07-25 | 3DMAX           | L   | 1.000      | -            | -                | -                | -         |    -1.67 | adeX, Jeebs, NBK-, Nivera, reiko |
|           19 |      279 | 2024-07-24 | AMKAL           | L   | 1.000      | -            | -                | -                | -         |    -3.73 | adeX, lauNX, NBK-, Nivera, reiko |
|           18 |      294 | 2024-07-24 | Eternal Fire    | L   | 1.000      | -            | -                | -                | -         |    -0.40 | adeX, lauNX, NBK-, Nivera, reiko |
|           17 |      636 | 2024-07-16 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -11.77 | adeX, lauNX, NBK-, Nivera, reiko |
|           16 |      682 | 2024-07-15 | Verdant         | L   | 1.000      | -            | -                | -                | -         |   -16.75 | adeX, lauNX, NBK-, Nivera, reiko |
|           15 |      736 | 2024-07-12 | Verdant         | W   | 1.000      | 0.371        | 0.015 (0.006)    | 0.305 (0.113)    | 0 (0.000) |    14.65 | adeX, lauNX, NBK-, Nivera, reiko |
|           14 |      796 | 2024-07-09 | Johnny Speeds   | W   | 1.000      | 0.333        | 0.124 (0.041)    | 0.819 (0.273)    | 0 (0.000) |    28.42 | adeX, lauNX, NBK-, Nivera, reiko |
|           13 |      813 | 2024-07-08 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -11.21 | adeX, lauNX, NBK-, Nivera, reiko |
|           12 |      816 | 2024-07-08 | lajtbitexe      | W   | 1.000      | 0.333        | 0.007 (0.002)    | 0.112 (0.037)    | 0 (0.000) |    10.80 | adeX, lauNX, NBK-, Nivera, reiko |
|           11 |      821 | 2024-07-07 | kONO            | W   | 1.000      | 0.333        | 0.029 (0.010)    | 0.547 (0.182)    | 0 (0.000) |    17.89 | adeX, lauNX, NBK-, Nivera, reiko |
|           10 |      824 | 2024-07-06 | 777             | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.182 (0.061)    | 0 (0.000) |    11.60 | adeX, lauNX, NBK-, Nivera, reiko |
|            9 |      829 | 2024-07-05 | lajtbitexe      | L   | 1.000      | -            | -                | -                | -         |   -19.82 | adeX, lauNX, NBK-, Nivera, reiko |
|            8 |      860 | 2024-06-27 | Johnny Speeds   | L   | 0.964      | -            | -                | -                | -         |    -2.59 | adeX, lauNX, NBK-, Nivera, reiko |
|            7 |      863 | 2024-06-26 | lajtbitexe      | W   | 0.958      | 0.333        | 0.007 (0.002)    | 0.112 (0.036)    | 0 (0.000) |    10.76 | adeX, lauNX, NBK-, Nivera, reiko |
|            6 |      864 | 2024-06-25 | Johnny Speeds   | L   | 0.952      | -            | -                | -                | -         |    -2.48 | adeX, lauNX, NBK-, Nivera, reiko |
|            5 |      872 | 2024-06-23 | Heimo           | W   | 0.938      | 0.333        | 0.006 (0.002)    | 0.086 (0.027)    | 0 (0.000) |     9.14 | adeX, lauNX, NBK-, Nivera, reiko |
|            4 |      893 | 2024-06-16 | CYBERSHOKE      | L   | 0.894      | -            | -                | -                | -         |   -11.29 | adeX, lauNX, NBK-, Nivera, reiko |
|            3 |      919 | 2024-06-15 | Verdant         | W   | 0.887      | 0.143        | 0.015 (0.002)    | 0.305 (0.039)    | 0 (0.000) |    16.68 | adeX, lauNX, NBK-, Nivera, reiko |
|            2 |      970 | 2024-06-14 | Astralis Talent | W   | 0.879      | 0.143        | 0.009 (0.001)    | 0.201 (0.025)    | 0 (0.000) |    10.58 | adeX, lauNX, NBK-, Nivera, reiko |
|            1 |      997 | 2024-06-13 | Verdant         | L   | 0.873      | -            | -                | -                | -         |    -9.85 | adeX, lauNX, NBK-, Nivera, reiko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,892.50)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-09 |      1.000 | $6,000.00      | $6,000.00       |
| 2024-06-27 |      0.964 | $3,000.00      | $2,892.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
