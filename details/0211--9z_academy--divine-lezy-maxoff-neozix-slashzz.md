### Roster Details<br />
Team Name: 9z Academy<br />
Roster: divine, lezy, MaxOff, neozix, slashzz<br />
Global Rank: [211](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [56]( ../standings_americas.md)<br />
<br />
Final Rank Value:  509.7<br />
<br />
Final Rank Value (509.7) = Starting Rank Value (507.3) + Head To Head Adjustments (2.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.215[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.055<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 507.3
- 400 + ( ( 0.055 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 507.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |      175 | 2024-09-02 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -1.28 | divine, lezy, MaxOff, neozix, slashzz |
|           15 |      967 | 2024-08-10 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |    -4.16 | divine, lezy, MaxOff, neozix, slashzz |
|           14 |     1018 | 2024-08-08 | SPORT             | W   | 0.995      | 0.333        | 0.004 (0.001)    | 0.086 (0.029)    | 0 (0.000) |    20.51 | divine, lezy, MaxOff, neozix, slashzz |
|           13 |     1055 | 2024-08-07 | BESTIA            | L   | 0.988      | -            | -                | -                | -         |    -2.12 | divine, lezy, MaxOff, neozix, slashzz |
|           12 |     1331 | 2024-07-31 | Hype              | L   | 0.940      | -            | -                | -                | -         |    -3.71 | divine, lezy, MaxOff, neozix, slashzz |
|           11 |     1361 | 2024-07-30 | MIBR              | L   | 0.935      | -            | -                | -                | -         |    -0.29 | divine, lezy, MaxOff, neozix, slashzz |
|           10 |     1646 | 2024-07-21 | Dusty Roots       | L   | 0.875      | -            | -                | -                | -         |    -5.90 | divine, lezy, MaxOff, neozix, slashzz |
|            9 |     1703 | 2024-07-19 | Bounty Hunters    | L   | 0.863      | -            | -                | -                | -         |    -2.74 | divine, lezy, MaxOff, neozix, slashzz |
|            8 |     1753 | 2024-07-18 | SPORT             | W   | 0.856      | 0.371        | 0.004 (0.001)    | 0.086 (0.027)    | 0 (0.000) |    19.72 | divine, lezy, MaxOff, neozix, slashzz |
|            7 |     1929 | 2024-07-15 | Case              | L   | 0.836      | -            | -                | -                | -         |    -2.27 | divine, lezy, MaxOff, neozix, slashzz |
|            6 |     2030 | 2024-07-10 | W7M               | L   | 0.801      | -            | -                | -                | -         |    -4.95 | divine, lezy, MaxOff, neozix, slashzz |
|            5 |     2087 | 2024-07-06 | Patins da Ferrari | L   | 0.775      | -            | -                | -                | -         |    -4.56 | divine, lezy, MaxOff, neozix, slashzz |
|            4 |     2724 | 2024-06-02 | Dusty Roots       | L   | 0.549      | -            | -                | -                | -         |    -3.00 | divine, lezy, MaxOff, neozix, slashzz |
|            3 |     2801 | 2024-05-31 | Yawara            | W   | 0.534      | 0.371        | 0.000 (0.000)    | 0.033 (0.006)    | 0 (0.000) |     8.05 | divine, lezy, MaxOff, neozix, slashzz |
|            2 |     2853 | 2024-05-29 | Corinthians       | L   | 0.520      | -            | -                | -                | -         |    -8.84 | divine, lezy, MaxOff, neozix, slashzz |
|            1 |     2873 | 2024-05-28 | Solid             | L   | 0.514      | -            | -                | -                | -         |    -2.06 | divine, lezy, MaxOff, neozix, slashzz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
