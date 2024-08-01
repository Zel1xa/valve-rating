### Roster Details<br />
Team Name: Preasy<br />
Roster: AcilioN, Beccie, Equip, Griller, Skejs<br />
Global Rank: [128](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [89]( ../standings_europe.md)<br />
<br />
Final Rank Value:  782.1<br />
<br />
Final Rank Value (782.1) = Starting Rank Value (794.3) + Head To Head Adjustments (-12.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.308[<sup>2</sup>](#table1)
- Opponent Network: 0.056[<sup>2</sup>](#table1)
- LAN Wins: 0.059[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 794.3
- 400 + ( ( 0.191 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 794.3


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
|           23 |      380 | 2024-07-21 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -6.62 | AcilioN, Beccie, Equip, Griller, Skejs |
|           22 |      437 | 2024-07-19 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.61 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           21 |      453 | 2024-07-19 | FORZE Reload      | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.039 (0.013)    | 0 (0.000) |     7.07 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           20 |      498 | 2024-07-18 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -21.42 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           19 |      573 | 2024-07-17 | kONO              | W   | 1.000      | 0.333        | 0.029 (0.010)    | 0.547 (0.182)    | 0 (0.000) |    18.66 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           18 |      575 | 2024-07-17 | LEON              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.131 (0.019)    | 0 (0.000) |    11.26 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           17 |      707 | 2024-07-14 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -6.75 | AcilioN, Beccie, Equip, Griller, VireZ |
|           16 |      769 | 2024-07-10 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -8.80 | Beccie, Equip, Griller, Skejs, VireZ   |
|           15 |      904 | 2024-06-16 | Aurora Young Blud | L   | 0.892      | -            | -                | -                | -         |    -9.80 | Beccie, Equip, Griller, Skejs, VireZ   |
|           14 |      936 | 2024-06-15 | LEON              | W   | 0.886      | 0.143        | 0.007 (0.001)    | 0.131 (0.017)    | 0 (0.000) |     9.87 | Beccie, Equip, Griller, Skejs, VireZ   |
|           13 |     1031 | 2024-06-12 | MASONIC           | W   | 0.866      | 0.143        | 0.009 (0.001)    | 0.086 (0.011)    | 0 (0.000) |    12.71 | Beccie, Equip, Griller, Skejs, VireZ   |
|           12 |     1048 | 2024-06-11 | CYBERSHOKE        | L   | 0.860      | -            | -                | -                | -         |    -9.84 | Beccie, Equip, Griller, Skejs, VireZ   |
|           11 |     1146 | 2024-06-09 | Johnny Speeds     | L   | 0.846      | -            | -                | -                | -         |    -2.02 | Equip, Griller, Maze, Skejs, VireZ     |
|           10 |     1611 | 2024-05-28 | Permitta          | L   | 0.766      | -            | -                | -                | -         |    -7.99 | Beccie, Equip, Griller, Skejs, VireZ   |
|            9 |     1652 | 2024-05-26 | Johnny Speeds     | L   | 0.753      | -            | -                | -                | -         |    -1.61 | Beccie, Equip, Griller, Skejs, VireZ   |
|            8 |     1755 | 2024-05-22 | ECLOT             | W   | 0.726      | 0.371        | 0.064 (0.017)    | 0.501 (0.135)    | 0 (0.000) |    19.33 | Beccie, Equip, Griller, Skejs, VireZ   |
|            7 |     2046 | 2024-05-15 | kONO              | L   | 0.679      | -            | -                | -                | -         |    -7.76 | Beccie, Equip, Griller, Skejs, VireZ   |
|            6 |     2094 | 2024-05-14 | Zero Tenacity     | L   | 0.673      | -            | -                | -                | -         |    -4.00 | AcilioN, Beccie, Equip, Griller, VireZ |
|            5 |     2144 | 2024-05-12 | Johnny Speeds     | W   | 0.659      | 0.333        | 0.124 (0.027)    | 0.818 (0.180)    | 0 (0.000) |    19.61 | Beccie, Equip, Griller, Skejs, VireZ   |
|            4 |     2178 | 2024-05-11 | Passion UA        | L   | 0.652      | -            | -                | -                | -         |    -4.04 | Beccie, Equip, Griller, Skejs, VireZ   |
|            3 |     2461 | 2024-04-27 | 777               | L   | 0.561      | -            | -                | -                | -         |   -10.72 | Beccie, Equip, Griller, Skejs, VireZ   |
|            2 |     2599 | 2024-04-21 | Astralis Talent   | L   | 0.519      | -            | -                | -                | -         |    -8.35 | Beccie, Equip, Griller, Skejs, VireZ   |
|            1 |     2609 | 2024-04-20 | Sashi Academy     | W   | 0.515      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.515) |     1.60 | Beccie, Equip, Griller, Skejs, VireZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,949.72)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-09 |      0.848 | $1,445.00      | $1,224.64       |
| 2024-05-16 |      0.686 | $1,500.00      | $1,028.33       |
| 2024-04-27 |      0.562 | $795.00        | $446.75         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
