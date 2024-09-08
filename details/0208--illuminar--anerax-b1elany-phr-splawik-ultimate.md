### Roster Details<br />
Team Name: Illuminar<br />
Roster: ANeraX, b1elany, phr, splawik, ultimate<br />
Global Rank: [208](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [130]( ../standings_europe.md)<br />
<br />
Final Rank Value:  528.8<br />
<br />
Final Rank Value (528.8) = Starting Rank Value (502.0) + Head To Head Adjustments (26.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.204[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.053<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 502.0
- 400 + ( ( 0.053 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 502.0


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
|           10 |     2779 | 2024-06-01 | WOPA          | W   | 0.539      | 0.143        | 0.001 (0.000)    | 0.119 (0.009)    | 0 (0.000) |    11.04 | ANeraX, b1elany, phr, splawik, ultimate |
|            9 |     3691 | 2024-04-27 | EYEBALLERS    | L   | 0.306      | -            | -                | -                | -         |    -1.59 | ANeraX, Furlan, keis, phr, ultimate     |
|            8 |     3717 | 2024-04-26 | Zero Tenacity | L   | 0.299      | -            | -                | -                | -         |    -0.49 | ANeraX, Furlan, keis, phr, ultimate     |
|            7 |     3781 | 2024-04-23 | Nexus         | W   | 0.279      | 0.435        | 0.010 (0.001)    | 0.432 (0.052)    | 0 (0.000) |     7.37 | ANeraX, Furlan, keis, phr, ultimate     |
|            6 |     3807 | 2024-04-21 | BLEED         | L   | 0.268      | -            | -                | -                | -         |    -0.96 | ANeraX, Furlan, keis, phr, ultimate     |
|            5 |     3846 | 2024-04-20 | Viperio       | W   | 0.259      | 0.143        | 0.001 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     5.13 | ANeraX, Furlan, keis, phr, ultimate     |
|            4 |     3920 | 2024-04-18 | Portugal      | W   | 0.248      | 0.143        | 0.001 (0.000)    | 0.068 (0.002)    | 0 (0.000) |     5.05 | ANeraX, Furlan, keis, phr, ultimate     |
|            3 |     3966 | 2024-04-17 | Secret        | W   | 0.241      | 0.143        | 0.000 (0.000)    | 0.024 (0.001)    | 0 (0.000) |     3.98 | ANeraX, Furlan, keis, phr, ultimate     |
|            2 |     4374 | 2024-04-03 | PGE Turow     | L   | 0.147      | -            | -                | -                | -         |    -2.28 | ANeraX, Furlan, keis, phr, ultimate     |
|            1 |     4416 | 2024-04-02 | UNiTY         | L   | 0.139      | -            | -                | -                | -         |    -0.44 | ANeraX, Furlan, keis, phr, ultimate     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
