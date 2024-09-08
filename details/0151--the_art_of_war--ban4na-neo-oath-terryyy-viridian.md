### Roster Details<br />
Team Name: The Art of War<br />
Roster: BaN4na, neo, Oath, Terryyy, viridian<br />
Global Rank: [151](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [12]( ../standings_asia.md)<br />
<br />
Final Rank Value:  698.7<br />
<br />
Final Rank Value (698.7) = Starting Rank Value (653.3) + Head To Head Adjustments (45.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.229[<sup>1</sup>](#table2)
- Bounty Collected: 0.241[<sup>2</sup>](#table1)
- Opponent Network: 0.053[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 653.3
- 400 + ( ( 0.131 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 653.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |      361 | 2024-08-27 | Arcade           | L   | 1.000      | -            | -                | -                | -         |   -19.61 | BaN4na, neo, Oath, Terryyy, viridian     |
|           18 |      401 | 2024-08-27 | Rooster          | L   | 1.000      | -            | -                | -                | -         |   -13.41 | BaN4na, neo, Oath, Terryyy, viridian     |
|           17 |      410 | 2024-08-26 | KZG              | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.152 (0.022)    | 0 (0.000) |    12.49 | BaN4na, neo, Oath, Terryyy, viridian     |
|           16 |      532 | 2024-08-24 | Arcade           | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.245 (0.035)    | 0 (0.000) |    11.19 | BaN4na, neo, Oath, Terryyy, viridian     |
|           15 |      534 | 2024-08-24 | TALON            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.262 (0.037)    | 0 (0.000) |    11.64 | BaN4na, neo, Oath, Terryyy, viridian     |
|           14 |      541 | 2024-08-23 | Shanghai Sharks  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.03 | BaN4na, neo, Oath, Terryyy, viridian     |
|           13 |      590 | 2024-08-22 | Rooster          | L   | 1.000      | -            | -                | -                | -         |   -13.19 | BaN4na, neo, Oath, Terryyy, viridian     |
|           12 |      658 | 2024-08-21 | Mindfreak        | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.227 (0.032)    | 0 (0.000) |    18.38 | BaN4na, neo, Oath, Terryyy, viridian     |
|           11 |      678 | 2024-08-20 | Housebets        | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.153 (0.022)    | 0 (0.000) |    16.78 | BaN4na, neo, Oath, Terryyy, viridian     |
|           10 |      890 | 2024-08-13 | Housebets        | L   | 1.000      | -            | -                | -                | -         |   -14.63 | BaN4na, neo, Oath, Terryyy, viridian     |
|            9 |      896 | 2024-08-13 | Housebets        | L   | 1.000      | -            | -                | -                | -         |   -15.98 | BaN4na, neo, Oath, Terryyy, viridian     |
|            8 |      988 | 2024-08-09 | Arcade           | L   | 1.000      | -            | -                | -                | -         |   -19.57 | BaN4na, neo, Oath, Terryyy, viridian     |
|            7 |      990 | 2024-08-09 | Let's go golfing | L   | 1.000      | -            | -                | -                | -         |   -12.61 | BaN4na, neo, Oath, Terryyy, viridian     |
|            6 |     1086 | 2024-08-07 | Arcade           | W   | 0.986      | 0.333        | 0.002 (0.001)    | 0.245 (0.080)    | 0 (0.000) |    11.37 | BaN4na, neo, Oath, Terryyy, viridian     |
|            5 |     1091 | 2024-08-07 | Arcade           | W   | 0.986      | 0.333        | 0.002 (0.001)    | 0.245 (0.080)    | 0 (0.000) |    12.34 | BaN4na, neo, Oath, Terryyy, viridian     |
|            4 |     1344 | 2024-07-31 | Above The Rest   | W   | 0.939      | -            | -                | -                | 0 (0.000) |     7.39 | BaN4na, neo, Oath, Terryyy, viridian     |
|            3 |     1387 | 2024-07-30 | Vantage          | W   | 0.932      | 0.143        | 0.002 (0.000)    | 0.150 (0.020)    | 0 (0.000) |    12.33 | BaN4na, neo, Oath, Terryyy, viridian     |
|            2 |     1606 | 2024-07-23 | Rooster          | W   | 0.886      | 0.333        | 0.007 (0.002)    | 0.342 (0.101)    | -         |    17.09 | BaN4na, bebest, neo, sunshinez, viridian |
|            1 |     1611 | 2024-07-23 | Rooster          | W   | 0.886      | 0.333        | 0.007 (0.002)    | 0.342 (0.101)    | -         |    18.38 | BaN4na, bebest, neo, sunshinez, viridian |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($131.00)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
