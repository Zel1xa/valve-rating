### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, fostar, Kaide, mo0N, sowalio<br />
Global Rank: [93](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
<br />
Final Rank Value:  888.3<br />
<br />
Final Rank Value (888.3) = Starting Rank Value (931.7) + Head To Head Adjustments (-43.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.494[<sup>1</sup>](#table2)
- Bounty Collected: 0.375[<sup>2</sup>](#table1)
- Opponent Network: 0.167[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 931.7
- 400 + ( ( 0.259 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 931.7


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
|           48 |       50 | 2024-08-04 | Project G       | L   | 1.000      | -            | -                | -                | -         |   -27.68 | dekz, fostar, Kaide, mo0N, sowalio |
|           47 |      393 | 2024-07-25 | 9z              | L   | 1.000      | -            | -                | -                | -         |    -1.32 | dekz, fostar, Kaide, mo0N, sowalio |
|           46 |      473 | 2024-07-23 | Metizport       | W   | 1.000      | 0.435        | 0.036 (0.016)    | 0.444 (0.193)    | 0 (0.000) |    17.38 | dekz, fostar, Kaide, mo0N, sowalio |
|           45 |      568 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -8.97 | dekz, fostar, Kaide, mo0N, sowalio |
|           44 |      720 | 2024-07-17 | VP.Prodigy      | W   | 1.000      | 0.435        | 0.025 (0.011)    | 0.392 (0.170)    | 0 (0.000) |    14.47 | dekz, fostar, Kaide, mo0N, sowalio |
|           43 |      766 | 2024-07-16 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -15.38 | dekz, fostar, Kaide, mo0N, sowalio |
|           42 |     1036 | 2024-06-16 | ARCRED          | W   | 0.861      | 0.450        | 0.041 (0.016)    | 0.377 (0.146)    | 0 (0.000) |    16.63 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           41 |     1056 | 2024-06-15 | System5         | L   | 0.855      | -            | -                | -                | -         |   -20.99 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           40 |     1069 | 2024-06-15 | Spirit Academy  | W   | 0.854      | 0.450        | 0.013 (0.005)    | -                | 0 (0.000) |     7.79 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           39 |     1100 | 2024-06-14 | Zero Tenacity   | L   | 0.849      | -            | -                | -                | -         |    -7.28 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           38 |     1107 | 2024-06-14 | LEON            | W   | 0.848      | -            | -                | -                | 0 (0.000) |     6.12 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           37 |     1249 | 2024-06-09 | Insilio         | L   | 0.815      | -            | -                | -                | -         |   -10.71 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           36 |     1396 | 2024-06-07 | SINNERS         | L   | 0.800      | -            | -                | -                | -         |    -9.19 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           35 |     1509 | 2024-06-05 | ARCRED          | L   | 0.788      | -            | -                | -                | -         |   -11.73 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           34 |     1525 | 2024-06-05 | Rare Atom       | L   | 0.786      | -            | -                | -                | -         |   -16.28 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           33 |     1574 | 2024-06-03 | Insilio         | W   | 0.776      | 0.372        | 0.023 (0.007)    | 0.552 (0.159)    | 0 (0.000) |    12.25 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           32 |     1583 | 2024-06-03 | HAVU            | L   | 0.774      | -            | -                | -                | -         |   -19.23 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           31 |     1617 | 2024-06-01 | Zero Tenacity   | W   | 0.762      | 0.372        | 0.143 (0.041)    | 1.000 (0.284)    | 0 (0.000) |    17.43 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           30 |     1680 | 2024-05-30 | Portugal        | W   | 0.749      | -            | -                | -                | 0 (0.000) |     4.44 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           29 |     1693 | 2024-05-30 | FURIA           | L   | 0.747      | -            | -                | -                | -         |    -0.58 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           28 |     1737 | 2024-05-28 | MOUZ NXT        | L   | 0.735      | -            | -                | -                | -         |    -7.68 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           27 |     1778 | 2024-05-26 | Zero Tenacity   | L   | 0.721      | -            | -                | -                | -         |    -6.58 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           26 |     1788 | 2024-05-25 | B8              | L   | 0.716      | -            | -                | -                | -         |    -5.15 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           25 |     1826 | 2024-05-23 | Nexus           | W   | 0.701      | 0.435        | 0.014 (0.004)    | 0.457 (0.139)    | 0 (0.000) |     6.48 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           24 |     1919 | 2024-05-21 | Endpoint        | W   | 0.686      | 0.435        | -                | 0.513 (0.153)    | 0 (0.000) |    10.19 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           23 |     2257 | 2024-05-11 | 9 Pandas        | L   | 0.621      | -            | -                | -                | -         |    -8.25 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           22 |     2283 | 2024-05-10 | Nemiga          | W   | 0.613      | 0.435        | 0.315 (0.084)    | 0.720 (0.192)    | -         |    15.14 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           21 |     2340 | 2024-05-07 | Insilio         | W   | 0.595      | 0.435        | 0.023 (0.006)    | 0.552 (0.143)    | -         |     9.47 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           20 |     2383 | 2024-05-05 | HAVU            | W   | 0.581      | -            | -                | -                | -         |     4.06 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           19 |     2413 | 2024-05-03 | V1dar           | W   | 0.567      | -            | -                | -                | -         |     1.80 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           18 |     2470 | 2024-05-01 | GL Academy      | L   | 0.553      | -            | -                | -                | -         |   -12.75 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           17 |     2512 | 2024-04-29 | Permitta        | L   | 0.540      | -            | -                | -                | -         |    -8.07 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           16 |     2543 | 2024-04-27 | Astralis Talent | W   | 0.528      | -            | -                | -                | -         |     0.76 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           15 |     2703 | 2024-04-20 | Zero Tenacity   | L   | 0.481      | -            | -                | -                | -         |    -5.04 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           14 |     2783 | 2024-04-18 | Sashi           | L   | 0.469      | -            | -                | -                | -         |    -4.04 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           13 |     2793 | 2024-04-18 | Aurora          | W   | 0.468      | 0.143        | 0.421 (0.028)    | -                | -         |    14.47 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           12 |     2800 | 2024-04-18 | NOM             | W   | 0.468      | -            | -                | -                | -         |     1.57 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           11 |     2853 | 2024-04-17 | JANO            | W   | 0.460      | -            | -                | -                | -         |     2.86 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           10 |     3493 | 2024-03-19 | Sashi           | L   | 0.269      | -            | -                | -                | -         |    -2.08 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            9 |     3550 | 2024-03-16 | Permitta        | W   | 0.248      | 0.372        | -                | 0.940 (0.087)    | -         |     4.42 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            8 |     3687 | 2024-03-11 | Nexus           | L   | 0.215      | -            | -                | -                | -         |    -4.28 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            7 |     3724 | 2024-03-09 | Spirit Academy  | W   | 0.202      | -            | -                | -                | -         |     0.68 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            6 |     3750 | 2024-03-08 | ARCRED          | W   | 0.195      | -            | -                | -                | -         |     2.93 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            5 |     3980 | 2024-02-27 | Spirit Academy  | L   | 0.129      | -            | -                | -                | -         |    -3.65 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            4 |     3984 | 2024-02-27 | ALTERNATE aTTaX | W   | 0.129      | -            | -                | -                | -         |     2.31 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            3 |     4389 | 2024-02-09 | FORZE           | L   | 0.008      | -            | -                | -                | -         |    -0.14 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            2 |     4400 | 2024-02-08 | AMKAL           | L   | 0.002      | -            | -                | -                | -         |    -0.02 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            1 |     4403 | 2024-02-08 | ex-Guild Eagles | W   | 0.001      | -            | -                | -                | -         |     0.01 | dekz, Kaide, mo0N, sowalio, w1nt3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,404.21)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.861 | $30,000.00     | $25,816.67      |
| 2024-06-10 |      0.822 | $3,300.00      | $2,713.79       |
| 2024-05-12 |      0.629 | $2,000.00      | $1,257.08       |
| 2024-03-25 |      0.308 | $2,000.00      | $616.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
