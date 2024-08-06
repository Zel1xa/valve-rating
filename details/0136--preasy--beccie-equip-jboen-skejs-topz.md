### Roster Details<br />
Team Name: Preasy<br />
Roster: Beccie, Equip, JBOEN, Skejs, tOPZ<br />
Global Rank: [136](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [93]( ../standings_europe.md)<br />
<br />
Final Rank Value:  768.8<br />
<br />
Final Rank Value (768.8) = Starting Rank Value (782.4) + Head To Head Adjustments (-13.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.324[<sup>1</sup>](#table2)
- Bounty Collected: 0.306[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.186<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 782.4
- 400 + ( ( 0.186 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 782.4


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
|           21 |        7 | 2024-08-05 | Young Ninjas      | L   | 1.000      | -            | -                | -                | -         |   -15.46 | Beccie, Equip, JBOEN, Skejs, tOPZ      |
|           20 |      526 | 2024-07-21 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -6.36 | AcilioN, Beccie, Equip, Griller, Skejs |
|           19 |      581 | 2024-07-19 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.66 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           18 |      596 | 2024-07-19 | FORZE Reload      | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.039 (0.013)    | 0 (0.000) |     6.98 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           17 |      637 | 2024-07-18 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.88 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           16 |      712 | 2024-07-17 | kONO              | W   | 1.000      | 0.333        | 0.028 (0.009)    | 0.566 (0.189)    | 0 (0.000) |    17.48 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           15 |      714 | 2024-07-17 | LEON              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.127 (0.018)    | 0 (0.000) |    11.07 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           14 |      900 | 2024-07-10 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -8.67 | Beccie, Equip, Griller, Skejs, VireZ   |
|           13 |     1037 | 2024-06-16 | Aurora Young Blud | L   | 0.862      | -            | -                | -                | -         |    -9.50 | Beccie, Equip, Griller, Skejs, VireZ   |
|           12 |     1072 | 2024-06-15 | LEON              | W   | 0.856      | 0.143        | 0.007 (0.001)    | 0.127 (0.016)    | 0 (0.000) |     9.60 | Beccie, Equip, Griller, Skejs, VireZ   |
|           11 |     1173 | 2024-06-12 | MASONIC           | W   | 0.836      | 0.143        | 0.009 (0.001)    | 0.083 (0.010)    | 0 (0.000) |    12.12 | Beccie, Equip, Griller, Skejs, VireZ   |
|           10 |     1189 | 2024-06-11 | CYBERSHOKE        | L   | 0.830      | -            | -                | -                | -         |    -9.49 | Beccie, Equip, Griller, Skejs, VireZ   |
|            9 |     1736 | 2024-05-28 | Permitta          | L   | 0.736      | -            | -                | -                | -         |    -7.22 | Beccie, Equip, Griller, Skejs, VireZ   |
|            8 |     1775 | 2024-05-26 | Johnny Speeds     | L   | 0.723      | -            | -                | -                | -         |    -1.48 | Beccie, Equip, Griller, Skejs, VireZ   |
|            7 |     1868 | 2024-05-22 | ECLOT             | W   | 0.696      | 0.371        | 0.062 (0.016)    | 0.549 (0.142)    | 0 (0.000) |    19.72 | Beccie, Equip, Griller, Skejs, VireZ   |
|            6 |     2137 | 2024-05-15 | kONO              | L   | 0.649      | -            | -                | -                | -         |    -7.80 | Beccie, Equip, Griller, Skejs, VireZ   |
|            5 |     2232 | 2024-05-12 | Johnny Speeds     | W   | 0.629      | 0.333        | 0.122 (0.026)    | 1.000 (0.210)    | 0 (0.000) |    18.77 | Beccie, Equip, Griller, Skejs, VireZ   |
|            4 |     2266 | 2024-05-11 | Passion UA        | L   | 0.622      | -            | -                | -                | -         |    -3.53 | Beccie, Equip, Griller, Skejs, VireZ   |
|            3 |     2544 | 2024-04-27 | 777               | L   | 0.530      | -            | -                | -                | -         |   -10.00 | Beccie, Equip, Griller, Skejs, VireZ   |
|            2 |     2678 | 2024-04-21 | Astralis Talent   | L   | 0.489      | -            | -                | -                | -         |    -7.88 | Beccie, Equip, Griller, Skejs, VireZ   |
|            1 |     2686 | 2024-04-20 | Sashi Academy     | W   | 0.485      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.485) |     1.60 | Beccie, Equip, Griller, Skejs, VireZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,655.59)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-05-16 |      0.655 | $1,500.00      | $982.92         |
| 2024-04-27 |      0.532 | $795.00        | $422.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
