### Roster Details<br />
Team Name: MIGHT<br />
Roster: djay, Fr3nk1e, Nifty, scar, Snakes<br />
Global Rank: [202](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [57]( ../standings_americas.md)<br />
<br />
Final Rank Value:  512.2<br />
<br />
Final Rank Value (512.2) = Starting Rank Value (528.8) + Head To Head Adjustments (-16.7)<br />

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
- 400 + ( ( 0.063 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 528.8


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
|           29 |     1826 | 2024-05-22 | Limitless        | L   | 0.704      | -            | -                | -                | -         |    -4.06 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           28 |     1831 | 2024-05-22 | Limitless        | L   | 0.703      | -            | -                | -                | -         |    -4.21 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           27 |     1908 | 2024-05-20 | Take Flyte       | L   | 0.690      | -            | -                | -                | -         |    -6.72 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           26 |     1912 | 2024-05-20 | Take Flyte       | W   | 0.690      | 0.477        | 0.002 (0.001)    | 0.239 (0.079)    | 0 (0.000) |    15.42 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           25 |     2072 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.657      | -            | -                | -                | -         |    -4.54 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           24 |     2079 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.657      | -            | -                | -                | -         |    -4.72 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           23 |     2132 | 2024-05-14 | BOSS             | L   | 0.650      | -            | -                | -                | -         |    -3.54 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           22 |     2140 | 2024-05-14 | BOSS             | L   | 0.650      | -            | -                | -                | -         |    -3.66 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           21 |     2275 | 2024-05-09 | Wildcard         | L   | 0.617      | -            | -                | -                | -         |    -2.18 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           20 |     2278 | 2024-05-09 | Wildcard         | L   | 0.616      | -            | -                | -                | -         |    -2.23 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           19 |     2293 | 2024-05-08 | Elevate          | L   | 0.610      | -            | -                | -                | -         |    -1.47 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           18 |     2295 | 2024-05-08 | Elevate          | L   | 0.610      | -            | -                | -                | -         |    -1.49 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           17 |     2960 | 2024-04-10 | Phoenix          | W   | 0.424      | 0.477        | 0.004 (0.001)    | 0.281 (0.057)    | 0 (0.000) |    10.29 | danss, djay, Nifty, scar, Snakes   |
|           16 |     2965 | 2024-04-10 | Phoenix          | L   | 0.423      | -            | -                | -                | -         |    -3.06 | danss, djay, Nifty, scar, Snakes   |
|           15 |     3013 | 2024-04-09 | Nouns            | L   | 0.417      | -            | -                | -                | -         |    -1.35 | danss, djay, Louie, scar, Snakes   |
|           14 |     3017 | 2024-04-09 | Nouns            | L   | 0.417      | -            | -                | -                | -         |    -1.36 | danss, djay, Nifty, scar, Snakes   |
|           13 |     3144 | 2024-04-04 | Party Astronauts | L   | 0.384      | -            | -                | -                | -         |    -1.15 | danss, djay, Nifty, scar, Snakes   |
|           12 |     3151 | 2024-04-04 | Party Astronauts | L   | 0.383      | -            | -                | -                | -         |    -1.17 | danss, djay, Nifty, scar, Snakes   |
|           11 |     3320 | 2024-03-27 | Limitless        | L   | 0.331      | -            | -                | -                | -         |    -3.52 | danss, djay, Nifty, scar, Snakes   |
|           10 |     3326 | 2024-03-27 | Limitless        | L   | 0.330      | -            | -                | -                | -         |    -3.62 | danss, djay, Nifty, scar, Snakes   |
|            9 |     3371 | 2024-03-26 | NRG              | L   | 0.324      | -            | -                | -                | -         |    -1.53 | danss, djay, Nifty, scar, Snakes   |
|            8 |     3376 | 2024-03-26 | NRG              | L   | 0.324      | -            | -                | -                | -         |    -1.56 | danss, djay, Nifty, scar, Snakes   |
|            7 |     3776 | 2024-03-06 | LAG              | L   | 0.191      | -            | -                | -                | -         |    -0.99 | danss, djay, Nifty, scar, Snakes   |
|            6 |     3777 | 2024-03-06 | LAG              | W   | 0.190      | 0.477        | 0.012 (0.001)    | 0.351 (0.032)    | 0 (0.000) |     5.05 | danss, djay, Nifty, scar, Snakes   |
|            5 |     3815 | 2024-03-05 | Mythic           | W   | 0.184      | 0.477        | 0.010 (0.001)    | 0.297 (0.026)    | 0 (0.000) |     4.66 | danss, djay, Nifty, scar, Snakes   |
|            4 |     3817 | 2024-03-05 | Mythic           | W   | 0.184      | 0.477        | 0.010 (0.001)    | 0.297 (0.026)    | 0 (0.000) |     4.70 | danss, djay, Nifty, scar, Snakes   |
|            3 |     4066 | 2024-02-22 | Liquid           | L   | 0.103      | -            | -                | -                | -         |    -0.01 | danss, djay, Nifty, scar, Snakes   |
|            2 |     4069 | 2024-02-22 | Phoenix          | W   | 0.103      | 0.143        | 0.004 (0.000)    | 0.281 (0.004)    | 0 (0.000) |     2.47 | danss, djay, Nifty, scar, Snakes   |
|            1 |     4216 | 2024-02-16 | Rocket           | L   | 0.063      | -            | -                | -                | -         |    -1.10 | danss, djay, Nifty, scar, Snakes   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
