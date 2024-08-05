### Roster Details<br />
Team Name: FLUFFY AIMERS<br />
Roster: ayy, jason, nooz, PNDLM, sacrifice<br />
Global Rank: [140](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [39]( ../standings_americas.md)<br />
<br />
Final Rank Value:  745.5<br />
<br />
Final Rank Value (745.5) = Starting Rank Value (767.8) + Head To Head Adjustments (-22.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.333[<sup>1</sup>](#table2)
- Bounty Collected: 0.236[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.121[<sup>2</sup>](#table1)

The average of these factors is 0.178<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 767.8
- 400 + ( ( 0.178 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 767.8


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
|           20 |     1962 | 2024-05-14 | Wildcard    | L   | 0.682      | -            | -                | -                | -         |    -6.07 | ayy, jason, nooz, PNDLM, sacrifice     |
|           19 |     1967 | 2024-05-14 | Wildcard    | L   | 0.681      | -            | -                | -                | -         |    -6.38 | ayy, jason, nooz, PNDLM, sacrifice     |
|           18 |     2104 | 2024-05-09 | Limitless   | W   | 0.648      | 0.477        | 0.001 (0.000)    | 0.170 (0.053)    | 0 (0.000) |     7.22 | ayy, jason, nooz, PNDLM, sacrifice     |
|           17 |     2107 | 2024-05-09 | Limitless   | L   | 0.648      | -            | -                | -                | -         |   -13.55 | ayy, jason, nooz, PNDLM, sacrifice     |
|           16 |     2486 | 2024-04-21 | For Fun     | W   | 0.528      | 0.319        | 0.003 (0.001)    | 0.020 (0.003)    | 1 (0.528) |     6.26 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           15 |     2488 | 2024-04-21 | Will to Win | W   | 0.527      | 0.319        | 0.001 (0.000)    | 0.000 (0.000)    | 1 (0.527) |     3.52 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           14 |     2790 | 2024-04-10 | Take Flyte  | L   | 0.455      | -            | -                | -                | -         |    -8.47 | ayy, intra, jason, PNDLM, sacrifice    |
|           13 |     2795 | 2024-04-10 | Take Flyte  | W   | 0.455      | 0.477        | 0.002 (0.000)    | 0.241 (0.052)    | 0 (0.000) |     5.96 | ayy, jason, nooz, PNDLM, sacrifice     |
|           12 |     2981 | 2024-04-04 | BOSS        | L   | 0.415      | -            | -                | -                | -         |    -5.80 | ayy, intra, jason, nooz, sacrifice     |
|           11 |     2987 | 2024-04-04 | BOSS        | L   | 0.414      | -            | -                | -                | -         |    -6.02 | ayy, intra, jason, PNDLM, sacrifice    |
|           10 |     3376 | 2024-03-15 | NRG         | L   | 0.282      | -            | -                | -                | -         |    -3.57 | ayy, intra, jason, PNDLM, sacrifice    |
|            9 |     3378 | 2024-03-15 | NRG         | W   | 0.282      | 0.477        | 0.020 (0.003)    | 0.519 (0.070)    | 0 (0.000) |     5.41 | ayy, intra, jason, PNDLM, sacrifice    |
|            8 |     3582 | 2024-03-07 | LAG         | L   | 0.229      | -            | -                | -                | -         |    -2.77 | ayy, jason, LEARSI, PNDLM, sacrifice   |
|            7 |     3583 | 2024-03-07 | LAG         | W   | 0.228      | 0.477        | 0.013 (0.001)    | 0.344 (0.037)    | 0 (0.000) |     4.49 | ayy, jason, LEARSI, PNDLM, sacrifice   |
|            6 |     4047 | 2024-02-16 | Mythic      | L   | 0.094      | -            | -                | -                | -         |    -1.35 | intra, jason, LEARSI, PNDLM, sacrifice |
|            5 |     4051 | 2024-02-16 | LAG         | W   | 0.094      | 0.143        | 0.013 (0.000)    | 0.344 (0.005)    | 0 (0.000) |     1.88 | intra, jason, LEARSI, PNDLM, sacrifice |
|            4 |     4105 | 2024-02-14 | Mythic      | L   | 0.082      | -            | -                | -                | -         |    -1.18 | intra, jason, LEARSI, PNDLM, sacrifice |
|            3 |     4107 | 2024-02-14 | Mythic      | L   | 0.082      | -            | -                | -                | -         |    -1.19 | intra, jason, LEARSI, PNDLM, sacrifice |
|            2 |     4146 | 2024-02-13 | Carpe Diem  | L   | 0.075      | -            | -                | -                | -         |    -1.48 | intra, jason, LEARSI, PNDLM, sacrifice |
|            1 |     4149 | 2024-02-13 | Carpe Diem  | W   | 0.075      | 0.477        | 0.005 (0.000)    | 0.042 (0.002)    | 0 (0.000) |     0.89 | intra, jason, LEARSI, PNDLM, sacrifice |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,327.40)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.854 | $1,200.00      | $1,025.21       |
| 2024-04-21 |      0.528 | $4,357.00      | $2,302.19       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
