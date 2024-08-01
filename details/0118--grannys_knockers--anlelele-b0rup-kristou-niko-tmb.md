### Roster Details<br />
Team Name: Grannys Knockers<br />
Roster: Anlelele, b0RUP, Kristou, niko, TMB<br />
Global Rank: [118](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [85]( ../standings_europe.md)<br />
<br />
Final Rank Value:  813.6<br />
<br />
Final Rank Value (813.6) = Starting Rank Value (767.3) + Head To Head Adjustments (46.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.322[<sup>1</sup>](#table2)
- Bounty Collected: 0.334[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.179<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 767.3
- 400 + ( ( 0.179 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 767.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     2242 | 2024-05-08 | Sashi             | L   | 0.632      | -            | -                | -                | -         |    -1.94 | Anlelele, b0RUP, Kristou, niko, TMB |
|           10 |     2266 | 2024-05-07 | Gaimin Gladiators | W   | 0.624      | 0.396        | 0.040 (0.010)    | 0.360 (0.089)    | 0 (0.000) |    15.10 | Anlelele, b0RUP, Kristou, niko, TMB |
|            9 |     2281 | 2024-05-06 | brazylijski luz   | W   | 0.617      | 0.396        | 0.008 (0.002)    | 0.308 (0.075)    | 0 (0.000) |    11.40 | Anlelele, b0RUP, Kristou, niko, TMB |
|            8 |     2358 | 2024-05-02 | Endpoint          | L   | 0.592      | -            | -                | -                | -         |    -5.77 | Anlelele, b0RUP, Kristou, niko, TMB |
|            7 |     2391 | 2024-05-01 | ALTERNATE aTTaX   | W   | 0.584      | 0.384        | 0.032 (0.007)    | 0.563 (0.126)    | 0 (0.000) |    13.34 | Anlelele, b0RUP, Kristou, niko, TMB |
|            6 |     2430 | 2024-04-29 | MOUZ NXT          | L   | 0.571      | -            | -                | -                | -         |    -3.26 | b0RUP, Kristou, niko, refrezh, TMB  |
|            5 |     2449 | 2024-04-28 | Nemiga            | W   | 0.564      | 0.435        | 0.324 (0.079)    | 0.697 (0.171)    | 0 (0.000) |    15.89 | b0RUP, Kristou, niko, refrezh, TMB  |
|            4 |     2526 | 2024-04-25 | Nexus             | W   | 0.545      | 0.435        | 0.014 (0.003)    | 0.504 (0.119)    | 0 (0.000) |    10.43 | b0RUP, Kristou, niko, refrezh, TMB  |
|            3 |     2571 | 2024-04-23 | Sangal            | L   | 0.531      | -            | -                | -                | -         |    -2.07 | Anlelele, b0RUP, Kristou, niko, TMB |
|            2 |     2575 | 2024-04-22 | Zero Tenacity     | L   | 0.526      | -            | -                | -                | -         |    -2.49 | b0RUP, Kristou, niko, refrezh, TMB  |
|            1 |     2587 | 2024-04-22 | Permitta          | L   | 0.524      | -            | -                | -                | -         |    -4.25 | b0RUP, Kristou, niko, refrezh, TMB  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,553.33)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
