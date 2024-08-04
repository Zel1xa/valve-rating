### Roster Details<br />
Team Name: FLUFFY AIMERS<br />
Roster: ayy, jason, nooz, PNDLM, sacrifice<br />
Global Rank: [147](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [40]( ../standings_americas.md)<br />
<br />
Final Rank Value:  737.9<br />
<br />
Final Rank Value (737.9) = Starting Rank Value (758.6) + Head To Head Adjustments (-20.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.333[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.115[<sup>2</sup>](#table1)

The average of these factors is 0.175<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 758.6
- 400 + ( ( 0.175 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 758.6


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
|           20 |     2111 | 2024-05-14 | Wildcard    | L   | 0.656      | -            | -                | -                | -         |    -6.22 | ayy, jason, nooz, PNDLM, sacrifice     |
|           19 |     2116 | 2024-05-14 | Wildcard    | L   | 0.656      | -            | -                | -                | -         |    -6.54 | ayy, jason, nooz, PNDLM, sacrifice     |
|           18 |     2253 | 2024-05-09 | Limitless   | W   | 0.623      | 0.477        | 0.001 (0.000)    | 0.167 (0.050)    | 0 (0.000) |     7.03 | ayy, jason, nooz, PNDLM, sacrifice     |
|           17 |     2256 | 2024-05-09 | Limitless   | L   | 0.622      | -            | -                | -                | -         |   -12.91 | ayy, jason, nooz, PNDLM, sacrifice     |
|           16 |     2635 | 2024-04-21 | For Fun     | W   | 0.503      | 0.319        | 0.003 (0.001)    | 0.020 (0.003)    | 1 (0.503) |     6.02 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           15 |     2637 | 2024-04-21 | Will to Win | W   | 0.502      | 0.319        | 0.001 (0.000)    | 0.000 (0.000)    | 1 (0.502) |     3.44 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           14 |     2939 | 2024-04-10 | Take Flyte  | L   | 0.429      | -            | -                | -                | -         |    -7.89 | ayy, intra, jason, PNDLM, sacrifice    |
|           13 |     2944 | 2024-04-10 | Take Flyte  | W   | 0.429      | 0.477        | 0.002 (0.000)    | 0.240 (0.049)    | 0 (0.000) |     5.74 | ayy, jason, nooz, PNDLM, sacrifice     |
|           12 |     3130 | 2024-04-04 | BOSS        | L   | 0.389      | -            | -                | -                | -         |    -5.39 | ayy, intra, jason, nooz, sacrifice     |
|           11 |     3136 | 2024-04-04 | BOSS        | L   | 0.389      | -            | -                | -                | -         |    -5.57 | ayy, intra, jason, PNDLM, sacrifice    |
|           10 |     3525 | 2024-03-15 | NRG         | L   | 0.256      | -            | -                | -                | -         |    -3.12 | ayy, intra, jason, PNDLM, sacrifice    |
|            9 |     3527 | 2024-03-15 | NRG         | W   | 0.256      | 0.477        | 0.020 (0.002)    | 0.521 (0.064)    | 0 (0.000) |     5.03 | ayy, intra, jason, PNDLM, sacrifice    |
|            8 |     3731 | 2024-03-07 | LAG         | L   | 0.203      | -            | -                | -                | -         |    -2.57 | ayy, jason, LEARSI, PNDLM, sacrifice   |
|            7 |     3732 | 2024-03-07 | LAG         | W   | 0.203      | 0.477        | 0.012 (0.001)    | 0.353 (0.034)    | 0 (0.000) |     3.88 | ayy, jason, LEARSI, PNDLM, sacrifice   |
|            6 |     4196 | 2024-02-16 | Mythic      | L   | 0.069      | -            | -                | -                | -         |    -0.98 | intra, jason, LEARSI, PNDLM, sacrifice |
|            5 |     4200 | 2024-02-16 | LAG         | W   | 0.069      | 0.143        | 0.012 (0.000)    | 0.353 (0.003)    | 0 (0.000) |     1.33 | intra, jason, LEARSI, PNDLM, sacrifice |
|            4 |     4254 | 2024-02-14 | Mythic      | L   | 0.056      | -            | -                | -                | -         |    -0.80 | intra, jason, LEARSI, PNDLM, sacrifice |
|            3 |     4256 | 2024-02-14 | Mythic      | L   | 0.056      | -            | -                | -                | -         |    -0.80 | intra, jason, LEARSI, PNDLM, sacrifice |
|            2 |     4295 | 2024-02-13 | Carpe Diem  | L   | 0.050      | -            | -                | -                | -         |    -0.96 | intra, jason, LEARSI, PNDLM, sacrifice |
|            1 |     4298 | 2024-02-13 | Carpe Diem  | W   | 0.049      | 0.477        | 0.005 (0.000)    | 0.038 (0.001)    | 0 (0.000) |     0.60 | intra, jason, LEARSI, PNDLM, sacrifice |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,185.33)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.829 | $1,200.00      | $994.53         |
| 2024-04-21 |      0.503 | $4,357.00      | $2,190.80       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />