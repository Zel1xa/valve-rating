### Roster Details<br />
Team Name: Preasy<br />
Roster: AcilioN, Beccie, Equip, Griller, Skejs<br />
Global Rank: [132](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [91]( ../standings_europe.md)<br />
<br />
Final Rank Value:  779.5<br />
<br />
Final Rank Value (779.5) = Starting Rank Value (790.7) + Head To Head Adjustments (-11.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.306[<sup>2</sup>](#table1)
- Opponent Network: 0.059[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 790.7
- 400 + ( ( 0.191 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 790.7


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
|           23 |      515 | 2024-07-21 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -6.26 | AcilioN, Beccie, Equip, Griller, Skejs |
|           22 |      570 | 2024-07-19 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.60 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           21 |      585 | 2024-07-19 | FORZE Reload      | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.040 (0.013)    | 0 (0.000) |     7.13 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           20 |      626 | 2024-07-18 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.71 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           19 |      701 | 2024-07-17 | kONO              | W   | 1.000      | 0.333        | 0.028 (0.009)    | 0.574 (0.191)    | 0 (0.000) |    17.70 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           18 |      703 | 2024-07-17 | LEON              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.129 (0.018)    | 0 (0.000) |    11.25 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           17 |      827 | 2024-07-14 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -6.25 | AcilioN, Beccie, Equip, Griller, VireZ |
|           16 |      889 | 2024-07-10 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -8.83 | Beccie, Equip, Griller, Skejs, VireZ   |
|           15 |     1026 | 2024-06-16 | Aurora Young Blud | L   | 0.866      | -            | -                | -                | -         |   -10.22 | Beccie, Equip, Griller, Skejs, VireZ   |
|           14 |     1061 | 2024-06-15 | LEON              | W   | 0.859      | 0.143        | 0.007 (0.001)    | 0.129 (0.016)    | 0 (0.000) |     9.55 | Beccie, Equip, Griller, Skejs, VireZ   |
|           13 |     1162 | 2024-06-12 | MASONIC           | W   | 0.839      | 0.143        | 0.009 (0.001)    | 0.084 (0.010)    | 0 (0.000) |    12.11 | Beccie, Equip, Griller, Skejs, VireZ   |
|           12 |     1178 | 2024-06-11 | CYBERSHOKE        | L   | 0.833      | -            | -                | -                | -         |    -9.58 | Beccie, Equip, Griller, Skejs, VireZ   |
|           11 |     1274 | 2024-06-09 | Johnny Speeds     | L   | 0.819      | -            | -                | -                | -         |    -1.91 | Equip, Griller, Maze, Skejs, VireZ     |
|           10 |     1725 | 2024-05-28 | Permitta          | L   | 0.739      | -            | -                | -                | -         |    -7.55 | Beccie, Equip, Griller, Skejs, VireZ   |
|            9 |     1764 | 2024-05-26 | Johnny Speeds     | L   | 0.726      | -            | -                | -                | -         |    -1.53 | Beccie, Equip, Griller, Skejs, VireZ   |
|            8 |     1857 | 2024-05-22 | ECLOT             | W   | 0.699      | 0.371        | 0.062 (0.016)    | 0.557 (0.144)    | 0 (0.000) |    19.76 | Beccie, Equip, Griller, Skejs, VireZ   |
|            7 |     2126 | 2024-05-15 | kONO              | L   | 0.652      | -            | -                | -                | -         |    -7.95 | Beccie, Equip, Griller, Skejs, VireZ   |
|            6 |     2173 | 2024-05-14 | Zero Tenacity     | L   | 0.646      | -            | -                | -                | -         |    -3.70 | AcilioN, Beccie, Equip, Griller, VireZ |
|            5 |     2221 | 2024-05-12 | Johnny Speeds     | W   | 0.632      | 0.333        | 0.122 (0.026)    | 0.940 (0.198)    | 0 (0.000) |    18.82 | Beccie, Equip, Griller, Skejs, VireZ   |
|            4 |     2255 | 2024-05-11 | Passion UA        | L   | 0.625      | -            | -                | -                | -         |    -3.73 | Beccie, Equip, Griller, Skejs, VireZ   |
|            3 |     2533 | 2024-04-27 | 777               | L   | 0.534      | -            | -                | -                | -         |   -10.21 | Beccie, Equip, Griller, Skejs, VireZ   |
|            2 |     2667 | 2024-04-21 | Astralis Talent   | L   | 0.492      | -            | -                | -                | -         |    -8.07 | Beccie, Equip, Griller, Skejs, VireZ   |
|            1 |     2675 | 2024-04-20 | Sashi Academy     | W   | 0.488      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.488) |     1.54 | Beccie, Equip, Griller, Skejs, VireZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,848.94)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-09 |      0.821 | $1,445.00      | $1,185.70       |
| 2024-05-16 |      0.659 | $1,500.00      | $987.92         |
| 2024-04-27 |      0.535 | $795.00        | $425.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
