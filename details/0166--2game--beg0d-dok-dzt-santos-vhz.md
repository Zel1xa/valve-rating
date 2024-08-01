### Roster Details<br />
Team Name: 2GAME<br />
Roster: beg0d, dok, dzt, santos, vhz<br />
Global Rank: [166](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [47]( ../standings_americas.md)<br />
<br />
Final Rank Value:  678.4<br />
<br />
Final Rank Value (678.4) = Starting Rank Value (680.8) + Head To Head Adjustments (-2.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.240[<sup>2</sup>](#table1)
- Opponent Network: 0.030[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 680.8
- 400 + ( ( 0.137 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 680.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |     2915 | 2024-04-10 | RED Canids  | L   | 0.448      | -            | -                | -                | -         |    -1.53 | beg0d, dok, dzt, santos, vhz |
|           20 |     2918 | 2024-04-10 | RED Canids  | L   | 0.448      | -            | -                | -                | -         |    -1.55 | beg0d, dok, dzt, santos, vhz |
|           19 |     3076 | 2024-04-05 | adalYamigos | W   | 0.415      | 0.450        | 0.000 (0.000)    | 0.085 (0.016)    | 0 (0.000) |     6.50 | beg0d, dok, dzt, santos, vhz |
|           18 |     3077 | 2024-04-05 | adalYamigos | L   | 0.414      | -            | -                | -                | -         |    -6.70 | beg0d, dok, dzt, santos, vhz |
|           17 |     3144 | 2024-04-03 | Sharks      | L   | 0.402      | -            | -                | -                | -         |    -1.96 | beg0d, dok, dzt, santos, vhz |
|           16 |     3147 | 2024-04-03 | Sharks      | L   | 0.401      | -            | -                | -                | -         |    -2.00 | beg0d, dok, dzt, santos, vhz |
|           15 |     3286 | 2024-03-27 | Corinthians | W   | 0.355      | 0.450        | 0.000 (0.000)    | 0.053 (0.009)    | 0 (0.000) |     3.28 | beg0d, dok, dzt, santos, vhz |
|           14 |     3291 | 2024-03-27 | Corinthians | L   | 0.355      | -            | -                | -                | -         |    -8.06 | beg0d, dok, dzt, santos, vhz |
|           13 |     3329 | 2024-03-26 | Galorys     | L   | 0.349      | -            | -                | -                | -         |    -2.64 | beg0d, dok, dzt, santos, vhz |
|           12 |     3333 | 2024-03-26 | Galorys     | L   | 0.348      | -            | -                | -                | -         |    -2.70 | beg0d, dok, dzt, santos, vhz |
|           11 |     3414 | 2024-03-20 | Solid       | W   | 0.308      | 0.450        | 0.027 (0.004)    | 0.844 (0.117)    | 0 (0.000) |     7.49 | beg0d, dok, dzt, santos, vhz |
|           10 |     3417 | 2024-03-20 | Solid       | L   | 0.308      | -            | -                | -                | -         |    -2.22 | beg0d, dok, dzt, santos, vhz |
|            9 |     3501 | 2024-03-15 | ODDIK       | L   | 0.275      | -            | -                | -                | -         |    -1.19 | beg0d, dok, dzt, santos, vhz |
|            8 |     3502 | 2024-03-15 | ODDIK       | L   | 0.275      | -            | -                | -                | -         |    -1.20 | beg0d, dok, dzt, santos, vhz |
|            7 |     3781 | 2024-03-05 | W7M         | W   | 0.209      | 0.450        | 0.007 (0.001)    | 0.626 (0.059)    | 0 (0.000) |     4.79 | beg0d, dok, dzt, santos, vhz |
|            6 |     3783 | 2024-03-05 | W7M         | W   | 0.208      | 0.450        | 0.007 (0.001)    | 0.626 (0.059)    | 0 (0.000) |     4.85 | beg0d, dok, dzt, santos, vhz |
|            5 |     3996 | 2024-02-24 | Case        | L   | 0.142      | -            | -                | -                | -         |    -0.84 | beg0d, dok, dzt, santos, vhz |
|            4 |     4001 | 2024-02-24 | Case        | W   | 0.142      | 0.450        | 0.030 (0.002)    | 0.722 (0.046)    | 0 (0.000) |     3.65 | beg0d, dok, dzt, santos, vhz |
|            3 |     4066 | 2024-02-21 | Imperial    | L   | 0.122      | -            | -                | -                | -         |    -0.13 | beg0d, dok, dzt, santos, vhz |
|            2 |     4069 | 2024-02-21 | Imperial    | L   | 0.122      | -            | -                | -                | -         |    -0.13 | beg0d, dok, dzt, santos, vhz |
|            1 |     4252 | 2024-02-14 | 9z          | L   | 0.075      | -            | -                | -                | -         |    -0.10 | beg0d, dok, dzt, santos, vhz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($762.92)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
