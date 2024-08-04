### Roster Details<br />
Team Name: TYLOO<br />
Roster: advent, JamYoung, kaze, Mercury, zdr<br />
Global Rank: [132](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
<br />
Final Rank Value:  768.8<br />
<br />
Final Rank Value (768.8) = Starting Rank Value (762.6) + Head To Head Adjustments (6.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.369[<sup>1</sup>](#table2)
- Bounty Collected: 0.261[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.077[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 762.6
- 400 + ( ( 0.177 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 762.6


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
|           16 |     2479 | 2024-04-27 | M80             | L   | 0.544      | -            | -                | -                | -         |    -1.12 | advent, JamYoung, kaze, Mercury, zdr    |
|           15 |     2499 | 2024-04-26 | Sharks          | W   | 0.538      | 0.889        | 0.020 (0.009)    | 0.033 (0.016)    | 1 (0.538) |     8.54 | advent, JamYoung, kaze, Mercury, zdr    |
|           14 |     2536 | 2024-04-25 | Falcons         | L   | 0.530      | -            | -                | -                | -         |    -0.42 | advent, JamYoung, kaze, Mercury, zdr    |
|           13 |     2557 | 2024-04-24 | G2              | L   | 0.523      | -            | -                | -                | -         |    -0.02 | advent, JamYoung, kaze, Mercury, zdr    |
|           12 |     2692 | 2024-04-19 | Rare Atom       | L   | 0.490      | -            | -                | -                | -         |    -8.95 | advent, JamYoung, kaze, Mercury, zdr    |
|           11 |     2732 | 2024-04-18 | The MongolZ     | L   | 0.484      | -            | -                | -                | -         |    -0.03 | advent, JamYoung, kaze, Mercury, zdr    |
|           10 |     2744 | 2024-04-18 | Lynn Vision     | W   | 0.483      | 0.143        | 0.078 (0.005)    | 0.153 (0.011)    | 0 (0.000) |    11.95 | advent, JamYoung, kaze, Mercury, zdr    |
|            9 |     2771 | 2024-04-17 | Sheer Conquer   | W   | 0.477      | 0.143        | 0.000 (0.000)    | 0.019 (0.001)    | 0 (0.000) |     2.82 | advent, JamYoung, kaze, Mercury, zdr    |
|            8 |     2775 | 2024-04-17 | The Huns        | W   | 0.476      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     1.80 | advent, JamYoung, kaze, Mercury, zdr    |
|            7 |     3029 | 2024-04-08 | Lynn Vision     | L   | 0.417      | -            | -                | -                | -         |    -2.75 | advent, JamYoung, kaze, Mercury, zdr    |
|            6 |     3039 | 2024-04-07 | MOUZ            | L   | 0.415      | -            | -                | -                | -         |    -0.03 | advent, JamYoung, kaze, Mercury, zdr    |
|            5 |     3572 | 2024-03-13 | LYG             | L   | 0.243      | -            | -                | -                | -         |    -4.41 | advent, JamYoung, lyrics3, Mercury, zdr |
|            4 |     3579 | 2024-03-13 | padaem Holodnie | W   | 0.243      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.89 | advent, JamYoung, lyrics3, Mercury, zdr |
|            3 |     3928 | 2024-02-26 | ATOX            | L   | 0.142      | -            | -                | -                | -         |    -1.61 | advent, aumaN, JamYoung, kaze, Mercury  |
|            2 |     3940 | 2024-02-25 | Lynn Vision     | L   | 0.136      | -            | -                | -                | -         |    -0.98 | advent, aumaN, JamYoung, kaze, Mercury  |
|            1 |     3942 | 2024-02-25 | JiJieHao        | W   | 0.135      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 1 (0.135) |     0.51 | advent, aumaN, JamYoung, kaze, Mercury  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,337.31)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.644 | $7,000.00      | $4,511.11       |
| 2024-04-14 |      0.457 | $4,000.00      | $1,826.20       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
