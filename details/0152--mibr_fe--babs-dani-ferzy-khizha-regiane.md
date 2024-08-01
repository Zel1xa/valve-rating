### Roster Details<br />
Team Name: MIBR fe<br />
Roster: Babs, Dani, ferzy, khizha, REGIANE<br />
Global Rank: [152](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [42]( ../standings_americas.md)<br />
<br />
Final Rank Value:  713.8<br />
<br />
Final Rank Value (713.8) = Starting Rank Value (696.2) + Head To Head Adjustments (17.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.319[<sup>1</sup>](#table2)
- Bounty Collected: 0.249[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 696.2
- 400 + ( ( 0.144 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 696.2


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
|           10 |      171 | 2024-07-27 | panelinha | W   | 1.000      | 0.250        | 0.033 (0.008)    | 0.158 (0.040)    | 0 (0.000) |    22.39 | Babs, Dani, ferzy, khizha, REGIANE |
|            9 |      911 | 2024-06-15 | shrekas   | L   | 0.890      | -            | -                | -                | -         |   -15.76 | Babs, Dani, ferzy, khizha, REGIANE |
|            8 |     1639 | 2024-05-26 | Atrix     | W   | 0.756      | 0.250        | 0.003 (0.001)    | 0.061 (0.012)    | 0 (0.000) |    10.38 | Babs, Dani, ferzy, khizha, REGIANE |
|            7 |     2650 | 2024-04-19 | GENKID4M4 | L   | 0.509      | -            | -                | -                | -         |    -9.79 | Babs, Dani, ferzy, khizha, REGIANE |
|            6 |     2874 | 2024-04-11 | W7M fe    | W   | 0.456      | 0.332        | 0.002 (0.000)    | 0.050 (0.008)    | 0 (0.000) |     5.89 | Babs, Dani, ferzy, khizha, REGIANE |
|            5 |     3106 | 2024-04-04 | Atrix     | W   | 0.409      | 0.332        | 0.003 (0.000)    | 0.061 (0.008)    | 0 (0.000) |     5.63 | Babs, Dani, ferzy, khizha, REGIANE |
|            4 |     3252 | 2024-03-28 | KG fe     | W   | 0.363      | 0.332        | 0.002 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     3.23 | Babs, Dani, ferzy, khizha, REGIANE |
|            3 |     3411 | 2024-03-20 | panelinha | L   | 0.309      | -            | -                | -                | -         |    -2.79 | Babs, Dani, ferzy, khizha, REGIANE |
|            2 |     3560 | 2024-03-13 | FURIA fe  | L   | 0.263      | -            | -                | -                | -         |    -4.48 | Babs, Dani, ferzy, khizha, REGIANE |
|            1 |     3712 | 2024-03-07 | Divina fe | W   | 0.223      | 0.332        | 0.002 (0.000)    | 0.022 (0.002)    | 0 (0.000) |     2.89 | Babs, Dani, ferzy, khizha, REGIANE |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,404.62)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $750.00        | $750.00         |
| 2024-06-15 |      0.890 | $250.00        | $222.40         |
| 2024-05-26 |      0.756 | $750.00        | $566.88         |
| 2024-04-19 |      0.509 | $1,700.00      | $865.35         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
