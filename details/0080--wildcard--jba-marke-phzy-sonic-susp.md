### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, MarKE, phzy, Sonic, susp<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [20]( ../standings_americas.md)<br />
<br />
Final Rank Value:  951.8<br />
<br />
Final Rank Value (951.8) = Starting Rank Value (813.8) + Head To Head Adjustments (138.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.313[<sup>2</sup>](#table1)
- Opponent Network: 0.147[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 813.8
- 400 + ( ( 0.201 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 813.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |       73 | 2024-08-03 | Take Flyte       | W   | 1.000      | 0.303        | -                | 0.231 (0.070)    | 0 (0.000) |     5.26 | JBa, MarKE, phzy, Sonic, susp     |
|           11 |      181 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.501 (0.239)    | 0 (0.000) |    13.79 | JBa, phzy, Sonic, stanislaw, susp |
|           10 |      187 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.501 (0.239)    | 0 (0.000) |    15.05 | JBa, phzy, Sonic, stanislaw, susp |
|            9 |      521 | 2024-07-21 | NRG              | W   | 1.000      | 0.303        | 0.020 (0.006)    | 0.502 (0.152)    | 0 (0.000) |    20.02 | JBa, phzy, Sonic, stanislaw, susp |
|            8 |      522 | 2024-07-21 | Elevate          | W   | 1.000      | 0.303        | 0.027 (0.008)    | 0.501 (0.152)    | 0 (0.000) |    18.54 | JBa, phzy, Sonic, stanislaw, susp |
|            7 |      547 | 2024-07-20 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.510 (0.155)    | 0 (0.000) |    20.59 | JBa, phzy, Sonic, stanislaw, susp |
|            6 |      621 | 2024-07-18 | Take Flyte       | W   | 1.000      | 0.477        | 0.002 (0.001)    | 0.231 (0.110)    | 0 (0.000) |     9.03 | JBa, phzy, Sonic, stanislaw, susp |
|            5 |      626 | 2024-07-18 | Take Flyte       | W   | 1.000      | 0.477        | 0.002 (0.001)    | 0.231 (0.110)    | 0 (0.000) |     9.72 | JBa, phzy, Sonic, stanislaw, susp |
|            4 |      691 | 2024-07-17 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.128 (0.061)    | 0 (0.000) |    10.31 | JBa, phzy, Sonic, stanislaw, susp |
|            3 |      694 | 2024-07-17 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | -                | 0 (0.000) |    11.16 | JBa, phzy, Sonic, stanislaw, susp |
|            2 |      750 | 2024-07-16 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.376 (0.179)    | -         |    17.94 | JBa, phzy, Sonic, stanislaw, susp |
|            1 |      756 | 2024-07-16 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -13.36 | JBa, phzy, Sonic, stanislaw, susp |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,000.00)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
