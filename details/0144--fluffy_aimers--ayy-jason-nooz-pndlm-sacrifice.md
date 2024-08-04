### Roster Details<br />
Team Name: FLUFFY AIMERS<br />
Roster: ayy, jason, nooz, PNDLM, sacrifice<br />
Global Rank: [144](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [39]( ../standings_americas.md)<br />
<br />
Final Rank Value:  739.4<br />
<br />
Final Rank Value (739.4) = Starting Rank Value (759.2) + Head To Head Adjustments (-19.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.333[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.116[<sup>2</sup>](#table1)

The average of these factors is 0.176<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 759.2
- 400 + ( ( 0.176 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 759.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     2075 | 2024-05-14 | Wildcard    | L   | 0.661      | -            | -                | -                | -         |    -5.73 | ayy, jason, nooz, PNDLM, sacrifice     |
|           19 |     2080 | 2024-05-14 | Wildcard    | L   | 0.661      | -            | -                | -                | -         |    -6.00 | ayy, jason, nooz, PNDLM, sacrifice     |
|           18 |     2217 | 2024-05-09 | Limitless   | W   | 0.628      | 0.477        | 0.001 (0.000)    | 0.168 (0.050)    | 0 (0.000) |     7.09 | ayy, jason, nooz, PNDLM, sacrifice     |
|           17 |     2220 | 2024-05-09 | Limitless   | L   | 0.627      | -            | -                | -                | -         |   -13.01 | ayy, jason, nooz, PNDLM, sacrifice     |
|           16 |     2598 | 2024-04-21 | For Fun     | W   | 0.508      | 0.319        | 0.003 (0.001)    | 0.020 (0.003)    | 1 (0.508) |     6.07 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           15 |     2600 | 2024-04-21 | Will to Win | W   | 0.507      | 0.319        | 0.001 (0.000)    | 0.000 (0.000)    | 1 (0.507) |     3.46 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           14 |     2902 | 2024-04-10 | Take Flyte  | L   | 0.434      | -            | -                | -                | -         |    -8.02 | ayy, intra, jason, PNDLM, sacrifice    |
|           13 |     2907 | 2024-04-10 | Take Flyte  | W   | 0.434      | 0.477        | 0.002 (0.000)    | 0.240 (0.050)    | 0 (0.000) |     5.76 | ayy, jason, nooz, PNDLM, sacrifice     |
|           12 |     3093 | 2024-04-04 | BOSS        | L   | 0.394      | -            | -                | -                | -         |    -5.49 | ayy, intra, jason, nooz, sacrifice     |
|           11 |     3099 | 2024-04-04 | BOSS        | L   | 0.394      | -            | -                | -                | -         |    -5.67 | ayy, intra, jason, PNDLM, sacrifice    |
|           10 |     3488 | 2024-03-15 | NRG         | L   | 0.261      | -            | -                | -                | -         |    -3.18 | ayy, intra, jason, PNDLM, sacrifice    |
|            9 |     3490 | 2024-03-15 | NRG         | W   | 0.261      | 0.477        | 0.020 (0.002)    | 0.521 (0.065)    | 0 (0.000) |     5.13 | ayy, intra, jason, PNDLM, sacrifice    |
|            8 |     3693 | 2024-03-07 | LAG         | L   | 0.208      | -            | -                | -                | -         |    -2.52 | ayy, jason, LEARSI, PNDLM, sacrifice   |
|            7 |     3694 | 2024-03-07 | LAG         | W   | 0.207      | 0.477        | 0.012 (0.001)    | 0.341 (0.034)    | 0 (0.000) |     4.08 | ayy, jason, LEARSI, PNDLM, sacrifice   |
|            6 |     4157 | 2024-02-16 | Mythic      | L   | 0.074      | -            | -                | -                | -         |    -1.05 | intra, jason, LEARSI, PNDLM, sacrifice |
|            5 |     4161 | 2024-02-16 | LAG         | W   | 0.073      | 0.143        | 0.012 (0.000)    | 0.341 (0.004)    | 0 (0.000) |     1.46 | intra, jason, LEARSI, PNDLM, sacrifice |
|            4 |     4215 | 2024-02-14 | Mythic      | L   | 0.061      | -            | -                | -                | -         |    -0.87 | intra, jason, LEARSI, PNDLM, sacrifice |
|            3 |     4217 | 2024-02-14 | Mythic      | L   | 0.061      | -            | -                | -                | -         |    -0.87 | intra, jason, LEARSI, PNDLM, sacrifice |
|            2 |     4256 | 2024-02-13 | Carpe Diem  | L   | 0.054      | -            | -                | -                | -         |    -1.06 | intra, jason, LEARSI, PNDLM, sacrifice |
|            1 |     4259 | 2024-02-13 | Carpe Diem  | W   | 0.054      | 0.477        | 0.005 (0.000)    | 0.039 (0.001)    | 0 (0.000) |     0.66 | intra, jason, LEARSI, PNDLM, sacrifice |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,212.22)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.834 | $1,200.00      | $1,000.33       |
| 2024-04-21 |      0.508 | $4,357.00      | $2,211.88       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
