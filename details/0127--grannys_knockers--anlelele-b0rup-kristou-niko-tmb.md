### Roster Details<br />
Team Name: Grannys Knockers<br />
Roster: Anlelele, b0RUP, Kristou, niko, TMB<br />
Global Rank: [127](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [88]( ../standings_europe.md)<br />
<br />
Final Rank Value:  787.2<br />
<br />
Final Rank Value (787.2) = Starting Rank Value (753.2) + Head To Head Adjustments (33.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.328[<sup>2</sup>](#table1)
- Opponent Network: 0.042[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.173<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 753.2
- 400 + ( ( 0.173 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 753.2


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
|           10 |     2298 | 2024-05-08 | Sashi             | L   | 0.610      | -            | -                | -                | -         |    -1.67 | Anlelele, b0RUP, Kristou, niko, TMB |
|            9 |     2322 | 2024-05-07 | Gaimin Gladiators | W   | 0.602      | 0.396        | 0.038 (0.009)    | 0.349 (0.083)    | 0 (0.000) |    14.81 | Anlelele, b0RUP, Kristou, niko, TMB |
|            8 |     2337 | 2024-05-06 | brazylijski luz   | W   | 0.595      | 0.396        | 0.008 (0.002)    | 0.261 (0.062)    | 0 (0.000) |    11.33 | Anlelele, b0RUP, Kristou, niko, TMB |
|            7 |     2413 | 2024-05-02 | Endpoint          | L   | 0.570      | -            | -                | -                | -         |    -5.41 | Anlelele, b0RUP, Kristou, niko, TMB |
|            6 |     2483 | 2024-04-29 | MOUZ NXT          | L   | 0.549      | -            | -                | -                | -         |    -3.14 | b0RUP, Kristou, niko, refrezh, TMB  |
|            5 |     2502 | 2024-04-28 | Nemiga            | W   | 0.542      | 0.435        | 0.317 (0.075)    | 0.733 (0.173)    | 0 (0.000) |    15.54 | b0RUP, Kristou, niko, refrezh, TMB  |
|            4 |     2579 | 2024-04-25 | Nexus             | W   | 0.523      | 0.435        | 0.014 (0.003)    | 0.465 (0.106)    | 0 (0.000) |    10.19 | b0RUP, Kristou, niko, refrezh, TMB  |
|            3 |     2622 | 2024-04-23 | Sangal            | L   | 0.509      | -            | -                | -                | -         |    -1.77 | Anlelele, b0RUP, Kristou, niko, TMB |
|            2 |     2625 | 2024-04-22 | Zero Tenacity     | L   | 0.504      | -            | -                | -                | -         |    -2.21 | b0RUP, Kristou, niko, refrezh, TMB  |
|            1 |     2637 | 2024-04-22 | Permitta          | L   | 0.502      | -            | -                | -                | -         |    -3.73 | b0RUP, Kristou, niko, refrezh, TMB  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,465.56)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
