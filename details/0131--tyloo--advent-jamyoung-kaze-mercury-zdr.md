### Roster Details<br />
Team Name: TYLOO<br />
Roster: advent, JamYoung, kaze, Mercury, zdr<br />
Global Rank: [131](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
<br />
Final Rank Value:  774.3<br />
<br />
Final Rank Value (774.3) = Starting Rank Value (769.1) + Head To Head Adjustments (5.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.370[<sup>1</sup>](#table2)
- Bounty Collected: 0.263[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.081[<sup>2</sup>](#table1)

The average of these factors is 0.179<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 769.1
- 400 + ( ( 0.179 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 769.1


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
|           16 |     2466 | 2024-04-27 | M80             | L   | 0.559      | -            | -                | -                | -         |    -1.09 | advent, JamYoung, kaze, Mercury, zdr    |
|           15 |     2487 | 2024-04-26 | Sharks          | W   | 0.553      | 0.889        | 0.020 (0.010)    | 0.054 (0.026)    | 1 (0.553) |     9.06 | advent, JamYoung, kaze, Mercury, zdr    |
|           14 |     2524 | 2024-04-25 | Falcons         | L   | 0.545      | -            | -                | -                | -         |    -0.40 | advent, JamYoung, kaze, Mercury, zdr    |
|           13 |     2545 | 2024-04-24 | G2              | L   | 0.538      | -            | -                | -                | -         |    -0.02 | advent, JamYoung, kaze, Mercury, zdr    |
|           12 |     2687 | 2024-04-19 | Rare Atom       | L   | 0.504      | -            | -                | -                | -         |   -10.49 | advent, JamYoung, kaze, Mercury, zdr    |
|           11 |     2728 | 2024-04-18 | The MongolZ     | L   | 0.499      | -            | -                | -                | -         |    -0.03 | advent, JamYoung, kaze, Mercury, zdr    |
|           10 |     2740 | 2024-04-18 | Lynn Vision     | W   | 0.498      | 0.143        | 0.080 (0.006)    | 0.156 (0.011)    | 0 (0.000) |    12.39 | advent, JamYoung, kaze, Mercury, zdr    |
|            9 |     2768 | 2024-04-17 | Sheer Conquer   | W   | 0.491      | 0.143        | 0.000 (0.000)    | 0.019 (0.001)    | 0 (0.000) |     2.84 | advent, JamYoung, kaze, Mercury, zdr    |
|            8 |     2772 | 2024-04-17 | The Huns        | W   | 0.491      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     1.80 | advent, JamYoung, kaze, Mercury, zdr    |
|            7 |     3028 | 2024-04-08 | Lynn Vision     | L   | 0.432      | -            | -                | -                | -         |    -2.77 | advent, JamYoung, kaze, Mercury, zdr    |
|            6 |     3038 | 2024-04-07 | MOUZ            | L   | 0.430      | -            | -                | -                | -         |    -0.03 | advent, JamYoung, kaze, Mercury, zdr    |
|            5 |     3589 | 2024-03-13 | LYG             | L   | 0.258      | -            | -                | -                | -         |    -4.71 | advent, JamYoung, lyrics3, Mercury, zdr |
|            4 |     3596 | 2024-03-13 | padaem Holodnie | W   | 0.258      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.92 | advent, JamYoung, lyrics3, Mercury, zdr |
|            3 |     3954 | 2024-02-26 | ATOX            | L   | 0.157      | -            | -                | -                | -         |    -1.77 | advent, aumaN, JamYoung, kaze, Mercury  |
|            2 |     3967 | 2024-02-25 | Lynn Vision     | L   | 0.150      | -            | -                | -                | -         |    -1.06 | advent, aumaN, JamYoung, kaze, Mercury  |
|            1 |     3969 | 2024-02-25 | JiJieHao        | W   | 0.150      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 1 (0.150) |     0.56 | advent, aumaN, JamYoung, kaze, Mercury  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,499.26)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.659 | $7,000.00      | $4,614.17       |
| 2024-04-14 |      0.471 | $4,000.00      | $1,885.09       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
