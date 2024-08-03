### Roster Details<br />
Team Name: Preasy<br />
Roster: AcilioN, Beccie, Equip, Griller, Skejs<br />
Global Rank: [128](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [89]( ../standings_europe.md)<br />
<br />
Final Rank Value:  779.1<br />
<br />
Final Rank Value (779.1) = Starting Rank Value (791.7) + Head To Head Adjustments (-12.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.307[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.057[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 791.7
- 400 + ( ( 0.191 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 791.7


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
|           23 |      440 | 2024-07-21 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -6.50 | AcilioN, Beccie, Equip, Griller, Skejs |
|           22 |      494 | 2024-07-19 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.70 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           21 |      510 | 2024-07-19 | FORZE Reload      | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.040 (0.013)    | 0 (0.000) |     7.13 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           20 |      551 | 2024-07-18 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.71 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           19 |      625 | 2024-07-17 | kONO              | W   | 1.000      | 0.333        | 0.028 (0.009)    | 0.555 (0.185)    | 0 (0.000) |    17.66 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           18 |      627 | 2024-07-17 | LEON              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.135 (0.019)    | 0 (0.000) |    11.50 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           17 |      747 | 2024-07-14 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -6.49 | AcilioN, Beccie, Equip, Griller, VireZ |
|           16 |      806 | 2024-07-10 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -8.80 | Beccie, Equip, Griller, Skejs, VireZ   |
|           15 |      936 | 2024-06-16 | Aurora Young Blud | L   | 0.878      | -            | -                | -                | -         |   -10.90 | Beccie, Equip, Griller, Skejs, VireZ   |
|           14 |      965 | 2024-06-15 | LEON              | W   | 0.871      | 0.143        | 0.007 (0.001)    | 0.135 (0.017)    | 0 (0.000) |     9.90 | Beccie, Equip, Griller, Skejs, VireZ   |
|           13 |     1057 | 2024-06-12 | MASONIC           | W   | 0.851      | 0.143        | 0.009 (0.001)    | 0.088 (0.011)    | 0 (0.000) |    12.29 | Beccie, Equip, Griller, Skejs, VireZ   |
|           12 |     1071 | 2024-06-11 | CYBERSHOKE        | L   | 0.845      | -            | -                | -                | -         |    -9.59 | Beccie, Equip, Griller, Skejs, VireZ   |
|           11 |     1166 | 2024-06-09 | Johnny Speeds     | L   | 0.831      | -            | -                | -                | -         |    -2.01 | Equip, Griller, Maze, Skejs, VireZ     |
|           10 |     1609 | 2024-05-28 | Permitta          | L   | 0.752      | -            | -                | -                | -         |    -7.71 | Beccie, Equip, Griller, Skejs, VireZ   |
|            9 |     1647 | 2024-05-26 | Johnny Speeds     | L   | 0.738      | -            | -                | -                | -         |    -1.61 | Beccie, Equip, Griller, Skejs, VireZ   |
|            8 |     1740 | 2024-05-22 | ECLOT             | W   | 0.712      | 0.371        | 0.063 (0.017)    | 0.578 (0.152)    | 0 (0.000) |    20.09 | Beccie, Equip, Griller, Skejs, VireZ   |
|            7 |     2008 | 2024-05-15 | kONO              | L   | 0.664      | -            | -                | -                | -         |    -8.04 | Beccie, Equip, Griller, Skejs, VireZ   |
|            6 |     2055 | 2024-05-14 | Zero Tenacity     | L   | 0.658      | -            | -                | -                | -         |    -3.86 | AcilioN, Beccie, Equip, Griller, VireZ |
|            5 |     2103 | 2024-05-12 | Johnny Speeds     | W   | 0.644      | 0.333        | 0.122 (0.026)    | 0.930 (0.200)    | 0 (0.000) |    19.14 | Beccie, Equip, Griller, Skejs, VireZ   |
|            4 |     2137 | 2024-05-11 | Passion UA        | L   | 0.638      | -            | -                | -                | -         |    -4.00 | Beccie, Equip, Griller, Skejs, VireZ   |
|            3 |     2414 | 2024-04-27 | 777               | L   | 0.546      | -            | -                | -                | -         |   -10.58 | Beccie, Equip, Griller, Skejs, VireZ   |
|            2 |     2547 | 2024-04-21 | Astralis Talent   | L   | 0.504      | -            | -                | -                | -         |    -8.36 | Beccie, Equip, Griller, Skejs, VireZ   |
|            1 |     2555 | 2024-04-20 | Sashi Academy     | W   | 0.500      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.500) |     1.57 | Beccie, Equip, Griller, Skejs, VireZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,894.83)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-09 |      0.833 | $1,445.00      | $1,203.43       |
| 2024-05-16 |      0.671 | $1,500.00      | $1,006.32       |
| 2024-04-27 |      0.547 | $795.00        | $435.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
