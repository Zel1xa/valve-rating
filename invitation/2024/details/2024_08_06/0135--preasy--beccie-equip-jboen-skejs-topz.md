### Roster Details<br />
Team Name: Preasy<br />
Roster: Beccie, Equip, JBOEN, Skejs, tOPZ<br />
Global Rank: [135](../../standings_global_2024_08_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_08_06.md)<br />
Regional Rank: [92]( ../../standings_europe_2024_08_06.md)<br />
<br />
Final Rank Value:  770.5<br />
<br />
Final Rank Value (770.5) = Starting Rank Value (782.6) + Head To Head Adjustments (-12.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.324[<sup>1</sup>](#table2)
- Bounty Collected: 0.306[<sup>2</sup>](#table1)
- Opponent Network: 0.059[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.186<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 782.6
- 400 + ( ( 0.186 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 782.6


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
|           21 |       30 | 2024-08-05 | Young Ninjas      | L   | 1.000      | -            | -                | -                | -         |   -15.55 | Beccie, Equip, JBOEN, Skejs, tOPZ      |
|           20 |      549 | 2024-07-21 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -6.36 | AcilioN, Beccie, Equip, Griller, Skejs |
|           19 |      604 | 2024-07-19 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.64 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           18 |      619 | 2024-07-19 | FORZE Reload      | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.038 (0.013)    | 0 (0.000) |     6.96 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           17 |      660 | 2024-07-18 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.85 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           16 |      735 | 2024-07-17 | kONO              | W   | 1.000      | 0.333        | 0.028 (0.009)    | 0.553 (0.184)    | 0 (0.000) |    17.56 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           15 |      737 | 2024-07-17 | LEON              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.124 (0.018)    | 0 (0.000) |    11.07 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           14 |      923 | 2024-07-10 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -8.60 | Beccie, Equip, Griller, Skejs, VireZ   |
|           13 |     1060 | 2024-06-16 | Aurora Young Blud | L   | 0.858      | -            | -                | -                | -         |    -8.55 | Beccie, Equip, Griller, Skejs, VireZ   |
|           12 |     1095 | 2024-06-15 | LEON              | W   | 0.851      | 0.143        | 0.007 (0.001)    | 0.124 (0.015)    | 0 (0.000) |     9.60 | Beccie, Equip, Griller, Skejs, VireZ   |
|           11 |     1196 | 2024-06-12 | MASONIC           | W   | 0.831      | 0.143        | 0.009 (0.001)    | 0.081 (0.010)    | 0 (0.000) |    12.05 | Beccie, Equip, Griller, Skejs, VireZ   |
|           10 |     1212 | 2024-06-11 | CYBERSHOKE        | L   | 0.825      | -            | -                | -                | -         |    -9.43 | Beccie, Equip, Griller, Skejs, VireZ   |
|            9 |     1759 | 2024-05-28 | Permitta          | L   | 0.732      | -            | -                | -                | -         |    -6.93 | Beccie, Equip, Griller, Skejs, VireZ   |
|            8 |     1798 | 2024-05-26 | Johnny Speeds     | L   | 0.718      | -            | -                | -                | -         |    -1.45 | Beccie, Equip, Griller, Skejs, VireZ   |
|            7 |     1891 | 2024-05-22 | ECLOT             | W   | 0.692      | 0.371        | 0.061 (0.016)    | 0.537 (0.138)    | 0 (0.000) |    19.62 | Beccie, Equip, Griller, Skejs, VireZ   |
|            6 |     2160 | 2024-05-15 | kONO              | L   | 0.644      | -            | -                | -                | -         |    -7.65 | Beccie, Equip, Griller, Skejs, VireZ   |
|            5 |     2255 | 2024-05-12 | Johnny Speeds     | W   | 0.625      | 0.333        | 0.122 (0.025)    | 1.000 (0.208)    | 0 (0.000) |    18.65 | Beccie, Equip, Griller, Skejs, VireZ   |
|            4 |     2289 | 2024-05-11 | Passion UA        | L   | 0.618      | -            | -                | -                | -         |    -3.45 | Beccie, Equip, Griller, Skejs, VireZ   |
|            3 |     2567 | 2024-04-27 | 777               | L   | 0.526      | -            | -                | -                | -         |    -9.91 | Beccie, Equip, Griller, Skejs, VireZ   |
|            2 |     2701 | 2024-04-21 | Astralis Talent   | L   | 0.484      | -            | -                | -                | -         |    -7.81 | Beccie, Equip, Griller, Skejs, VireZ   |
|            1 |     2709 | 2024-04-20 | Sashi Academy     | W   | 0.480      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.480) |     1.58 | Beccie, Equip, Griller, Skejs, VireZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,645.71)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-05-16 |      0.651 | $1,500.00      | $976.46         |
| 2024-04-27 |      0.527 | $795.00        | $419.25         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
