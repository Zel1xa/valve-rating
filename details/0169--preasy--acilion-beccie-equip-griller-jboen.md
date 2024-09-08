### Roster Details<br />
Team Name: Preasy<br />
Roster: AcilioN, Beccie, Equip, Griller, JBOEN<br />
Global Rank: [169](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [109]( ../standings_europe.md)<br />
<br />
Final Rank Value:  651.6<br />
<br />
Final Rank Value (651.6) = Starting Rank Value (723.7) + Head To Head Adjustments (-72.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.314[<sup>1</sup>](#table2)
- Bounty Collected: 0.285[<sup>2</sup>](#table1)
- Opponent Network: 0.043[<sup>2</sup>](#table1)
- LAN Wins: 0.027[<sup>2</sup>](#table1)

The average of these factors is 0.167<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 723.7
- 400 + ( ( 0.167 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 723.7


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
|           30 |      585 | 2024-08-22 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -10.48 | AcilioN, Beccie, Equip, Griller, JBOEN |
|           29 |      634 | 2024-08-21 | FAVBET            | L   | 1.000      | -            | -                | -                | -         |    -8.12 | AcilioN, Beccie, Equip, Griller, JBOEN |
|           28 |      748 | 2024-08-18 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |    -6.32 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           27 |      848 | 2024-08-14 | Permitta          | L   | 1.000      | -            | -                | -                | -         |    -7.08 | Beccie, Equip, JBOEN, Skejs, tOPZ      |
|           26 |      933 | 2024-08-12 | Monte Gen         | L   | 1.000      | -            | -                | -                | -         |   -10.51 | Beccie, Equip, JBOEN, Skejs, tOPZ      |
|           25 |     1012 | 2024-08-09 | Project G         | L   | 0.999      | -            | -                | -                | -         |   -21.99 | Beccie, Equip, JBOEN, Skejs, tOPZ      |
|           24 |     1076 | 2024-08-07 | The Suspect       | L   | 0.987      | -            | -                | -                | -         |   -10.92 | Beccie, Equip, JBOEN, Skejs, tOPZ      |
|           23 |     1143 | 2024-08-05 | Young Ninjas      | L   | 0.974      | -            | -                | -                | -         |   -11.58 | Beccie, Equip, JBOEN, Skejs, tOPZ      |
|           22 |     1662 | 2024-07-21 | TSM               | L   | 0.872      | -            | -                | -                | -         |    -4.31 | AcilioN, Beccie, Equip, Griller, Skejs |
|           21 |     1717 | 2024-07-19 | Johnny Speeds     | L   | 0.861      | -            | -                | -                | -         |    -2.79 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           20 |     1732 | 2024-07-19 | FORZE Reload      | W   | 0.859      | 0.333        | 0.000 (0.000)    | 0.032 (0.009)    | 0 (0.000) |     6.92 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           19 |     1773 | 2024-07-18 | Into the Breach   | L   | 0.854      | -            | -                | -                | -         |    -9.36 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           18 |     1848 | 2024-07-17 | kONO              | W   | 0.847      | 0.333        | 0.025 (0.007)    | 0.532 (0.150)    | 0 (0.000) |    16.64 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           17 |     1850 | 2024-07-17 | LEON              | W   | 0.846      | 0.143        | 0.005 (0.001)    | 0.080 (0.010)    | 0 (0.000) |    10.48 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           16 |     1977 | 2024-07-14 | Passion UA        | L   | 0.825      | -            | -                | -                | -         |    -4.32 | AcilioN, Beccie, Equip, Griller, VireZ |
|           15 |     2039 | 2024-07-10 | Insilio           | L   | 0.799      | -            | -                | -                | -         |    -6.43 | Beccie, Equip, Griller, Skejs, VireZ   |
|           14 |     2176 | 2024-06-16 | Aurora Young Blud | L   | 0.639      | -            | -                | -                | -         |    -5.31 | Beccie, Equip, Griller, Skejs, VireZ   |
|           13 |     2211 | 2024-06-15 | LEON              | W   | 0.632      | 0.143        | 0.005 (0.000)    | 0.080 (0.007)    | 0 (0.000) |     7.93 | Beccie, Equip, Griller, Skejs, VireZ   |
|           12 |     2312 | 2024-06-12 | MASONIC           | W   | 0.612      | 0.143        | 0.005 (0.000)    | 0.046 (0.004)    | 0 (0.000) |     8.37 | Beccie, Equip, Griller, Skejs, VireZ   |
|           11 |     2328 | 2024-06-11 | CYBERSHOKE        | L   | 0.606      | -            | -                | -                | -         |    -4.86 | Beccie, Equip, Griller, Skejs, VireZ   |
|           10 |     2875 | 2024-05-28 | Permitta          | L   | 0.513      | -            | -                | -                | -         |    -4.20 | Beccie, Equip, Griller, Skejs, VireZ   |
|            9 |     2914 | 2024-05-26 | Johnny Speeds     | L   | 0.499      | -            | -                | -                | -         |    -1.52 | Beccie, Equip, Griller, Skejs, VireZ   |
|            8 |     3007 | 2024-05-22 | ECLOT             | W   | 0.473      | 0.371        | 0.047 (0.008)    | 0.698 (0.122)    | 0 (0.000) |    13.01 | Beccie, Equip, Griller, Skejs, VireZ   |
|            7 |     3276 | 2024-05-15 | kONO              | L   | 0.425      | -            | -                | -                | -         |    -4.31 | Beccie, Equip, Griller, Skejs, VireZ   |
|            6 |     3323 | 2024-05-14 | Zero Tenacity     | L   | 0.419      | -            | -                | -                | -         |    -1.92 | AcilioN, Beccie, Equip, Griller, VireZ |
|            5 |     3371 | 2024-05-12 | Johnny Speeds     | W   | 0.406      | 0.333        | 0.102 (0.014)    | 0.956 (0.129)    | 0 (0.000) |    11.67 | Beccie, Equip, Griller, Skejs, VireZ   |
|            4 |     3405 | 2024-05-11 | Passion UA        | L   | 0.399      | -            | -                | -                | -         |    -1.98 | Beccie, Equip, Griller, Skejs, VireZ   |
|            3 |     3683 | 2024-04-27 | 777               | L   | 0.307      | -            | -                | -                | -         |    -5.56 | Beccie, Equip, Griller, Skejs, VireZ   |
|            2 |     3817 | 2024-04-21 | Astralis Talent   | L   | 0.265      | -            | -                | -                | -         |    -4.47 | Beccie, Equip, Griller, Skejs, VireZ   |
|            1 |     3825 | 2024-04-20 | Sashi Academy     | W   | 0.261      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.261) |     1.15 | Beccie, Equip, Griller, Skejs, VireZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,977.76)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      0.868 | $1,250.00      | $1,084.72       |
| 2024-05-16 |      0.432 | $1,500.00      | $647.92         |
| 2024-04-27 |      0.308 | $795.00        | $245.13         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
