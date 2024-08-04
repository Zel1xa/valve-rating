### Roster Details<br />
Team Name: Grannys Knockers<br />
Roster: Anlelele, b0RUP, Kristou, niko, TMB<br />
Global Rank: [125](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
<br />
Final Rank Value:  786.9<br />
<br />
Final Rank Value (786.9) = Starting Rank Value (753.0) + Head To Head Adjustments (33.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.328[<sup>2</sup>](#table1)
- Opponent Network: 0.042[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.173<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 753.0
- 400 + ( ( 0.173 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 753.0


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
|           10 |     2262 | 2024-05-08 | Sashi             | L   | 0.614      | -            | -                | -                | -         |    -1.70 | Anlelele, b0RUP, Kristou, niko, TMB |
|            9 |     2286 | 2024-05-07 | Gaimin Gladiators | W   | 0.606      | 0.396        | 0.038 (0.009)    | 0.351 (0.084)    | 0 (0.000) |    14.89 | Anlelele, b0RUP, Kristou, niko, TMB |
|            8 |     2301 | 2024-05-06 | brazylijski luz   | W   | 0.599      | 0.396        | 0.008 (0.002)    | 0.262 (0.062)    | 0 (0.000) |    11.38 | Anlelele, b0RUP, Kristou, niko, TMB |
|            7 |     2377 | 2024-05-02 | Endpoint          | L   | 0.574      | -            | -                | -                | -         |    -5.45 | Anlelele, b0RUP, Kristou, niko, TMB |
|            6 |     2447 | 2024-04-29 | MOUZ NXT          | L   | 0.553      | -            | -                | -                | -         |    -3.18 | b0RUP, Kristou, niko, refrezh, TMB  |
|            5 |     2466 | 2024-04-28 | Nemiga            | W   | 0.547      | 0.435        | 0.317 (0.075)    | 0.695 (0.165)    | 0 (0.000) |    15.51 | b0RUP, Kristou, niko, refrezh, TMB  |
|            4 |     2543 | 2024-04-25 | Nexus             | W   | 0.527      | 0.435        | 0.014 (0.003)    | 0.465 (0.107)    | 0 (0.000) |    10.26 | b0RUP, Kristou, niko, refrezh, TMB  |
|            3 |     2586 | 2024-04-23 | Sangal            | L   | 0.513      | -            | -                | -                | -         |    -1.82 | Anlelele, b0RUP, Kristou, niko, TMB |
|            2 |     2589 | 2024-04-22 | Zero Tenacity     | L   | 0.509      | -            | -                | -                | -         |    -2.25 | b0RUP, Kristou, niko, refrezh, TMB  |
|            1 |     2601 | 2024-04-22 | Permitta          | L   | 0.506      | -            | -                | -                | -         |    -3.77 | b0RUP, Kristou, niko, refrezh, TMB  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,482.22)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
