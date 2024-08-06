### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: BRACE, damyo, Omichella, pz, yourwombat<br />
Global Rank: [135](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
<br />
Final Rank Value:  773.1<br />
<br />
Final Rank Value (773.1) = Starting Rank Value (775.6) + Head To Head Adjustments (-2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.359[<sup>1</sup>](#table2)
- Bounty Collected: 0.244[<sup>2</sup>](#table1)
- Opponent Network: 0.034[<sup>2</sup>](#table1)
- LAN Wins: 0.096[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.6
- 400 + ( ( 0.183 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 775.6


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
|           35 |       47 | 2024-08-04 | Lynn Vision | L   | 1.000      | -            | -                | -                | -         |    -5.41 | BRACE, damyo, Omichella, pz, yourwombat      |
|           34 |      472 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.18 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           33 |      476 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.29 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           32 |      653 | 2024-07-18 | Arcade      | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.134 (0.045)    | 0 (0.000) |    10.71 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           31 |      657 | 2024-07-18 | Arcade      | L   | 1.000      | -            | -                | -                | -         |   -21.22 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           30 |      771 | 2024-07-16 | DXA         | L   | 1.000      | -            | -                | -                | -         |   -21.52 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           29 |      773 | 2024-07-16 | DXA         | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.222 (0.074)    | 0 (0.000) |     9.54 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           28 |     1399 | 2024-06-07 | Mindfreak   | L   | 0.802      | -            | -                | -                | -         |   -14.96 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           27 |     1468 | 2024-06-06 | Rooster     | L   | 0.795      | -            | -                | -                | -         |   -12.00 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           26 |     1871 | 2024-05-22 | KZG         | W   | 0.696      | 0.333        | 0.005 (0.001)    | 0.109 (0.025)    | 0 (0.000) |     6.66 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           25 |     1876 | 2024-05-22 | KZG         | W   | 0.696      | 0.333        | 0.005 (0.001)    | 0.109 (0.025)    | 0 (0.000) |     7.02 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           24 |     2129 | 2024-05-15 | Arcade      | W   | 0.649      | 0.333        | 0.002 (0.001)    | 0.134 (0.029)    | 0 (0.000) |     5.75 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           23 |     2134 | 2024-05-15 | Arcade      | W   | 0.649      | 0.333        | 0.002 (0.001)    | 0.134 (0.029)    | -         |     6.03 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           22 |     2407 | 2024-05-03 | FURIA       | L   | 0.570      | -            | -                | -                | -         |    -0.16 | ADDICT, BRACE, damyo, hazr, pz               |
|           21 |     2454 | 2024-05-01 | ENCE        | L   | 0.557      | -            | -                | -                | -         |    -0.55 | ADDICT, BRACE, damyo, hazr, pz               |
|           20 |     2486 | 2024-04-30 | MOUZ        | L   | 0.550      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, damyo, hazr, pz               |
|           19 |     2709 | 2024-04-20 | FlyQuest    | L   | 0.483      | -            | -                | -                | -         |    -1.68 | ADDICT, BRACE, damyo, hazr, pz               |
|           18 |     2713 | 2024-04-19 | Rooster     | W   | 0.482      | 0.143        | 0.010 (0.001)    | -                | -         |     7.78 | ADDICT, BRACE, damyo, hazr, pz               |
|           17 |     2756 | 2024-04-19 | Mindfreak   | W   | 0.476      | -            | -                | -                | -         |     5.76 | ADDICT, BRACE, damyo, hazr, pz               |
|           16 |     2761 | 2024-04-18 | Rooster     | L   | 0.475      | -            | -                | -                | -         |    -7.29 | ADDICT, BRACE, damyo, hazr, pz               |
|           15 |     3010 | 2024-04-10 | Rooster     | W   | 0.416      | 0.333        | 0.010 (0.001)    | 0.246 (0.034)    | -         |     6.72 | ADDICT, BRACE, damyo, hazr, pz               |
|           14 |     3017 | 2024-04-10 | Rooster     | L   | 0.416      | -            | -                | -                | -         |    -6.51 | ADDICT, BRACE, damyo, hazr, pz               |
|           13 |     3243 | 2024-04-03 | DXA         | W   | 0.369      | 0.333        | 0.002 (0.000)    | 0.222 (0.027)    | -         |     4.14 | ADDICT, BRACE, damyo, hazr, pz               |
|           12 |     3248 | 2024-04-03 | DXA         | W   | 0.369      | 0.333        | -                | 0.222 (0.027)    | -         |     4.27 | ADDICT, BRACE, damyo, hazr, pz               |
|           11 |     3371 | 2024-03-27 | Mindfreak   | L   | 0.323      | -            | -                | -                | -         |    -6.81 | ADDICT, BRACE, damyo, hazr, pz               |
|           10 |     3376 | 2024-03-27 | Mindfreak   | W   | 0.323      | 0.333        | 0.004 (0.000)    | -                | -         |     3.39 | ADDICT, BRACE, damyo, hazr, pz               |
|            9 |     3419 | 2024-03-23 | DXA         | W   | 0.296      | 0.315        | -                | 0.222 (0.021)    | 1 (0.296) |     3.53 | ADDICT, BRACE, damyo, hazr, pz               |
|            8 |     3422 | 2024-03-23 | Arcade      | W   | 0.295      | -            | -                | -                | 1 (0.295) |     3.45 | ADDICT, BRACE, damyo, hazr, pz               |
|            7 |     3480 | 2024-03-20 | Canon Event | W   | 0.275      | -            | -                | -                | -         |     1.57 | ADDICT, BRACE, damyo, hazr, pz               |
|            6 |     3481 | 2024-03-20 | Canon Event | W   | 0.275      | -            | -                | -                | -         |     1.59 | ADDICT, BRACE, damyo, hazr, pz               |
|            5 |     3551 | 2024-03-15 | Gods Reign  | L   | 0.248      | -            | -                | -                | -         |    -3.99 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            4 |     3572 | 2024-03-14 | GRDX        | W   | 0.242      | -            | -                | -                | 1 (0.242) |     1.55 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            3 |     3605 | 2024-03-14 | Aurora      | L   | 0.235      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            2 |     3818 | 2024-03-06 | Vantage     | W   | 0.183      | -            | -                | -                | -         |     1.89 | ADDICT, BRACE, damyo, hazr, pz               |
|            1 |     3820 | 2024-03-06 | Vantage     | W   | 0.182      | -            | -                | -                | -         |     1.91 | ADDICT, BRACE, damyo, hazr, pz               |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,288.94)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.815 | $1,050.00      | $855.46         |
| 2024-05-12 |      0.631 | $3,500.00      | $2,206.94       |
| 2024-03-23 |      0.296 | $3,308.00      | $977.93         |
| 2024-03-16 |      0.250 | $5,000.00      | $1,248.61       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
