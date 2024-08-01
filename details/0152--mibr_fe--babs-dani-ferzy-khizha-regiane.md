### Roster Details<br />
Team Name: MIBR fe<br />
Roster: Babs, Dani, ferzy, khizha, REGIANE<br />
Global Rank: [152](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [42]( ../standings_americas.md)<br />
<br />
Final Rank Value:  713.4<br />
<br />
Final Rank Value (713.4) = Starting Rank Value (695.8) + Head To Head Adjustments (17.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.319[<sup>1</sup>](#table2)
- Bounty Collected: 0.249[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 695.8
- 400 + ( ( 0.144 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 695.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      175 | 2024-07-27 | panelinha | W   | 1.000      | 0.250        | 0.033 (0.008)    | 0.158 (0.039)    | 0 (0.000) |    22.38 | Babs, Dani, ferzy, khizha, REGIANE |
|            9 |      915 | 2024-06-15 | shrekas   | L   | 0.888      | -            | -                | -                | -         |   -15.74 | Babs, Dani, ferzy, khizha, REGIANE |
|            8 |     1643 | 2024-05-26 | Atrix     | W   | 0.754      | 0.250        | 0.003 (0.001)    | 0.061 (0.012)    | 0 (0.000) |    10.36 | Babs, Dani, ferzy, khizha, REGIANE |
|            7 |     2654 | 2024-04-19 | GENKID4M4 | L   | 0.508      | -            | -                | -                | -         |    -9.76 | Babs, Dani, ferzy, khizha, REGIANE |
|            6 |     2878 | 2024-04-11 | W7M fe    | W   | 0.454      | 0.332        | 0.002 (0.000)    | 0.050 (0.008)    | 0 (0.000) |     5.87 | Babs, Dani, ferzy, khizha, REGIANE |
|            5 |     3110 | 2024-04-04 | Atrix     | W   | 0.408      | 0.332        | 0.003 (0.000)    | 0.061 (0.008)    | 0 (0.000) |     5.62 | Babs, Dani, ferzy, khizha, REGIANE |
|            4 |     3256 | 2024-03-28 | KG fe     | W   | 0.361      | 0.332        | 0.002 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     3.21 | Babs, Dani, ferzy, khizha, REGIANE |
|            3 |     3415 | 2024-03-20 | panelinha | L   | 0.308      | -            | -                | -                | -         |    -2.79 | Babs, Dani, ferzy, khizha, REGIANE |
|            2 |     3564 | 2024-03-13 | FURIA fe  | L   | 0.261      | -            | -                | -                | -         |    -4.46 | Babs, Dani, ferzy, khizha, REGIANE |
|            1 |     3716 | 2024-03-07 | Divina fe | W   | 0.221      | 0.332        | 0.002 (0.000)    | 0.022 (0.002)    | 0 (0.000) |     2.87 | Babs, Dani, ferzy, khizha, REGIANE |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,400.87)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $750.00        | $750.00         |
| 2024-06-15 |      0.888 | $250.00        | $222.05         |
| 2024-05-26 |      0.754 | $750.00        | $565.83         |
| 2024-04-19 |      0.508 | $1,700.00      | $862.99         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
