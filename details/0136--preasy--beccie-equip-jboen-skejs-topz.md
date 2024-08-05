### Roster Details<br />
Team Name: Preasy<br />
Roster: Beccie, Equip, JBOEN, Skejs, tOPZ<br />
Global Rank: [136](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [93]( ../standings_europe.md)<br />
<br />
Final Rank Value:  768.9<br />
<br />
Final Rank Value (768.9) = Starting Rank Value (782.5) + Head To Head Adjustments (-13.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.324[<sup>1</sup>](#table2)
- Bounty Collected: 0.306[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.187<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 782.5
- 400 + ( ( 0.187 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 782.5


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
|           21 |        5 | 2024-08-05 | Young Ninjas      | L   | 1.000      | -            | -                | -                | -         |   -15.44 | Beccie, Equip, JBOEN, Skejs, tOPZ      |
|           20 |      524 | 2024-07-21 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -6.36 | AcilioN, Beccie, Equip, Griller, Skejs |
|           19 |      579 | 2024-07-19 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.67 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           18 |      594 | 2024-07-19 | FORZE Reload      | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.039 (0.013)    | 0 (0.000) |     6.98 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           17 |      635 | 2024-07-18 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.89 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           16 |      710 | 2024-07-17 | kONO              | W   | 1.000      | 0.333        | 0.028 (0.009)    | 0.566 (0.189)    | 0 (0.000) |    17.49 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           15 |      712 | 2024-07-17 | LEON              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.127 (0.018)    | 0 (0.000) |    11.06 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           14 |      898 | 2024-07-10 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -8.66 | Beccie, Equip, Griller, Skejs, VireZ   |
|           13 |     1035 | 2024-06-16 | Aurora Young Blud | L   | 0.864      | -            | -                | -                | -         |    -9.52 | Beccie, Equip, Griller, Skejs, VireZ   |
|           12 |     1070 | 2024-06-15 | LEON              | W   | 0.857      | 0.143        | 0.007 (0.001)    | 0.127 (0.016)    | 0 (0.000) |     9.62 | Beccie, Equip, Griller, Skejs, VireZ   |
|           11 |     1171 | 2024-06-12 | MASONIC           | W   | 0.837      | 0.143        | 0.009 (0.001)    | 0.083 (0.010)    | 0 (0.000) |    12.15 | Beccie, Equip, Griller, Skejs, VireZ   |
|           10 |     1187 | 2024-06-11 | CYBERSHOKE        | L   | 0.832      | -            | -                | -                | -         |    -9.51 | Beccie, Equip, Griller, Skejs, VireZ   |
|            9 |     1734 | 2024-05-28 | Permitta          | L   | 0.738      | -            | -                | -                | -         |    -7.24 | Beccie, Equip, Griller, Skejs, VireZ   |
|            8 |     1773 | 2024-05-26 | Johnny Speeds     | L   | 0.725      | -            | -                | -                | -         |    -1.49 | Beccie, Equip, Griller, Skejs, VireZ   |
|            7 |     1866 | 2024-05-22 | ECLOT             | W   | 0.698      | 0.371        | 0.062 (0.016)    | 0.550 (0.142)    | 0 (0.000) |    19.77 | Beccie, Equip, Griller, Skejs, VireZ   |
|            6 |     2135 | 2024-05-15 | kONO              | L   | 0.650      | -            | -                | -                | -         |    -7.82 | Beccie, Equip, Griller, Skejs, VireZ   |
|            5 |     2230 | 2024-05-12 | Johnny Speeds     | W   | 0.631      | 0.333        | 0.122 (0.026)    | 1.000 (0.210)    | 0 (0.000) |    18.82 | Beccie, Equip, Griller, Skejs, VireZ   |
|            4 |     2264 | 2024-05-11 | Passion UA        | L   | 0.624      | -            | -                | -                | -         |    -3.54 | Beccie, Equip, Griller, Skejs, VireZ   |
|            3 |     2542 | 2024-04-27 | 777               | L   | 0.532      | -            | -                | -                | -         |   -10.03 | Beccie, Equip, Griller, Skejs, VireZ   |
|            2 |     2676 | 2024-04-21 | Astralis Talent   | L   | 0.490      | -            | -                | -                | -         |    -7.91 | Beccie, Equip, Griller, Skejs, VireZ   |
|            1 |     2684 | 2024-04-20 | Sashi Academy     | W   | 0.487      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.487) |     1.60 | Beccie, Equip, Griller, Skejs, VireZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,659.74)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-05-16 |      0.657 | $1,500.00      | $985.63         |
| 2024-04-27 |      0.533 | $795.00        | $424.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
