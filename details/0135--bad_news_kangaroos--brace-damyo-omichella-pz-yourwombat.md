### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: BRACE, damyo, Omichella, pz, yourwombat<br />
Global Rank: [135](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
<br />
Final Rank Value:  773.4<br />
<br />
Final Rank Value (773.4) = Starting Rank Value (775.9) + Head To Head Adjustments (-2.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.360[<sup>1</sup>](#table2)
- Bounty Collected: 0.244[<sup>2</sup>](#table1)
- Opponent Network: 0.034[<sup>2</sup>](#table1)
- LAN Wins: 0.097[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.9
- 400 + ( ( 0.184 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 775.9


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
|           35 |       35 | 2024-08-04 | Lynn Vision | L   | 1.000      | -            | -                | -                | -         |    -5.41 | BRACE, damyo, Omichella, pz, yourwombat      |
|           34 |      461 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.18 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           33 |      465 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.28 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           32 |      642 | 2024-07-18 | Arcade      | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.136 (0.045)    | 0 (0.000) |    10.69 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           31 |      646 | 2024-07-18 | Arcade      | L   | 1.000      | -            | -                | -                | -         |   -21.24 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           30 |      760 | 2024-07-16 | DXA         | L   | 1.000      | -            | -                | -                | -         |   -21.55 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           29 |      762 | 2024-07-16 | DXA         | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.225 (0.075)    | 0 (0.000) |     9.51 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           28 |     1388 | 2024-06-07 | Mindfreak   | L   | 0.805      | -            | -                | -                | -         |   -15.03 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           27 |     1457 | 2024-06-06 | Rooster     | L   | 0.799      | -            | -                | -                | -         |   -12.06 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           26 |     1860 | 2024-05-22 | KZG         | W   | 0.699      | 0.333        | 0.005 (0.001)    | 0.111 (0.026)    | 0 (0.000) |     6.67 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           25 |     1865 | 2024-05-22 | KZG         | W   | 0.699      | 0.333        | 0.005 (0.001)    | 0.111 (0.026)    | 0 (0.000) |     7.03 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           24 |     2118 | 2024-05-15 | Arcade      | W   | 0.652      | 0.333        | 0.002 (0.001)    | 0.136 (0.030)    | 0 (0.000) |     5.76 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           23 |     2123 | 2024-05-15 | Arcade      | W   | 0.652      | 0.333        | 0.002 (0.001)    | 0.136 (0.030)    | -         |     6.04 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           22 |     2396 | 2024-05-03 | FURIA       | L   | 0.574      | -            | -                | -                | -         |    -0.17 | ADDICT, BRACE, damyo, hazr, pz               |
|           21 |     2443 | 2024-05-01 | ENCE        | L   | 0.560      | -            | -                | -                | -         |    -0.57 | ADDICT, BRACE, damyo, hazr, pz               |
|           20 |     2475 | 2024-04-30 | MOUZ        | L   | 0.553      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, damyo, hazr, pz               |
|           19 |     2698 | 2024-04-20 | FlyQuest    | L   | 0.486      | -            | -                | -                | -         |    -1.68 | ADDICT, BRACE, damyo, hazr, pz               |
|           18 |     2702 | 2024-04-19 | Rooster     | W   | 0.485      | 0.143        | 0.010 (0.001)    | -                | -         |     7.83 | ADDICT, BRACE, damyo, hazr, pz               |
|           17 |     2745 | 2024-04-19 | Mindfreak   | W   | 0.479      | -            | -                | -                | -         |     5.79 | ADDICT, BRACE, damyo, hazr, pz               |
|           16 |     2750 | 2024-04-18 | Rooster     | L   | 0.478      | -            | -                | -                | -         |    -7.34 | ADDICT, BRACE, damyo, hazr, pz               |
|           15 |     2999 | 2024-04-10 | Rooster     | W   | 0.419      | 0.333        | 0.010 (0.001)    | 0.250 (0.035)    | -         |     6.77 | ADDICT, BRACE, damyo, hazr, pz               |
|           14 |     3006 | 2024-04-10 | Rooster     | L   | 0.419      | -            | -                | -                | -         |    -6.57 | ADDICT, BRACE, damyo, hazr, pz               |
|           13 |     3232 | 2024-04-03 | DXA         | W   | 0.372      | 0.333        | 0.002 (0.000)    | 0.225 (0.028)    | -         |     4.17 | ADDICT, BRACE, damyo, hazr, pz               |
|           12 |     3237 | 2024-04-03 | DXA         | W   | 0.372      | 0.333        | -                | 0.225 (0.028)    | -         |     4.29 | ADDICT, BRACE, damyo, hazr, pz               |
|           11 |     3360 | 2024-03-27 | Mindfreak   | L   | 0.326      | -            | -                | -                | -         |    -6.89 | ADDICT, BRACE, damyo, hazr, pz               |
|           10 |     3365 | 2024-03-27 | Mindfreak   | W   | 0.326      | 0.333        | 0.004 (0.000)    | -                | -         |     3.42 | ADDICT, BRACE, damyo, hazr, pz               |
|            9 |     3408 | 2024-03-23 | DXA         | W   | 0.299      | 0.315        | -                | 0.225 (0.021)    | 1 (0.299) |     3.56 | ADDICT, BRACE, damyo, hazr, pz               |
|            8 |     3411 | 2024-03-23 | Arcade      | W   | 0.298      | -            | -                | -                | 1 (0.298) |     3.48 | ADDICT, BRACE, damyo, hazr, pz               |
|            7 |     3469 | 2024-03-20 | Canon Event | W   | 0.279      | -            | -                | -                | -         |     1.58 | ADDICT, BRACE, damyo, hazr, pz               |
|            6 |     3470 | 2024-03-20 | Canon Event | W   | 0.278      | -            | -                | -                | -         |     1.60 | ADDICT, BRACE, damyo, hazr, pz               |
|            5 |     3540 | 2024-03-15 | Gods Reign  | L   | 0.251      | -            | -                | -                | -         |    -4.05 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            4 |     3561 | 2024-03-14 | GRDX        | W   | 0.245      | -            | -                | -                | 1 (0.245) |     1.57 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            3 |     3594 | 2024-03-14 | Aurora      | L   | 0.238      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            2 |     3807 | 2024-03-06 | Vantage     | W   | 0.186      | -            | -                | -                | -         |     1.91 | ADDICT, BRACE, damyo, hazr, pz               |
|            1 |     3809 | 2024-03-06 | Vantage     | W   | 0.186      | -            | -                | -                | -         |     1.94 | ADDICT, BRACE, damyo, hazr, pz               |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,331.80)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.818 | $1,050.00      | $858.96         |
| 2024-05-12 |      0.634 | $3,500.00      | $2,218.61       |
| 2024-03-23 |      0.299 | $3,308.00      | $988.95         |
| 2024-03-16 |      0.253 | $5,000.00      | $1,265.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
