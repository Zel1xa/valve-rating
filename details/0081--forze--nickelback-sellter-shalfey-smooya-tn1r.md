### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [81](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  931.7<br />
<br />
Final Rank Value (931.7) = Starting Rank Value (884.8) + Head To Head Adjustments (46.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.380[<sup>2</sup>](#table1)
- Opponent Network: 0.055[<sup>2</sup>](#table1)
- LAN Wins: 0.064[<sup>2</sup>](#table1)

The average of these factors is 0.236<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 884.8
- 400 + ( ( 0.236 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 884.8


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
|           30 |     2394 | 2024-05-04 | Monte           | L   | 0.578      | -            | -                | -                | -         |    -7.56 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2422 | 2024-05-02 | GamerLegion     | L   | 0.567      | -            | -                | -                | -         |    -4.66 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     2448 | 2024-05-01 | FURIA           | W   | 0.560      | 0.889        | 0.284 (0.141)    | 0.481 (0.239)    | 1 (0.560) |    17.31 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |     2471 | 2024-04-30 | Monte           | L   | 0.553      | -            | -                | -                | -         |    -7.23 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |     2926 | 2024-04-12 | BIG             | L   | 0.433      | -            | -                | -                | -         |    -1.55 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     2959 | 2024-04-11 | Aurora          | L   | 0.425      | -            | -                | -                | -         |    -0.26 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     2991 | 2024-04-10 | TSM             | W   | 0.420      | -            | -                | -                | 0 (0.000) |     2.59 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     3046 | 2024-04-09 | brazylijski luz | W   | 0.413      | 0.500        | 0.008 (0.002)    | 0.257 (0.053)    | 0 (0.000) |     4.27 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     3087 | 2024-04-08 | ENCE            | W   | 0.405      | 0.684        | 0.174 (0.048)    | 0.432 (0.120)    | 0 (0.000) |    12.17 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     3360 | 2024-03-27 | 500             | L   | 0.327      | -            | -                | -                | -         |    -7.83 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     3391 | 2024-03-26 | Apeks           | W   | 0.318      | 0.500        | 0.027 (0.004)    | 0.160 (0.026)    | 0 (0.000) |     4.81 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     3397 | 2024-03-25 | B8              | L   | 0.313      | -            | -                | -                | -         |    -2.79 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     3402 | 2024-03-24 | BetBoom         | W   | 0.305      | 0.143        | 0.249 (0.011)    | 0.529 (0.023)    | 0 (0.000) |     9.04 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     3413 | 2024-03-23 | VP.Prodigy      | W   | 0.299      | 0.143        | -                | 0.393 (0.017)    | 0 (0.000) |     4.20 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     3427 | 2024-03-22 | ex-Preasy       | W   | 0.292      | -            | -                | -                | 0 (0.000) |     3.37 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     3450 | 2024-03-21 | PARIVISION      | L   | 0.286      | -            | -                | -                | -         |    -2.15 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     3474 | 2024-03-20 | NAVI Junior     | W   | 0.279      | -            | -                | -                | 0 (0.000) |     1.00 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     3831 | 2024-03-05 | KOI             | L   | 0.180      | -            | -                | -                | -         |    -1.55 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     3836 | 2024-03-05 | AMKAL           | W   | 0.180      | 0.143        | 0.130 (0.003)    | 0.465 (0.012)    | 0 (0.000) |     4.49 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     3843 | 2024-03-05 | 3DMAX           | W   | 0.180      | 0.143        | 0.508 (0.013)    | 1.000 (0.026)    | -         |     5.58 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     3932 | 2024-03-01 | Aurora          | L   | 0.153      | -            | -                | -                | -         |    -0.06 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     3941 | 2024-02-29 | 9 Pandas        | W   | 0.147      | 0.143        | 0.081 (0.002)    | 0.717 (0.015)    | -         |     2.98 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     3953 | 2024-02-28 | KOI             | W   | 0.140      | 0.143        | 0.058 (0.001)    | -                | -         |     3.30 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     3958 | 2024-02-28 | Aurora          | W   | 0.139      | 0.143        | 0.422 (0.008)    | 0.778 (0.015)    | -         |     4.32 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     3971 | 2024-02-27 | V1dar           | W   | 0.133      | -            | -                | -                | -         |     0.49 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     3979 | 2024-02-27 | ARCRED          | W   | 0.133      | -            | -                | -                | -         |     2.25 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4378 | 2024-02-09 | Sashi           | L   | 0.013      | -            | -                | -                | -         |    -0.07 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4383 | 2024-02-09 | RUBY            | W   | 0.012      | -            | -                | -                | -         |     0.21 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4391 | 2024-02-08 | BetBoom         | W   | 0.007      | -            | -                | -                | -         |     0.20 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4396 | 2024-02-08 | Sashi           | L   | 0.006      | -            | -                | -                | -         |    -0.03 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,580.07)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.819 | $3,000.00      | $2,457.71       |
| 2024-05-12 |      0.632 | $7,000.00      | $4,426.53       |
| 2024-04-14 |      0.446 | $26,250.00     | $11,695.83      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
