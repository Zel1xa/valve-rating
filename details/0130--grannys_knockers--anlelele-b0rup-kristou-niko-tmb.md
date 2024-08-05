### Roster Details<br />
Team Name: Grannys Knockers<br />
Roster: Anlelele, b0RUP, Kristou, niko, TMB<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [90]( ../standings_europe.md)<br />
<br />
Final Rank Value:  786.9<br />
<br />
Final Rank Value (786.9) = Starting Rank Value (753.1) + Head To Head Adjustments (33.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.327[<sup>2</sup>](#table1)
- Opponent Network: 0.041[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.172<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 753.1
- 400 + ( ( 0.172 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 753.1


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
|           10 |     2319 | 2024-05-08 | Sashi             | L   | 0.605      | -            | -                | -                | -         |    -1.66 | Anlelele, b0RUP, Kristou, niko, TMB |
|            9 |     2343 | 2024-05-07 | Gaimin Gladiators | W   | 0.598      | 0.396        | 0.037 (0.009)    | 0.342 (0.081)    | 0 (0.000) |    14.67 | Anlelele, b0RUP, Kristou, niko, TMB |
|            8 |     2358 | 2024-05-06 | brazylijski luz   | W   | 0.591      | 0.396        | 0.008 (0.002)    | 0.257 (0.060)    | 0 (0.000) |    11.23 | Anlelele, b0RUP, Kristou, niko, TMB |
|            7 |     2434 | 2024-05-02 | Endpoint          | L   | 0.565      | -            | -                | -                | -         |    -5.36 | Anlelele, b0RUP, Kristou, niko, TMB |
|            6 |     2504 | 2024-04-29 | MOUZ NXT          | L   | 0.545      | -            | -                | -                | -         |    -3.08 | b0RUP, Kristou, niko, refrezh, TMB  |
|            5 |     2523 | 2024-04-28 | Nemiga            | W   | 0.538      | 0.435        | 0.316 (0.074)    | 0.722 (0.169)    | 0 (0.000) |    15.41 | b0RUP, Kristou, niko, refrezh, TMB  |
|            4 |     2600 | 2024-04-25 | Nexus             | W   | 0.518      | 0.435        | 0.014 (0.003)    | 0.458 (0.103)    | 0 (0.000) |    10.12 | b0RUP, Kristou, niko, refrezh, TMB  |
|            3 |     2643 | 2024-04-23 | Sangal            | L   | 0.504      | -            | -                | -                | -         |    -1.74 | Anlelele, b0RUP, Kristou, niko, TMB |
|            2 |     2646 | 2024-04-22 | Zero Tenacity     | L   | 0.500      | -            | -                | -                | -         |    -2.16 | b0RUP, Kristou, niko, refrezh, TMB  |
|            1 |     2658 | 2024-04-22 | Permitta          | L   | 0.498      | -            | -                | -                | -         |    -3.69 | b0RUP, Kristou, niko, refrezh, TMB  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,447.78)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
