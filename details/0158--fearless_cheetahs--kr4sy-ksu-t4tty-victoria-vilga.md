### Roster Details<br />
Team Name: Fearless Cheetahs<br />
Roster: kr4sy, Ksu, t4tty, Victoria, vilga<br />
Global Rank: [158](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [102]( ../standings_europe.md)<br />
<br />
Final Rank Value:  692.9<br />
<br />
Final Rank Value (692.9) = Starting Rank Value (678.9) + Head To Head Adjustments (14.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.281[<sup>1</sup>](#table2)
- Bounty Collected: 0.259[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.136<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 678.9
- 400 + ( ( 0.136 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 678.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     2639 | 2024-04-21 | Astralis W    | L   | 0.500      | -            | -                | -                | -         |    -8.63 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            9 |     2657 | 2024-04-20 | BIG EQUIPA    | L   | 0.494      | -            | -                | -                | -         |    -6.21 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            8 |     2704 | 2024-04-19 | 1WIN Gang     | W   | 0.487      | 0.331        | 0.001 (0.000)    | 0.017 (0.003)    | 0 (0.000) |     6.68 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            7 |     2922 | 2024-04-11 | Crescent fe   | W   | 0.434      | 0.331        | 0.005 (0.001)    | 0.078 (0.011)    | 0 (0.000) |     5.94 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            6 |     3094 | 2024-04-07 | NIP Impact    | L   | 0.405      | -            | -                | -                | -         |    -6.07 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            5 |     3110 | 2024-04-06 | Let Her Cook  | W   | 0.398      | 0.262        | 0.060 (0.006)    | 0.144 (0.015)    | 0 (0.000) |     9.87 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            4 |     3331 | 2024-03-27 | Spirit fe     | W   | 0.334      | 0.331        | 0.005 (0.001)    | 0.141 (0.016)    | 0 (0.000) |     5.00 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            3 |     3416 | 2024-03-21 | Let Her Cook  | W   | 0.294      | 0.331        | 0.060 (0.006)    | 0.144 (0.014)    | 0 (0.000) |     7.42 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            2 |     3773 | 2024-03-06 | NAVI Javelins | L   | 0.194      | -            | -                | -                | -         |    -1.91 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            1 |     3991 | 2024-02-25 | 1WIN Gang     | W   | 0.127      | 0.250        | 0.001 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     1.89 | kr4sy, Ksu, t4tty, Victoria, vilga |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($895.81)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.500 | $1,600.00      | $800.48         |
| 2024-02-25 |      0.127 | $750.00        | $95.33          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
