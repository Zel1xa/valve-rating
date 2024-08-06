### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [82](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [60]( ../standings_europe.md)<br />
<br />
Final Rank Value:  929.9<br />
<br />
Final Rank Value (929.9) = Starting Rank Value (884.0) + Head To Head Adjustments (45.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.446[<sup>1</sup>](#table2)
- Bounty Collected: 0.379[<sup>2</sup>](#table1)
- Opponent Network: 0.054[<sup>2</sup>](#table1)
- LAN Wins: 0.064[<sup>2</sup>](#table1)

The average of these factors is 0.236<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 884.0
- 400 + ( ( 0.236 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 884.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |     2400 | 2024-05-04 | Monte           | L   | 0.574      | -            | -                | -                | -         |    -7.50 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2428 | 2024-05-02 | GamerLegion     | L   | 0.562      | -            | -                | -                | -         |    -4.62 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     2454 | 2024-05-01 | FURIA           | W   | 0.555      | 0.889        | 0.284 (0.140)    | 0.479 (0.237)    | 1 (0.555) |    17.18 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |     2477 | 2024-04-30 | Monte           | L   | 0.549      | -            | -                | -                | -         |    -7.18 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |     2932 | 2024-04-12 | BIG             | L   | 0.428      | -            | -                | -                | -         |    -1.53 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     2965 | 2024-04-11 | Aurora          | L   | 0.421      | -            | -                | -                | -         |    -0.25 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     2997 | 2024-04-10 | TSM             | W   | 0.416      | -            | -                | -                | 0 (0.000) |     2.58 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     3052 | 2024-04-09 | brazylijski luz | W   | 0.409      | 0.500        | 0.008 (0.002)    | 0.256 (0.052)    | 0 (0.000) |     4.25 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     3093 | 2024-04-08 | ENCE            | W   | 0.401      | 0.684        | 0.173 (0.047)    | 0.431 (0.118)    | 0 (0.000) |    12.04 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     3366 | 2024-03-27 | 500             | L   | 0.322      | -            | -                | -                | -         |    -7.72 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     3397 | 2024-03-26 | Apeks           | W   | 0.314      | 0.500        | 0.026 (0.004)    | 0.158 (0.025)    | 0 (0.000) |     4.74 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     3403 | 2024-03-25 | B8              | L   | 0.308      | -            | -                | -                | -         |    -2.74 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     3408 | 2024-03-24 | BetBoom         | W   | 0.300      | 0.143        | 0.248 (0.011)    | 0.526 (0.023)    | 0 (0.000) |     8.91 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     3419 | 2024-03-23 | VP.Prodigy      | W   | 0.294      | 0.143        | -                | 0.392 (0.016)    | 0 (0.000) |     4.16 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     3433 | 2024-03-22 | ex-Preasy       | W   | 0.288      | -            | -                | -                | 0 (0.000) |     3.31 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     3456 | 2024-03-21 | PARIVISION      | L   | 0.281      | -            | -                | -                | -         |    -2.09 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     3480 | 2024-03-20 | NAVI Junior     | W   | 0.275      | -            | -                | -                | 0 (0.000) |     0.99 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     3837 | 2024-03-05 | KOI             | L   | 0.176      | -            | -                | -                | -         |    -1.51 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     3842 | 2024-03-05 | AMKAL           | W   | 0.176      | 0.143        | 0.130 (0.003)    | 0.463 (0.012)    | 0 (0.000) |     4.39 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     3849 | 2024-03-05 | 3DMAX           | W   | 0.175      | 0.143        | 0.509 (0.013)    | 1.000 (0.025)    | -         |     5.45 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     3938 | 2024-03-01 | Aurora          | L   | 0.149      | -            | -                | -                | -         |    -0.06 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     3947 | 2024-02-29 | 9 Pandas        | W   | 0.142      | 0.143        | 0.081 (0.002)    | 0.716 (0.015)    | -         |     2.89 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     3959 | 2024-02-28 | KOI             | W   | 0.136      | 0.143        | 0.058 (0.001)    | -                | -         |     3.20 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     3964 | 2024-02-28 | Aurora          | W   | 0.135      | 0.143        | 0.421 (0.008)    | 0.776 (0.015)    | -         |     4.19 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     3977 | 2024-02-27 | V1dar           | W   | 0.129      | -            | -                | -                | -         |     0.47 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     3985 | 2024-02-27 | ARCRED          | W   | 0.129      | -            | -                | -                | -         |     2.19 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4384 | 2024-02-09 | Sashi           | L   | 0.009      | -            | -                | -                | -         |    -0.05 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4389 | 2024-02-09 | RUBY            | W   | 0.008      | -            | -                | -                | -         |     0.14 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4397 | 2024-02-08 | BetBoom         | W   | 0.002      | -            | -                | -                | -         |     0.07 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4402 | 2024-02-08 | Sashi           | L   | 0.001      | -            | -                | -                | -         |    -0.01 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,423.99)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.815 | $3,000.00      | $2,444.79       |
| 2024-05-12 |      0.628 | $7,000.00      | $4,396.39       |
| 2024-04-14 |      0.441 | $26,250.00     | $11,582.81      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
