### Roster Details<br />
Team Name: MIGHT<br />
Roster: djay, Fr3nk1e, Nifty, scar, Snakes<br />
Global Rank: [202](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [57]( ../standings_americas.md)<br />
<br />
Final Rank Value:  512.1<br />
<br />
Final Rank Value (512.1) = Starting Rank Value (528.8) + Head To Head Adjustments (-16.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.229[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.063<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 528.8
- 400 + ( ( 0.063 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 528.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |     1834 | 2024-05-22 | Limitless        | L   | 0.702      | -            | -                | -                | -         |    -4.05 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           28 |     1839 | 2024-05-22 | Limitless        | L   | 0.702      | -            | -                | -                | -         |    -4.21 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           27 |     1916 | 2024-05-20 | Take Flyte       | L   | 0.689      | -            | -                | -                | -         |    -6.70 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           26 |     1920 | 2024-05-20 | Take Flyte       | W   | 0.689      | 0.477        | 0.002 (0.001)    | 0.237 (0.078)    | 0 (0.000) |    15.40 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           25 |     2080 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.656      | -            | -                | -                | -         |    -4.53 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           24 |     2087 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.656      | -            | -                | -                | -         |    -4.71 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           23 |     2140 | 2024-05-14 | BOSS             | L   | 0.649      | -            | -                | -                | -         |    -3.54 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           22 |     2148 | 2024-05-14 | BOSS             | L   | 0.649      | -            | -                | -                | -         |    -3.66 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           21 |     2283 | 2024-05-09 | Wildcard         | L   | 0.616      | -            | -                | -                | -         |    -2.18 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           20 |     2286 | 2024-05-09 | Wildcard         | L   | 0.615      | -            | -                | -                | -         |    -2.23 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           19 |     2301 | 2024-05-08 | Elevate          | L   | 0.609      | -            | -                | -                | -         |    -1.46 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           18 |     2303 | 2024-05-08 | Elevate          | L   | 0.609      | -            | -                | -                | -         |    -1.49 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           17 |     2968 | 2024-04-10 | Phoenix          | W   | 0.422      | 0.477        | 0.004 (0.001)    | 0.278 (0.056)    | 0 (0.000) |    10.26 | danss, djay, Nifty, scar, Snakes   |
|           16 |     2973 | 2024-04-10 | Phoenix          | L   | 0.422      | -            | -                | -                | -         |    -3.05 | danss, djay, Nifty, scar, Snakes   |
|           15 |     3021 | 2024-04-09 | Nouns            | L   | 0.416      | -            | -                | -                | -         |    -1.35 | danss, djay, Louie, scar, Snakes   |
|           14 |     3025 | 2024-04-09 | Nouns            | L   | 0.416      | -            | -                | -                | -         |    -1.36 | danss, djay, Nifty, scar, Snakes   |
|           13 |     3152 | 2024-04-04 | Party Astronauts | L   | 0.383      | -            | -                | -                | -         |    -1.15 | danss, djay, Nifty, scar, Snakes   |
|           12 |     3159 | 2024-04-04 | Party Astronauts | L   | 0.382      | -            | -                | -                | -         |    -1.17 | danss, djay, Nifty, scar, Snakes   |
|           11 |     3328 | 2024-03-27 | Limitless        | L   | 0.329      | -            | -                | -                | -         |    -3.51 | danss, djay, Nifty, scar, Snakes   |
|           10 |     3334 | 2024-03-27 | Limitless        | L   | 0.329      | -            | -                | -                | -         |    -3.60 | danss, djay, Nifty, scar, Snakes   |
|            9 |     3379 | 2024-03-26 | NRG              | L   | 0.323      | -            | -                | -                | -         |    -1.53 | danss, djay, Nifty, scar, Snakes   |
|            8 |     3384 | 2024-03-26 | NRG              | L   | 0.323      | -            | -                | -                | -         |    -1.55 | danss, djay, Nifty, scar, Snakes   |
|            7 |     3784 | 2024-03-06 | LAG              | L   | 0.189      | -            | -                | -                | -         |    -0.98 | danss, djay, Nifty, scar, Snakes   |
|            6 |     3785 | 2024-03-06 | LAG              | W   | 0.189      | 0.477        | 0.012 (0.001)    | 0.347 (0.031)    | 0 (0.000) |     5.02 | danss, djay, Nifty, scar, Snakes   |
|            5 |     3823 | 2024-03-05 | Mythic           | W   | 0.183      | 0.477        | 0.010 (0.001)    | 0.293 (0.026)    | 0 (0.000) |     4.63 | danss, djay, Nifty, scar, Snakes   |
|            4 |     3825 | 2024-03-05 | Mythic           | W   | 0.182      | 0.477        | 0.010 (0.001)    | 0.293 (0.026)    | 0 (0.000) |     4.67 | danss, djay, Nifty, scar, Snakes   |
|            3 |     4074 | 2024-02-22 | Liquid           | L   | 0.102      | -            | -                | -                | -         |    -0.01 | danss, djay, Nifty, scar, Snakes   |
|            2 |     4077 | 2024-02-22 | Phoenix          | W   | 0.102      | 0.143        | 0.004 (0.000)    | 0.278 (0.004)    | 0 (0.000) |     2.44 | danss, djay, Nifty, scar, Snakes   |
|            1 |     4224 | 2024-02-16 | Rocket           | L   | 0.062      | -            | -                | -                | -         |    -1.08 | danss, djay, Nifty, scar, Snakes   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
