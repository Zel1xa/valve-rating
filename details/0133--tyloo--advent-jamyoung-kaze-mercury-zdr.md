### Roster Details<br />
Team Name: TYLOO<br />
Roster: advent, JamYoung, kaze, Mercury, zdr<br />
Global Rank: [133](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [10]( ../standings_asia.md)<br />
<br />
Final Rank Value:  774.1<br />
<br />
Final Rank Value (774.1) = Starting Rank Value (762.9) + Head To Head Adjustments (11.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.368[<sup>1</sup>](#table2)
- Bounty Collected: 0.261[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.074[<sup>2</sup>](#table1)

The average of these factors is 0.176<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 762.9
- 400 + ( ( 0.176 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 762.9


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
|           16 |     2559 | 2024-04-27 | M80             | L   | 0.527      | -            | -                | -                | -         |    -1.13 | advent, JamYoung, kaze, Mercury, zdr    |
|           15 |     2579 | 2024-04-26 | Sharks          | W   | 0.521      | 0.889        | 0.020 (0.009)    | 0.031 (0.014)    | 1 (0.521) |     8.13 | advent, JamYoung, kaze, Mercury, zdr    |
|           14 |     2617 | 2024-04-25 | Falcons         | L   | 0.513      | -            | -                | -                | -         |    -0.43 | advent, JamYoung, kaze, Mercury, zdr    |
|           13 |     2638 | 2024-04-24 | G2              | L   | 0.506      | -            | -                | -                | -         |    -0.02 | advent, JamYoung, kaze, Mercury, zdr    |
|           12 |     2773 | 2024-04-19 | Rare Atom       | L   | 0.472      | -            | -                | -                | -         |    -5.33 | advent, JamYoung, kaze, Mercury, zdr    |
|           11 |     2813 | 2024-04-18 | The MongolZ     | L   | 0.466      | -            | -                | -                | -         |    -0.03 | advent, JamYoung, kaze, Mercury, zdr    |
|           10 |     2825 | 2024-04-18 | Lynn Vision     | W   | 0.465      | 0.143        | 0.086 (0.006)    | 0.182 (0.012)    | 0 (0.000) |    12.37 | advent, JamYoung, kaze, Mercury, zdr    |
|            9 |     2852 | 2024-04-17 | Sheer Conquer   | W   | 0.459      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     2.69 | advent, JamYoung, kaze, Mercury, zdr    |
|            8 |     2856 | 2024-04-17 | The Huns        | W   | 0.459      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     1.72 | advent, JamYoung, kaze, Mercury, zdr    |
|            7 |     3110 | 2024-04-08 | Lynn Vision     | L   | 0.399      | -            | -                | -                | -         |    -1.90 | advent, JamYoung, kaze, Mercury, zdr    |
|            6 |     3120 | 2024-04-07 | MOUZ            | L   | 0.398      | -            | -                | -                | -         |    -0.03 | advent, JamYoung, kaze, Mercury, zdr    |
|            5 |     3654 | 2024-03-13 | LYG             | L   | 0.226      | -            | -                | -                | -         |    -4.09 | advent, JamYoung, lyrics3, Mercury, zdr |
|            4 |     3661 | 2024-03-13 | padaem Holodnie | W   | 0.225      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.83 | advent, JamYoung, lyrics3, Mercury, zdr |
|            3 |     4010 | 2024-02-26 | ATOX            | L   | 0.124      | -            | -                | -                | -         |    -1.42 | advent, aumaN, JamYoung, kaze, Mercury  |
|            2 |     4022 | 2024-02-25 | Lynn Vision     | L   | 0.118      | -            | -                | -                | -         |    -0.60 | advent, aumaN, JamYoung, kaze, Mercury  |
|            1 |     4024 | 2024-02-25 | JiJieHao        | W   | 0.117      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 1 (0.117) |     0.44 | advent, aumaN, JamYoung, kaze, Mercury  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,143.80)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.627 | $7,000.00      | $4,387.96       |
| 2024-04-14 |      0.439 | $4,000.00      | $1,755.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
