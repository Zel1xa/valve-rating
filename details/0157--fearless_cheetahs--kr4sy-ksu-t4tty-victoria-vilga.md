### Roster Details<br />
Team Name: Fearless Cheetahs<br />
Roster: kr4sy, Ksu, t4tty, Victoria, vilga<br />
Global Rank: [157](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [101]( ../standings_europe.md)<br />
<br />
Final Rank Value:  692.9<br />
<br />
Final Rank Value (692.9) = Starting Rank Value (679.4) + Head To Head Adjustments (13.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.280[<sup>1</sup>](#table2)
- Bounty Collected: 0.258[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.136<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 679.4
- 400 + ( ( 0.136 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 679.4


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
|           10 |     2675 | 2024-04-21 | Astralis W    | L   | 0.488      | -            | -                | -                | -         |    -8.41 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            9 |     2693 | 2024-04-20 | BIG EQUIPA    | L   | 0.482      | -            | -                | -                | -         |    -6.05 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            8 |     2740 | 2024-04-19 | 1WIN Gang     | W   | 0.475      | 0.331        | 0.001 (0.000)    | 0.016 (0.003)    | 0 (0.000) |     6.55 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            7 |     2958 | 2024-04-11 | Crescent fe   | W   | 0.422      | 0.331        | 0.004 (0.001)    | 0.074 (0.010)    | 0 (0.000) |     5.81 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            6 |     3130 | 2024-04-07 | NIP Impact    | L   | 0.393      | -            | -                | -                | -         |    -5.88 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            5 |     3146 | 2024-04-06 | Let Her Cook  | W   | 0.387      | 0.262        | 0.060 (0.006)    | 0.137 (0.014)    | 0 (0.000) |     9.59 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            4 |     3367 | 2024-03-27 | Spirit fe     | W   | 0.322      | 0.331        | 0.005 (0.001)    | 0.136 (0.014)    | 0 (0.000) |     4.83 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            3 |     3452 | 2024-03-21 | Let Her Cook  | W   | 0.282      | 0.331        | 0.060 (0.006)    | 0.137 (0.013)    | 0 (0.000) |     7.13 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            2 |     3809 | 2024-03-06 | NAVI Javelins | L   | 0.182      | -            | -                | -                | -         |    -1.79 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            1 |     4027 | 2024-02-25 | 1WIN Gang     | W   | 0.115      | 0.250        | 0.001 (0.000)    | 0.016 (0.000)    | 0 (0.000) |     1.72 | kr4sy, Ksu, t4tty, Victoria, vilga |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($868.01)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.488 | $1,600.00      | $781.56         |
| 2024-02-25 |      0.115 | $750.00        | $86.46          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />