### Roster Details<br />
Team Name: TYLOO<br />
Roster: advent, JamYoung, kaze, Mercury, zdr<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  774.9<br />
<br />
Final Rank Value (774.9) = Starting Rank Value (770.0) + Head To Head Adjustments (4.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.370[<sup>1</sup>](#table2)
- Bounty Collected: 0.263[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.082[<sup>2</sup>](#table1)

The average of these factors is 0.179<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 770.0
- 400 + ( ( 0.179 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 770.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |     2366 | 2024-04-27 | M80             | L   | 0.565      | -            | -                | -                | -         |    -1.10 | advent, JamYoung, kaze, Mercury, zdr    |
|           15 |     2386 | 2024-04-26 | Sharks          | W   | 0.559      | 0.889        | 0.020 (0.010)    | 0.034 (0.017)    | 1 (0.559) |     8.82 | advent, JamYoung, kaze, Mercury, zdr    |
|           14 |     2424 | 2024-04-25 | Falcons         | L   | 0.551      | -            | -                | -                | -         |    -0.38 | advent, JamYoung, kaze, Mercury, zdr    |
|           13 |     2445 | 2024-04-24 | G2              | L   | 0.544      | -            | -                | -                | -         |    -0.02 | advent, JamYoung, kaze, Mercury, zdr    |
|           12 |     2580 | 2024-04-19 | Rare Atom       | L   | 0.510      | -            | -                | -                | -         |   -10.66 | advent, JamYoung, kaze, Mercury, zdr    |
|           11 |     2620 | 2024-04-18 | The MongolZ     | L   | 0.505      | -            | -                | -                | -         |    -0.03 | advent, JamYoung, kaze, Mercury, zdr    |
|           10 |     2632 | 2024-04-18 | Lynn Vision     | W   | 0.504      | 0.143        | 0.079 (0.006)    | 0.158 (0.011)    | 0 (0.000) |    12.58 | advent, JamYoung, kaze, Mercury, zdr    |
|            9 |     2659 | 2024-04-17 | Sheer Conquer   | W   | 0.497      | 0.143        | 0.000 (0.000)    | 0.019 (0.001)    | 0 (0.000) |     2.87 | advent, JamYoung, kaze, Mercury, zdr    |
|            8 |     2663 | 2024-04-17 | The Huns        | W   | 0.497      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     1.82 | advent, JamYoung, kaze, Mercury, zdr    |
|            7 |     2917 | 2024-04-08 | Lynn Vision     | L   | 0.438      | -            | -                | -                | -         |    -2.77 | advent, JamYoung, kaze, Mercury, zdr    |
|            6 |     2927 | 2024-04-07 | MOUZ            | L   | 0.436      | -            | -                | -                | -         |    -0.03 | advent, JamYoung, kaze, Mercury, zdr    |
|            5 |     3461 | 2024-03-13 | LYG             | L   | 0.264      | -            | -                | -                | -         |    -4.82 | advent, JamYoung, lyrics3, Mercury, zdr |
|            4 |     3468 | 2024-03-13 | padaem Holodnie | W   | 0.264      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.93 | advent, JamYoung, lyrics3, Mercury, zdr |
|            3 |     3817 | 2024-02-26 | ATOX            | L   | 0.163      | -            | -                | -                | -         |    -1.83 | advent, aumaN, JamYoung, kaze, Mercury  |
|            2 |     3829 | 2024-02-25 | Lynn Vision     | L   | 0.156      | -            | -                | -                | -         |    -1.09 | advent, aumaN, JamYoung, kaze, Mercury  |
|            1 |     3831 | 2024-02-25 | JiJieHao        | W   | 0.156      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 1 (0.156) |     0.57 | advent, aumaN, JamYoung, kaze, Mercury  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,565.31)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.665 | $7,000.00      | $4,656.20       |
| 2024-04-14 |      0.477 | $4,000.00      | $1,909.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
