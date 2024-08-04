### Roster Details<br />
Team Name: Preasy<br />
Roster: AcilioN, Beccie, Equip, Griller, Skejs<br />
Global Rank: [129](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [90]( ../standings_europe.md)<br />
<br />
Final Rank Value:  778.2<br />
<br />
Final Rank Value (778.2) = Starting Rank Value (789.9) + Head To Head Adjustments (-11.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.307[<sup>2</sup>](#table1)
- Opponent Network: 0.057[<sup>2</sup>](#table1)
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
|           23 |      474 | 2024-07-21 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -6.51 | AcilioN, Beccie, Equip, Griller, Skejs |
|           22 |      529 | 2024-07-19 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.67 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           21 |      544 | 2024-07-19 | FORZE Reload      | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.039 (0.013)    | 0 (0.000) |     7.15 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           20 |      585 | 2024-07-18 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.71 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           19 |      660 | 2024-07-17 | kONO              | W   | 1.000      | 0.333        | 0.028 (0.009)    | 0.536 (0.179)    | 0 (0.000) |    17.74 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           18 |      662 | 2024-07-17 | LEON              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.130 (0.019)    | 0 (0.000) |    11.28 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           17 |      786 | 2024-07-14 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -6.38 | AcilioN, Beccie, Equip, Griller, VireZ |
|           16 |      848 | 2024-07-10 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -8.78 | Beccie, Equip, Griller, Skejs, VireZ   |
|           15 |      985 | 2024-06-16 | Aurora Young Blud | L   | 0.872      | -            | -                | -                | -         |   -10.30 | Beccie, Equip, Griller, Skejs, VireZ   |
|           14 |     1020 | 2024-06-15 | LEON              | W   | 0.866      | 0.143        | 0.007 (0.001)    | 0.130 (0.016)    | 0 (0.000) |     9.65 | Beccie, Equip, Griller, Skejs, VireZ   |
|           13 |     1121 | 2024-06-12 | MASONIC           | W   | 0.846      | 0.143        | 0.009 (0.001)    | 0.085 (0.010)    | 0 (0.000) |    12.26 | Beccie, Equip, Griller, Skejs, VireZ   |
|           12 |     1137 | 2024-06-11 | CYBERSHOKE        | L   | 0.840      | -            | -                | -                | -         |    -9.65 | Beccie, Equip, Griller, Skejs, VireZ   |
|           11 |     1233 | 2024-06-09 | Johnny Speeds     | L   | 0.825      | -            | -                | -                | -         |    -2.00 | Equip, Griller, Maze, Skejs, VireZ     |
|           10 |     1684 | 2024-05-28 | Permitta          | L   | 0.746      | -            | -                | -                | -         |    -7.63 | Beccie, Equip, Griller, Skejs, VireZ   |
|            9 |     1723 | 2024-05-26 | Johnny Speeds     | L   | 0.733      | -            | -                | -                | -         |    -1.60 | Beccie, Equip, Griller, Skejs, VireZ   |
|            8 |     1816 | 2024-05-22 | ECLOT             | W   | 0.706      | 0.371        | 0.062 (0.016)    | 0.559 (0.146)    | 0 (0.000) |    19.93 | Beccie, Equip, Griller, Skejs, VireZ   |
|            7 |     2085 | 2024-05-15 | kONO              | L   | 0.659      | -            | -                | -                | -         |    -7.97 | Beccie, Equip, Griller, Skejs, VireZ   |
|            6 |     2132 | 2024-05-14 | Zero Tenacity     | L   | 0.653      | -            | -                | -                | -         |    -3.77 | AcilioN, Beccie, Equip, Griller, VireZ |
|            5 |     2180 | 2024-05-12 | Johnny Speeds     | W   | 0.639      | 0.333        | 0.122 (0.026)    | 0.902 (0.192)    | 0 (0.000) |    18.97 | Beccie, Equip, Griller, Skejs, VireZ   |
|            4 |     2214 | 2024-05-11 | Passion UA        | L   | 0.632      | -            | -                | -                | -         |    -3.83 | Beccie, Equip, Griller, Skejs, VireZ   |
|            3 |     2492 | 2024-04-27 | 777               | L   | 0.540      | -            | -                | -                | -         |   -10.33 | Beccie, Equip, Griller, Skejs, VireZ   |
|            2 |     2626 | 2024-04-21 | Astralis Talent   | L   | 0.499      | -            | -                | -                | -         |    -8.16 | Beccie, Equip, Griller, Skejs, VireZ   |
|            1 |     2634 | 2024-04-20 | Sashi Academy     | W   | 0.495      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.495) |     1.57 | Beccie, Equip, Griller, Skejs, VireZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,874.31)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-09 |      0.827 | $1,445.00      | $1,195.50       |
| 2024-05-16 |      0.665 | $1,500.00      | $998.09         |
| 2024-04-27 |      0.542 | $795.00        | $430.72         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
