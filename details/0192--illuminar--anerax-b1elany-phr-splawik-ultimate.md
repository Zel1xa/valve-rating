### Roster Details<br />
Team Name: Illuminar<br />
Roster: ANeraX, b1elany, phr, splawik, ultimate<br />
Global Rank: [192](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [120]( ../standings_europe.md)<br />
<br />
Final Rank Value:  572.6<br />
<br />
Final Rank Value (572.6) = Starting Rank Value (523.6) + Head To Head Adjustments (49.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.060<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 523.6
- 400 + ( ( 0.060 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 523.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     1519 | 2024-06-01 | WOPA          | W   | 0.791      | 0.143        | 0.001 (0.000)    | 0.127 (0.014)    | 0 (0.000) |    14.16 | ANeraX, b1elany, phr, splawik, ultimate |
|            9 |     2474 | 2024-04-27 | EYEBALLERS    | L   | 0.558      | -            | -                | -                | -         |    -2.36 | ANeraX, Furlan, keis, phr, ultimate     |
|            8 |     2499 | 2024-04-26 | Zero Tenacity | L   | 0.551      | -            | -                | -                | -         |    -1.10 | ANeraX, Furlan, keis, phr, ultimate     |
|            7 |     2565 | 2024-04-23 | Nexus         | W   | 0.532      | 0.435        | 0.014 (0.003)    | 0.504 (0.116)    | 0 (0.000) |    14.16 | ANeraX, Furlan, keis, phr, ultimate     |
|            6 |     2593 | 2024-04-21 | BLEED         | L   | 0.520      | -            | -                | -                | -         |    -0.95 | ANeraX, Furlan, keis, phr, ultimate     |
|            5 |     2634 | 2024-04-20 | Viperio       | W   | 0.512      | 0.143        | 0.002 (0.000)    | 0.038 (0.003)    | 0 (0.000) |    10.18 | ANeraX, Furlan, keis, phr, ultimate     |
|            4 |     2710 | 2024-04-18 | Portugal      | W   | 0.500      | 0.143        | 0.003 (0.000)    | 0.122 (0.009)    | 0 (0.000) |    11.40 | ANeraX, Furlan, keis, phr, ultimate     |
|            3 |     2757 | 2024-04-17 | Secret        | W   | 0.494      | 0.143        | 0.000 (0.000)    | 0.060 (0.004)    | 0 (0.000) |     8.45 | ANeraX, Furlan, keis, phr, ultimate     |
|            2 |     3173 | 2024-04-03 | PGE Turow     | L   | 0.399      | -            | -                | -                | -         |    -3.93 | ANeraX, Furlan, keis, phr, ultimate     |
|            1 |     3217 | 2024-04-02 | UNiTY         | L   | 0.392      | -            | -                | -                | -         |    -0.99 | ANeraX, Furlan, keis, phr, ultimate     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
