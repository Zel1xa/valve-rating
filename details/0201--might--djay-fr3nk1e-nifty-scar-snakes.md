### Roster Details<br />
Team Name: MIGHT<br />
Roster: djay, Fr3nk1e, Nifty, scar, Snakes<br />
Global Rank: [201](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [56]( ../standings_americas.md)<br />
<br />
Final Rank Value:  512.1<br />
<br />
Final Rank Value (512.1) = Starting Rank Value (528.8) + Head To Head Adjustments (-16.6)<br />

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
|           29 |     1837 | 2024-05-22 | Limitless        | L   | 0.700      | -            | -                | -                | -         |    -4.04 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           28 |     1842 | 2024-05-22 | Limitless        | L   | 0.700      | -            | -                | -                | -         |    -4.19 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           27 |     1919 | 2024-05-20 | Take Flyte       | L   | 0.687      | -            | -                | -                | -         |    -6.67 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           26 |     1923 | 2024-05-20 | Take Flyte       | W   | 0.687      | 0.477        | 0.002 (0.001)    | 0.236 (0.077)    | 0 (0.000) |    15.36 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           25 |     2083 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.654      | -            | -                | -                | -         |    -4.51 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           24 |     2090 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.653      | -            | -                | -                | -         |    -4.70 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           23 |     2143 | 2024-05-14 | BOSS             | L   | 0.647      | -            | -                | -                | -         |    -3.50 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           22 |     2151 | 2024-05-14 | BOSS             | L   | 0.646      | -            | -                | -                | -         |    -3.62 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           21 |     2286 | 2024-05-09 | Wildcard         | L   | 0.613      | -            | -                | -                | -         |    -2.17 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           20 |     2289 | 2024-05-09 | Wildcard         | L   | 0.613      | -            | -                | -                | -         |    -2.22 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           19 |     2304 | 2024-05-08 | Elevate          | L   | 0.607      | -            | -                | -                | -         |    -1.46 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           18 |     2306 | 2024-05-08 | Elevate          | L   | 0.607      | -            | -                | -                | -         |    -1.48 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           17 |     2971 | 2024-04-10 | Phoenix          | W   | 0.420      | 0.477        | 0.004 (0.001)    | 0.277 (0.056)    | 0 (0.000) |    10.21 | danss, djay, Nifty, scar, Snakes   |
|           16 |     2976 | 2024-04-10 | Phoenix          | L   | 0.420      | -            | -                | -                | -         |    -3.03 | danss, djay, Nifty, scar, Snakes   |
|           15 |     3024 | 2024-04-09 | Nouns            | L   | 0.414      | -            | -                | -                | -         |    -1.34 | danss, djay, Louie, scar, Snakes   |
|           14 |     3028 | 2024-04-09 | Nouns            | L   | 0.413      | -            | -                | -                | -         |    -1.36 | danss, djay, Nifty, scar, Snakes   |
|           13 |     3155 | 2024-04-04 | Party Astronauts | L   | 0.380      | -            | -                | -                | -         |    -1.15 | danss, djay, Nifty, scar, Snakes   |
|           12 |     3162 | 2024-04-04 | Party Astronauts | L   | 0.380      | -            | -                | -                | -         |    -1.16 | danss, djay, Nifty, scar, Snakes   |
|           11 |     3331 | 2024-03-27 | Limitless        | L   | 0.327      | -            | -                | -                | -         |    -3.48 | danss, djay, Nifty, scar, Snakes   |
|           10 |     3337 | 2024-03-27 | Limitless        | L   | 0.327      | -            | -                | -                | -         |    -3.57 | danss, djay, Nifty, scar, Snakes   |
|            9 |     3382 | 2024-03-26 | NRG              | L   | 0.321      | -            | -                | -                | -         |    -1.52 | danss, djay, Nifty, scar, Snakes   |
|            8 |     3387 | 2024-03-26 | NRG              | L   | 0.320      | -            | -                | -                | -         |    -1.54 | danss, djay, Nifty, scar, Snakes   |
|            7 |     3787 | 2024-03-06 | LAG              | L   | 0.187      | -            | -                | -                | -         |    -0.97 | danss, djay, Nifty, scar, Snakes   |
|            6 |     3788 | 2024-03-06 | LAG              | W   | 0.187      | 0.477        | 0.012 (0.001)    | 0.385 (0.034)    | 0 (0.000) |     4.96 | danss, djay, Nifty, scar, Snakes   |
|            5 |     3826 | 2024-03-05 | Mythic           | W   | 0.181      | 0.477        | 0.010 (0.001)    | 0.292 (0.025)    | 0 (0.000) |     4.57 | danss, djay, Nifty, scar, Snakes   |
|            4 |     3828 | 2024-03-05 | Mythic           | W   | 0.180      | 0.477        | 0.010 (0.001)    | 0.292 (0.025)    | 0 (0.000) |     4.61 | danss, djay, Nifty, scar, Snakes   |
|            3 |     4077 | 2024-02-22 | Liquid           | L   | 0.100      | -            | -                | -                | -         |    -0.01 | danss, djay, Nifty, scar, Snakes   |
|            2 |     4080 | 2024-02-22 | Phoenix          | W   | 0.099      | 0.143        | 0.004 (0.000)    | 0.277 (0.004)    | 0 (0.000) |     2.39 | danss, djay, Nifty, scar, Snakes   |
|            1 |     4227 | 2024-02-16 | Rocket           | L   | 0.059      | -            | -                | -                | -         |    -1.04 | danss, djay, Nifty, scar, Snakes   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
