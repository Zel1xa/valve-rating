### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [67](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  964.6<br />
<br />
Final Rank Value (964.6) = Starting Rank Value (933.2) + Head To Head Adjustments (31.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.418[<sup>1</sup>](#table2)
- Bounty Collected: 0.418[<sup>2</sup>](#table1)
- Opponent Network: 0.173[<sup>2</sup>](#table1)
- LAN Wins: 0.027[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 933.2
- 400 + ( ( 0.259 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 933.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |       47 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |    -9.54 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |      209 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.512 (0.256)    | 0 (0.000) |     9.69 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |      493 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -12.81 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |      629 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.012)    | 0.554 (0.277)    | 0 (0.000) |    15.65 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1113 | 2024-06-09 | Sangal          | L   | 0.846      | -            | -                | -                | -         |    -6.18 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1312 | 2024-06-06 | SINNERS         | W   | 0.826      | 0.500        | 0.038 (0.016)    | 0.768 (0.317)    | 0 (0.000) |    14.40 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1376 | 2024-06-05 | 3DMAX           | W   | 0.820      | 0.500        | 0.505 (0.207)    | 1.000 (0.410)    | 0 (0.000) |    24.88 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1506 | 2024-06-01 | ENCE            | L   | 0.793      | -            | -                | -                | -         |    -2.07 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     1512 | 2024-06-01 | Zero Tenacity   | L   | 0.792      | -            | -                | -                | -         |    -7.00 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2219 | 2024-05-09 | B8              | L   | 0.637      | -            | -                | -                | -         |    -7.08 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2386 | 2024-05-01 | Zero Tenacity   | L   | 0.585      | -            | -                | -                | -         |    -6.49 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2711 | 2024-04-18 | ex-Guild Eagles | L   | 0.500      | -            | -                | -                | -         |   -10.36 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2722 | 2024-04-18 | fnatic          | W   | 0.499      | 0.143        | 0.292 (0.021)    | 0.568 (0.041)    | 0 (0.000) |    14.20 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2797 | 2024-04-16 | BLEED           | L   | 0.486      | -            | -                | -                | -         |    -6.48 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     2930 | 2024-04-10 | RUSH B          | W   | 0.447      | 0.500        | 0.017 (0.004)    | 0.308 (0.069)    | 0 (0.000) |     5.34 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     2985 | 2024-04-09 | Aurora          | W   | 0.440      | 0.500        | 0.431 (0.095)    | 0.798 (0.176)    | 0 (0.000) |    13.62 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     2991 | 2024-04-09 | Apeks           | L   | 0.439      | -            | -                | -                | -         |    -7.28 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     3018 | 2024-04-08 | GUN5            | W   | 0.433      | -            | -                | -                | -         |     0.62 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     3019 | 2024-04-08 | fnatic          | L   | 0.432      | -            | -                | -                | -         |    -1.19 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3122 | 2024-04-04 | NOM             | W   | 0.406      | -            | -                | -                | -         |     1.02 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3158 | 2024-04-03 | 9INE            | W   | 0.400      | -            | -                | -                | -         |     1.10 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3202 | 2024-04-02 | TSM             | W   | 0.393      | -            | -                | -                | -         |     2.39 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3269 | 2024-03-28 | EYEBALLERS      | L   | 0.359      | -            | -                | -                | -         |    -6.28 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3446 | 2024-03-18 | FURIA           | L   | 0.293      | -            | -                | -                | -         |    -0.12 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3461 | 2024-03-17 | ENCE            | L   | 0.287      | -            | -                | -                | -         |    -0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3477 | 2024-03-17 | SAW             | L   | 0.286      | -            | -                | -                | -         |    -1.80 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3574 | 2024-03-13 | Sangal          | W   | 0.260      | 0.500        | 0.221 (0.029)    | 0.823 (0.107)    | -         |     6.09 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3628 | 2024-03-11 | B8              | L   | 0.247      | -            | -                | -                | -         |    -2.33 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3637 | 2024-03-11 | Apeks           | L   | 0.246      | -            | -                | -                | -         |    -4.12 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3750 | 2024-03-06 | 9 Pandas        | W   | 0.214      | 0.500        | 0.083 (0.009)    | 0.577 (0.062)    | -         |     3.95 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3786 | 2024-03-05 | FORZE           | W   | 0.207      | -            | -                | -                | -         |     3.09 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3792 | 2024-03-05 | Nemiga          | W   | 0.207      | 0.143        | 0.324 (0.010)    | 0.697 (0.021)    | -         |     5.10 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3805 | 2024-03-05 | ex-Sprout       | W   | 0.206      | -            | -                | -                | -         |     0.61 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3845 | 2024-03-03 | The Chosen Few  | L   | 0.193      | -            | -                | -                | -         |    -4.97 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3901 | 2024-02-29 | Aurora          | L   | 0.173      | -            | -                | -                | -         |    -0.08 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3905 | 2024-02-29 | HAVU            | W   | 0.172      | -            | -                | -                | -         |     1.19 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3914 | 2024-02-28 | FORZE           | L   | 0.167      | -            | -                | -                | -         |    -2.90 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     3919 | 2024-02-28 | kONO            | W   | 0.166      | -            | -                | -                | -         |     1.77 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4218 | 2024-02-16 | fnatic          | W   | 0.085      | -            | -                | -                | 1 (0.085) |     2.46 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4242 | 2024-02-15 | 9 Pandas        | W   | 0.078      | -            | -                | -                | 1 (0.078) |     1.46 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4271 | 2024-02-14 | 3DMAX           | W   | 0.073      | 0.143        | 0.505 (0.005)    | -                | 1 (0.073) |     2.28 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4285 | 2024-02-14 | Natus Vincere   | L   | 0.072      | -            | -                | -                | -         |    -0.01 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,217.78)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $12,000.00     | $10,152.50      |
| 2024-03-20 |      0.307 | $10,000.00     | $3,065.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
