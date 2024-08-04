### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, MarKE, phzy, Sonic, susp<br />
Global Rank: [71](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [20]( ../standings_americas.md)<br />
<br />
Final Rank Value:  951.8<br />
<br />
Final Rank Value (951.8) = Starting Rank Value (813.2) + Head To Head Adjustments (138.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.314[<sup>2</sup>](#table1)
- Opponent Network: 0.151[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 813.2
- 400 + ( ( 0.202 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 813.2


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
|           12 |       27 | 2024-08-03 | Take Flyte       | W   | 1.000      | 0.303        | -                | 0.240 (0.073)    | 0 (0.000) |     5.26 | JBa, MarKE, phzy, Sonic, susp     |
|           11 |      135 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.521 (0.248)    | 0 (0.000) |    13.84 | JBa, phzy, Sonic, stanislaw, susp |
|           10 |      141 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.521 (0.248)    | 0 (0.000) |    15.11 | JBa, phzy, Sonic, stanislaw, susp |
|            9 |      475 | 2024-07-21 | NRG              | W   | 1.000      | 0.303        | 0.020 (0.006)    | 0.521 (0.158)    | 0 (0.000) |    20.08 | JBa, phzy, Sonic, stanislaw, susp |
|            8 |      476 | 2024-07-21 | Elevate          | W   | 1.000      | 0.303        | 0.027 (0.008)    | 0.521 (0.158)    | 0 (0.000) |    18.59 | JBa, phzy, Sonic, stanislaw, susp |
|            7 |      501 | 2024-07-20 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.531 (0.161)    | 0 (0.000) |    20.68 | JBa, phzy, Sonic, stanislaw, susp |
|            6 |      575 | 2024-07-18 | Take Flyte       | W   | 1.000      | 0.477        | 0.002 (0.001)    | 0.240 (0.115)    | 0 (0.000) |     9.04 | JBa, phzy, Sonic, stanislaw, susp |
|            5 |      580 | 2024-07-18 | Take Flyte       | W   | 1.000      | 0.477        | 0.002 (0.001)    | 0.240 (0.115)    | 0 (0.000) |     9.73 | JBa, phzy, Sonic, stanislaw, susp |
|            4 |      645 | 2024-07-17 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.134 (0.064)    | 0 (0.000) |    10.35 | JBa, phzy, Sonic, stanislaw, susp |
|            3 |      648 | 2024-07-17 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | -                | 0 (0.000) |    11.20 | JBa, phzy, Sonic, stanislaw, susp |
|            2 |      704 | 2024-07-16 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.353 (0.168)    | -         |    18.02 | JBa, phzy, Sonic, stanislaw, susp |
|            1 |      710 | 2024-07-16 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -13.28 | JBa, phzy, Sonic, stanislaw, susp |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,000.00)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
