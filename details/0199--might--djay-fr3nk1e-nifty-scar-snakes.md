### Roster Details<br />
Team Name: MIGHT<br />
Roster: djay, Fr3nk1e, Nifty, scar, Snakes<br />
Global Rank: [199](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [54]( ../standings_americas.md)<br />
<br />
Final Rank Value:  513.2<br />
<br />
Final Rank Value (513.2) = Starting Rank Value (529.9) + Head To Head Adjustments (-16.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.231[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.063<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 529.9
- 400 + ( ( 0.063 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 529.9


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
|           29 |     1709 | 2024-05-22 | Limitless        | L   | 0.716      | -            | -                | -                | -         |    -4.07 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           28 |     1714 | 2024-05-22 | Limitless        | L   | 0.716      | -            | -                | -                | -         |    -4.23 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           27 |     1791 | 2024-05-20 | Take Flyte       | L   | 0.703      | -            | -                | -                | -         |    -6.88 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           26 |     1795 | 2024-05-20 | Take Flyte       | W   | 0.702      | 0.477        | 0.002 (0.001)    | 0.249 (0.083)    | 0 (0.000) |    15.65 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           25 |     1954 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.669      | -            | -                | -                | -         |    -4.73 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           24 |     1961 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.669      | -            | -                | -                | -         |    -4.93 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           23 |     2014 | 2024-05-14 | BOSS             | L   | 0.662      | -            | -                | -                | -         |    -3.62 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           22 |     2022 | 2024-05-14 | BOSS             | L   | 0.662      | -            | -                | -                | -         |    -3.74 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           21 |     2157 | 2024-05-09 | Wildcard         | L   | 0.629      | -            | -                | -                | -         |    -1.95 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           20 |     2160 | 2024-05-09 | Wildcard         | L   | 0.629      | -            | -                | -                | -         |    -1.99 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           19 |     2175 | 2024-05-08 | Elevate          | L   | 0.623      | -            | -                | -                | -         |    -1.84 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           18 |     2177 | 2024-05-08 | Elevate          | L   | 0.622      | -            | -                | -                | -         |    -1.87 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           17 |     2840 | 2024-04-10 | Perseverance     | W   | 0.436      | 0.477        | 0.004 (0.001)    | 0.253 (0.053)    | 0 (0.000) |    10.60 | danss, djay, Nifty, scar, Snakes   |
|           16 |     2845 | 2024-04-10 | Perseverance     | L   | 0.436      | -            | -                | -                | -         |    -3.13 | danss, djay, Nifty, scar, Snakes   |
|           15 |     2893 | 2024-04-09 | Nouns            | L   | 0.429      | -            | -                | -                | -         |    -1.42 | danss, djay, Louie, scar, Snakes   |
|           14 |     2897 | 2024-04-09 | Nouns            | L   | 0.429      | -            | -                | -                | -         |    -1.44 | danss, djay, Nifty, scar, Snakes   |
|           13 |     3024 | 2024-04-04 | Party Astronauts | L   | 0.396      | -            | -                | -                | -         |    -1.14 | danss, djay, Nifty, scar, Snakes   |
|           12 |     3031 | 2024-04-04 | Party Astronauts | L   | 0.396      | -            | -                | -                | -         |    -1.16 | danss, djay, Nifty, scar, Snakes   |
|           11 |     3200 | 2024-03-27 | Limitless        | L   | 0.343      | -            | -                | -                | -         |    -3.67 | danss, djay, Nifty, scar, Snakes   |
|           10 |     3206 | 2024-03-27 | Limitless        | L   | 0.343      | -            | -                | -                | -         |    -3.77 | danss, djay, Nifty, scar, Snakes   |
|            9 |     3249 | 2024-03-26 | NRG              | L   | 0.336      | -            | -                | -                | -         |    -1.60 | danss, djay, Nifty, scar, Snakes   |
|            8 |     3253 | 2024-03-26 | NRG              | L   | 0.336      | -            | -                | -                | -         |    -1.62 | danss, djay, Nifty, scar, Snakes   |
|            7 |     3648 | 2024-03-06 | LAG              | L   | 0.203      | -            | -                | -                | -         |    -0.99 | danss, djay, Nifty, scar, Snakes   |
|            6 |     3649 | 2024-03-06 | LAG              | W   | 0.203      | 0.477        | 0.012 (0.001)    | 0.353 (0.034)    | 0 (0.000) |     5.43 | danss, djay, Nifty, scar, Snakes   |
|            5 |     3687 | 2024-03-05 | Mythic           | W   | 0.196      | 0.477        | 0.010 (0.001)    | 0.311 (0.029)    | 0 (0.000) |     4.96 | danss, djay, Nifty, scar, Snakes   |
|            4 |     3689 | 2024-03-05 | Mythic           | W   | 0.196      | 0.477        | 0.010 (0.001)    | 0.311 (0.029)    | 0 (0.000) |     5.01 | danss, djay, Nifty, scar, Snakes   |
|            3 |     3938 | 2024-02-22 | Liquid           | L   | 0.115      | -            | -                | -                | -         |    -0.01 | danss, djay, Nifty, scar, Snakes   |
|            2 |     3941 | 2024-02-22 | Perseverance     | W   | 0.115      | 0.143        | 0.004 (0.000)    | 0.253 (0.004)    | 0 (0.000) |     2.77 | danss, djay, Nifty, scar, Snakes   |
|            1 |     4087 | 2024-02-16 | Rocket           | L   | 0.075      | -            | -                | -                | -         |    -1.31 | danss, djay, Nifty, scar, Snakes   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
