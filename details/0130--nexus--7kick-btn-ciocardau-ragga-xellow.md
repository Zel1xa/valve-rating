### Roster Details<br />
Team Name: Nexus<br />
Roster: 7kick, BTN, Ciocardau, ragga, XELLOW<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [90]( ../standings_europe.md)<br />
<br />
Final Rank Value:  784.6<br />
<br />
Final Rank Value (784.6) = Starting Rank Value (841.2) + Head To Head Adjustments (-56.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.349[<sup>1</sup>](#table2)
- Bounty Collected: 0.355[<sup>2</sup>](#table1)
- Opponent Network: 0.153[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.214<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 841.2
- 400 + ( ( 0.214 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 841.2


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
|           62 |       16 | 2024-08-06 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |    -6.84 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           61 |      230 | 2024-07-31 | EYEBALLERS        | W   | 1.000      | 0.143        | -                | 0.488 (0.070)    | 0 (0.000) |    15.80 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           60 |      292 | 2024-07-29 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -4.65 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           59 |      425 | 2024-07-25 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -14.05 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           58 |      569 | 2024-07-20 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -3.01 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           57 |      612 | 2024-07-19 | PERA              | W   | 1.000      | 0.333        | 0.047 (0.016)    | 0.435 (0.145)    | 0 (0.000) |    23.66 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           56 |      655 | 2024-07-18 | TSM               | W   | 1.000      | 0.333        | 0.040 (0.013)    | 0.500 (0.167)    | 0 (0.000) |    26.20 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           55 |      671 | 2024-07-18 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -6.31 | 7kick, BTN, Ciocardau, Ed1m, ragga   |
|           54 |      749 | 2024-07-17 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -11.04 | 7kick, BTN, Ed1m, ragga, XELLOW      |
|           53 |      775 | 2024-07-16 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -0.29 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           52 |      840 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.333        | 0.037 (0.012)    | 0.800 (0.267)    | 0 (0.000) |    25.62 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           51 |      848 | 2024-07-14 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.70 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           50 |      867 | 2024-07-13 | Serbia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.93 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           49 |      910 | 2024-07-10 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.46 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           48 |      941 | 2024-07-09 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.03 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           47 |     1182 | 2024-06-12 | Permitta          | L   | 0.833      | -            | -                | -                | -         |    -6.31 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           46 |     1205 | 2024-06-11 | FAVBET            | L   | 0.827      | -            | -                | -                | -         |   -10.58 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           45 |     1301 | 2024-06-09 | EYEBALLERS        | L   | 0.812      | -            | -                | -                | -         |    -7.43 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           44 |     1326 | 2024-06-08 | Enterprise        | L   | 0.807      | -            | -                | -                | -         |    -7.98 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           43 |     1401 | 2024-06-07 | Astralis Talent   | W   | 0.800      | -            | -                | -                | 0 (0.000) |    12.62 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           42 |     1413 | 2024-06-07 | 9INE              | L   | 0.799      | -            | -                | -                | -         |    -8.10 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           41 |     1439 | 2024-06-06 | 3DMAX             | L   | 0.794      | -            | -                | -                | -         |    -0.40 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           40 |     1535 | 2024-06-05 | BLEED             | L   | 0.785      | -            | -                | -                | -         |    -0.74 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           39 |     1775 | 2024-05-27 | The Prodigies     | L   | 0.727      | -            | -                | -                | -         |   -18.12 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           38 |     1783 | 2024-05-27 | MOUZ NXT          | L   | 0.725      | -            | -                | -                | -         |    -3.94 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           37 |     1818 | 2024-05-25 | Permitta          | L   | 0.712      | -            | -                | -                | -         |    -7.54 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           36 |     1845 | 2024-05-23 | RUBY              | L   | 0.700      | -            | -                | -                | -         |    -6.46 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           35 |     1960 | 2024-05-20 | ALTERNATE aTTaX   | W   | 0.680      | 0.435        | 0.031 (0.009)    | 0.537 (0.159)    | 0 (0.000) |    14.57 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           34 |     1965 | 2024-05-20 | PERA              | L   | 0.680      | -            | -                | -                | -         |    -6.62 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           33 |     2062 | 2024-05-17 | Passion UA        | L   | 0.658      | -            | -                | -                | -         |    -4.33 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           32 |     2159 | 2024-05-15 | Space             | L   | 0.644      | -            | -                | -                | -         |    -9.03 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           31 |     2228 | 2024-05-13 | Sampi             | L   | 0.632      | -            | -                | -                | -         |    -6.97 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           30 |     2438 | 2024-05-03 | ENCE Academy      | L   | 0.565      | -            | -                | -                | -         |   -11.29 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     2483 | 2024-05-01 | Insilio           | L   | 0.552      | -            | -                | -                | -         |    -6.41 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     2515 | 2024-04-30 | fnatic            | L   | 0.544      | -            | -                | -                | -         |    -0.37 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     2519 | 2024-04-29 | Endpoint          | L   | 0.540      | -            | -                | -                | -         |    -7.09 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     2524 | 2024-04-29 | VP.Prodigy        | L   | 0.539      | -            | -                | -                | -         |    -8.02 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     2529 | 2024-04-29 | LEON              | W   | 0.538      | -            | -                | -                | 0 (0.000) |     5.05 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     2534 | 2024-04-29 | Enterprise        | W   | 0.538      | 0.384        | 0.039 (0.008)    | 0.641 (0.132)    | 0 (0.000) |     9.74 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     2550 | 2024-04-28 | brazylijski luz   | L   | 0.532      | -            | -                | -                | -         |    -8.67 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     2618 | 2024-04-25 | Metizport         | W   | 0.513      | 0.384        | -                | 0.510 (0.101)    | -         |    10.47 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     2626 | 2024-04-25 | Grannys Knockers  | L   | 0.512      | -            | -                | -                | -         |   -10.08 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     2647 | 2024-04-24 | AMKAL             | L   | 0.505      | -            | -                | -                | -         |    -2.61 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     2665 | 2024-04-23 | Illuminar         | L   | 0.498      | -            | -                | -                | -         |   -13.33 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     2678 | 2024-04-22 | Zero Tenacity     | L   | 0.492      | -            | -                | -                | -         |    -3.59 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     2689 | 2024-04-21 | Young Ninjas      | W   | 0.487      | -            | -                | -                | -         |     5.80 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     2693 | 2024-04-21 | PARIVISION        | L   | 0.486      | -            | -                | -                | -         |    -3.30 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     2729 | 2024-04-20 | Permitta          | W   | 0.479      | 0.500        | 0.039 (0.009)    | 0.919 (0.220)    | -         |    10.30 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           14 |     2799 | 2024-04-18 | Young Ninjas      | L   | 0.467      | -            | -                | -                | -         |    -9.19 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     2830 | 2024-04-18 | Enterprise        | L   | 0.465      | -            | -                | -                | -         |    -6.14 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           12 |     3028 | 2024-04-10 | B8                | W   | 0.412      | 0.384        | 0.170 (0.027)    | 0.912 (0.145)    | -         |     9.83 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           11 |     3172 | 2024-04-05 | SINNERS           | L   | 0.380      | -            | -                | -                | -         |    -1.93 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           10 |     3314 | 2024-04-01 | Sashi             | W   | 0.352      | 0.384        | 0.184 (0.025)    | 0.958 (0.129)    | -         |     9.21 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            9 |     3423 | 2024-03-25 | Sashi             | L   | 0.307      | -            | -                | -                | -         |    -1.57 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            8 |     3684 | 2024-03-12 | Nemiga            | W   | 0.220      | 0.372        | 0.314 (0.026)    | -                | -         |     5.99 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            7 |     3706 | 2024-03-11 | RUBY              | W   | 0.213      | 0.372        | 0.095 (0.008)    | -                | -         |     4.24 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            6 |     3746 | 2024-03-09 | INGLORIOUS        | W   | 0.200      | -            | -                | -                | -         |     1.00 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            5 |     3770 | 2024-03-08 | FAVBET            | W   | 0.193      | -            | -                | -                | -         |     2.41 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            4 |     3916 | 2024-03-03 | TSM               | L   | 0.160      | -            | -                | -                | -         |    -3.63 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            3 |     4164 | 2024-02-20 | ex-Guild Eagles   | L   | 0.079      | -            | -                | -                | -         |    -1.34 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            2 |     4185 | 2024-02-19 | Monte             | L   | 0.074      | -            | -                | -                | -         |    -0.70 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            1 |     4191 | 2024-02-19 | Astralis          | L   | 0.072      | -            | -                | -                | -         |    -0.02 | BTN, ERSIN, ragga, s0und, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,377.93)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-05-02 |      0.560 | $1,000.00      | $559.86         |
| 2024-03-25 |      0.307 | $4,300.00      | $1,318.07       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
