### Roster Details<br />
Team Name: Grannys Knockers<br />
Roster: Anlelele, b0RUP, Kristou, niko, TMB<br />
Global Rank: [123](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [86]( ../standings_europe.md)<br />
<br />
Final Rank Value:  794.2<br />
<br />
Final Rank Value (794.2) = Starting Rank Value (759.1) + Head To Head Adjustments (35.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.322[<sup>1</sup>](#table2)
- Bounty Collected: 0.331[<sup>2</sup>](#table1)
- Opponent Network: 0.044[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 759.1
- 400 + ( ( 0.174 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 759.1


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
|           10 |     2145 | 2024-05-08 | Sashi             | L   | 0.638      | -            | -                | -                | -         |    -1.72 | Anlelele, b0RUP, Kristou, niko, TMB |
|            9 |     2169 | 2024-05-07 | Gaimin Gladiators | W   | 0.630      | 0.396        | 0.040 (0.010)    | 0.363 (0.091)    | 0 (0.000) |    15.68 | Anlelele, b0RUP, Kristou, niko, TMB |
|            8 |     2184 | 2024-05-06 | brazylijski luz   | W   | 0.623      | 0.396        | 0.008 (0.002)    | 0.264 (0.065)    | 0 (0.000) |    11.86 | Anlelele, b0RUP, Kristou, niko, TMB |
|            7 |     2260 | 2024-05-02 | Endpoint          | L   | 0.598      | -            | -                | -                | -         |    -5.67 | Anlelele, b0RUP, Kristou, niko, TMB |
|            6 |     2330 | 2024-04-29 | MOUZ NXT          | L   | 0.577      | -            | -                | -                | -         |    -3.37 | b0RUP, Kristou, niko, refrezh, TMB  |
|            5 |     2349 | 2024-04-28 | Nemiga            | W   | 0.570      | 0.435        | 0.322 (0.080)    | 0.698 (0.173)    | 0 (0.000) |    16.26 | b0RUP, Kristou, niko, refrezh, TMB  |
|            4 |     2426 | 2024-04-25 | Nexus             | W   | 0.551      | 0.435        | 0.014 (0.003)    | 0.465 (0.111)    | 0 (0.000) |    10.71 | b0RUP, Kristou, niko, refrezh, TMB  |
|            3 |     2469 | 2024-04-23 | Sangal            | L   | 0.537      | -            | -                | -                | -         |    -2.00 | Anlelele, b0RUP, Kristou, niko, TMB |
|            2 |     2472 | 2024-04-22 | Zero Tenacity     | L   | 0.532      | -            | -                | -                | -         |    -2.38 | b0RUP, Kristou, niko, refrezh, TMB  |
|            1 |     2484 | 2024-04-22 | Permitta          | L   | 0.530      | -            | -                | -                | -         |    -4.20 | b0RUP, Kristou, niko, refrezh, TMB  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,577.35)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
