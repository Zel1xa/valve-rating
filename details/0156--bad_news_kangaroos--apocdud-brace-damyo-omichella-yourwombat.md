### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: apocdud, BRACE, damyo, Omichella, yourwombat<br />
Global Rank: [156](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [15]( ../standings_asia.md)<br />
<br />
Final Rank Value:  692.5<br />
<br />
Final Rank Value (692.5) = Starting Rank Value (674.4) + Head To Head Adjustments (18.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.280[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.4
- 400 + ( ( 0.134 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 674.4


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
|           12 |      412 | 2024-07-23 | MANTRA    | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.80 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           11 |      417 | 2024-07-23 | MANTRA    | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.03 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           10 |      593 | 2024-07-18 | Arcade    | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.137 (0.046)    | 0 (0.000) |    13.67 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            9 |      598 | 2024-07-18 | Arcade    | L   | 1.000      | -            | -                | -                | -         |   -18.03 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            8 |      711 | 2024-07-16 | DXA       | L   | 1.000      | -            | -                | -                | -         |   -18.10 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            7 |      714 | 2024-07-16 | DXA       | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.227 (0.076)    | 0 (0.000) |    13.19 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            6 |     1339 | 2024-06-07 | Mindfreak | L   | 0.813      | -            | -                | -                | -         |   -11.71 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|            5 |     1408 | 2024-06-06 | Rooster   | L   | 0.806      | -            | -                | -                | -         |    -8.60 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|            4 |     1811 | 2024-05-22 | KZG       | W   | 0.707      | 0.333        | 0.005 (0.001)    | 0.112 (0.026)    | 0 (0.000) |     9.79 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|            3 |     1816 | 2024-05-22 | KZG       | W   | 0.706      | 0.333        | 0.005 (0.001)    | 0.112 (0.026)    | 0 (0.000) |    10.42 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|            2 |     2069 | 2024-05-15 | Arcade    | W   | 0.660      | 0.333        | 0.002 (0.001)    | 0.137 (0.030)    | 0 (0.000) |     8.57 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|            1 |     2074 | 2024-05-15 | Arcade    | W   | 0.660      | 0.333        | 0.002 (0.001)    | 0.137 (0.030)    | 0 (0.000) |     9.07 | ADDICT, BRACE, damyo, hazr, yourwombat       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($866.83)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
