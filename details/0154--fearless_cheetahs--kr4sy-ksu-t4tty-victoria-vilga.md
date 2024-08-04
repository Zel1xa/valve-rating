### Roster Details<br />
Team Name: Fearless Cheetahs<br />
Roster: kr4sy, Ksu, t4tty, Victoria, vilga<br />
Global Rank: [154](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [101]( ../standings_europe.md)<br />
<br />
Final Rank Value:  693.3<br />
<br />
Final Rank Value (693.3) = Starting Rank Value (679.2) + Head To Head Adjustments (14.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.281[<sup>1</sup>](#table2)
- Bounty Collected: 0.259[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 679.2
- 400 + ( ( 0.137 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 679.2


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
|           10 |     2602 | 2024-04-21 | Astralis W    | L   | 0.505      | -            | -                | -                | -         |    -8.71 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            9 |     2620 | 2024-04-20 | BIG EQUIPA    | L   | 0.499      | -            | -                | -                | -         |    -6.27 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            8 |     2667 | 2024-04-19 | 1WIN Gang     | W   | 0.492      | 0.331        | 0.001 (0.000)    | 0.017 (0.003)    | 0 (0.000) |     6.73 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            7 |     2885 | 2024-04-11 | Crescent fe   | W   | 0.438      | 0.331        | 0.005 (0.001)    | 0.078 (0.011)    | 0 (0.000) |     6.02 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            6 |     3057 | 2024-04-07 | NIP Impact    | L   | 0.410      | -            | -                | -                | -         |    -6.19 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            5 |     3073 | 2024-04-06 | Let Her Cook  | W   | 0.403      | 0.262        | 0.060 (0.006)    | 0.145 (0.015)    | 0 (0.000) |     9.96 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            4 |     3294 | 2024-03-27 | Spirit fe     | W   | 0.339      | 0.331        | 0.005 (0.001)    | 0.140 (0.016)    | 0 (0.000) |     5.06 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            3 |     3379 | 2024-03-21 | Let Her Cook  | W   | 0.299      | 0.331        | 0.060 (0.006)    | 0.145 (0.014)    | 0 (0.000) |     7.53 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            2 |     3735 | 2024-03-06 | NAVI Javelins | L   | 0.199      | -            | -                | -                | -         |    -1.95 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            1 |     3953 | 2024-02-25 | 1WIN Gang     | W   | 0.132      | 0.250        | 0.001 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     1.96 | kr4sy, Ksu, t4tty, Victoria, vilga |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($907.18)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.505 | $1,600.00      | $808.22         |
| 2024-02-25 |      0.132 | $750.00        | $98.96          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
