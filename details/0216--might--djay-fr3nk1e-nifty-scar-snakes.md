### Roster Details<br />
Team Name: MIGHT<br />
Roster: djay, Fr3nk1e, Nifty, scar, Snakes<br />
Global Rank: [216](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [58]( ../standings_americas.md)<br />
<br />
Final Rank Value:  482.4<br />
<br />
Final Rank Value (482.4) = Starting Rank Value (496.7) + Head To Head Adjustments (-14.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.193[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.050<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 496.7
- 400 + ( ( 0.050 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 496.7


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
|           22 |     2976 | 2024-05-22 | Carpe Diem       | L   | 0.477      | -            | -                | -                | -         |    -3.12 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           21 |     2981 | 2024-05-22 | Carpe Diem       | L   | 0.477      | -            | -                | -                | -         |    -3.21 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           20 |     3058 | 2024-05-20 | Take Flyte       | L   | 0.464      | -            | -                | -                | -         |    -4.14 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           19 |     3062 | 2024-05-20 | Take Flyte       | W   | 0.463      | 0.477        | 0.002 (0.000)    | 0.230 (0.051)    | 0 (0.000) |    10.69 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           18 |     3222 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.430      | -            | -                | -                | -         |    -2.35 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           17 |     3229 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.430      | -            | -                | -                | -         |    -2.40 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           16 |     3282 | 2024-05-14 | BOSS             | L   | 0.423      | -            | -                | -                | -         |    -2.24 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           15 |     3290 | 2024-05-14 | BOSS             | L   | 0.423      | -            | -                | -                | -         |    -2.29 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           14 |     3425 | 2024-05-09 | Wildcard         | L   | 0.390      | -            | -                | -                | -         |    -0.66 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           13 |     3428 | 2024-05-09 | Wildcard         | L   | 0.390      | -            | -                | -                | -         |    -0.66 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           12 |     3443 | 2024-05-08 | timbermen        | L   | 0.384      | -            | -                | -                | -         |    -0.98 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           11 |     3445 | 2024-05-08 | timbermen        | L   | 0.383      | -            | -                | -                | -         |    -0.99 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           10 |     4110 | 2024-04-10 | Phoenix          | W   | 0.197      | 0.477        | 0.003 (0.000)    | 0.214 (0.020)    | 0 (0.000) |     4.75 | danss, djay, Nifty, scar, Snakes   |
|            9 |     4115 | 2024-04-10 | Phoenix          | L   | 0.197      | -            | -                | -                | -         |    -1.46 | danss, djay, Nifty, scar, Snakes   |
|            8 |     4163 | 2024-04-09 | Nouns            | L   | 0.190      | -            | -                | -                | -         |    -0.60 | danss, djay, Louie, scar, Snakes   |
|            7 |     4167 | 2024-04-09 | Nouns            | L   | 0.190      | -            | -                | -                | -         |    -0.60 | danss, djay, Nifty, scar, Snakes   |
|            6 |     4294 | 2024-04-04 | Party Astronauts | L   | 0.157      | -            | -                | -                | -         |    -0.55 | danss, djay, Nifty, scar, Snakes   |
|            5 |     4301 | 2024-04-04 | Party Astronauts | L   | 0.157      | -            | -                | -                | -         |    -0.55 | danss, djay, Nifty, scar, Snakes   |
|            4 |     4470 | 2024-03-27 | Limitless        | L   | 0.104      | -            | -                | -                | -         |    -1.05 | danss, djay, Nifty, scar, Snakes   |
|            3 |     4476 | 2024-03-27 | Limitless        | L   | 0.104      | -            | -                | -                | -         |    -1.06 | danss, djay, Nifty, scar, Snakes   |
|            2 |     4521 | 2024-03-26 | NRG              | L   | 0.097      | -            | -                | -                | -         |    -0.43 | danss, djay, Nifty, scar, Snakes   |
|            1 |     4526 | 2024-03-26 | NRG              | L   | 0.097      | -            | -                | -                | -         |    -0.43 | danss, djay, Nifty, scar, Snakes   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
