### Roster Details<br />
Team Name: TYLOO<br />
Roster: advent, JamYoung, kaze, Mercury, zdr<br />
Global Rank: [148](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
<br />
Final Rank Value:  706.3<br />
<br />
Final Rank Value (706.3) = Starting Rank Value (697.3) + Head To Head Adjustments (8.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.239[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.031[<sup>2</sup>](#table1)

The average of these factors is 0.154<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 697.3
- 400 + ( ( 0.154 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 697.3


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
|           13 |     3682 | 2024-04-27 | M80             | L   | 0.307      | -            | -                | -                | -         |    -0.96 | advent, JamYoung, kaze, Mercury, zdr    |
|           12 |     3702 | 2024-04-26 | Sharks          | W   | 0.301      | 0.889        | 0.014 (0.004)    | 0.014 (0.004)    | 1 (0.301) |     4.97 | advent, JamYoung, kaze, Mercury, zdr    |
|           11 |     3740 | 2024-04-25 | Falcons         | L   | 0.293      | -            | -                | -                | -         |    -0.10 | advent, JamYoung, kaze, Mercury, zdr    |
|           10 |     3761 | 2024-04-24 | G2              | L   | 0.286      | -            | -                | -                | -         |    -0.01 | advent, JamYoung, kaze, Mercury, zdr    |
|            9 |     3896 | 2024-04-19 | Rare Atom       | L   | 0.252      | -            | -                | -                | -         |    -2.44 | advent, JamYoung, kaze, Mercury, zdr    |
|            8 |     3936 | 2024-04-18 | The MongolZ     | L   | 0.247      | -            | -                | -                | -         |    -0.01 | advent, JamYoung, kaze, Mercury, zdr    |
|            7 |     3948 | 2024-04-18 | Lynn Vision     | W   | 0.246      | 0.143        | 0.073 (0.003)    | 0.114 (0.004)    | 0 (0.000) |     5.92 | advent, JamYoung, kaze, Mercury, zdr    |
|            6 |     3975 | 2024-04-17 | Sheer Conquer   | W   | 0.240      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     1.73 | advent, JamYoung, kaze, Mercury, zdr    |
|            5 |     3979 | 2024-04-17 | The Huns        | W   | 0.239      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.21 | advent, JamYoung, kaze, Mercury, zdr    |
|            4 |     4233 | 2024-04-08 | Lynn Vision     | L   | 0.180      | -            | -                | -                | -         |    -1.32 | advent, JamYoung, kaze, Mercury, zdr    |
|            3 |     4243 | 2024-04-07 | MOUZ            | L   | 0.178      | -            | -                | -                | -         |    -0.01 | advent, JamYoung, kaze, Mercury, zdr    |
|            2 |     4777 | 2024-03-13 | LYG             | L   | 0.006      | -            | -                | -                | -         |    -0.11 | advent, JamYoung, lyrics3, Mercury, zdr |
|            1 |     4784 | 2024-03-13 | padaem Holodnie | W   | 0.006      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.03 | advent, JamYoung, lyrics3, Mercury, zdr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,727.87)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.407 | $7,000.00      | $2,850.56       |
| 2024-04-14 |      0.219 | $4,000.00      | $877.31         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
