### Roster Details<br />
Team Name: Preasy<br />
Roster: AcilioN, Beccie, Equip, Griller, Skejs<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [91]( ../standings_europe.md)<br />
<br />
Final Rank Value:  777.5<br />
<br />
Final Rank Value (777.5) = Starting Rank Value (789.9) + Head To Head Adjustments (-12.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.307[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.057[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 789.9
- 400 + ( ( 0.191 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 789.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      466 | 2024-07-21 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -6.50 | AcilioN, Beccie, Equip, Griller, Skejs |
|           22 |      521 | 2024-07-19 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.66 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           21 |      536 | 2024-07-19 | FORZE Reload      | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.039 (0.013)    | 0 (0.000) |     7.17 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           20 |      577 | 2024-07-18 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.68 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           19 |      652 | 2024-07-17 | kONO              | W   | 1.000      | 0.333        | 0.028 (0.009)    | 0.536 (0.179)    | 0 (0.000) |    17.77 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           18 |      654 | 2024-07-17 | LEON              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.130 (0.019)    | 0 (0.000) |    11.28 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           17 |      778 | 2024-07-14 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -6.40 | AcilioN, Beccie, Equip, Griller, VireZ |
|           16 |      840 | 2024-07-10 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -8.83 | Beccie, Equip, Griller, Skejs, VireZ   |
|           15 |      977 | 2024-06-16 | Aurora Young Blud | L   | 0.873      | -            | -                | -                | -         |   -10.86 | Beccie, Equip, Griller, Skejs, VireZ   |
|           14 |     1012 | 2024-06-15 | LEON              | W   | 0.866      | 0.143        | 0.007 (0.001)    | 0.130 (0.016)    | 0 (0.000) |     9.64 | Beccie, Equip, Griller, Skejs, VireZ   |
|           13 |     1113 | 2024-06-12 | MASONIC           | W   | 0.846      | 0.143        | 0.009 (0.001)    | 0.085 (0.010)    | 0 (0.000) |    12.28 | Beccie, Equip, Griller, Skejs, VireZ   |
|           12 |     1129 | 2024-06-11 | CYBERSHOKE        | L   | 0.841      | -            | -                | -                | -         |    -9.71 | Beccie, Equip, Griller, Skejs, VireZ   |
|           11 |     1225 | 2024-06-09 | Johnny Speeds     | L   | 0.826      | -            | -                | -                | -         |    -2.00 | Equip, Griller, Maze, Skejs, VireZ     |
|           10 |     1676 | 2024-05-28 | Permitta          | L   | 0.747      | -            | -                | -                | -         |    -7.66 | Beccie, Equip, Griller, Skejs, VireZ   |
|            9 |     1715 | 2024-05-26 | Johnny Speeds     | L   | 0.734      | -            | -                | -                | -         |    -1.61 | Beccie, Equip, Griller, Skejs, VireZ   |
|            8 |     1808 | 2024-05-22 | ECLOT             | W   | 0.707      | 0.371        | 0.062 (0.016)    | 0.559 (0.146)    | 0 (0.000) |    19.94 | Beccie, Equip, Griller, Skejs, VireZ   |
|            7 |     2077 | 2024-05-15 | kONO              | L   | 0.659      | -            | -                | -                | -         |    -7.98 | Beccie, Equip, Griller, Skejs, VireZ   |
|            6 |     2124 | 2024-05-14 | Zero Tenacity     | L   | 0.654      | -            | -                | -                | -         |    -3.77 | AcilioN, Beccie, Equip, Griller, VireZ |
|            5 |     2172 | 2024-05-12 | Johnny Speeds     | W   | 0.640      | 0.333        | 0.122 (0.026)    | 0.901 (0.192)    | 0 (0.000) |    18.99 | Beccie, Equip, Griller, Skejs, VireZ   |
|            4 |     2206 | 2024-05-11 | Passion UA        | L   | 0.633      | -            | -                | -                | -         |    -3.85 | Beccie, Equip, Griller, Skejs, VireZ   |
|            3 |     2484 | 2024-04-27 | 777               | L   | 0.541      | -            | -                | -                | -         |   -10.34 | Beccie, Equip, Griller, Skejs, VireZ   |
|            2 |     2618 | 2024-04-21 | Astralis Talent   | L   | 0.499      | -            | -                | -                | -         |    -8.18 | Beccie, Equip, Griller, Skejs, VireZ   |
|            1 |     2626 | 2024-04-20 | Sashi Academy     | W   | 0.496      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.496) |     1.57 | Beccie, Equip, Griller, Skejs, VireZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,876.99)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-09 |      0.828 | $1,445.00      | $1,196.54       |
| 2024-05-16 |      0.666 | $1,500.00      | $999.17         |
| 2024-04-27 |      0.542 | $795.00        | $431.29         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
