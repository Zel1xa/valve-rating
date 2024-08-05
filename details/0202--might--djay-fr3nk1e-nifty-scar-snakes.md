### Roster Details<br />
Team Name: MIGHT<br />
Roster: djay, Fr3nk1e, Nifty, scar, Snakes<br />
Global Rank: [202](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [57]( ../standings_americas.md)<br />
<br />
Final Rank Value:  512.0<br />
<br />
Final Rank Value (512.0) = Starting Rank Value (528.7) + Head To Head Adjustments (-16.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.229[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.063<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 528.7
- 400 + ( ( 0.063 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 528.7


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
|           29 |     1835 | 2024-05-22 | Limitless        | L   | 0.702      | -            | -                | -                | -         |    -4.05 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           28 |     1840 | 2024-05-22 | Limitless        | L   | 0.702      | -            | -                | -                | -         |    -4.21 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           27 |     1917 | 2024-05-20 | Take Flyte       | L   | 0.689      | -            | -                | -                | -         |    -6.70 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           26 |     1921 | 2024-05-20 | Take Flyte       | W   | 0.688      | 0.477        | 0.002 (0.001)    | 0.236 (0.078)    | 0 (0.000) |    15.39 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           25 |     2081 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.655      | -            | -                | -                | -         |    -4.53 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           24 |     2088 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.655      | -            | -                | -                | -         |    -4.71 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           23 |     2141 | 2024-05-14 | BOSS             | L   | 0.649      | -            | -                | -                | -         |    -3.54 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           22 |     2149 | 2024-05-14 | BOSS             | L   | 0.648      | -            | -                | -                | -         |    -3.65 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           21 |     2284 | 2024-05-09 | Wildcard         | L   | 0.615      | -            | -                | -                | -         |    -2.18 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           20 |     2287 | 2024-05-09 | Wildcard         | L   | 0.615      | -            | -                | -                | -         |    -2.23 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           19 |     2302 | 2024-05-08 | Elevate          | L   | 0.609      | -            | -                | -                | -         |    -1.46 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           18 |     2304 | 2024-05-08 | Elevate          | L   | 0.608      | -            | -                | -                | -         |    -1.48 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           17 |     2969 | 2024-04-10 | Phoenix          | W   | 0.422      | 0.477        | 0.004 (0.001)    | 0.278 (0.056)    | 0 (0.000) |    10.25 | danss, djay, Nifty, scar, Snakes   |
|           16 |     2974 | 2024-04-10 | Phoenix          | L   | 0.422      | -            | -                | -                | -         |    -3.05 | danss, djay, Nifty, scar, Snakes   |
|           15 |     3022 | 2024-04-09 | Nouns            | L   | 0.416      | -            | -                | -                | -         |    -1.35 | danss, djay, Louie, scar, Snakes   |
|           14 |     3026 | 2024-04-09 | Nouns            | L   | 0.415      | -            | -                | -                | -         |    -1.36 | danss, djay, Nifty, scar, Snakes   |
|           13 |     3153 | 2024-04-04 | Party Astronauts | L   | 0.382      | -            | -                | -                | -         |    -1.15 | danss, djay, Nifty, scar, Snakes   |
|           12 |     3160 | 2024-04-04 | Party Astronauts | L   | 0.382      | -            | -                | -                | -         |    -1.16 | danss, djay, Nifty, scar, Snakes   |
|           11 |     3329 | 2024-03-27 | Limitless        | L   | 0.329      | -            | -                | -                | -         |    -3.50 | danss, djay, Nifty, scar, Snakes   |
|           10 |     3335 | 2024-03-27 | Limitless        | L   | 0.329      | -            | -                | -                | -         |    -3.60 | danss, djay, Nifty, scar, Snakes   |
|            9 |     3380 | 2024-03-26 | NRG              | L   | 0.322      | -            | -                | -                | -         |    -1.53 | danss, djay, Nifty, scar, Snakes   |
|            8 |     3385 | 2024-03-26 | NRG              | L   | 0.322      | -            | -                | -                | -         |    -1.55 | danss, djay, Nifty, scar, Snakes   |
|            7 |     3785 | 2024-03-06 | LAG              | L   | 0.189      | -            | -                | -                | -         |    -0.98 | danss, djay, Nifty, scar, Snakes   |
|            6 |     3786 | 2024-03-06 | LAG              | W   | 0.189      | 0.477        | 0.012 (0.001)    | 0.347 (0.031)    | 0 (0.000) |     5.00 | danss, djay, Nifty, scar, Snakes   |
|            5 |     3824 | 2024-03-05 | Mythic           | W   | 0.182      | 0.477        | 0.010 (0.001)    | 0.293 (0.025)    | 0 (0.000) |     4.62 | danss, djay, Nifty, scar, Snakes   |
|            4 |     3826 | 2024-03-05 | Mythic           | W   | 0.182      | 0.477        | 0.010 (0.001)    | 0.293 (0.025)    | 0 (0.000) |     4.66 | danss, djay, Nifty, scar, Snakes   |
|            3 |     4075 | 2024-02-22 | Liquid           | L   | 0.102      | -            | -                | -                | -         |    -0.01 | danss, djay, Nifty, scar, Snakes   |
|            2 |     4078 | 2024-02-22 | Phoenix          | W   | 0.101      | 0.143        | 0.004 (0.000)    | 0.278 (0.004)    | 0 (0.000) |     2.43 | danss, djay, Nifty, scar, Snakes   |
|            1 |     4225 | 2024-02-16 | Rocket           | L   | 0.061      | -            | -                | -                | -         |    -1.07 | danss, djay, Nifty, scar, Snakes   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
