### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1334.7<br />
<br />
Final Rank Value (1334.7) = Starting Rank Value (1477.1) + Head To Head Adjustments (-142.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.267[<sup>2</sup>](#table1)
- LAN Wins: 0.803[<sup>2</sup>](#table1)

The average of these factors is 0.525<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1477.1
- 400 + ( ( 0.525 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1477.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |       12 | 2024-08-05 | PARIVISION         | L   | 1.000      | -            | -                | -                | -         |   -25.61 | gla1ve, Goofy, Kylar, podi, sdy    |
|           45 |       25 | 2024-08-04 | 9INE               | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.533 (0.232)    | -         |     2.66 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      327 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.39 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      354 | 2024-07-26 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      394 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.565 (0.367)    | 1 (1.000) |     5.53 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      404 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -12.24 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      421 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.87 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |      434 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.511 (0.332)    | 1 (1.000) |    12.83 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1034 | 2024-06-16 | Falcons            | L   | 0.863      | -            | -                | -                | -         |   -11.32 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1098 | 2024-06-14 | Complexity         | W   | 0.851      | 0.500        | 0.342 (0.145)    | 0.373 (0.159)    | 1 (0.851) |    21.23 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1107 | 2024-06-14 | MIBR               | W   | 0.850      | 0.500        | 0.208 (0.088)    | 0.648 (0.275)    | 1 (0.850) |    15.43 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1440 | 2024-06-06 | HEROIC             | L   | 0.797      | -            | -                | -                | -         |    -5.97 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1451 | 2024-06-06 | Astralis           | L   | 0.797      | -            | -                | -                | -         |    -3.04 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1487 | 2024-06-05 | Sashi              | W   | 0.792      | 0.715        | 0.184 (0.104)    | 0.982 (0.556)    | 1 (0.792) |     7.87 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1500 | 2024-06-05 | The MongolZ        | L   | 0.791      | -            | -                | -                | -         |    -1.07 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1509 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.790      | -            | -                | -                | -         |    -6.01 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1616 | 2024-06-01 | DMS                | L   | 0.765      | -            | -                | -                | -         |   -21.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           29 |     1625 | 2024-06-01 | KOI                | W   | 0.764      | -            | -                | -                | -         |     3.27 | gla1ve, Goofy, Kylar, podi, sdy    |
|           28 |     1635 | 2024-06-01 | DMS                | L   | 0.763      | -            | -                | -                | -         |   -22.11 | gla1ve, Goofy, Kylar, podi, sdy    |
|           27 |     1914 | 2024-05-21 | Liquid             | L   | 0.689      | -            | -                | -                | -         |    -5.49 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     2000 | 2024-05-18 | fnatic             | W   | 0.670      | 0.769        | 0.371 (0.191)    | 0.696 (0.359)    | -         |    12.95 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     2023 | 2024-05-17 | Gaimin Gladiators  | W   | 0.665      | 0.769        | 0.037 (0.019)    | 0.340 (0.174)    | -         |     2.11 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2034 | 2024-05-17 | fnatic             | L   | 0.663      | -            | -                | -                | -         |    -7.56 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2392 | 2024-05-04 | FURIA              | L   | 0.577      | -            | -                | -                | -         |    -3.76 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2406 | 2024-05-03 | GamerLegion        | L   | 0.570      | -            | -                | -                | -         |   -14.73 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2426 | 2024-05-02 | Monte              | W   | 0.565      | 0.889        | 0.057 (0.029)    | -                | 1 (0.565) |     1.61 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2454 | 2024-05-01 | Bad News Kangaroos | W   | 0.557      | 0.889        | 0.016 (0.008)    | 0.222 (0.110)    | 1 (0.557) |     0.55 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2485 | 2024-04-30 | GamerLegion        | L   | 0.550      | -            | -                | -                | -         |   -14.63 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     2746 | 2024-04-19 | AMKAL              | L   | 0.477      | -            | -                | -                | -         |   -12.65 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     2833 | 2024-04-17 | Enterprise         | W   | 0.463      | 0.384        | -                | 0.616 (0.110)    | -         |     0.77 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     3004 | 2024-04-10 | OG                 | L   | 0.417      | -            | -                | -                | -         |   -12.10 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3089 | 2024-04-08 | FORZE              | L   | 0.403      | -            | -                | -                | -         |   -12.11 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3197 | 2024-04-04 | Aurora Young Blud  | W   | 0.377      | -            | -                | -                | -         |     0.42 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3491 | 2024-03-19 | FURIA              | L   | 0.271      | -            | -                | -                | -         |    -1.70 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3507 | 2024-03-18 | paiN               | L   | 0.263      | -            | -                | -                | -         |    -4.86 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3514 | 2024-03-17 | KOI                | W   | 0.259      | -            | -                | -                | 1 (0.259) |     0.85 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3534 | 2024-03-17 | Imperial           | L   | 0.257      | -            | -                | -                | -         |    -6.18 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     3665 | 2024-03-12 | B8                 | L   | 0.224      | -            | -                | -                | -         |    -6.33 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     3678 | 2024-03-11 | HEROIC             | L   | 0.218      | -            | -                | -                | -         |    -2.70 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     3688 | 2024-03-11 | Metizport          | W   | 0.217      | -            | -                | -                | -         |     0.19 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4090 | 2024-02-22 | Astralis           | W   | 0.096      | -            | -                | -                | 1 (0.096) |     2.43 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4112 | 2024-02-21 | Vitality           | L   | 0.090      | -            | -                | -                | -         |    -0.31 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4145 | 2024-02-20 | GamerLegion        | W   | 0.083      | -            | -                | -                | -         |     0.05 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4165 | 2024-02-19 | ex-Guild Eagles    | W   | 0.078      | -            | -                | -                | -         |     0.06 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4173 | 2024-02-19 | Spirit             | L   | 0.076      | -            | -                | -                | -         |    -0.20 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4378 | 2024-02-09 | Falcons            | L   | 0.012      | -            | -                | -                | -         |    -0.21 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,783.26)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-05 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.864 | $10,000.00     | $8,636.11       |
| 2024-06-09 |      0.817 | $8,000.00      | $6,537.78       |
| 2024-05-23 |      0.703 | $12,500.00     | $8,793.40       |
| 2024-05-12 |      0.631 | $7,000.00      | $4,413.89       |
| 2024-04-14 |      0.444 | $15,000.00     | $6,656.25       |
| 2024-03-20 |      0.278 | $10,000.00     | $2,779.17       |
| 2024-02-11 |      0.024 | $40,000.00     | $966.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
