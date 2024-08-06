### Roster Details<br />
Team Name: Nexus<br />
Roster: 7kick, BTN, Ciocardau, ragga, XELLOW<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [90]( ../standings_europe.md)<br />
<br />
Final Rank Value:  783.7<br />
<br />
Final Rank Value (783.7) = Starting Rank Value (840.5) + Head To Head Adjustments (-56.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.349[<sup>1</sup>](#table2)
- Bounty Collected: 0.355[<sup>2</sup>](#table1)
- Opponent Network: 0.152[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.214<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 840.5
- 400 + ( ( 0.214 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 840.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           62 |        9 | 2024-08-06 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |    -6.86 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           61 |      223 | 2024-07-31 | EYEBALLERS        | W   | 1.000      | 0.143        | -                | 0.488 (0.070)    | 0 (0.000) |    15.80 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           60 |      285 | 2024-07-29 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -4.66 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           59 |      418 | 2024-07-25 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -14.02 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           58 |      562 | 2024-07-20 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -3.00 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           57 |      605 | 2024-07-19 | PERA              | W   | 1.000      | 0.333        | 0.047 (0.016)    | 0.435 (0.145)    | 0 (0.000) |    23.68 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           56 |      648 | 2024-07-18 | TSM               | W   | 1.000      | 0.333        | 0.040 (0.013)    | 0.461 (0.154)    | 0 (0.000) |    26.20 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           55 |      664 | 2024-07-18 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -6.30 | 7kick, BTN, Ciocardau, Ed1m, ragga   |
|           54 |      742 | 2024-07-17 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -11.06 | 7kick, BTN, Ed1m, ragga, XELLOW      |
|           53 |      768 | 2024-07-16 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -0.29 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           52 |      833 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.333        | 0.037 (0.012)    | 0.790 (0.263)    | 0 (0.000) |    25.58 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           51 |      841 | 2024-07-14 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.67 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           50 |      860 | 2024-07-13 | Serbia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.97 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           49 |      903 | 2024-07-10 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.43 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           48 |      934 | 2024-07-09 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.05 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           47 |     1175 | 2024-06-12 | Permitta          | L   | 0.834      | -            | -                | -                | -         |    -6.32 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           46 |     1198 | 2024-06-11 | FAVBET            | L   | 0.827      | -            | -                | -                | -         |   -10.56 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           45 |     1294 | 2024-06-09 | EYEBALLERS        | L   | 0.812      | -            | -                | -                | -         |    -7.43 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           44 |     1319 | 2024-06-08 | Enterprise        | L   | 0.808      | -            | -                | -                | -         |    -7.98 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           43 |     1394 | 2024-06-07 | Astralis Talent   | W   | 0.800      | -            | -                | -                | 0 (0.000) |    12.66 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           42 |     1406 | 2024-06-07 | 9INE              | L   | 0.799      | -            | -                | -                | -         |    -8.07 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           41 |     1432 | 2024-06-06 | 3DMAX             | L   | 0.795      | -            | -                | -                | -         |    -0.40 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           40 |     1528 | 2024-06-05 | BLEED             | L   | 0.786      | -            | -                | -                | -         |    -0.74 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           39 |     1768 | 2024-05-27 | The Prodigies     | L   | 0.728      | -            | -                | -                | -         |   -18.11 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           38 |     1776 | 2024-05-27 | MOUZ NXT          | L   | 0.725      | -            | -                | -                | -         |    -3.96 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           37 |     1811 | 2024-05-25 | Permitta          | L   | 0.713      | -            | -                | -                | -         |    -7.55 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           36 |     1838 | 2024-05-23 | RUBY              | L   | 0.700      | -            | -                | -                | -         |    -6.45 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           35 |     1953 | 2024-05-20 | ALTERNATE aTTaX   | W   | 0.681      | 0.435        | 0.031 (0.009)    | 0.537 (0.159)    | 0 (0.000) |    14.56 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           34 |     1958 | 2024-05-20 | PERA              | L   | 0.680      | -            | -                | -                | -         |    -6.60 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           33 |     2055 | 2024-05-17 | Passion UA        | L   | 0.659      | -            | -                | -                | -         |    -4.34 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           32 |     2152 | 2024-05-15 | Space             | L   | 0.645      | -            | -                | -                | -         |    -9.02 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           31 |     2221 | 2024-05-13 | Sampi             | L   | 0.632      | -            | -                | -                | -         |    -6.96 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           30 |     2431 | 2024-05-03 | ENCE Academy      | L   | 0.565      | -            | -                | -                | -         |   -11.28 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     2476 | 2024-05-01 | Insilio           | L   | 0.553      | -            | -                | -                | -         |    -6.41 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     2508 | 2024-04-30 | fnatic            | L   | 0.545      | -            | -                | -                | -         |    -0.37 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     2512 | 2024-04-29 | Endpoint          | L   | 0.541      | -            | -                | -                | -         |    -7.10 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     2517 | 2024-04-29 | VP.Prodigy        | L   | 0.539      | -            | -                | -                | -         |    -8.02 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     2522 | 2024-04-29 | LEON              | W   | 0.539      | -            | -                | -                | 0 (0.000) |     5.07 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     2527 | 2024-04-29 | Enterprise        | W   | 0.538      | 0.384        | 0.039 (0.008)    | 0.641 (0.133)    | 0 (0.000) |     9.77 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     2543 | 2024-04-28 | brazylijski luz   | L   | 0.532      | -            | -                | -                | -         |    -8.66 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     2611 | 2024-04-25 | Metizport         | W   | 0.514      | 0.384        | -                | 0.510 (0.101)    | -         |    10.46 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     2619 | 2024-04-25 | Grannys Knockers  | L   | 0.512      | -            | -                | -                | -         |   -10.07 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     2640 | 2024-04-24 | AMKAL             | L   | 0.505      | -            | -                | -                | -         |    -2.60 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     2658 | 2024-04-23 | Illuminar         | L   | 0.499      | -            | -                | -                | -         |   -13.33 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     2671 | 2024-04-22 | Zero Tenacity     | L   | 0.493      | -            | -                | -                | -         |    -3.60 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     2682 | 2024-04-21 | Young Ninjas      | W   | 0.488      | -            | -                | -                | -         |     5.83 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     2686 | 2024-04-21 | PARIVISION        | L   | 0.487      | -            | -                | -                | -         |    -3.78 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     2722 | 2024-04-20 | Permitta          | W   | 0.479      | 0.500        | 0.039 (0.009)    | 0.919 (0.220)    | -         |    10.31 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           14 |     2792 | 2024-04-18 | Young Ninjas      | L   | 0.468      | -            | -                | -                | -         |    -9.18 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     2823 | 2024-04-18 | Enterprise        | L   | 0.465      | -            | -                | -                | -         |    -6.13 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           12 |     3021 | 2024-04-10 | B8                | W   | 0.413      | 0.384        | 0.170 (0.027)    | 0.912 (0.145)    | -         |     9.85 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           11 |     3165 | 2024-04-05 | SINNERS           | L   | 0.380      | -            | -                | -                | -         |    -1.92 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           10 |     3307 | 2024-04-01 | Sashi             | W   | 0.352      | 0.384        | 0.184 (0.025)    | 0.958 (0.130)    | -         |     9.23 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            9 |     3416 | 2024-03-25 | Sashi             | L   | 0.307      | -            | -                | -                | -         |    -1.57 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            8 |     3677 | 2024-03-12 | Nemiga            | W   | 0.221      | 0.372        | 0.314 (0.026)    | -                | -         |     6.01 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            7 |     3699 | 2024-03-11 | RUBY              | W   | 0.214      | 0.372        | 0.095 (0.008)    | -                | -         |     4.26 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            6 |     3739 | 2024-03-09 | INGLORIOUS        | W   | 0.201      | -            | -                | -                | -         |     1.00 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            5 |     3763 | 2024-03-08 | FAVBET            | W   | 0.194      | -            | -                | -                | -         |     2.43 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            4 |     3909 | 2024-03-03 | TSM               | L   | 0.161      | -            | -                | -                | -         |    -3.64 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            3 |     4157 | 2024-02-20 | ex-Guild Eagles   | L   | 0.080      | -            | -                | -                | -         |    -1.35 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            2 |     4178 | 2024-02-19 | Monte             | L   | 0.074      | -            | -                | -                | -         |    -0.71 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            1 |     4184 | 2024-02-19 | Astralis          | L   | 0.073      | -            | -                | -                | -         |    -0.02 | BTN, ERSIN, ragga, s0und, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,381.12)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-05-02 |      0.560 | $1,000.00      | $560.46         |
| 2024-03-25 |      0.307 | $4,300.00      | $1,320.66       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
