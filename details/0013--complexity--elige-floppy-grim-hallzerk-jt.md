### Roster Details<br />
Team Name: Complexity<br />
Roster: EliGE, floppy, Grim, hallzerk, JT<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1567.8<br />
<br />
Final Rank Value (1567.8) = Starting Rank Value (1655.5) + Head To Head Adjustments (-87.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.685[<sup>1</sup>](#table2)
- Bounty Collected: 0.594[<sup>2</sup>](#table1)
- Opponent Network: 0.228[<sup>2</sup>](#table1)
- LAN Wins: 0.929[<sup>2</sup>](#table1)

The average of these factors is 0.609<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1655.5
- 400 + ( ( 0.609 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1655.5


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
|           34 |       66 | 2024-07-30 | OG            | W   | 1.000      | 0.581        | 0.143 (0.083)    | -                | 1 (1.000) |     1.45 | EliGE, floppy, Grim, hallzerk, JT |
|           33 |       97 | 2024-07-29 | HEROIC        | L   | 1.000      | -            | -                | -                | -         |   -15.22 | EliGE, floppy, Grim, hallzerk, JT |
|           32 |      468 | 2024-07-18 | M80           | L   | 1.000      | -            | -                | -                | -         |   -27.17 | EliGE, floppy, Grim, hallzerk, JT |
|           31 |      520 | 2024-07-17 | Virtus.pro    | L   | 1.000      | -            | -                | -                | -         |   -12.26 | EliGE, floppy, Grim, hallzerk, JT |
|           30 |      852 | 2024-06-16 | Falcons       | W   | 0.898      | 0.500        | 0.231 (0.104)    | -                | 1 (0.898) |     8.61 | EliGE, floppy, Grim, hallzerk, JT |
|           29 |      861 | 2024-06-16 | Aurora        | W   | 0.897      | 0.500        | 0.429 (0.192)    | 0.800 (0.358)    | 1 (0.897) |     7.92 | EliGE, floppy, Grim, hallzerk, JT |
|           28 |      891 | 2024-06-15 | MIBR          | W   | 0.891      | 0.500        | 0.200 (0.089)    | 0.637 (0.284)    | 1 (0.891) |     7.15 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |      921 | 2024-06-14 | ENCE          | L   | 0.885      | -            | -                | -                | -         |   -22.04 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |      933 | 2024-06-14 | Alliance      | W   | 0.884      | -            | -                | -                | 1 (0.884) |     0.40 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |     1253 | 2024-06-06 | FURIA         | L   | 0.832      | -            | -                | -                | -         |   -13.92 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |     1273 | 2024-06-06 | BetBoom       | L   | 0.831      | -            | -                | -                | -         |   -20.72 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1285 | 2024-06-06 | fnatic        | L   | 0.830      | -            | -                | -                | -         |   -19.40 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     1329 | 2024-06-05 | BIG           | W   | 0.825      | 0.715        | 0.157 (0.093)    | 0.300 (0.177)    | 1 (0.825) |     2.81 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     1342 | 2024-06-05 | Eternal Fire  | W   | 0.823      | 0.715        | 0.752 (0.443)    | 0.462 (0.272)    | 1 (0.823) |    14.51 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     1564 | 2024-05-27 | MOUZ          | L   | 0.768      | -            | -                | -                | -         |    -4.72 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     1574 | 2024-05-27 | Liquid        | L   | 0.766      | -            | -                | -                | -         |   -16.88 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     2069 | 2024-05-11 | MOUZ          | L   | 0.659      | -            | -                | -                | -         |    -4.71 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     2120 | 2024-05-09 | Virtus.pro    | W   | 0.645      | 0.889        | 0.494 (0.283)    | 0.327 (0.187)    | 1 (0.645) |    11.35 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     2188 | 2024-05-05 | Natus Vincere | W   | 0.619      | 0.889        | 1.000 (0.551)    | 0.331 (0.183)    | 1 (0.619) |    16.84 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     2255 | 2024-05-02 | HEROIC        | W   | 0.598      | 0.889        | 0.234 (0.124)    | 0.382 (0.203)    | 1 (0.598) |     8.19 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     2302 | 2024-04-30 | PERA          | W   | 0.585      | 0.889        | -                | 0.452 (0.235)    | -         |     0.29 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     3226 | 2024-03-24 | FaZe          | L   | 0.338      | -            | -                | -                | -         |    -4.25 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     3236 | 2024-03-23 | Vitality      | L   | 0.332      | -            | -                | -                | -         |    -2.49 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     3251 | 2024-03-22 | MOUZ          | L   | 0.325      | -            | -                | -                | -         |    -2.23 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     3269 | 2024-03-21 | HEROIC        | W   | 0.319      | 1.000        | -                | 0.382 (0.122)    | -         |     4.37 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     3278 | 2024-03-21 | paiN          | W   | 0.318      | 1.000        | 0.333 (0.106)    | 0.797 (0.254)    | -         |     2.32 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     3595 | 2024-03-07 | OG            | L   | 0.226      | -            | -                | -                | -         |    -6.93 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     3684 | 2024-03-04 | Liquid        | W   | 0.207      | -            | -                | -                | -         |     1.74 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     3699 | 2024-03-03 | FURIA         | L   | 0.200      | -            | -                | -                | -         |    -2.37 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     3737 | 2024-03-02 | BOSS          | W   | 0.192      | -            | -                | -                | -         |     0.06 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     3756 | 2024-03-01 | Elevate       | W   | 0.186      | -            | -                | -                | -         |     0.15 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     4245 | 2024-02-05 | Falcons       | L   | 0.019      | -            | -                | -                | -         |    -0.46 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     4266 | 2024-02-04 | Spirit        | L   | 0.012      | -            | -                | -                | -         |    -0.07 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     4285 | 2024-02-03 | Apeks         | W   | 0.006      | -            | -                | -                | -         |     0.00 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($115,275.14)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.35) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.898 | $50,000.00     | $44,911.34      |
| 2024-06-09 |      0.852 | $8,000.00      | $6,814.70       |
| 2024-06-02 |      0.806 | $4,000.00      | $3,224.02       |
| 2024-05-12 |      0.665 | $45,000.00     | $29,932.71      |
| 2024-03-31 |      0.386 | $20,000.00     | $7,720.09       |
| 2024-03-10 |      0.246 | $5,000.00      | $1,231.76       |
| 2024-02-11 |      0.059 | $16,000.00     | $940.52         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
