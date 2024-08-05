### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: apocdud, BRACE, damyo, Omichella, yourwombat<br />
Global Rank: [154](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [13]( ../standings_asia.md)<br />
<br />
Final Rank Value:  696.4<br />
<br />
Final Rank Value (696.4) = Starting Rank Value (678.0) + Head To Head Adjustments (18.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.280[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 678.0
- 400 + ( ( 0.135 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 678.0


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
|           12 |      295 | 2024-07-23 | MANTRA    | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.72 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           11 |      299 | 2024-07-23 | MANTRA    | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.94 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           10 |      476 | 2024-07-18 | Arcade    | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.139 (0.046)    | 0 (0.000) |    13.63 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            9 |      480 | 2024-07-18 | Arcade    | L   | 1.000      | -            | -                | -                | -         |   -18.07 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            8 |      594 | 2024-07-16 | DXA       | L   | 1.000      | -            | -                | -                | -         |   -18.18 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            7 |      596 | 2024-07-16 | DXA       | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.228 (0.076)    | 0 (0.000) |    13.11 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            6 |     1222 | 2024-06-07 | Mindfreak | L   | 0.837      | -            | -                | -                | -         |   -11.98 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|            5 |     1291 | 2024-06-06 | Rooster   | L   | 0.830      | -            | -                | -                | -         |    -8.71 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|            4 |     1694 | 2024-05-22 | KZG       | W   | 0.730      | 0.333        | 0.006 (0.001)    | 0.113 (0.028)    | 0 (0.000) |    10.05 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|            3 |     1699 | 2024-05-22 | KZG       | W   | 0.730      | 0.333        | 0.006 (0.001)    | 0.113 (0.028)    | 0 (0.000) |    10.71 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|            2 |     1952 | 2024-05-15 | Arcade    | W   | 0.684      | 0.333        | 0.003 (0.001)    | 0.139 (0.032)    | 0 (0.000) |     8.86 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|            1 |     1957 | 2024-05-15 | Arcade    | W   | 0.684      | 0.333        | 0.003 (0.001)    | 0.139 (0.032)    | 0 (0.000) |     9.39 | ADDICT, BRACE, damyo, hazr, yourwombat       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($891.80)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
