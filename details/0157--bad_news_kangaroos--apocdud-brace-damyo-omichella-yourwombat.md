### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: apocdud, BRACE, damyo, Omichella, yourwombat<br />
Global Rank: [157](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [15]( ../standings_asia.md)<br />
<br />
Final Rank Value:  692.7<br />
<br />
Final Rank Value (692.7) = Starting Rank Value (675.2) + Head To Head Adjustments (17.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.280[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 675.2
- 400 + ( ( 0.135 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 675.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |      386 | 2024-07-23 | MANTRA    | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.79 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           11 |      391 | 2024-07-23 | MANTRA    | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.02 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           10 |      567 | 2024-07-18 | Arcade    | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.142 (0.047)    | 0 (0.000) |    13.81 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            9 |      574 | 2024-07-18 | Arcade    | L   | 1.000      | -            | -                | -                | -         |   -17.87 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            8 |      682 | 2024-07-16 | DXA       | L   | 1.000      | -            | -                | -                | -         |   -18.13 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            7 |      687 | 2024-07-16 | DXA       | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.235 (0.078)    | 0 (0.000) |    13.16 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            6 |     1275 | 2024-06-07 | Mindfreak | L   | 0.818      | -            | -                | -                | -         |   -11.83 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|            5 |     1344 | 2024-06-06 | Rooster   | L   | 0.811      | -            | -                | -                | -         |    -8.65 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|            4 |     1743 | 2024-05-22 | KZG       | W   | 0.711      | 0.333        | 0.005 (0.001)    | 0.116 (0.027)    | 0 (0.000) |     9.31 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|            3 |     1748 | 2024-05-22 | KZG       | W   | 0.711      | 0.333        | 0.005 (0.001)    | 0.116 (0.027)    | 0 (0.000) |     9.91 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|            2 |     2000 | 2024-05-15 | Arcade    | W   | 0.665      | 0.333        | 0.002 (0.001)    | 0.142 (0.031)    | 0 (0.000) |     8.71 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|            1 |     2005 | 2024-05-15 | Arcade    | W   | 0.664      | 0.333        | 0.002 (0.001)    | 0.142 (0.031)    | 0 (0.000) |     9.23 | ADDICT, BRACE, damyo, hazr, yourwombat       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($871.84)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
