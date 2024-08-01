### Roster Details<br />
Team Name: Preasy<br />
Roster: AcilioN, Beccie, Equip, Griller, Skejs<br />
Global Rank: [126](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [88]( ../standings_europe.md)<br />
<br />
Final Rank Value:  782.2<br />
<br />
Final Rank Value (782.2) = Starting Rank Value (793.7) + Head To Head Adjustments (-11.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.308[<sup>2</sup>](#table1)
- Opponent Network: 0.055[<sup>2</sup>](#table1)
- LAN Wins: 0.059[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 793.7
- 400 + ( ( 0.191 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 793.7


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
|           23 |      386 | 2024-07-21 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -6.63 | AcilioN, Beccie, Equip, Griller, Skejs |
|           22 |      443 | 2024-07-19 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.63 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           21 |      459 | 2024-07-19 | FORZE Reload      | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.039 (0.013)    | 0 (0.000) |     7.06 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           20 |      504 | 2024-07-18 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.67 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           19 |      579 | 2024-07-17 | kONO              | W   | 1.000      | 0.333        | 0.029 (0.010)    | 0.547 (0.182)    | 0 (0.000) |    18.66 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           18 |      581 | 2024-07-17 | LEON              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.131 (0.019)    | 0 (0.000) |    11.27 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           17 |      713 | 2024-07-14 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -6.75 | AcilioN, Beccie, Equip, Griller, VireZ |
|           16 |      775 | 2024-07-10 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -8.82 | Beccie, Equip, Griller, Skejs, VireZ   |
|           15 |      910 | 2024-06-16 | Aurora Young Blud | L   | 0.891      | -            | -                | -                | -         |    -9.76 | Beccie, Equip, Griller, Skejs, VireZ   |
|           14 |      942 | 2024-06-15 | LEON              | W   | 0.884      | 0.143        | 0.007 (0.001)    | 0.131 (0.017)    | 0 (0.000) |     9.86 | Beccie, Equip, Griller, Skejs, VireZ   |
|           13 |     1037 | 2024-06-12 | MASONIC           | W   | 0.864      | 0.143        | 0.009 (0.001)    | 0.086 (0.011)    | 0 (0.000) |    12.69 | Beccie, Equip, Griller, Skejs, VireZ   |
|           12 |     1054 | 2024-06-11 | CYBERSHOKE        | L   | 0.858      | -            | -                | -                | -         |    -9.82 | Beccie, Equip, Griller, Skejs, VireZ   |
|           11 |     1152 | 2024-06-09 | Johnny Speeds     | L   | 0.844      | -            | -                | -                | -         |    -2.02 | Equip, Griller, Maze, Skejs, VireZ     |
|           10 |     1617 | 2024-05-28 | Permitta          | L   | 0.765      | -            | -                | -                | -         |    -8.01 | Beccie, Equip, Griller, Skejs, VireZ   |
|            9 |     1658 | 2024-05-26 | Johnny Speeds     | L   | 0.751      | -            | -                | -                | -         |    -1.61 | Beccie, Equip, Griller, Skejs, VireZ   |
|            8 |     1761 | 2024-05-22 | ECLOT             | W   | 0.725      | 0.371        | 0.064 (0.017)    | 0.501 (0.135)    | 0 (0.000) |    19.27 | Beccie, Equip, Griller, Skejs, VireZ   |
|            7 |     2052 | 2024-05-15 | kONO              | L   | 0.677      | -            | -                | -                | -         |    -7.75 | Beccie, Equip, Griller, Skejs, VireZ   |
|            6 |     2100 | 2024-05-14 | Zero Tenacity     | L   | 0.671      | -            | -                | -                | -         |    -3.98 | AcilioN, Beccie, Equip, Griller, VireZ |
|            5 |     2150 | 2024-05-12 | Johnny Speeds     | W   | 0.657      | 0.333        | 0.124 (0.027)    | 0.819 (0.179)    | 0 (0.000) |    19.56 | Beccie, Equip, Griller, Skejs, VireZ   |
|            4 |     2184 | 2024-05-11 | Passion UA        | L   | 0.651      | -            | -                | -                | -         |    -4.03 | Beccie, Equip, Griller, Skejs, VireZ   |
|            3 |     2467 | 2024-04-27 | 777               | L   | 0.559      | -            | -                | -                | -         |   -10.69 | Beccie, Equip, Griller, Skejs, VireZ   |
|            2 |     2605 | 2024-04-21 | Astralis Talent   | L   | 0.517      | -            | -                | -                | -         |    -8.32 | Beccie, Equip, Griller, Skejs, VireZ   |
|            1 |     2615 | 2024-04-20 | Sashi Academy     | W   | 0.513      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.513) |     1.60 | Beccie, Equip, Griller, Skejs, VireZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,943.48)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-09 |      0.846 | $1,445.00      | $1,222.23       |
| 2024-05-16 |      0.684 | $1,500.00      | $1,025.83       |
| 2024-04-27 |      0.560 | $795.00        | $445.42         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
