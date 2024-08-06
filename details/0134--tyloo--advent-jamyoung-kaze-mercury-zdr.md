### Roster Details<br />
Team Name: TYLOO<br />
Roster: advent, JamYoung, kaze, Mercury, zdr<br />
Global Rank: [134](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [10]( ../standings_asia.md)<br />
<br />
Final Rank Value:  773.5<br />
<br />
Final Rank Value (773.5) = Starting Rank Value (762.5) + Head To Head Adjustments (11.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.368[<sup>1</sup>](#table2)
- Bounty Collected: 0.261[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.074[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 762.5
- 400 + ( ( 0.177 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 762.5


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
|           16 |     2543 | 2024-04-27 | M80             | L   | 0.530      | -            | -                | -                | -         |    -1.13 | advent, JamYoung, kaze, Mercury, zdr    |
|           15 |     2563 | 2024-04-26 | Sharks          | W   | 0.525      | 0.889        | 0.020 (0.009)    | 0.032 (0.015)    | 1 (0.525) |     8.20 | advent, JamYoung, kaze, Mercury, zdr    |
|           14 |     2601 | 2024-04-25 | Falcons         | L   | 0.516      | -            | -                | -                | -         |    -0.43 | advent, JamYoung, kaze, Mercury, zdr    |
|           13 |     2622 | 2024-04-24 | G2              | L   | 0.510      | -            | -                | -                | -         |    -0.02 | advent, JamYoung, kaze, Mercury, zdr    |
|           12 |     2757 | 2024-04-19 | Rare Atom       | L   | 0.476      | -            | -                | -                | -         |    -5.41 | advent, JamYoung, kaze, Mercury, zdr    |
|           11 |     2797 | 2024-04-18 | The MongolZ     | L   | 0.470      | -            | -                | -                | -         |    -0.03 | advent, JamYoung, kaze, Mercury, zdr    |
|           10 |     2809 | 2024-04-18 | Lynn Vision     | W   | 0.469      | 0.143        | 0.086 (0.006)    | 0.187 (0.013)    | 0 (0.000) |    12.38 | advent, JamYoung, kaze, Mercury, zdr    |
|            9 |     2836 | 2024-04-17 | Sheer Conquer   | W   | 0.463      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     2.72 | advent, JamYoung, kaze, Mercury, zdr    |
|            8 |     2840 | 2024-04-17 | The Huns        | W   | 0.463      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     1.74 | advent, JamYoung, kaze, Mercury, zdr    |
|            7 |     3094 | 2024-04-08 | Lynn Vision     | L   | 0.403      | -            | -                | -                | -         |    -1.99 | advent, JamYoung, kaze, Mercury, zdr    |
|            6 |     3104 | 2024-04-07 | MOUZ            | L   | 0.401      | -            | -                | -                | -         |    -0.03 | advent, JamYoung, kaze, Mercury, zdr    |
|            5 |     3638 | 2024-03-13 | LYG             | L   | 0.230      | -            | -                | -                | -         |    -4.16 | advent, JamYoung, lyrics3, Mercury, zdr |
|            4 |     3645 | 2024-03-13 | padaem Holodnie | W   | 0.229      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.84 | advent, JamYoung, lyrics3, Mercury, zdr |
|            3 |     3994 | 2024-02-26 | ATOX            | L   | 0.128      | -            | -                | -                | -         |    -1.46 | advent, aumaN, JamYoung, kaze, Mercury  |
|            2 |     4006 | 2024-02-25 | Lynn Vision     | L   | 0.122      | -            | -                | -                | -         |    -0.65 | advent, aumaN, JamYoung, kaze, Mercury  |
|            1 |     4008 | 2024-02-25 | JiJieHao        | W   | 0.121      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 1 (0.121) |     0.46 | advent, aumaN, JamYoung, kaze, Mercury  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,184.54)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.631 | $7,000.00      | $4,413.89       |
| 2024-04-14 |      0.443 | $4,000.00      | $1,770.65       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
