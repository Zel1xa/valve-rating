### Roster Details<br />
Team Name: Grannys Knockers<br />
Roster: Anlelele, b0RUP, Kristou, niko, TMB<br />
Global Rank: [131](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [91]( ../standings_europe.md)<br />
<br />
Final Rank Value:  786.8<br />
<br />
Final Rank Value (786.8) = Starting Rank Value (753.0) + Head To Head Adjustments (33.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.327[<sup>2</sup>](#table1)
- Opponent Network: 0.041[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.172<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 753.0
- 400 + ( ( 0.172 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 753.0


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
|           10 |     2322 | 2024-05-08 | Sashi             | L   | 0.603      | -            | -                | -                | -         |    -1.65 | Anlelele, b0RUP, Kristou, niko, TMB |
|            9 |     2346 | 2024-05-07 | Gaimin Gladiators | W   | 0.595      | 0.396        | 0.037 (0.009)    | 0.340 (0.080)    | 0 (0.000) |    14.61 | Anlelele, b0RUP, Kristou, niko, TMB |
|            8 |     2361 | 2024-05-06 | brazylijski luz   | W   | 0.589      | 0.396        | 0.008 (0.002)    | 0.256 (0.060)    | 0 (0.000) |    11.18 | Anlelele, b0RUP, Kristou, niko, TMB |
|            7 |     2437 | 2024-05-02 | Endpoint          | L   | 0.563      | -            | -                | -                | -         |    -5.33 | Anlelele, b0RUP, Kristou, niko, TMB |
|            6 |     2507 | 2024-04-29 | MOUZ NXT          | L   | 0.542      | -            | -                | -                | -         |    -3.06 | b0RUP, Kristou, niko, refrezh, TMB  |
|            5 |     2526 | 2024-04-28 | Nemiga            | W   | 0.536      | 0.435        | 0.315 (0.073)    | 0.721 (0.168)    | 0 (0.000) |    15.34 | b0RUP, Kristou, niko, refrezh, TMB  |
|            4 |     2603 | 2024-04-25 | Nexus             | W   | 0.516      | 0.435        | 0.014 (0.003)    | 0.457 (0.103)    | 0 (0.000) |    10.09 | b0RUP, Kristou, niko, refrezh, TMB  |
|            3 |     2646 | 2024-04-23 | Sangal            | L   | 0.502      | -            | -                | -                | -         |    -1.73 | Anlelele, b0RUP, Kristou, niko, TMB |
|            2 |     2649 | 2024-04-22 | Zero Tenacity     | L   | 0.498      | -            | -                | -                | -         |    -2.15 | b0RUP, Kristou, niko, refrezh, TMB  |
|            1 |     2661 | 2024-04-22 | Permitta          | L   | 0.496      | -            | -                | -                | -         |    -3.51 | b0RUP, Kristou, niko, refrezh, TMB  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,438.89)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
