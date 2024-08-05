### Roster Details<br />
Team Name: Preasy<br />
Roster: AcilioN, Beccie, Equip, Griller, Skejs<br />
Global Rank: [129](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [90]( ../standings_europe.md)<br />
<br />
Final Rank Value:  780.1<br />
<br />
Final Rank Value (780.1) = Starting Rank Value (794.7) + Head To Head Adjustments (-14.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.308[<sup>2</sup>](#table1)
- Opponent Network: 0.055[<sup>2</sup>](#table1)
- LAN Wins: 0.060[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 794.7
- 400 + ( ( 0.191 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 794.7


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
|           23 |      349 | 2024-07-21 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -6.61 | AcilioN, Beccie, Equip, Griller, Skejs |
|           22 |      404 | 2024-07-19 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.61 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           21 |      419 | 2024-07-19 | FORZE Reload      | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.038 (0.013)    | 0 (0.000) |     7.13 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           20 |      460 | 2024-07-18 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -21.57 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           19 |      535 | 2024-07-17 | kONO              | W   | 1.000      | 0.333        | 0.029 (0.010)    | 0.537 (0.179)    | 0 (0.000) |    17.86 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           18 |      537 | 2024-07-17 | LEON              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.131 (0.019)    | 0 (0.000) |    11.27 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           17 |      661 | 2024-07-14 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -6.47 | AcilioN, Beccie, Equip, Griller, VireZ |
|           16 |      723 | 2024-07-10 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -8.70 | Beccie, Equip, Griller, Skejs, VireZ   |
|           15 |      860 | 2024-06-16 | Aurora Young Blud | L   | 0.897      | -            | -                | -                | -         |   -11.12 | Beccie, Equip, Griller, Skejs, VireZ   |
|           14 |      895 | 2024-06-15 | LEON              | W   | 0.890      | 0.143        | 0.007 (0.001)    | 0.131 (0.017)    | 0 (0.000) |     9.89 | Beccie, Equip, Griller, Skejs, VireZ   |
|           13 |      996 | 2024-06-12 | MASONIC           | W   | 0.870      | 0.143        | 0.009 (0.001)    | 0.087 (0.011)    | 0 (0.000) |    12.80 | Beccie, Equip, Griller, Skejs, VireZ   |
|           12 |     1012 | 2024-06-11 | CYBERSHOKE        | L   | 0.864      | -            | -                | -                | -         |    -9.90 | Beccie, Equip, Griller, Skejs, VireZ   |
|           11 |     1108 | 2024-06-09 | Johnny Speeds     | L   | 0.850      | -            | -                | -                | -         |    -2.02 | Equip, Griller, Maze, Skejs, VireZ     |
|           10 |     1559 | 2024-05-28 | Permitta          | L   | 0.771      | -            | -                | -                | -         |    -8.16 | Beccie, Equip, Griller, Skejs, VireZ   |
|            9 |     1598 | 2024-05-26 | Johnny Speeds     | L   | 0.757      | -            | -                | -                | -         |    -1.62 | Beccie, Equip, Griller, Skejs, VireZ   |
|            8 |     1691 | 2024-05-22 | ECLOT             | W   | 0.731      | 0.371        | 0.064 (0.017)    | 0.502 (0.136)    | 0 (0.000) |    19.45 | Beccie, Equip, Griller, Skejs, VireZ   |
|            7 |     1960 | 2024-05-15 | kONO              | L   | 0.683      | -            | -                | -                | -         |    -8.17 | Beccie, Equip, Griller, Skejs, VireZ   |
|            6 |     2007 | 2024-05-14 | Zero Tenacity     | L   | 0.677      | -            | -                | -                | -         |    -3.95 | AcilioN, Beccie, Equip, Griller, VireZ |
|            5 |     2055 | 2024-05-12 | Johnny Speeds     | W   | 0.664      | 0.333        | 0.123 (0.027)    | 0.817 (0.181)    | 0 (0.000) |    19.74 | Beccie, Equip, Griller, Skejs, VireZ   |
|            4 |     2089 | 2024-05-11 | Passion UA        | L   | 0.657      | -            | -                | -                | -         |    -4.07 | Beccie, Equip, Griller, Skejs, VireZ   |
|            3 |     2367 | 2024-04-27 | 777               | L   | 0.565      | -            | -                | -                | -         |   -10.80 | Beccie, Equip, Griller, Skejs, VireZ   |
|            2 |     2501 | 2024-04-21 | Astralis Talent   | L   | 0.523      | -            | -                | -                | -         |    -8.51 | Beccie, Equip, Griller, Skejs, VireZ   |
|            1 |     2509 | 2024-04-20 | Sashi Academy     | W   | 0.519      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.519) |     1.61 | Beccie, Equip, Griller, Skejs, VireZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,965.94)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-09 |      0.852 | $1,445.00      | $1,230.91       |
| 2024-05-16 |      0.690 | $1,500.00      | $1,034.84       |
| 2024-04-27 |      0.566 | $795.00        | $450.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
