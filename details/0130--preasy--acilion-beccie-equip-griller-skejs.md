### Roster Details<br />
Team Name: Preasy<br />
Roster: AcilioN, Beccie, Equip, Griller, Skejs<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [91]( ../standings_europe.md)<br />
<br />
Final Rank Value:  777.5<br />
<br />
Final Rank Value (777.5) = Starting Rank Value (790.0) + Head To Head Adjustments (-12.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.307[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.057[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 790.0
- 400 + ( ( 0.191 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 790.0


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
|           23 |      463 | 2024-07-21 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -6.52 | AcilioN, Beccie, Equip, Griller, Skejs |
|           22 |      518 | 2024-07-19 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.66 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           21 |      533 | 2024-07-19 | FORZE Reload      | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.039 (0.013)    | 0 (0.000) |     7.17 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           20 |      574 | 2024-07-18 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.69 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           19 |      649 | 2024-07-17 | kONO              | W   | 1.000      | 0.333        | 0.028 (0.009)    | 0.536 (0.179)    | 0 (0.000) |    17.79 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           18 |      651 | 2024-07-17 | LEON              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.130 (0.019)    | 0 (0.000) |    11.28 | Beccie, Equip, Griller, JBOEN, Skejs   |
|           17 |      775 | 2024-07-14 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -6.47 | AcilioN, Beccie, Equip, Griller, VireZ |
|           16 |      836 | 2024-07-10 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -8.81 | Beccie, Equip, Griller, Skejs, VireZ   |
|           15 |      973 | 2024-06-16 | Aurora Young Blud | L   | 0.876      | -            | -                | -                | -         |   -10.90 | Beccie, Equip, Griller, Skejs, VireZ   |
|           14 |     1008 | 2024-06-15 | LEON              | W   | 0.869      | 0.143        | 0.007 (0.001)    | 0.130 (0.016)    | 0 (0.000) |     9.67 | Beccie, Equip, Griller, Skejs, VireZ   |
|           13 |     1109 | 2024-06-12 | MASONIC           | W   | 0.849      | 0.143        | 0.009 (0.001)    | 0.085 (0.010)    | 0 (0.000) |    12.33 | Beccie, Equip, Griller, Skejs, VireZ   |
|           12 |     1125 | 2024-06-11 | CYBERSHOKE        | L   | 0.844      | -            | -                | -                | -         |    -9.74 | Beccie, Equip, Griller, Skejs, VireZ   |
|           11 |     1221 | 2024-06-09 | Johnny Speeds     | L   | 0.829      | -            | -                | -                | -         |    -2.01 | Equip, Griller, Maze, Skejs, VireZ     |
|           10 |     1672 | 2024-05-28 | Permitta          | L   | 0.750      | -            | -                | -                | -         |    -7.69 | Beccie, Equip, Griller, Skejs, VireZ   |
|            9 |     1711 | 2024-05-26 | Johnny Speeds     | L   | 0.737      | -            | -                | -                | -         |    -1.61 | Beccie, Equip, Griller, Skejs, VireZ   |
|            8 |     1804 | 2024-05-22 | ECLOT             | W   | 0.710      | 0.371        | 0.063 (0.016)    | 0.559 (0.147)    | 0 (0.000) |    20.03 | Beccie, Equip, Griller, Skejs, VireZ   |
|            7 |     2073 | 2024-05-15 | kONO              | L   | 0.662      | -            | -                | -                | -         |    -8.00 | Beccie, Equip, Griller, Skejs, VireZ   |
|            6 |     2120 | 2024-05-14 | Zero Tenacity     | L   | 0.657      | -            | -                | -                | -         |    -3.79 | AcilioN, Beccie, Equip, Griller, VireZ |
|            5 |     2168 | 2024-05-12 | Johnny Speeds     | W   | 0.643      | 0.333        | 0.122 (0.026)    | 0.901 (0.193)    | 0 (0.000) |    19.09 | Beccie, Equip, Griller, Skejs, VireZ   |
|            4 |     2202 | 2024-05-11 | Passion UA        | L   | 0.636      | -            | -                | -                | -         |    -3.98 | Beccie, Equip, Griller, Skejs, VireZ   |
|            3 |     2480 | 2024-04-27 | 777               | L   | 0.544      | -            | -                | -                | -         |   -10.40 | Beccie, Equip, Griller, Skejs, VireZ   |
|            2 |     2613 | 2024-04-21 | Astralis Talent   | L   | 0.502      | -            | -                | -                | -         |    -8.22 | Beccie, Equip, Griller, Skejs, VireZ   |
|            1 |     2621 | 2024-04-20 | Sashi Academy     | W   | 0.499      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.499) |     1.58 | Beccie, Equip, Griller, Skejs, VireZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,888.42)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-09 |      0.831 | $1,445.00      | $1,200.96       |
| 2024-05-16 |      0.669 | $1,500.00      | $1,003.75       |
| 2024-04-27 |      0.546 | $795.00        | $433.72         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
