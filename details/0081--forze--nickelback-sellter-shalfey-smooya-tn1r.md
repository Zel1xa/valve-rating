### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [81](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  930.9<br />
<br />
Final Rank Value (930.9) = Starting Rank Value (884.5) + Head To Head Adjustments (46.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.380[<sup>2</sup>](#table1)
- Opponent Network: 0.054[<sup>2</sup>](#table1)
- LAN Wins: 0.064[<sup>2</sup>](#table1)

The average of these factors is 0.236<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 884.5
- 400 + ( ( 0.236 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 884.5


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
|           30 |     2396 | 2024-05-04 | Monte           | L   | 0.576      | -            | -                | -                | -         |    -7.54 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2424 | 2024-05-02 | GamerLegion     | L   | 0.565      | -            | -                | -                | -         |    -4.64 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     2450 | 2024-05-01 | FURIA           | W   | 0.558      | 0.889        | 0.284 (0.141)    | 0.480 (0.238)    | 1 (0.558) |    17.26 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |     2473 | 2024-04-30 | Monte           | L   | 0.551      | -            | -                | -                | -         |    -7.21 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |     2928 | 2024-04-12 | BIG             | L   | 0.431      | -            | -                | -                | -         |    -1.54 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     2961 | 2024-04-11 | Aurora          | L   | 0.423      | -            | -                | -                | -         |    -0.26 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     2993 | 2024-04-10 | TSM             | W   | 0.418      | -            | -                | -                | 0 (0.000) |     2.58 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     3048 | 2024-04-09 | brazylijski luz | W   | 0.411      | 0.500        | 0.008 (0.002)    | 0.256 (0.053)    | 0 (0.000) |     4.26 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     3089 | 2024-04-08 | ENCE            | W   | 0.403      | 0.684        | 0.174 (0.048)    | 0.432 (0.119)    | 0 (0.000) |    12.11 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     3362 | 2024-03-27 | 500             | L   | 0.325      | -            | -                | -                | -         |    -7.79 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     3393 | 2024-03-26 | Apeks           | W   | 0.317      | 0.500        | 0.027 (0.004)    | 0.159 (0.025)    | 0 (0.000) |     4.78 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     3399 | 2024-03-25 | B8              | L   | 0.311      | -            | -                | -                | -         |    -2.77 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     3404 | 2024-03-24 | BetBoom         | W   | 0.303      | 0.143        | 0.249 (0.011)    | 0.527 (0.023)    | 0 (0.000) |     8.98 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     3415 | 2024-03-23 | VP.Prodigy      | W   | 0.297      | 0.143        | -                | 0.393 (0.017)    | 0 (0.000) |     4.18 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     3429 | 2024-03-22 | ex-Preasy       | W   | 0.290      | -            | -                | -                | 0 (0.000) |     3.35 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     3452 | 2024-03-21 | PARIVISION      | L   | 0.284      | -            | -                | -                | -         |    -2.13 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     3476 | 2024-03-20 | NAVI Junior     | W   | 0.277      | -            | -                | -                | 0 (0.000) |     1.00 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     3833 | 2024-03-05 | KOI             | L   | 0.179      | -            | -                | -                | -         |    -1.53 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     3838 | 2024-03-05 | AMKAL           | W   | 0.178      | 0.143        | 0.130 (0.003)    | 0.464 (0.012)    | 0 (0.000) |     4.45 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     3845 | 2024-03-05 | 3DMAX           | W   | 0.178      | 0.143        | 0.509 (0.013)    | 1.000 (0.025)    | -         |     5.53 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     3934 | 2024-03-01 | Aurora          | L   | 0.152      | -            | -                | -                | -         |    -0.06 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     3943 | 2024-02-29 | 9 Pandas        | W   | 0.145      | 0.143        | 0.081 (0.002)    | 0.717 (0.015)    | -         |     2.94 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     3955 | 2024-02-28 | KOI             | W   | 0.138      | 0.143        | 0.058 (0.001)    | -                | -         |     3.26 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     3960 | 2024-02-28 | Aurora          | W   | 0.137      | 0.143        | 0.421 (0.008)    | 0.777 (0.015)    | -         |     4.27 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     3973 | 2024-02-27 | V1dar           | W   | 0.132      | -            | -                | -                | -         |     0.48 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     3981 | 2024-02-27 | ARCRED          | W   | 0.131      | -            | -                | -                | -         |     2.22 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4380 | 2024-02-09 | Sashi           | L   | 0.012      | -            | -                | -                | -         |    -0.06 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4385 | 2024-02-09 | RUBY            | W   | 0.010      | -            | -                | -                | -         |     0.18 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4393 | 2024-02-08 | BetBoom         | W   | 0.005      | -            | -                | -                | -         |     0.15 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4398 | 2024-02-08 | Sashi           | L   | 0.004      | -            | -                | -                | -         |    -0.02 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,514.62)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.817 | $3,000.00      | $2,452.29       |
| 2024-05-12 |      0.631 | $7,000.00      | $4,413.89       |
| 2024-04-14 |      0.444 | $26,250.00     | $11,648.44      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
