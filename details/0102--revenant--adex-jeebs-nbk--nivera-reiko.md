### Roster Details<br />
Team Name: Revenant<br />
Roster: adeX, Jeebs, NBK-, Nivera, reiko<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
<br />
Final Rank Value:  848.9<br />
<br />
Final Rank Value (848.9) = Starting Rank Value (801.2) + Head To Head Adjustments (47.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.315[<sup>2</sup>](#table1)
- Opponent Network: 0.080[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.196<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 801.2
- 400 + ( ( 0.196 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 801.2


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
|           17 |      281 | 2024-07-26 | DMS             | L   | 1.000      | -            | -                | -                | -         |   -13.46 | adeX, Jeebs, NBK-, Nivera, reiko |
|           16 |      307 | 2024-07-25 | 3DMAX           | L   | 1.000      | -            | -                | -                | -         |    -1.86 | adeX, Jeebs, NBK-, Nivera, reiko |
|           15 |      337 | 2024-07-24 | AMKAL           | L   | 1.000      | -            | -                | -                | -         |    -4.14 | adeX, lauNX, NBK-, Nivera, reiko |
|           14 |      351 | 2024-07-24 | Eternal Fire    | L   | 1.000      | -            | -                | -                | -         |    -0.47 | adeX, lauNX, NBK-, Nivera, reiko |
|           13 |      771 | 2024-07-12 | Verdant         | W   | 1.000      | 0.371        | 0.015 (0.005)    | 0.310 (0.115)    | 0 (0.000) |    15.26 | adeX, lauNX, NBK-, Nivera, reiko |
|           12 |      829 | 2024-07-09 | Johnny Speeds   | W   | 1.000      | 0.333        | 0.122 (0.041)    | 0.930 (0.310)    | 0 (0.000) |    28.46 | adeX, lauNX, NBK-, Nivera, reiko |
|           11 |      846 | 2024-07-08 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -10.77 | adeX, lauNX, NBK-, Nivera, reiko |
|           10 |      849 | 2024-07-08 | lajtbitexe      | W   | 1.000      | 0.333        | 0.007 (0.002)    | 0.116 (0.039)    | 0 (0.000) |    11.52 | adeX, lauNX, NBK-, Nivera, reiko |
|            9 |      853 | 2024-07-07 | kONO            | W   | 1.000      | 0.333        | 0.028 (0.009)    | 0.555 (0.185)    | 0 (0.000) |    17.71 | adeX, lauNX, NBK-, Nivera, reiko |
|            8 |      856 | 2024-07-06 | 777             | W   | 1.000      | 0.333        | 0.014 (0.005)    | 0.184 (0.061)    | 0 (0.000) |    11.43 | adeX, lauNX, NBK-, Nivera, reiko |
|            7 |      861 | 2024-07-05 | lajtbitexe      | L   | 1.000      | -            | -                | -                | -         |   -19.01 | adeX, lauNX, NBK-, Nivera, reiko |
|            6 |      894 | 2024-06-25 | Johnny Speeds   | L   | 0.938      | -            | -                | -                | -         |    -2.46 | adeX, lauNX, NBK-, Nivera, reiko |
|            5 |      901 | 2024-06-23 | Heimo           | W   | 0.924      | 0.333        | 0.006 (0.002)    | 0.089 (0.027)    | 0 (0.000) |     9.02 | adeX, lauNX, NBK-, Nivera, reiko |
|            4 |      921 | 2024-06-16 | CYBERSHOKE      | L   | 0.880      | -            | -                | -                | -         |   -11.21 | adeX, lauNX, NBK-, Nivera, reiko |
|            3 |      945 | 2024-06-15 | Verdant         | W   | 0.874      | 0.143        | 0.015 (0.002)    | 0.310 (0.039)    | 0 (0.000) |    16.33 | adeX, lauNX, NBK-, Nivera, reiko |
|            2 |      994 | 2024-06-14 | Astralis Talent | W   | 0.865      | 0.143        | 0.007 (0.001)    | 0.168 (0.021)    | 0 (0.000) |    11.09 | adeX, lauNX, NBK-, Nivera, reiko |
|            1 |     1021 | 2024-06-13 | Verdant         | L   | 0.859      | -            | -                | -                | -         |    -9.77 | adeX, lauNX, NBK-, Nivera, reiko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,815.28)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-09 |      1.000 | $6,000.00      | $6,000.00       |
| 2024-06-25 |      0.938 | $3,000.00      | $2,815.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
