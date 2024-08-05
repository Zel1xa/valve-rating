### Roster Details<br />
Team Name: Preasy<br />
Roster: AcilioN, Beccie, Equip, Griller, Skejs<br />
Global Rank: [131](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [91]( ../standings_europe.md)<br />
<br />
Final Rank Value:  778.7<br />
<br />
Final Rank Value (778.7) = Starting Rank Value (790.2) + Head To Head Adjustments (-11.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.306[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 790.2
- 400 + ( ( 0.191 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 790.2


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
|           23 |      502 | 2024-07-21 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -6.49 | AcilioN, Beccie, Equip, Griller, Skejs |
|           22 |      557 | 2024-07-19 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.61 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           21 |      572 | 2024-07-19 | FORZE Reload      | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.040 (0.013)    | 0 (0.000) |     7.14 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           20 |      613 | 2024-07-18 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.71 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           19 |      688 | 2024-07-17 | kONO              | W   | 1.000      | 0.333        | 0.028 (0.009)    | 0.536 (0.179)    | 0 (0.000) |    17.73 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           18 |      690 | 2024-07-17 | LEON              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.130 (0.019)    | 0 (0.000) |    11.26 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           17 |      814 | 2024-07-14 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -6.33 | AcilioN, Beccie, Equip, Griller, VireZ |
|           16 |      876 | 2024-07-10 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -8.82 | Beccie, Equip, Griller, Skejs, VireZ   |
|           15 |     1013 | 2024-06-16 | Aurora Young Blud | L   | 0.869      | -            | -                | -                | -         |   -10.28 | Beccie, Equip, Griller, Skejs, VireZ   |
|           14 |     1048 | 2024-06-15 | LEON              | W   | 0.862      | 0.143        | 0.007 (0.001)    | 0.130 (0.016)    | 0 (0.000) |     9.60 | Beccie, Equip, Griller, Skejs, VireZ   |
|           13 |     1149 | 2024-06-12 | MASONIC           | W   | 0.842      | 0.143        | 0.009 (0.001)    | 0.085 (0.010)    | 0 (0.000) |    12.18 | Beccie, Equip, Griller, Skejs, VireZ   |
|           12 |     1165 | 2024-06-11 | CYBERSHOKE        | L   | 0.836      | -            | -                | -                | -         |    -9.62 | Beccie, Equip, Griller, Skejs, VireZ   |
|           11 |     1261 | 2024-06-09 | Johnny Speeds     | L   | 0.822      | -            | -                | -                | -         |    -1.93 | Equip, Griller, Maze, Skejs, VireZ     |
|           10 |     1712 | 2024-05-28 | Permitta          | L   | 0.743      | -            | -                | -                | -         |    -7.58 | Beccie, Equip, Griller, Skejs, VireZ   |
|            9 |     1751 | 2024-05-26 | Johnny Speeds     | L   | 0.729      | -            | -                | -                | -         |    -1.54 | Beccie, Equip, Griller, Skejs, VireZ   |
|            8 |     1844 | 2024-05-22 | ECLOT             | W   | 0.703      | 0.371        | 0.062 (0.016)    | 0.558 (0.145)    | 0 (0.000) |    19.86 | Beccie, Equip, Griller, Skejs, VireZ   |
|            7 |     2113 | 2024-05-15 | kONO              | L   | 0.655      | -            | -                | -                | -         |    -7.96 | Beccie, Equip, Griller, Skejs, VireZ   |
|            6 |     2160 | 2024-05-14 | Zero Tenacity     | L   | 0.649      | -            | -                | -                | -         |    -3.72 | AcilioN, Beccie, Equip, Griller, VireZ |
|            5 |     2208 | 2024-05-12 | Johnny Speeds     | W   | 0.636      | 0.333        | 0.122 (0.026)    | 0.942 (0.200)    | 0 (0.000) |    18.91 | Beccie, Equip, Griller, Skejs, VireZ   |
|            4 |     2242 | 2024-05-11 | Passion UA        | L   | 0.629      | -            | -                | -                | -         |    -3.76 | Beccie, Equip, Griller, Skejs, VireZ   |
|            3 |     2520 | 2024-04-27 | 777               | L   | 0.537      | -            | -                | -                | -         |   -10.27 | Beccie, Equip, Griller, Skejs, VireZ   |
|            2 |     2654 | 2024-04-21 | Astralis Talent   | L   | 0.495      | -            | -                | -                | -         |    -8.12 | Beccie, Equip, Griller, Skejs, VireZ   |
|            1 |     2662 | 2024-04-20 | Sashi Academy     | W   | 0.491      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.491) |     1.56 | Beccie, Equip, Griller, Skejs, VireZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,861.41)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-09 |      0.824 | $1,445.00      | $1,190.52       |
| 2024-05-16 |      0.662 | $1,500.00      | $992.92         |
| 2024-04-27 |      0.538 | $795.00        | $427.98         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
