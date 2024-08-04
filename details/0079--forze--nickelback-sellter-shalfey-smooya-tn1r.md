### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [79](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  933.6<br />
<br />
Final Rank Value (933.6) = Starting Rank Value (885.1) + Head To Head Adjustments (48.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.381[<sup>2</sup>](#table1)
- Opponent Network: 0.056[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.237<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 885.1
- 400 + ( ( 0.237 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 885.1


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
|           30 |     2344 | 2024-05-04 | Monte           | L   | 0.586      | -            | -                | -                | -         |    -7.63 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2372 | 2024-05-02 | GamerLegion     | L   | 0.575      | -            | -                | -                | -         |    -4.77 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     2398 | 2024-05-01 | FURIA           | W   | 0.568      | 0.889        | 0.284 (0.143)    | 0.490 (0.248)    | 1 (0.568) |    17.56 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |     2421 | 2024-04-30 | Monte           | L   | 0.561      | -            | -                | -                | -         |    -7.30 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |     2876 | 2024-04-12 | BIG             | L   | 0.441      | -            | -                | -                | -         |    -1.59 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     2909 | 2024-04-11 | Aurora          | L   | 0.433      | -            | -                | -                | -         |    -0.28 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     2941 | 2024-04-10 | TSM             | W   | 0.428      | -            | -                | -                | 0 (0.000) |     2.62 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     2996 | 2024-04-09 | brazylijski luz | W   | 0.422      | 0.500        | 0.008 (0.002)    | 0.262 (0.055)    | 0 (0.000) |     4.33 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     3037 | 2024-04-08 | ENCE            | W   | 0.414      | 0.684        | 0.169 (0.048)    | 0.400 (0.113)    | 0 (0.000) |    12.38 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     3310 | 2024-03-27 | 500             | L   | 0.335      | -            | -                | -                | -         |    -8.05 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     3341 | 2024-03-26 | Apeks           | W   | 0.327      | 0.500        | 0.027 (0.004)    | 0.166 (0.027)    | 0 (0.000) |     4.97 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     3347 | 2024-03-25 | B8              | L   | 0.321      | -            | -                | -                | -         |    -2.88 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     3352 | 2024-03-24 | BetBoom         | W   | 0.313      | 0.143        | 0.251 (0.011)    | 0.541 (0.024)    | 0 (0.000) |     9.29 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     3363 | 2024-03-23 | VP.Prodigy      | W   | 0.307      | 0.143        | -                | 0.401 (0.018)    | 0 (0.000) |     4.28 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     3377 | 2024-03-22 | ex-Preasy       | W   | 0.300      | -            | -                | -                | 0 (0.000) |     3.50 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     3400 | 2024-03-21 | PARIVISION      | L   | 0.294      | -            | -                | -                | -         |    -2.29 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     3424 | 2024-03-20 | NAVI Junior     | W   | 0.287      | -            | -                | -                | 0 (0.000) |     1.02 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     3781 | 2024-03-05 | KOI             | L   | 0.189      | -            | -                | -                | -         |    -1.62 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     3786 | 2024-03-05 | AMKAL           | W   | 0.188      | 0.143        | 0.130 (0.003)    | 0.475 (0.013)    | 0 (0.000) |     4.70 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     3793 | 2024-03-05 | 3DMAX           | W   | 0.188      | 0.143        | 0.506 (0.014)    | 1.000 (0.027)    | -         |     5.84 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     3882 | 2024-03-01 | Aurora          | L   | 0.162      | -            | -                | -                | -         |    -0.07 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     3891 | 2024-02-29 | 9 Pandas        | W   | 0.155      | 0.143        | 0.082 (0.002)    | 0.690 (0.015)    | -         |     3.16 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     3903 | 2024-02-28 | KOI             | W   | 0.148      | 0.143        | 0.058 (0.001)    | -                | -         |     3.51 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     3908 | 2024-02-28 | Aurora          | W   | 0.147      | 0.143        | 0.423 (0.009)    | 0.793 (0.017)    | -         |     4.58 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     3921 | 2024-02-27 | V1dar           | W   | 0.142      | -            | -                | -                | -         |     0.52 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     3929 | 2024-02-27 | ARCRED          | W   | 0.141      | -            | -                | -                | -         |     2.10 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4328 | 2024-02-09 | Sashi           | L   | 0.022      | -            | -                | -                | -         |    -0.12 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4333 | 2024-02-09 | RUBY            | W   | 0.021      | -            | -                | -                | -         |     0.36 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4341 | 2024-02-08 | BetBoom         | W   | 0.015      | -            | -                | -                | -         |     0.45 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4346 | 2024-02-08 | Sashi           | L   | 0.014      | -            | -                | -                | -         |    -0.08 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,881.31)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.828 | $3,000.00      | $2,482.64       |
| 2024-05-12 |      0.641 | $7,000.00      | $4,484.70       |
| 2024-04-14 |      0.454 | $26,250.00     | $11,913.98      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
