### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [57](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1000.5<br />
<br />
Final Rank Value (1000.5) = Starting Rank Value (991.1) + Head To Head Adjustments (9.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.539[<sup>1</sup>](#table2)
- Bounty Collected: 0.409[<sup>2</sup>](#table1)
- Opponent Network: 0.084[<sup>2</sup>](#table1)
- LAN Wins: 0.123[<sup>2</sup>](#table1)

The average of these factors is 0.289<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 991.1
- 400 + ( ( 0.289 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 991.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |      157 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.37 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      193 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.18 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1563 | 2024-05-30 | Chinggis Warriors | L   | 0.765      | -            | -                | -                | -         |   -19.76 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1591 | 2024-05-29 | ATOX              | L   | 0.757      | -            | -                | -                | -         |   -17.02 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1848 | 2024-05-19 | paiN              | L   | 0.691      | -            | -                | -                | -         |    -3.38 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1856 | 2024-05-18 | Liquid            | L   | 0.688      | -            | -                | -                | -         |    -1.49 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2321 | 2024-05-01 | Insilio           | L   | 0.573      | -            | -                | -                | -         |   -11.94 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2350 | 2024-04-30 | Sashi             | L   | 0.566      | -            | -                | -                | -         |    -5.97 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2571 | 2024-04-20 | MIBR              | L   | 0.499      | -            | -                | -                | -         |    -1.53 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2586 | 2024-04-19 | 9z                | W   | 0.496      | 0.589        | 0.136 (0.040)    | 0.528 (0.154)    | 1 (0.496) |    11.22 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2597 | 2024-04-19 | Monte             | W   | 0.494      | 0.589        | 0.060 (0.017)    | 0.168 (0.049)    | 1 (0.494) |     6.84 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2641 | 2024-04-18 | MIBR              | L   | 0.488      | -            | -                | -                | -         |    -1.52 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2770 | 2024-04-14 | Aurora            | L   | 0.459      | -            | -                | -                | -         |    -0.50 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2779 | 2024-04-13 | BetBoom           | W   | 0.454      | 0.684        | 0.252 (0.078)    | 0.563 (0.175)    | 0 (0.000) |    12.69 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2788 | 2024-04-13 | BIG               | W   | 0.452      | 0.684        | 0.156 (0.048)    | 0.316 (0.098)    | 0 (0.000) |    11.79 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2801 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.446      | 0.684        | 0.204 (0.062)    | 0.502 (0.153)    | 0 (0.000) |    13.49 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     2873 | 2024-04-10 | ENCE              | W   | 0.432      | 0.684        | 0.170 (0.050)    | 0.415 (0.123)    | 0 (0.000) |    12.51 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     2951 | 2024-04-08 | Aurora            | L   | 0.420      | -            | -                | -                | -         |    -0.32 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3565 | 2024-03-10 | SAW               | L   | 0.227      | -            | -                | -                | -         |    -1.90 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3590 | 2024-03-09 | HEROIC            | W   | 0.219      | 0.535        | 0.230 (0.027)    | 0.388 (0.046)    | 0 (0.000) |     6.64 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3633 | 2024-03-07 | Complexity        | W   | 0.207      | 0.535        | 0.313 (0.035)    | 0.394 (0.044)    | 0 (0.000) |     6.37 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     3975 | 2024-02-21 | GamerLegion       | L   | 0.106      | -            | -                | -                | -         |    -2.54 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4007 | 2024-02-20 | Gaimin Gladiators | L   | 0.098      | -            | -                | -                | -         |    -1.64 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4024 | 2024-02-19 | ex-Preasy         | W   | 0.094      | 0.143        | 0.012 (0.000)    | 0.119 (0.002)    | 1 (0.094) |     0.69 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4031 | 2024-02-19 | Apeks             | L   | 0.092      | -            | -                | -                | -         |    -1.80 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,586.77)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.580 | $1,000.00      | $579.77         |
| 2024-04-20 |      0.501 | $10,000.00     | $5,010.65       |
| 2024-04-14 |      0.459 | $70,000.00     | $32,154.63      |
| 2024-03-10 |      0.227 | $12,500.00     | $2,841.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
