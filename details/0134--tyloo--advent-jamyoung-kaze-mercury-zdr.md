### Roster Details<br />
Team Name: TYLOO<br />
Roster: advent, JamYoung, kaze, Mercury, zdr<br />
Global Rank: [134](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [10]( ../standings_asia.md)<br />
<br />
Final Rank Value:  769.9<br />
<br />
Final Rank Value (769.9) = Starting Rank Value (762.0) + Head To Head Adjustments (7.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.369[<sup>1</sup>](#table2)
- Bounty Collected: 0.261[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.076[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 762.0
- 400 + ( ( 0.177 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 762.0


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
|           16 |     2519 | 2024-04-27 | M80             | L   | 0.537      | -            | -                | -                | -         |    -1.11 | advent, JamYoung, kaze, Mercury, zdr    |
|           15 |     2539 | 2024-04-26 | Sharks          | W   | 0.531      | 0.889        | 0.020 (0.009)    | 0.033 (0.015)    | 1 (0.531) |     8.39 | advent, JamYoung, kaze, Mercury, zdr    |
|           14 |     2577 | 2024-04-25 | Falcons         | L   | 0.523      | -            | -                | -                | -         |    -0.42 | advent, JamYoung, kaze, Mercury, zdr    |
|           13 |     2598 | 2024-04-24 | G2              | L   | 0.516      | -            | -                | -                | -         |    -0.02 | advent, JamYoung, kaze, Mercury, zdr    |
|           12 |     2733 | 2024-04-19 | Rare Atom       | L   | 0.482      | -            | -                | -                | -         |    -8.80 | advent, JamYoung, kaze, Mercury, zdr    |
|           11 |     2773 | 2024-04-18 | The MongolZ     | L   | 0.477      | -            | -                | -                | -         |    -0.03 | advent, JamYoung, kaze, Mercury, zdr    |
|           10 |     2785 | 2024-04-18 | Lynn Vision     | W   | 0.476      | 0.143        | 0.078 (0.005)    | 0.191 (0.013)    | 0 (0.000) |    12.53 | advent, JamYoung, kaze, Mercury, zdr    |
|            9 |     2812 | 2024-04-17 | Sheer Conquer   | W   | 0.470      | 0.143        | 0.000 (0.000)    | 0.019 (0.001)    | 0 (0.000) |     2.77 | advent, JamYoung, kaze, Mercury, zdr    |
|            8 |     2816 | 2024-04-17 | The Huns        | W   | 0.469      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     1.77 | advent, JamYoung, kaze, Mercury, zdr    |
|            7 |     3070 | 2024-04-08 | Lynn Vision     | L   | 0.410      | -            | -                | -                | -         |    -2.05 | advent, JamYoung, kaze, Mercury, zdr    |
|            6 |     3080 | 2024-04-07 | MOUZ            | L   | 0.408      | -            | -                | -                | -         |    -0.03 | advent, JamYoung, kaze, Mercury, zdr    |
|            5 |     3614 | 2024-03-13 | LYG             | L   | 0.236      | -            | -                | -                | -         |    -4.28 | advent, JamYoung, lyrics3, Mercury, zdr |
|            4 |     3621 | 2024-03-13 | padaem Holodnie | W   | 0.236      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.87 | advent, JamYoung, lyrics3, Mercury, zdr |
|            3 |     3970 | 2024-02-26 | ATOX            | L   | 0.135      | -            | -                | -                | -         |    -1.53 | advent, aumaN, JamYoung, kaze, Mercury  |
|            2 |     3982 | 2024-02-25 | Lynn Vision     | L   | 0.128      | -            | -                | -                | -         |    -0.69 | advent, aumaN, JamYoung, kaze, Mercury  |
|            1 |     3984 | 2024-02-25 | JiJieHao        | W   | 0.128      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 1 (0.128) |     0.49 | advent, aumaN, JamYoung, kaze, Mercury  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,257.87)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.637 | $7,000.00      | $4,460.56       |
| 2024-04-14 |      0.449 | $4,000.00      | $1,797.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
