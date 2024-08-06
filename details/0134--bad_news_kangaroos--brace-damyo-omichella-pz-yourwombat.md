### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: BRACE, damyo, Omichella, pz, yourwombat<br />
Global Rank: [134](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
<br />
Final Rank Value:  773.1<br />
<br />
Final Rank Value (773.1) = Starting Rank Value (775.2) + Head To Head Adjustments (-2.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.359[<sup>1</sup>](#table2)
- Bounty Collected: 0.243[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.095[<sup>2</sup>](#table1)

The average of these factors is 0.182<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.2
- 400 + ( ( 0.182 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 775.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |       69 | 2024-08-04 | Lynn Vision | L   | 1.000      | -            | -                | -                | -         |    -5.10 | BRACE, damyo, Omichella, pz, yourwombat      |
|           34 |      494 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.19 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           33 |      498 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.29 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           32 |      675 | 2024-07-18 | Arcade      | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.130 (0.043)    | 0 (0.000) |    10.73 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           31 |      679 | 2024-07-18 | Arcade      | L   | 1.000      | -            | -                | -                | -         |   -21.19 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           30 |      793 | 2024-07-16 | DXA         | L   | 1.000      | -            | -                | -                | -         |   -21.49 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           29 |      795 | 2024-07-16 | DXA         | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.217 (0.072)    | 0 (0.000) |     9.58 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           28 |     1421 | 2024-06-07 | Mindfreak   | L   | 0.798      | -            | -                | -                | -         |   -14.87 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           27 |     1490 | 2024-06-06 | Rooster     | L   | 0.791      | -            | -                | -                | -         |   -11.93 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           26 |     1893 | 2024-05-22 | KZG         | W   | 0.692      | 0.333        | 0.005 (0.001)    | 0.106 (0.024)    | 0 (0.000) |     6.65 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           25 |     1898 | 2024-05-22 | KZG         | W   | 0.691      | 0.333        | 0.005 (0.001)    | 0.106 (0.024)    | 0 (0.000) |     7.01 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           24 |     2151 | 2024-05-15 | Arcade      | W   | 0.645      | 0.333        | 0.002 (0.001)    | 0.130 (0.028)    | 0 (0.000) |     5.73 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           23 |     2156 | 2024-05-15 | Arcade      | W   | 0.645      | 0.333        | 0.002 (0.001)    | 0.130 (0.028)    | -         |     6.01 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           22 |     2429 | 2024-05-03 | FURIA       | L   | 0.566      | -            | -                | -                | -         |    -0.16 | ADDICT, BRACE, damyo, hazr, pz               |
|           21 |     2476 | 2024-05-01 | ENCE        | L   | 0.553      | -            | -                | -                | -         |    -0.54 | ADDICT, BRACE, damyo, hazr, pz               |
|           20 |     2508 | 2024-04-30 | MOUZ        | L   | 0.545      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, damyo, hazr, pz               |
|           19 |     2731 | 2024-04-20 | FlyQuest    | L   | 0.478      | -            | -                | -                | -         |    -1.68 | ADDICT, BRACE, damyo, hazr, pz               |
|           18 |     2735 | 2024-04-19 | Rooster     | W   | 0.477      | 0.143        | 0.010 (0.001)    | -                | -         |     7.71 | ADDICT, BRACE, damyo, hazr, pz               |
|           17 |     2778 | 2024-04-19 | Mindfreak   | W   | 0.472      | -            | -                | -                | -         |     5.72 | ADDICT, BRACE, damyo, hazr, pz               |
|           16 |     2783 | 2024-04-18 | Rooster     | L   | 0.471      | -            | -                | -                | -         |    -7.22 | ADDICT, BRACE, damyo, hazr, pz               |
|           15 |     3032 | 2024-04-10 | Rooster     | W   | 0.412      | 0.333        | 0.010 (0.001)    | 0.241 (0.033)    | -         |     6.66 | ADDICT, BRACE, damyo, hazr, pz               |
|           14 |     3039 | 2024-04-10 | Rooster     | L   | 0.411      | -            | -                | -                | -         |    -6.44 | ADDICT, BRACE, damyo, hazr, pz               |
|           13 |     3265 | 2024-04-03 | DXA         | W   | 0.365      | 0.333        | 0.002 (0.000)    | 0.217 (0.026)    | -         |     4.11 | ADDICT, BRACE, damyo, hazr, pz               |
|           12 |     3270 | 2024-04-03 | DXA         | W   | 0.365      | 0.333        | -                | 0.217 (0.026)    | -         |     4.23 | ADDICT, BRACE, damyo, hazr, pz               |
|           11 |     3393 | 2024-03-27 | Mindfreak   | L   | 0.318      | -            | -                | -                | -         |    -6.71 | ADDICT, BRACE, damyo, hazr, pz               |
|           10 |     3398 | 2024-03-27 | Mindfreak   | W   | 0.318      | 0.333        | 0.004 (0.000)    | -                | -         |     3.36 | ADDICT, BRACE, damyo, hazr, pz               |
|            9 |     3441 | 2024-03-23 | DXA         | W   | 0.291      | 0.315        | -                | 0.217 (0.020)    | 1 (0.291) |     3.49 | ADDICT, BRACE, damyo, hazr, pz               |
|            8 |     3444 | 2024-03-23 | Arcade      | W   | 0.291      | -            | -                | -                | 1 (0.291) |     3.40 | ADDICT, BRACE, damyo, hazr, pz               |
|            7 |     3502 | 2024-03-20 | Canon Event | W   | 0.271      | -            | -                | -                | -         |     1.55 | ADDICT, BRACE, damyo, hazr, pz               |
|            6 |     3503 | 2024-03-20 | Canon Event | W   | 0.271      | -            | -                | -                | -         |     1.57 | ADDICT, BRACE, damyo, hazr, pz               |
|            5 |     3573 | 2024-03-15 | Gods Reign  | L   | 0.244      | -            | -                | -                | -         |    -3.92 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            4 |     3594 | 2024-03-14 | GRDX        | W   | 0.237      | -            | -                | -                | 1 (0.237) |     1.53 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            3 |     3627 | 2024-03-14 | Aurora      | L   | 0.231      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            2 |     3840 | 2024-03-06 | Vantage     | W   | 0.178      | -            | -                | -                | -         |     1.85 | ADDICT, BRACE, damyo, hazr, pz               |
|            1 |     3842 | 2024-03-06 | Vantage     | W   | 0.178      | -            | -                | -                | -         |     1.87 | ADDICT, BRACE, damyo, hazr, pz               |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,233.58)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.810 | $1,050.00      | $850.94         |
| 2024-05-12 |      0.626 | $3,500.00      | $2,191.88       |
| 2024-03-23 |      0.291 | $3,308.00      | $963.68         |
| 2024-03-16 |      0.245 | $5,000.00      | $1,227.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
