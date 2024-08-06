### Roster Details<br />
Team Name: MIGHT<br />
Roster: djay, Fr3nk1e, Nifty, scar, Snakes<br />
Global Rank: [202](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [57]( ../standings_americas.md)<br />
<br />
Final Rank Value:  511.8<br />
<br />
Final Rank Value (511.8) = Starting Rank Value (528.5) + Head To Head Adjustments (-16.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.228[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.062<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 528.5
- 400 + ( ( 0.062 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 528.5


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
|           29 |     1856 | 2024-05-22 | Limitless        | L   | 0.696      | -            | -                | -                | -         |    -4.02 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           28 |     1861 | 2024-05-22 | Limitless        | L   | 0.696      | -            | -                | -                | -         |    -4.17 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           27 |     1938 | 2024-05-20 | Take Flyte       | L   | 0.683      | -            | -                | -                | -         |    -6.62 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           26 |     1942 | 2024-05-20 | Take Flyte       | W   | 0.682      | 0.477        | 0.002 (0.001)    | 0.231 (0.075)    | 0 (0.000) |    15.28 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           25 |     2102 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.649      | -            | -                | -                | -         |    -4.48 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           24 |     2109 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.649      | -            | -                | -                | -         |    -4.66 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           23 |     2162 | 2024-05-14 | BOSS             | L   | 0.643      | -            | -                | -                | -         |    -3.49 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           22 |     2170 | 2024-05-14 | BOSS             | L   | 0.642      | -            | -                | -                | -         |    -3.60 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           21 |     2305 | 2024-05-09 | Wildcard         | L   | 0.609      | -            | -                | -                | -         |    -2.17 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           20 |     2308 | 2024-05-09 | Wildcard         | L   | 0.609      | -            | -                | -                | -         |    -2.21 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           19 |     2323 | 2024-05-08 | Elevate          | L   | 0.603      | -            | -                | -                | -         |    -1.45 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           18 |     2325 | 2024-05-08 | Elevate          | L   | 0.603      | -            | -                | -                | -         |    -1.47 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           17 |     2990 | 2024-04-10 | Phoenix          | W   | 0.416      | 0.477        | 0.004 (0.001)    | 0.270 (0.054)    | 0 (0.000) |    10.11 | danss, djay, Nifty, scar, Snakes   |
|           16 |     2995 | 2024-04-10 | Phoenix          | L   | 0.416      | -            | -                | -                | -         |    -3.00 | danss, djay, Nifty, scar, Snakes   |
|           15 |     3043 | 2024-04-09 | Nouns            | L   | 0.410      | -            | -                | -                | -         |    -1.33 | danss, djay, Louie, scar, Snakes   |
|           14 |     3047 | 2024-04-09 | Nouns            | L   | 0.409      | -            | -                | -                | -         |    -1.35 | danss, djay, Nifty, scar, Snakes   |
|           13 |     3174 | 2024-04-04 | Party Astronauts | L   | 0.376      | -            | -                | -                | -         |    -1.14 | danss, djay, Nifty, scar, Snakes   |
|           12 |     3181 | 2024-04-04 | Party Astronauts | L   | 0.376      | -            | -                | -                | -         |    -1.15 | danss, djay, Nifty, scar, Snakes   |
|           11 |     3350 | 2024-03-27 | Limitless        | L   | 0.323      | -            | -                | -                | -         |    -3.43 | danss, djay, Nifty, scar, Snakes   |
|           10 |     3356 | 2024-03-27 | Limitless        | L   | 0.323      | -            | -                | -                | -         |    -3.52 | danss, djay, Nifty, scar, Snakes   |
|            9 |     3401 | 2024-03-26 | NRG              | L   | 0.316      | -            | -                | -                | -         |    -1.50 | danss, djay, Nifty, scar, Snakes   |
|            8 |     3406 | 2024-03-26 | NRG              | L   | 0.316      | -            | -                | -                | -         |    -1.52 | danss, djay, Nifty, scar, Snakes   |
|            7 |     3806 | 2024-03-06 | LAG              | L   | 0.183      | -            | -                | -                | -         |    -0.95 | danss, djay, Nifty, scar, Snakes   |
|            6 |     3807 | 2024-03-06 | LAG              | W   | 0.183      | 0.477        | 0.012 (0.001)    | 0.376 (0.033)    | 0 (0.000) |     4.84 | danss, djay, Nifty, scar, Snakes   |
|            5 |     3845 | 2024-03-05 | Mythic           | W   | 0.176      | 0.477        | 0.010 (0.001)    | 0.285 (0.024)    | 0 (0.000) |     4.46 | danss, djay, Nifty, scar, Snakes   |
|            4 |     3847 | 2024-03-05 | Mythic           | W   | 0.176      | 0.477        | 0.010 (0.001)    | 0.285 (0.024)    | 0 (0.000) |     4.50 | danss, djay, Nifty, scar, Snakes   |
|            3 |     4096 | 2024-02-22 | Liquid           | L   | 0.096      | -            | -                | -                | -         |    -0.01 | danss, djay, Nifty, scar, Snakes   |
|            2 |     4099 | 2024-02-22 | Phoenix          | W   | 0.095      | 0.143        | 0.004 (0.000)    | 0.270 (0.004)    | 0 (0.000) |     2.29 | danss, djay, Nifty, scar, Snakes   |
|            1 |     4246 | 2024-02-16 | Rocket           | L   | 0.055      | -            | -                | -                | -         |    -0.97 | danss, djay, Nifty, scar, Snakes   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
