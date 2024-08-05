### Roster Details<br />
Team Name: Complexity<br />
Roster: EliGE, floppy, Grim, hallzerk, JT<br />
Global Rank: [14](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1570.2<br />
<br />
Final Rank Value (1570.2) = Starting Rank Value (1652.1) + Head To Head Adjustments (-81.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.682[<sup>1</sup>](#table2)
- Bounty Collected: 0.589[<sup>2</sup>](#table1)
- Opponent Network: 0.226[<sup>2</sup>](#table1)
- LAN Wins: 0.946[<sup>2</sup>](#table1)

The average of these factors is 0.611<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1652.1
- 400 + ( ( 0.611 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1652.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |       29 | 2024-08-04 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -4.13 | EliGE, floppy, Grim, hallzerk, JT |
|           33 |       78 | 2024-08-03 | Spirit        | L   | 1.000      | -            | -                | -                | -         |    -3.87 | EliGE, floppy, Grim, hallzerk, JT |
|           32 |      110 | 2024-08-02 | HEROIC        | W   | 1.000      | 0.581        | 0.225 (0.131)    | 0.365 (0.212)    | 1 (1.000) |    15.51 | EliGE, floppy, Grim, hallzerk, JT |
|           31 |      240 | 2024-07-30 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.37 | EliGE, floppy, Grim, hallzerk, JT |
|           30 |      270 | 2024-07-29 | HEROIC        | L   | 1.000      | -            | -                | -                | -         |   -15.77 | EliGE, floppy, Grim, hallzerk, JT |
|           29 |      642 | 2024-07-18 | M80           | L   | 1.000      | -            | -                | -                | -         |   -27.40 | EliGE, floppy, Grim, hallzerk, JT |
|           28 |      694 | 2024-07-17 | Virtus.pro    | L   | 1.000      | -            | -                | -                | -         |   -13.04 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |     1026 | 2024-06-16 | Falcons       | W   | 0.866      | 0.500        | 0.221 (0.096)    | -                | 1 (0.866) |     7.51 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |     1035 | 2024-06-16 | Aurora        | W   | 0.864      | 0.500        | 0.422 (0.182)    | 0.779 (0.336)    | 1 (0.864) |     7.71 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |     1065 | 2024-06-15 | MIBR          | W   | 0.858      | 0.500        | 0.208 (0.089)    | 0.649 (0.278)    | 1 (0.858) |     6.59 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |     1095 | 2024-06-14 | ENCE          | L   | 0.853      | -            | -                | -                | -         |   -21.29 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1107 | 2024-06-14 | Alliance      | W   | 0.852      | -            | -                | -                | 1 (0.852) |     0.38 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     1427 | 2024-06-06 | FURIA         | L   | 0.800      | -            | -                | -                | -         |   -13.70 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     1447 | 2024-06-06 | BetBoom       | L   | 0.799      | -            | -                | -                | -         |   -20.24 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     1459 | 2024-06-06 | fnatic        | L   | 0.798      | -            | -                | -                | -         |   -18.98 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     1503 | 2024-06-05 | BIG           | W   | 0.792      | 0.715        | 0.154 (0.088)    | 0.298 (0.169)    | 1 (0.792) |     3.36 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     1516 | 2024-06-05 | Eternal Fire  | W   | 0.791      | 0.715        | 0.740 (0.419)    | 0.449 (0.254)    | 1 (0.791) |    13.30 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     1738 | 2024-05-27 | MOUZ          | L   | 0.735      | -            | -                | -                | -         |    -5.06 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     1748 | 2024-05-27 | Liquid        | L   | 0.734      | -            | -                | -                | -         |   -13.50 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     2243 | 2024-05-11 | MOUZ          | L   | 0.627      | -            | -                | -                | -         |    -4.95 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     2294 | 2024-05-09 | Virtus.pro    | W   | 0.613      | 0.889        | 0.498 (0.271)    | 0.317 (0.173)    | 1 (0.613) |    10.19 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     2362 | 2024-05-05 | Natus Vincere | W   | 0.587      | 0.889        | 1.000 (0.522)    | 0.365 (0.191)    | 1 (0.587) |    15.81 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     2429 | 2024-05-02 | HEROIC        | W   | 0.566      | 0.889        | 0.225 (0.113)    | 0.365 (0.184)    | -         |     7.16 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     2476 | 2024-04-30 | PERA          | W   | 0.553      | 0.889        | -                | 0.446 (0.219)    | -         |     0.28 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     3400 | 2024-03-24 | FaZe          | L   | 0.305      | -            | -                | -                | -         |    -4.38 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     3410 | 2024-03-23 | Vitality      | L   | 0.300      | -            | -                | -                | -         |    -2.31 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     3425 | 2024-03-22 | MOUZ          | L   | 0.293      | -            | -                | -                | -         |    -2.29 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     3443 | 2024-03-21 | HEROIC        | W   | 0.287      | -            | -                | -                | -         |     3.55 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     3452 | 2024-03-21 | paiN          | W   | 0.286      | 1.000        | 0.325 (0.093)    | 0.856 (0.245)    | -         |     1.88 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     3769 | 2024-03-07 | OG            | L   | 0.194      | -            | -                | -                | -         |    -5.95 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     3858 | 2024-03-04 | Liquid        | W   | 0.174      | -            | -                | -                | -         |     2.29 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     3873 | 2024-03-03 | FURIA         | L   | 0.167      | -            | -                | -                | -         |    -2.13 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     3911 | 2024-03-02 | BOSS          | W   | 0.160      | -            | -                | -                | -         |     0.04 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     3930 | 2024-03-01 | Elevate       | W   | 0.154      | -            | -                | -                | -         |     0.12 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($110,058.68)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.34) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.866 | $50,000.00     | $43,291.67      |
| 2024-06-09 |      0.819 | $8,000.00      | $6,555.56       |
| 2024-06-02 |      0.774 | $4,000.00      | $3,094.44       |
| 2024-05-12 |      0.633 | $45,000.00     | $28,475.00      |
| 2024-03-31 |      0.354 | $20,000.00     | $7,072.22       |
| 2024-03-10 |      0.214 | $5,000.00      | $1,069.79       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
