### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1694.1<br />
<br />
Final Rank Value (1694.1) = Starting Rank Value (1731.8) + Head To Head Adjustments (-37.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.765[<sup>1</sup>](#table2)
- Bounty Collected: 0.648[<sup>2</sup>](#table1)
- Opponent Network: 0.295[<sup>2</sup>](#table1)
- LAN Wins: 0.875[<sup>2</sup>](#table1)

The average of these factors is 0.646<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1731.8
- 400 + ( ( 0.646 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1731.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |        7 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -22.75 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      376 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -6.35 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      418 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.654 (0.654)    | 0.385 (0.385)    | 1 (1.000) |    21.77 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      520 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.348 (0.348)    | 0.367 (0.367)    | 1 (1.000) |    12.26 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |      872 | 2024-06-15 | Natus Vincere | L   | 0.893      | -            | -                | -                | -         |    -5.56 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |      909 | 2024-06-14 | Astralis      | W   | 0.886      | 0.729        | 0.394 (0.255)    | 0.386 (0.249)    | 1 (0.886) |    14.32 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |      946 | 2024-06-13 | Spirit        | L   | 0.880      | -            | -                | -                | -         |    -5.78 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |      986 | 2024-06-12 | Vitality      | W   | 0.872      | 0.729        | 0.654 (0.416)    | 0.385 (0.245)    | 1 (0.872) |    20.35 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1532 | 2024-05-29 | BIG           | L   | 0.779      | -            | -                | -                | -         |   -22.37 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1547 | 2024-05-28 | FaZe          | L   | 0.773      | -            | -                | -                | -         |    -9.50 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1568 | 2024-05-27 | HEROIC        | W   | 0.767      | 0.624        | 0.234 (0.112)    | 0.382 (0.183)    | 1 (0.767) |     8.30 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     1860 | 2024-05-17 | Falcons       | L   | 0.698      | -            | -                | -                | -         |   -17.68 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     1899 | 2024-05-16 | MOUZ          | L   | 0.691      | -            | -                | -                | -         |    -5.25 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     1998 | 2024-05-14 | Falcons       | W   | 0.679      | 0.769        | 0.231 (0.121)    | -                | 1 (0.679) |     3.79 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2120 | 2024-05-09 | Complexity    | L   | 0.645      | -            | -                | -                | -         |   -11.35 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2139 | 2024-05-08 | The MongolZ   | W   | 0.639      | 0.889        | 1.000 (0.568)    | 0.719 (0.409)    | 1 (0.639) |    15.16 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2155 | 2024-05-07 | GamerLegion   | W   | 0.633      | 0.889        | 0.175 (0.098)    | -                | 1 (0.633) |     0.91 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2343 | 2024-04-28 | SAW           | W   | 0.572      | 0.889        | -                | 0.545 (0.277)    | 1 (0.572) |     1.08 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2374 | 2024-04-27 | fnatic        | W   | 0.564      | 0.889        | 0.371 (0.186)    | 0.633 (0.317)    | 1 (0.564) |     5.17 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2417 | 2024-04-25 | FaZe          | L   | 0.553      | -            | -                | -                | -         |    -7.63 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2440 | 2024-04-24 | SAW           | W   | 0.545      | 0.889        | -                | 0.545 (0.264)    | -         |     0.88 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2463 | 2024-04-23 | fnatic        | L   | 0.538      | -            | -                | -                | -         |   -12.20 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2759 | 2024-04-12 | G2            | L   | 0.463      | -            | -                | -                | -         |    -2.79 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     2843 | 2024-04-10 | Astralis      | L   | 0.450      | -            | -                | -                | -         |    -7.47 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     2895 | 2024-04-08 | FlyQuest      | W   | 0.443      | -            | -                | -                | -         |     0.67 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     2925 | 2024-04-08 | Wildcard      | W   | 0.436      | -            | -                | -                | -         |     0.03 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3225 | 2024-03-24 | G2            | L   | 0.338      | -            | -                | -                | -         |    -2.03 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3239 | 2024-03-23 | Eternal Fire  | L   | 0.331      | -            | -                | -                | -         |    -5.17 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3256 | 2024-03-22 | HEROIC        | W   | 0.324      | -            | -                | -                | -         |     3.31 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3270 | 2024-03-21 | paiN          | W   | 0.319      | 1.000        | 0.333 (0.106)    | 0.797 (0.254)    | -         |     1.60 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3280 | 2024-03-21 | Imperial      | L   | 0.318      | -            | -                | -                | -         |    -9.25 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3482 | 2024-03-12 | HEROIC        | W   | 0.259      | -            | -                | -                | -         |     2.52 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3498 | 2024-03-11 | Apeks         | W   | 0.253      | -            | -                | -                | -         |     0.09 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3509 | 2024-03-11 | B8            | W   | 0.252      | -            | -                | -                | -         |     0.21 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4091 | 2024-02-15 | Natus Vincere | W   | 0.085      | -            | -                | -                | -         |     2.17 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4123 | 2024-02-14 | fnatic        | W   | 0.080      | -            | -                | -                | -         |     0.77 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4142 | 2024-02-14 | SAW           | W   | 0.077      | -            | -                | -                | -         |     0.11 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($163,737.45)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.49) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.898 | $40,000.00     | $35,929.07      |
| 2024-06-02 |      0.806 | $5,000.00      | $4,030.02       |
| 2024-05-12 |      0.665 | $32,000.00     | $21,285.48      |
| 2024-04-14 |      0.477 | $10,000.00     | $4,772.78       |
| 2024-03-31 |      0.386 | $20,000.00     | $7,720.09       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
