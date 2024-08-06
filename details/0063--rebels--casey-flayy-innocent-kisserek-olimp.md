### Roster Details<br />
Team Name: Rebels<br />
Roster: casey, Flayy, innocent, kisserek, olimp<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  996.4<br />
<br />
Final Rank Value (996.4) = Starting Rank Value (989.8) + Head To Head Adjustments (6.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.413[<sup>1</sup>](#table2)
- Bounty Collected: 0.391[<sup>2</sup>](#table1)
- Opponent Network: 0.225[<sup>2</sup>](#table1)
- LAN Wins: 0.120[<sup>2</sup>](#table1)

The average of these factors is 0.288<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 989.8
- 400 + ( ( 0.288 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 989.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |        4 | 2024-08-05 | SINNERS           | L   | 1.000      | -            | -                | -                | -         |   -16.67 | casey, Flayy, innocent, kisserek, olimp |
|           44 |      228 | 2024-07-30 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.57 | casey, Flayy, innocent, kisserek, olimp |
|           43 |      426 | 2024-07-24 | SAW               | W   | 1.000      | 0.500        | 0.104 (0.052)    | 0.529 (0.265)    | 0 (0.000) |    22.54 | casey, Flayy, innocent, kisserek, olimp |
|           42 |      437 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -18.24 | casey, Flayy, innocent, kisserek, olimp |
|           41 |      480 | 2024-07-23 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.616 (0.228)    | 0 (0.000) |    11.89 | casey, Flayy, innocent, kisserek, olimp |
|           40 |      497 | 2024-07-22 | Insilio           | W   | 1.000      | 0.371        | -                | 0.552 (0.205)    | 0 (0.000) |    13.87 | casey, Flayy, innocent, kisserek, olimp |
|           39 |      598 | 2024-07-19 | B8                | L   | 1.000      | -            | -                | -                | -         |    -9.14 | casey, Flayy, innocent, kisserek, olimp |
|           38 |      663 | 2024-07-18 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.91 | casey, Flayy, innocent, kisserek, olimp |
|           37 |      724 | 2024-07-17 | 9INE              | W   | 1.000      | 0.500        | 0.022 (0.011)    | 0.533 (0.267)    | 0 (0.000) |    12.02 | casey, Flayy, innocent, kisserek, olimp |
|           36 |      812 | 2024-07-15 | brazylijski luz   | L   | 1.000      | -            | -                | -                | -         |   -22.93 | casey, Flayy, innocent, kisserek, olimp |
|           35 |      819 | 2024-07-15 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -7.87 | casey, Flayy, innocent, kisserek, olimp |
|           34 |      859 | 2024-07-12 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.616 (0.228)    | 0 (0.000) |    13.02 | casey, Flayy, innocent, kisserek, olimp |
|           33 |      896 | 2024-07-10 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.09 | casey, Flayy, innocent, kisserek, olimp |
|           32 |      908 | 2024-07-09 | 500               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.06 | casey, Flayy, innocent, kisserek, olimp |
|           31 |      944 | 2024-07-08 | Verdant           | W   | 1.000      | -            | -                | -                | -         |     9.82 | casey, Flayy, innocent, kisserek, olimp |
|           30 |     1133 | 2024-06-13 | Sampi             | L   | 0.844      | -            | -                | -                | -         |   -17.78 | casey, Flayy, innocent, kisserek, olimp |
|           29 |     1156 | 2024-06-12 | PERA              | L   | 0.838      | -            | -                | -                | -         |   -15.00 | casey, Flayy, innocent, kisserek, olimp |
|           28 |     1200 | 2024-06-10 | Permitta          | W   | 0.825      | 0.379        | -                | 0.901 (0.281)    | -         |    10.32 | casey, Flayy, innocent, kisserek, olimp |
|           27 |     1238 | 2024-06-09 | Rhyno             | L   | 0.818      | -            | -                | -                | -         |   -14.25 | casey, Flayy, kisserek, olimp, SZPERO   |
|           26 |     1363 | 2024-06-07 | BLEED             | W   | 0.805      | 0.500        | 0.126 (0.051)    | 0.511 (0.206)    | -         |    22.37 | casey, Flayy, innocent, kisserek, olimp |
|           25 |     1488 | 2024-06-05 | 9INE              | W   | 0.791      | 0.500        | -                | 0.533 (0.211)    | -         |     9.26 | casey, Flayy, innocent, kisserek, olimp |
|           24 |     1678 | 2024-05-30 | PERA              | W   | 0.751      | 0.379        | 0.048 (0.014)    | -                | -         |    10.45 | casey, Flayy, innocent, kisserek, olimp |
|           23 |     1715 | 2024-05-29 | UNiTY             | L   | 0.743      | -            | -                | -                | -         |   -13.83 | casey, Flayy, innocent, kisserek, olimp |
|           22 |     1802 | 2024-05-25 | kONO              | W   | 0.715      | -            | -                | -                | -         |     6.66 | casey, Flayy, innocent, kisserek, olimp |
|           21 |     1916 | 2024-05-21 | UNiTY             | L   | 0.689      | -            | -                | -                | -         |   -12.16 | casey, Flayy, innocent, kisserek, olimp |
|           20 |     1939 | 2024-05-20 | The Prodigies     | W   | 0.685      | -            | -                | -                | -         |     1.44 | casey, Flayy, innocent, kisserek, olimp |
|           19 |     2007 | 2024-05-18 | B8                | L   | 0.669      | -            | -                | -                | -         |    -7.07 | casey, Flayy, innocent, kisserek, olimp |
|           18 |     2035 | 2024-05-17 | Gaimin Gladiators | W   | 0.663      | -            | -                | -                | -         |    10.49 | casey, Flayy, innocent, kisserek, olimp |
|           17 |     2530 | 2024-04-27 | Aurora            | L   | 0.535      | -            | -                | -                | -         |    -0.53 | casey, Flayy, innocent, kisserek, olimp |
|           16 |     2580 | 2024-04-26 | MIBR              | W   | 0.522      | 0.500        | 0.208 (0.054)    | 0.648 (0.169)    | 1 (0.522) |    15.24 | casey, Flayy, innocent, kisserek, olimp |
|           15 |     2582 | 2024-04-25 | Rooster           | W   | 0.521      | -            | -                | -                | 1 (0.521) |     4.21 | casey, Flayy, innocent, kisserek, olimp |
|           14 |     2730 | 2024-04-19 | brazylijski luz   | L   | 0.478      | -            | -                | -                | -         |   -10.90 | casey, Flayy, innocent, kisserek, olimp |
|           13 |     2915 | 2024-04-13 | Monte             | L   | 0.437      | -            | -                | -                | -         |    -7.03 | casey, Flayy, innocent, kisserek, olimp |
|           12 |     3049 | 2024-04-09 | B8                | W   | 0.411      | 0.500        | 0.164 (0.034)    | 0.934 (0.192)    | -         |     7.71 | casey, Flayy, innocent, kisserek, olimp |
|           11 |     3191 | 2024-04-04 | ALTERNATE aTTaX   | W   | 0.377      | -            | -                | -                | -         |     5.57 | casey, Flayy, innocent, kisserek, olimp |
|           10 |     3241 | 2024-04-03 | SINNERS           | L   | 0.369      | -            | -                | -                | -         |    -3.43 | casey, Flayy, innocent, kisserek, olimp |
|            9 |     3322 | 2024-03-28 | ex-Sprout         | W   | 0.331      | -            | -                | -                | -         |     0.64 | casey, Flayy, innocent, kisserek, olimp |
|            8 |     3356 | 2024-03-27 | B8                | L   | 0.325      | -            | -                | -                | -         |    -3.74 | casey, Flayy, innocent, kisserek, olimp |
|            7 |     3365 | 2024-03-27 | Sashi             | W   | 0.325      | -            | -                | -                | -         |     7.17 | casey, Flayy, innocent, kisserek, olimp |
|            6 |     3395 | 2024-03-25 | Aurora            | L   | 0.311      | -            | -                | -                | -         |    -0.21 | casey, Flayy, innocent, kisserek, olimp |
|            5 |     3594 | 2024-03-14 | brazylijski luz   | L   | 0.238      | -            | -                | -                | -         |    -5.62 | casey, Flayy, kisserek, olimp, SZPERO   |
|            4 |     3862 | 2024-03-04 | BLEED             | L   | 0.172      | -            | -                | -                | -         |    -2.97 | casey, Flayy, kisserek, olimp, sNx      |
|            3 |     3896 | 2024-03-03 | Sangal            | W   | 0.164      | 0.500        | 0.219 (0.018)    | -                | -         |     3.69 | casey, Flayy, kisserek, olimp, sNx      |
|            2 |     3911 | 2024-03-02 | Aurora            | L   | 0.158      | -            | -                | -                | -         |    -0.11 | casey, Flayy, kisserek, olimp, sNx      |
|            1 |     3944 | 2024-02-29 | Sangal            | W   | 0.144      | 0.500        | 0.219 (0.016)    | -                | -         |     3.27 | casey, Flayy, kisserek, olimp, sNx      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,253.21)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-13 |      0.845 | $1,089.00      | $920.10         |
| 2024-06-09 |      0.817 | $2,000.00      | $1,634.86       |
| 2024-05-18 |      0.671 | $2,000.00      | $1,342.22       |
| 2024-04-28 |      0.536 | $10,000.00     | $5,356.02       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
