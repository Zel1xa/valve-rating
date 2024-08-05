### Roster Details<br />
Team Name: Elevate<br />
Roster: dare, intra, Peeping, shane, snav<br />
Global Rank: [87](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [23]( ../standings_americas.md)<br />
<br />
Final Rank Value:  908.5<br />
<br />
Final Rank Value (908.5) = Starting Rank Value (1003.5) + Head To Head Adjustments (-95.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.149[<sup>2</sup>](#table1)
- LAN Wins: 0.316[<sup>2</sup>](#table1)

The average of these factors is 0.295<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1003.5
- 400 + ( ( 0.295 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1003.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           69 |       26 | 2024-08-03 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.531 (0.161)    | 0 (0.000) |    19.17 | dare, intra, Peeping, shane, snav   |
|           68 |      139 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -13.84 | dare, dea, Peeping, shane, snav     |
|           67 |      145 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.11 | dare, dea, Peeping, shane, snav     |
|           66 |      384 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -12.31 | dare, dea, Peeping, shane, snav     |
|           65 |      387 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -13.41 | dare, dea, Peeping, shane, snav     |
|           64 |      480 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -18.59 | dare, Fr3nk1e, Peeping, shane, snav |
|           63 |      508 | 2024-07-20 | Phoenix          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.53 | dare, Fr3nk1e, Peeping, shane, snav |
|           62 |      578 | 2024-07-18 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -21.88 | dare, Fr3nk1e, Peeping, shane, snav |
|           61 |      580 | 2024-07-18 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.332 (0.158)    | 0 (0.000) |     9.16 | dare, Fr3nk1e, Peeping, shane, snav |
|           60 |      642 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.283 (0.135)    | 0 (0.000) |     5.48 | dare, Fr3nk1e, Peeping, shane, snav |
|           59 |      646 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.283 (0.135)    | 0 (0.000) |     5.77 | dare, Fr3nk1e, Peeping, shane, snav |
|           58 |      704 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.299 (0.142)    | 0 (0.000) |     8.70 | dare, Fr3nk1e, Peeping, shane, snav |
|           57 |      711 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.299 (0.142)    | 0 (0.000) |     9.35 | dare, Fr3nk1e, Peeping, shane, snav |
|           56 |      755 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -20.24 | dare, dea, Peeping, shane, snav     |
|           55 |      759 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -21.89 | dare, dea, Peeping, shane, snav     |
|           54 |      970 | 2024-06-23 | Locke's Kittens  | W   | 0.920      | -            | -                | -                | 1 (0.920) |     6.82 | dare, dea, Peeping, shane, snav     |
|           53 |      972 | 2024-06-23 | WICKED           | W   | 0.919      | -            | -                | -                | 1 (0.919) |     3.03 | dare, dea, Peeping, shane, snav     |
|           52 |      976 | 2024-06-22 | LOCK IN          | W   | 0.913      | -            | -                | -                | 1 (0.913) |     1.12 | dare, dea, Peeping, shane, snav     |
|           51 |      993 | 2024-06-16 | Legacy           | L   | 0.873      | -            | -                | -                | -         |   -11.29 | dare, dea, Peeping, shane, snav     |
|           50 |     1016 | 2024-06-15 | BOSS             | W   | 0.867      | -            | -                | -                | -         |     6.53 | dare, dea, Peeping, shane, snav     |
|           49 |     1051 | 2024-06-14 | FLUFFY AIMERS    | W   | 0.860      | -            | -                | -                | -         |     4.88 | dare, dea, Peeping, shane, snav     |
|           48 |     1329 | 2024-06-07 | Nouns            | L   | 0.812      | -            | -                | -                | -         |   -12.97 | dare, dea, Peeping, shane, snav     |
|           47 |     1332 | 2024-06-07 | Nouns            | W   | 0.812      | 0.143        | 0.057 (0.007)    | -                | -         |    12.78 | dare, dea, Peeping, shane, snav     |
|           46 |     1337 | 2024-06-07 | Legacy           | L   | 0.812      | -            | -                | -                | -         |   -11.15 | dare, dea, Peeping, shane, snav     |
|           45 |     1378 | 2024-06-06 | Nouns            | L   | 0.807      | -            | -                | -                | -         |   -12.80 | dare, dea, Peeping, shane, snav     |
|           44 |     1388 | 2024-06-06 | FlyQuest RED     | W   | 0.806      | 0.384        | 0.017 (0.005)    | -                | -         |     5.26 | dare, dea, Peeping, shane, snav     |
|           43 |     1449 | 2024-06-05 | Mythic           | W   | 0.800      | 0.477        | -                | 0.299 (0.114)    | -         |     7.07 | dare, dea, Peeping, shane, snav     |
|           42 |     1501 | 2024-06-04 | Party Astronauts | L   | 0.793      | -            | -                | -                | -         |   -13.90 | dare, dea, Peeping, shane, snav     |
|           41 |     1809 | 2024-05-22 | NRG              | W   | 0.707      | 0.477        | 0.020 (0.007)    | 0.521 (0.176)    | -         |     8.81 | dare, dea, Peeping, shane, snav     |
|           40 |     1815 | 2024-05-22 | NRG              | W   | 0.707      | 0.477        | 0.020 (0.007)    | 0.521 (0.176)    | -         |     9.36 | dare, dea, Peeping, shane, snav     |
|           39 |     1858 | 2024-05-21 | Take Flyte       | W   | 0.700      | -            | -                | -                | -         |     3.33 | dare, dea, Peeping, shane, snav     |
|           38 |     1862 | 2024-05-21 | Take Flyte       | W   | 0.700      | -            | -                | -                | -         |     3.44 | dare, dea, Peeping, shane, snav     |
|           37 |     1903 | 2024-05-20 | Mythic           | L   | 0.693      | -            | -                | -                | -         |   -16.29 | dare, dea, Peeping, shane, snav     |
|           36 |     1989 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.674      | -            | -                | -                | -         |     4.05 | dare, dea, Peeping, shane, snav     |
|           35 |     1990 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.673      | -            | -                | -                | -         |     4.20 | dare, dea, Peeping, shane, snav     |
|           34 |     2061 | 2024-05-15 | Limitless        | W   | 0.660      | -            | -                | -                | -         |     2.62 | dare, dea, Peeping, shane, snav     |
|           33 |     2068 | 2024-05-15 | Limitless        | W   | 0.660      | -            | -                | -                | -         |     2.68 | dare, dea, Peeping, shane, snav     |
|           32 |     2114 | 2024-05-14 | M80              | L   | 0.654      | -            | -                | -                | -         |    -3.60 | dare, dea, Peeping, shane, snav     |
|           31 |     2121 | 2024-05-14 | M80              | L   | 0.653      | -            | -                | -                | -         |    -3.72 | dare, dea, Peeping, shane, snav     |
|           30 |     2130 | 2024-05-14 | Phoenix          | W   | 0.653      | -            | -                | -                | -         |     4.33 | dare, dea, Peeping, shane, snav     |
|           29 |     2133 | 2024-05-14 | Phoenix          | W   | 0.653      | -            | -                | -                | -         |     4.50 | dare, dea, Peeping, shane, snav     |
|           28 |     2189 | 2024-05-12 | NRG              | L   | 0.639      | -            | -                | -                | -         |   -12.76 | dare, dea, intra, Peeping, snav     |
|           27 |     2209 | 2024-05-11 | Nouns            | W   | 0.633      | 0.270        | 0.057 (0.010)    | -                | -         |     8.92 | dare, dea, intra, Peeping, snav     |
|           26 |     2210 | 2024-05-11 | Wildcard         | W   | 0.633      | 0.270        | 0.048 (0.008)    | -                | -         |     7.59 | dare, dea, intra, Peeping, snav     |
|           25 |     2213 | 2024-05-11 | Nouns            | L   | 0.633      | -            | -                | -                | -         |   -10.66 | dare, dea, intra, Peeping, snav     |
|           24 |     2280 | 2024-05-08 | MIGHT            | W   | 0.614      | -            | -                | -                | -         |     1.47 | dare, dea, Peeping, shane, snav     |
|           23 |     2282 | 2024-05-08 | MIGHT            | W   | 0.613      | -            | -                | -                | -         |     1.50 | dare, dea, Peeping, shane, snav     |
|           22 |     2304 | 2024-05-07 | Party Astronauts | W   | 0.607      | 0.477        | 0.041 (0.012)    | 0.531 (0.154)    | -         |     8.80 | dare, dea, Peeping, shane, snav     |
|           21 |     2305 | 2024-05-07 | Party Astronauts | L   | 0.607      | -            | -                | -                | -         |   -10.57 | dare, dea, Peeping, shane, snav     |
|           20 |     2602 | 2024-04-23 | Wildcard         | L   | 0.514      | -            | -                | -                | -         |   -10.47 | dare, dea, Peeping, shane, snav     |
|           19 |     2604 | 2024-04-23 | Wildcard         | W   | 0.513      | 0.477        | 0.048 (0.012)    | -                | -         |     5.78 | dare, dea, Peeping, shane, snav     |
|           18 |     2741 | 2024-04-18 | Legacy           | L   | 0.480      | -            | -                | -                | -         |    -6.85 | dare, dea, Peeping, shane, snav     |
|           17 |     2746 | 2024-04-18 | M80              | L   | 0.479      | -            | -                | -                | -         |    -3.34 | dare, dea, Peeping, shane, snav     |
|           16 |     2791 | 2024-04-17 | Nouns            | W   | 0.473      | -            | -                | -                | -         |     6.45 | dare, dea, Peeping, shane, snav     |
|           15 |     2796 | 2024-04-17 | Wildcard         | W   | 0.473      | -            | -                | -                | -         |     5.46 | dare, dea, Peeping, shane, snav     |
|           14 |     2944 | 2024-04-10 | Nouns            | L   | 0.427      | -            | -                | -                | -         |    -7.85 | dare, dea, Peeping, shane, snav     |
|           13 |     2950 | 2024-04-10 | Nouns            | L   | 0.427      | -            | -                | -                | -         |    -8.14 | dare, dea, Peeping, shane, snav     |
|           12 |     3179 | 2024-04-03 | LAG              | W   | 0.380      | -            | -                | -                | -         |     3.65 | dare, dea, Peeping, shane, snav     |
|           11 |     3181 | 2024-04-03 | LAG              | L   | 0.380      | -            | -                | -                | -         |    -8.50 | dare, dea, Peeping, shane, snav     |
|           10 |     3356 | 2024-03-26 | BOSS             | W   | 0.327      | -            | -                | -                | -         |     2.57 | dare, dea, Peeping, shane, snav     |
|            9 |     3361 | 2024-03-26 | BOSS             | W   | 0.327      | -            | -                | -                | -         |     2.63 | dare, dea, Peeping, shane, snav     |
|            8 |     3528 | 2024-03-15 | Carpe Diem       | W   | 0.254      | -            | -                | -                | -         |     1.17 | dare, dea, Peeping, shane, snav     |
|            7 |     3530 | 2024-03-15 | Carpe Diem       | W   | 0.254      | -            | -                | -                | -         |     1.18 | dare, dea, Peeping, shane, snav     |
|            6 |     3629 | 2024-03-12 | Party Astronauts | L   | 0.233      | -            | -                | -                | -         |    -4.41 | dare, dea, Peeping, shane, snav     |
|            5 |     3729 | 2024-03-08 | Spirit           | L   | 0.204      | -            | -                | -                | -         |    -0.04 | dare, MRC9, Peeping, shane, snav    |
|            4 |     3881 | 2024-03-02 | ODDIK            | L   | 0.165      | -            | -                | -                | -         |    -2.65 | dare, nbgee12, Peeping, shane, snav |
|            3 |     3909 | 2024-03-01 | Complexity       | L   | 0.158      | -            | -                | -                | -         |    -0.13 | dare, nbgee12, Peeping, shane, snav |
|            2 |     4298 | 2024-02-13 | Mythic           | L   | 0.047      | -            | -                | -                | -         |    -1.14 | dare, dea, Peeping, shane, snav     |
|            1 |     4301 | 2024-02-13 | Mythic           | W   | 0.047      | -            | -                | -                | -         |     0.34 | dare, dea, Peeping, shane, snav     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,675.63)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-23 |      0.920 | $3,000.00      | $2,761.25       |
| 2024-06-16 |      0.873 | $1,500.00      | $1,310.21       |
| 2024-06-09 |      0.826 | $4,250.00      | $3,512.15       |
| 2024-03-10 |      0.218 | $5,000.00      | $1,092.01       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
