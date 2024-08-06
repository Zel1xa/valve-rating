### Roster Details<br />
Team Name: Grannys Knockers<br />
Roster: Anlelele, b0RUP, Kristou, niko, TMB<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [90]( ../standings_europe.md)<br />
<br />
Final Rank Value:  786.5<br />
<br />
Final Rank Value (786.5) = Starting Rank Value (752.8) + Head To Head Adjustments (33.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.320[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.041[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.172<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 752.8
- 400 + ( ( 0.172 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 752.8


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
|           10 |     2326 | 2024-05-08 | Sashi             | L   | 0.601      | -            | -                | -                | -         |    -1.65 | Anlelele, b0RUP, Kristou, niko, TMB |
|            9 |     2350 | 2024-05-07 | Gaimin Gladiators | W   | 0.593      | 0.396        | 0.037 (0.009)    | 0.339 (0.080)    | 0 (0.000) |    14.54 | Anlelele, b0RUP, Kristou, niko, TMB |
|            8 |     2365 | 2024-05-06 | brazylijski luz   | W   | 0.586      | 0.396        | 0.008 (0.002)    | 0.256 (0.059)    | 0 (0.000) |    11.13 | Anlelele, b0RUP, Kristou, niko, TMB |
|            7 |     2441 | 2024-05-02 | Endpoint          | L   | 0.561      | -            | -                | -                | -         |    -5.29 | Anlelele, b0RUP, Kristou, niko, TMB |
|            6 |     2511 | 2024-04-29 | MOUZ NXT          | L   | 0.540      | -            | -                | -                | -         |    -3.04 | b0RUP, Kristou, niko, refrezh, TMB  |
|            5 |     2530 | 2024-04-28 | Nemiga            | W   | 0.533      | 0.435        | 0.315 (0.073)    | 0.720 (0.167)    | 0 (0.000) |    15.26 | b0RUP, Kristou, niko, refrezh, TMB  |
|            4 |     2607 | 2024-04-25 | Nexus             | W   | 0.514      | 0.435        | 0.014 (0.003)    | 0.457 (0.102)    | 0 (0.000) |    10.08 | b0RUP, Kristou, niko, refrezh, TMB  |
|            3 |     2650 | 2024-04-23 | Sangal            | L   | 0.499      | -            | -                | -                | -         |    -1.71 | Anlelele, b0RUP, Kristou, niko, TMB |
|            2 |     2653 | 2024-04-22 | Zero Tenacity     | L   | 0.495      | -            | -                | -                | -         |    -2.13 | b0RUP, Kristou, niko, refrezh, TMB  |
|            1 |     2665 | 2024-04-22 | Permitta          | L   | 0.493      | -            | -                | -                | -         |    -3.49 | b0RUP, Kristou, niko, refrezh, TMB  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,428.89)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
