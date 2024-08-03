### Roster Details<br />
Team Name: TYLOO<br />
Roster: advent, JamYoung, kaze, Mercury, zdr<br />
Global Rank: [132](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
<br />
Final Rank Value:  769.4<br />
<br />
Final Rank Value (769.4) = Starting Rank Value (763.4) + Head To Head Adjustments (6.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.369[<sup>1</sup>](#table2)
- Bounty Collected: 0.261[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.077[<sup>2</sup>](#table1)

The average of these factors is 0.178<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 763.4
- 400 + ( ( 0.178 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 763.4


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
|           16 |     2413 | 2024-04-27 | M80             | L   | 0.546      | -            | -                | -                | -         |    -1.11 | advent, JamYoung, kaze, Mercury, zdr    |
|           15 |     2433 | 2024-04-26 | Sharks          | W   | 0.540      | 0.889        | 0.020 (0.009)    | 0.034 (0.016)    | 1 (0.540) |     8.53 | advent, JamYoung, kaze, Mercury, zdr    |
|           14 |     2470 | 2024-04-25 | Falcons         | L   | 0.532      | -            | -                | -                | -         |    -0.41 | advent, JamYoung, kaze, Mercury, zdr    |
|           13 |     2491 | 2024-04-24 | G2              | L   | 0.525      | -            | -                | -                | -         |    -0.02 | advent, JamYoung, kaze, Mercury, zdr    |
|           12 |     2626 | 2024-04-19 | Rare Atom       | L   | 0.491      | -            | -                | -                | -         |    -9.03 | advent, JamYoung, kaze, Mercury, zdr    |
|           11 |     2666 | 2024-04-18 | The MongolZ     | L   | 0.486      | -            | -                | -                | -         |    -0.03 | advent, JamYoung, kaze, Mercury, zdr    |
|           10 |     2678 | 2024-04-18 | Lynn Vision     | W   | 0.485      | 0.143        | 0.078 (0.005)    | 0.159 (0.011)    | 0 (0.000) |    11.97 | advent, JamYoung, kaze, Mercury, zdr    |
|            9 |     2705 | 2024-04-17 | Sheer Conquer   | W   | 0.478      | 0.143        | 0.000 (0.000)    | 0.019 (0.001)    | 0 (0.000) |     2.82 | advent, JamYoung, kaze, Mercury, zdr    |
|            8 |     2709 | 2024-04-17 | The Huns        | W   | 0.478      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     1.80 | advent, JamYoung, kaze, Mercury, zdr    |
|            7 |     2963 | 2024-04-08 | Lynn Vision     | L   | 0.419      | -            | -                | -                | -         |    -2.77 | advent, JamYoung, kaze, Mercury, zdr    |
|            6 |     2973 | 2024-04-07 | MOUZ            | L   | 0.417      | -            | -                | -                | -         |    -0.04 | advent, JamYoung, kaze, Mercury, zdr    |
|            5 |     3500 | 2024-03-13 | LYG             | L   | 0.245      | -            | -                | -                | -         |    -4.45 | advent, JamYoung, lyrics3, Mercury, zdr |
|            4 |     3507 | 2024-03-13 | padaem Holodnie | W   | 0.245      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.90 | advent, JamYoung, lyrics3, Mercury, zdr |
|            3 |     3855 | 2024-02-26 | ATOX            | L   | 0.144      | -            | -                | -                | -         |    -1.64 | advent, aumaN, JamYoung, kaze, Mercury  |
|            2 |     3867 | 2024-02-25 | Lynn Vision     | L   | 0.137      | -            | -                | -                | -         |    -1.00 | advent, aumaN, JamYoung, kaze, Mercury  |
|            1 |     3869 | 2024-02-25 | JiJieHao        | W   | 0.137      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 1 (0.137) |     0.52 | advent, aumaN, JamYoung, kaze, Mercury  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,356.16)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.646 | $7,000.00      | $4,523.10       |
| 2024-04-14 |      0.458 | $4,000.00      | $1,833.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
