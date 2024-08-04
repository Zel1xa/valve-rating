### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: ADDICT, BRACE, damyo, hazr, pz<br />
Global Rank: [127](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  783.0<br />
<br />
Final Rank Value (783.0) = Starting Rank Value (760.5) + Head To Head Adjustments (22.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.360[<sup>1</sup>](#table2)
- Bounty Collected: 0.228[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.099[<sup>2</sup>](#table1)

The average of these factors is 0.176<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 760.5
- 400 + ( ( 0.176 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 760.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     2347 | 2024-05-03 | FURIA       | L   | 0.581      | -            | -                | -                | -         |    -0.16 | ADDICT, BRACE, damyo, hazr, pz      |
|           26 |     2394 | 2024-05-01 | ENCE        | L   | 0.568      | -            | -                | -                | -         |    -0.56 | ADDICT, BRACE, damyo, hazr, pz      |
|           25 |     2426 | 2024-04-30 | MOUZ        | L   | 0.560      | -            | -                | -                | -         |    -0.04 | ADDICT, BRACE, damyo, hazr, pz      |
|           24 |     2649 | 2024-04-20 | FlyQuest    | L   | 0.493      | -            | -                | -                | -         |    -1.58 | ADDICT, BRACE, damyo, hazr, pz      |
|           23 |     2653 | 2024-04-19 | Rooster     | W   | 0.492      | 0.143        | 0.010 (0.001)    | 0.266 (0.019)    | 0 (0.000) |     8.19 | ADDICT, BRACE, damyo, hazr, pz      |
|           22 |     2696 | 2024-04-19 | Mindfreak   | W   | 0.487      | 0.143        | 0.004 (0.000)    | 0.227 (0.016)    | 0 (0.000) |     6.02 | ADDICT, BRACE, damyo, hazr, pz      |
|           21 |     2701 | 2024-04-18 | Rooster     | L   | 0.486      | -            | -                | -                | -         |    -7.21 | ADDICT, BRACE, damyo, hazr, pz      |
|           20 |     2950 | 2024-04-10 | Rooster     | W   | 0.427      | 0.333        | 0.010 (0.001)    | 0.266 (0.038)    | 0 (0.000) |     7.12 | ADDICT, BRACE, damyo, hazr, pz      |
|           19 |     2957 | 2024-04-10 | Rooster     | L   | 0.426      | -            | -                | -                | -         |    -6.45 | ADDICT, BRACE, damyo, hazr, pz      |
|           18 |     3183 | 2024-04-03 | DXA         | W   | 0.380      | 0.333        | 0.002 (0.000)    | 0.227 (0.029)    | 0 (0.000) |     4.35 | ADDICT, BRACE, damyo, hazr, pz      |
|           17 |     3188 | 2024-04-03 | DXA         | W   | 0.380      | 0.333        | 0.002 (0.000)    | 0.227 (0.029)    | 0 (0.000) |     4.48 | ADDICT, BRACE, damyo, hazr, pz      |
|           16 |     3311 | 2024-03-27 | Mindfreak   | L   | 0.334      | -            | -                | -                | -         |    -6.86 | ADDICT, BRACE, damyo, hazr, pz      |
|           15 |     3316 | 2024-03-27 | Mindfreak   | W   | 0.333      | 0.333        | 0.004 (0.000)    | 0.051 (0.006)    | 0 (0.000) |     3.70 | ADDICT, BRACE, damyo, hazr, pz      |
|           14 |     3359 | 2024-03-23 | DXA         | W   | 0.306      | 0.315        | 0.002 (0.000)    | 0.227 (0.022)    | 1 (0.306) |     3.74 | ADDICT, BRACE, damyo, hazr, pz      |
|           13 |     3362 | 2024-03-23 | Arcade      | W   | 0.306      | 0.315        | 0.002 (0.000)    | 0.137 (0.013)    | 1 (0.306) |     3.65 | ADDICT, BRACE, damyo, hazr, pz      |
|           12 |     3420 | 2024-03-20 | Canon Event | W   | 0.286      | -            | -                | -                | 0 (0.000) |     1.74 | ADDICT, BRACE, damyo, hazr, pz      |
|           11 |     3421 | 2024-03-20 | Canon Event | W   | 0.286      | -            | -                | -                | -         |     1.77 | ADDICT, BRACE, damyo, hazr, pz      |
|           10 |     3491 | 2024-03-15 | Gods Reign  | L   | 0.259      | -            | -                | -                | -         |    -3.98 | ADDICT, BRACE, hazr, pz, yourwombat |
|            9 |     3512 | 2024-03-14 | GRDX        | W   | 0.252      | 0.432        | 0.002 (0.000)    | -                | 1 (0.252) |     1.74 | ADDICT, BRACE, hazr, pz, yourwombat |
|            8 |     3545 | 2024-03-14 | Aurora      | L   | 0.246      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, hazr, pz, yourwombat |
|            7 |     3758 | 2024-03-06 | Vantage     | W   | 0.194      | 0.333        | 0.002 (0.000)    | 0.070 (0.005)    | -         |     2.12 | ADDICT, BRACE, damyo, hazr, pz      |
|            6 |     3760 | 2024-03-06 | Vantage     | W   | 0.193      | 0.333        | -                | 0.070 (0.005)    | -         |     2.15 | ADDICT, BRACE, damyo, hazr, pz      |
|            5 |     4014 | 2024-02-22 | Rooster     | L   | 0.112      | -            | -                | -                | -         |    -1.68 | ADDICT, BRACE, Hatz, hazr, pz       |
|            4 |     4032 | 2024-02-22 | Vantage     | W   | 0.107      | -            | -                | -                | -         |     1.20 | ADDICT, BRACE, Hatz, hazr, pz       |
|            3 |     4035 | 2024-02-21 | FlyQuest    | L   | 0.105      | -            | -                | -                | -         |    -0.33 | ADDICT, BRACE, Hatz, hazr, pz       |
|            2 |     4058 | 2024-02-21 | FlyQuest    | L   | 0.100      | -            | -                | -                | -         |    -0.31 | ADDICT, BRACE, Hatz, hazr, pz       |
|            1 |     4062 | 2024-02-21 | FlyQuest    | L   | 0.100      | -            | -                | -                | -         |    -0.31 | ADDICT, BRACE, Hatz, hazr, pz       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,428.24)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.826 | $1,050.00      | $866.83         |
| 2024-05-12 |      0.641 | $3,500.00      | $2,244.86       |
| 2024-03-23 |      0.306 | $3,308.00      | $1,013.76       |
| 2024-03-16 |      0.261 | $5,000.00      | $1,302.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
