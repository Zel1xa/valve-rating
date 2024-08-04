### Roster Details<br />
Team Name: Illuminar<br />
Roster: ANeraX, b1elany, phr, splawik, ultimate<br />
Global Rank: [193](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [121]( ../standings_europe.md)<br />
<br />
Final Rank Value:  568.7<br />
<br />
Final Rank Value (568.7) = Starting Rank Value (521.5) + Head To Head Adjustments (47.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.059<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 521.5
- 400 + ( ( 0.059 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 521.5


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
|           10 |     1612 | 2024-06-01 | WOPA          | W   | 0.771      | 0.143        | 0.001 (0.000)    | 0.127 (0.014)    | 0 (0.000) |    13.88 | ANeraX, b1elany, phr, splawik, ultimate |
|            9 |     2524 | 2024-04-27 | EYEBALLERS    | L   | 0.538      | -            | -                | -                | -         |    -2.28 | ANeraX, Furlan, keis, phr, ultimate     |
|            8 |     2550 | 2024-04-26 | Zero Tenacity | L   | 0.531      | -            | -                | -                | -         |    -1.02 | ANeraX, Furlan, keis, phr, ultimate     |
|            7 |     2614 | 2024-04-23 | Nexus         | W   | 0.512      | 0.435        | 0.014 (0.003)    | 0.465 (0.103)    | 0 (0.000) |    13.62 | ANeraX, Furlan, keis, phr, ultimate     |
|            6 |     2640 | 2024-04-21 | BLEED         | L   | 0.500      | -            | -                | -                | -         |    -0.92 | ANeraX, Furlan, keis, phr, ultimate     |
|            5 |     2679 | 2024-04-20 | Viperio       | W   | 0.492      | 0.143        | 0.001 (0.000)    | 0.037 (0.003)    | 0 (0.000) |     9.78 | ANeraX, Furlan, keis, phr, ultimate     |
|            4 |     2753 | 2024-04-18 | Portugal      | W   | 0.480      | 0.143        | 0.003 (0.000)    | 0.120 (0.008)    | 0 (0.000) |    10.86 | ANeraX, Furlan, keis, phr, ultimate     |
|            3 |     2799 | 2024-04-17 | Secret        | W   | 0.474      | 0.143        | 0.000 (0.000)    | 0.058 (0.004)    | 0 (0.000) |     8.09 | ANeraX, Furlan, keis, phr, ultimate     |
|            2 |     3207 | 2024-04-03 | PGE Turow     | L   | 0.379      | -            | -                | -                | -         |    -3.80 | ANeraX, Furlan, keis, phr, ultimate     |
|            1 |     3249 | 2024-04-02 | UNiTY         | L   | 0.372      | -            | -                | -                | -         |    -0.92 | ANeraX, Furlan, keis, phr, ultimate     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />