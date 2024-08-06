### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, MarKE, phzy, Sonic, susp<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [20]( ../standings_americas.md)<br />
<br />
Final Rank Value:  952.4<br />
<br />
Final Rank Value (952.4) = Starting Rank Value (814.5) + Head To Head Adjustments (138.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.313[<sup>2</sup>](#table1)
- Opponent Network: 0.150[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 814.5
- 400 + ( ( 0.202 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 814.5


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
|           12 |       59 | 2024-08-03 | Take Flyte       | W   | 1.000      | 0.303        | -                | 0.236 (0.072)    | 0 (0.000) |     5.25 | JBa, MarKE, phzy, Sonic, susp     |
|           11 |      167 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.512 (0.244)    | 0 (0.000) |    13.79 | JBa, phzy, Sonic, stanislaw, susp |
|           10 |      173 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.512 (0.244)    | 0 (0.000) |    15.05 | JBa, phzy, Sonic, stanislaw, susp |
|            9 |      507 | 2024-07-21 | NRG              | W   | 1.000      | 0.303        | 0.020 (0.006)    | 0.513 (0.155)    | 0 (0.000) |    20.02 | JBa, phzy, Sonic, stanislaw, susp |
|            8 |      508 | 2024-07-21 | Elevate          | W   | 1.000      | 0.303        | 0.027 (0.008)    | 0.512 (0.155)    | 0 (0.000) |    18.53 | JBa, phzy, Sonic, stanislaw, susp |
|            7 |      533 | 2024-07-20 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.522 (0.158)    | 0 (0.000) |    20.59 | JBa, phzy, Sonic, stanislaw, susp |
|            6 |      607 | 2024-07-18 | Take Flyte       | W   | 1.000      | 0.477        | 0.002 (0.001)    | 0.236 (0.113)    | 0 (0.000) |     9.01 | JBa, phzy, Sonic, stanislaw, susp |
|            5 |      612 | 2024-07-18 | Take Flyte       | W   | 1.000      | 0.477        | 0.002 (0.001)    | 0.236 (0.113)    | 0 (0.000) |     9.70 | JBa, phzy, Sonic, stanislaw, susp |
|            4 |      677 | 2024-07-17 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.131 (0.062)    | 0 (0.000) |    10.30 | JBa, phzy, Sonic, stanislaw, susp |
|            3 |      680 | 2024-07-17 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | -                | 0 (0.000) |    11.15 | JBa, phzy, Sonic, stanislaw, susp |
|            2 |      736 | 2024-07-16 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.385 (0.183)    | -         |    17.93 | JBa, phzy, Sonic, stanislaw, susp |
|            1 |      742 | 2024-07-16 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -13.37 | JBa, phzy, Sonic, stanislaw, susp |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,000.00)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
