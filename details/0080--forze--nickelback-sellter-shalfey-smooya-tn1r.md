### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  933.2<br />
<br />
Final Rank Value (933.2) = Starting Rank Value (885.0) + Head To Head Adjustments (48.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.381[<sup>2</sup>](#table1)
- Opponent Network: 0.055[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.237<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 885.0
- 400 + ( ( 0.237 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 885.0


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
|           30 |     2368 | 2024-05-04 | Monte           | L   | 0.585      | -            | -                | -                | -         |    -7.64 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2396 | 2024-05-02 | GamerLegion     | L   | 0.574      | -            | -                | -                | -         |    -4.75 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     2422 | 2024-05-01 | FURIA           | W   | 0.567      | 0.889        | 0.284 (0.143)    | 0.490 (0.247)    | 1 (0.567) |    17.53 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |     2445 | 2024-04-30 | Monte           | L   | 0.560      | -            | -                | -                | -         |    -7.31 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |     2900 | 2024-04-12 | BIG             | L   | 0.440      | -            | -                | -                | -         |    -1.58 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     2933 | 2024-04-11 | Aurora          | L   | 0.432      | -            | -                | -                | -         |    -0.27 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     2965 | 2024-04-10 | TSM             | W   | 0.427      | -            | -                | -                | 0 (0.000) |     2.62 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     3020 | 2024-04-09 | brazylijski luz | W   | 0.420      | 0.500        | 0.008 (0.002)    | 0.261 (0.055)    | 0 (0.000) |     4.34 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     3061 | 2024-04-08 | ENCE            | W   | 0.413      | 0.684        | 0.169 (0.048)    | 0.400 (0.113)    | 0 (0.000) |    12.35 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     3334 | 2024-03-27 | 500             | L   | 0.334      | -            | -                | -                | -         |    -8.02 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     3365 | 2024-03-26 | Apeks           | W   | 0.326      | 0.500        | 0.027 (0.004)    | 0.166 (0.027)    | 0 (0.000) |     4.94 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     3371 | 2024-03-25 | B8              | L   | 0.320      | -            | -                | -                | -         |    -2.87 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     3376 | 2024-03-24 | BetBoom         | W   | 0.312      | 0.143        | 0.251 (0.011)    | 0.541 (0.024)    | 0 (0.000) |     9.26 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     3387 | 2024-03-23 | VP.Prodigy      | W   | 0.306      | 0.143        | -                | 0.401 (0.018)    | 0 (0.000) |     4.28 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     3401 | 2024-03-22 | ex-Preasy       | W   | 0.299      | -            | -                | -                | 0 (0.000) |     3.47 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     3424 | 2024-03-21 | PARIVISION      | L   | 0.293      | -            | -                | -                | -         |    -2.26 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     3448 | 2024-03-20 | NAVI Junior     | W   | 0.286      | -            | -                | -                | 0 (0.000) |     1.02 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     3805 | 2024-03-05 | KOI             | L   | 0.188      | -            | -                | -                | -         |    -1.60 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     3810 | 2024-03-05 | AMKAL           | W   | 0.187      | 0.143        | 0.130 (0.003)    | 0.475 (0.013)    | 0 (0.000) |     4.67 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     3817 | 2024-03-05 | 3DMAX           | W   | 0.187      | 0.143        | 0.506 (0.014)    | 1.000 (0.027)    | -         |     5.81 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     3906 | 2024-03-01 | Aurora          | L   | 0.161      | -            | -                | -                | -         |    -0.07 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     3915 | 2024-02-29 | 9 Pandas        | W   | 0.154      | 0.143        | 0.081 (0.002)    | 0.690 (0.015)    | -         |     3.14 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     3927 | 2024-02-28 | KOI             | W   | 0.147      | 0.143        | 0.058 (0.001)    | -                | -         |     3.49 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     3932 | 2024-02-28 | Aurora          | W   | 0.146      | 0.143        | 0.423 (0.009)    | 0.793 (0.017)    | -         |     4.55 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     3945 | 2024-02-27 | V1dar           | W   | 0.141      | -            | -                | -                | -         |     0.52 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     3953 | 2024-02-27 | ARCRED          | W   | 0.140      | -            | -                | -                | -         |     2.08 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4352 | 2024-02-09 | Sashi           | L   | 0.021      | -            | -                | -                | -         |    -0.11 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4357 | 2024-02-09 | RUBY            | W   | 0.019      | -            | -                | -                | -         |     0.34 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4365 | 2024-02-08 | BetBoom         | W   | 0.014      | -            | -                | -                | -         |     0.42 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4370 | 2024-02-08 | Sashi           | L   | 0.013      | -            | -                | -                | -         |    -0.07 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,842.71)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.826 | $3,000.00      | $2,479.44       |
| 2024-05-12 |      0.640 | $7,000.00      | $4,477.25       |
| 2024-04-14 |      0.453 | $26,250.00     | $11,886.02      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
