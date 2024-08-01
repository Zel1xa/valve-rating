### Roster Details<br />
Team Name: Grannys Knockers<br />
Roster: Anlelele, b0RUP, Kristou, niko, TMB<br />
Global Rank: [118](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [85]( ../standings_europe.md)<br />
<br />
Final Rank Value:  814.5<br />
<br />
Final Rank Value (814.5) = Starting Rank Value (767.9) + Head To Head Adjustments (46.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.322[<sup>1</sup>](#table2)
- Bounty Collected: 0.334[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.179<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 767.9
- 400 + ( ( 0.179 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 767.9


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
|           11 |     2236 | 2024-05-08 | Sashi             | L   | 0.633      | -            | -                | -                | -         |    -1.95 | Anlelele, b0RUP, Kristou, niko, TMB |
|           10 |     2260 | 2024-05-07 | Gaimin Gladiators | W   | 0.626      | 0.396        | 0.040 (0.010)    | 0.361 (0.089)    | 0 (0.000) |    15.15 | Anlelele, b0RUP, Kristou, niko, TMB |
|            9 |     2275 | 2024-05-06 | brazylijski luz   | W   | 0.619      | 0.396        | 0.008 (0.002)    | 0.309 (0.076)    | 0 (0.000) |    11.43 | Anlelele, b0RUP, Kristou, niko, TMB |
|            8 |     2352 | 2024-05-02 | Endpoint          | L   | 0.593      | -            | -                | -                | -         |    -5.78 | Anlelele, b0RUP, Kristou, niko, TMB |
|            7 |     2385 | 2024-05-01 | ALTERNATE aTTaX   | W   | 0.586      | 0.384        | 0.032 (0.007)    | 0.564 (0.127)    | 0 (0.000) |    13.38 | Anlelele, b0RUP, Kristou, niko, TMB |
|            6 |     2424 | 2024-04-29 | MOUZ NXT          | L   | 0.573      | -            | -                | -                | -         |    -3.27 | b0RUP, Kristou, niko, refrezh, TMB  |
|            5 |     2443 | 2024-04-28 | Nemiga            | W   | 0.566      | 0.435        | 0.324 (0.080)    | 0.697 (0.172)    | 0 (0.000) |    15.95 | b0RUP, Kristou, niko, refrezh, TMB  |
|            4 |     2520 | 2024-04-25 | Nexus             | W   | 0.546      | 0.435        | 0.014 (0.003)    | 0.504 (0.120)    | 0 (0.000) |    10.46 | b0RUP, Kristou, niko, refrezh, TMB  |
|            3 |     2565 | 2024-04-23 | Sangal            | L   | 0.532      | -            | -                | -                | -         |    -2.08 | Anlelele, b0RUP, Kristou, niko, TMB |
|            2 |     2569 | 2024-04-22 | Zero Tenacity     | L   | 0.528      | -            | -                | -                | -         |    -2.50 | b0RUP, Kristou, niko, refrezh, TMB  |
|            1 |     2581 | 2024-04-22 | Permitta          | L   | 0.526      | -            | -                | -                | -         |    -4.22 | b0RUP, Kristou, niko, refrezh, TMB  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,560.00)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
