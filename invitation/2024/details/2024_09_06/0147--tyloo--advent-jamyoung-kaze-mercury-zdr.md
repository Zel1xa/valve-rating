### Roster Details<br />
Team Name: TYLOO<br />
Roster: advent, JamYoung, kaze, Mercury, zdr<br />
Global Rank: [147](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Asia]( ../../standings_asia_2024_09_06.md)<br />
Regional Rank: [11]( ../../standings_asia_2024_09_06.md)<br />
<br />
Final Rank Value:  711.1<br />
<br />
Final Rank Value (711.1) = Starting Rank Value (701.8) + Head To Head Adjustments (9.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.240[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.033[<sup>2</sup>](#table1)

The average of these factors is 0.154<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.8
- 400 + ( ( 0.154 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 701.8


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
|           13 |     3645 | 2024-04-27 | M80             | L   | 0.319      | -            | -                | -                | -         |    -0.95 | advent, JamYoung, kaze, Mercury, zdr    |
|           12 |     3665 | 2024-04-26 | Sharks          | W   | 0.313      | 0.889        | 0.015 (0.004)    | 0.015 (0.004)    | 1 (0.313) |     5.18 | advent, JamYoung, kaze, Mercury, zdr    |
|           11 |     3703 | 2024-04-25 | Falcons         | L   | 0.305      | -            | -                | -                | -         |    -0.10 | advent, JamYoung, kaze, Mercury, zdr    |
|           10 |     3724 | 2024-04-24 | G2              | L   | 0.298      | -            | -                | -                | -         |    -0.01 | advent, JamYoung, kaze, Mercury, zdr    |
|            9 |     3859 | 2024-04-19 | Rare Atom       | L   | 0.264      | -            | -                | -                | -         |    -2.54 | advent, JamYoung, kaze, Mercury, zdr    |
|            8 |     3899 | 2024-04-18 | The MongolZ     | L   | 0.259      | -            | -                | -                | -         |    -0.02 | advent, JamYoung, kaze, Mercury, zdr    |
|            7 |     3911 | 2024-04-18 | Lynn Vision     | W   | 0.258      | 0.143        | 0.073 (0.003)    | 0.119 (0.004)    | 0 (0.000) |     6.26 | advent, JamYoung, kaze, Mercury, zdr    |
|            6 |     3938 | 2024-04-17 | Sheer Conquer   | W   | 0.251      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     1.79 | advent, JamYoung, kaze, Mercury, zdr    |
|            5 |     3942 | 2024-04-17 | The Huns        | W   | 0.251      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.24 | advent, JamYoung, kaze, Mercury, zdr    |
|            4 |     4196 | 2024-04-08 | Lynn Vision     | L   | 0.192      | -            | -                | -                | -         |    -1.37 | advent, JamYoung, kaze, Mercury, zdr    |
|            3 |     4206 | 2024-04-07 | MOUZ            | L   | 0.190      | -            | -                | -                | -         |    -0.01 | advent, JamYoung, kaze, Mercury, zdr    |
|            2 |     4740 | 2024-03-13 | LYG             | L   | 0.018      | -            | -                | -                | -         |    -0.31 | advent, JamYoung, lyrics3, Mercury, zdr |
|            1 |     4747 | 2024-03-13 | padaem Holodnie | W   | 0.018      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.09 | advent, JamYoung, lyrics3, Mercury, zdr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,859.00)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.419 | $7,000.00      | $2,934.00       |
| 2024-04-14 |      0.231 | $4,000.00      | $925.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
