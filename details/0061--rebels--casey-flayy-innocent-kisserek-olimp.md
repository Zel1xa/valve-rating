### Roster Details<br />
Team Name: Rebels<br />
Roster: casey, Flayy, innocent, kisserek, olimp<br />
Global Rank: [61](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
<br />
Final Rank Value:  993.5<br />
<br />
Final Rank Value (993.5) = Starting Rank Value (1000.4) + Head To Head Adjustments (-6.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.418[<sup>1</sup>](#table2)
- Bounty Collected: 0.395[<sup>2</sup>](#table1)
- Opponent Network: 0.226[<sup>2</sup>](#table1)
- LAN Wins: 0.127[<sup>2</sup>](#table1)

The average of these factors is 0.292<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1000.4
- 400 + ( ( 0.292 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1000.4


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
|           49 |       79 | 2024-07-30 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.12 | casey, Flayy, innocent, kisserek, olimp |
|           48 |      277 | 2024-07-24 | SAW               | W   | 1.000      | 0.500        | 0.108 (0.054)    | 0.544 (0.272)    | 0 (0.000) |    23.34 | casey, Flayy, innocent, kisserek, olimp |
|           47 |      289 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -16.23 | casey, Flayy, innocent, kisserek, olimp |
|           46 |      332 | 2024-07-23 | Enterprise        | W   | 1.000      | 0.371        | 0.040 (0.015)    | 0.622 (0.231)    | 0 (0.000) |    13.22 | casey, Flayy, innocent, kisserek, olimp |
|           45 |      350 | 2024-07-22 | Insilio           | W   | 1.000      | 0.371        | -                | 0.554 (0.205)    | 0 (0.000) |    14.73 | casey, Flayy, innocent, kisserek, olimp |
|           44 |      442 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -12.49 | casey, Flayy, innocent, kisserek, olimp |
|           43 |      455 | 2024-07-19 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.94 | casey, Flayy, innocent, kisserek, olimp |
|           42 |      524 | 2024-07-18 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.07 | casey, Flayy, innocent, kisserek, olimp |
|           41 |      586 | 2024-07-17 | 9INE              | W   | 1.000      | 0.500        | 0.022 (0.011)    | 0.521 (0.260)    | 0 (0.000) |    14.07 | casey, Flayy, innocent, kisserek, olimp |
|           40 |      679 | 2024-07-15 | brazylijski luz   | L   | 1.000      | -            | -                | -                | -         |   -21.53 | casey, Flayy, innocent, kisserek, olimp |
|           39 |      687 | 2024-07-15 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.11 | casey, Flayy, innocent, kisserek, olimp |
|           38 |      699 | 2024-07-14 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.43 | casey, Flayy, innocent, kisserek, olimp |
|           37 |      715 | 2024-07-13 | Croatia           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.51 | casey, Flayy, innocent, kisserek, olimp |
|           36 |      728 | 2024-07-12 | Enterprise        | W   | 1.000      | 0.371        | 0.040 (0.015)    | 0.622 (0.231)    | 0 (0.000) |    12.59 | casey, Flayy, innocent, kisserek, olimp |
|           35 |      765 | 2024-07-10 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.05 | casey, Flayy, innocent, kisserek, olimp |
|           34 |      777 | 2024-07-09 | 500               | W   | 1.000      | -            | -                | -                | -         |     1.05 | casey, Flayy, innocent, kisserek, olimp |
|           33 |      813 | 2024-07-08 | Verdant           | W   | 1.000      | -            | -                | -                | -         |     9.59 | casey, Flayy, innocent, kisserek, olimp |
|           32 |      991 | 2024-06-13 | Sampi             | L   | 0.874      | -            | -                | -                | -         |   -18.95 | casey, Flayy, innocent, kisserek, olimp |
|           31 |     1014 | 2024-06-12 | PERA              | L   | 0.868      | -            | -                | -                | -         |   -15.93 | casey, Flayy, innocent, kisserek, olimp |
|           30 |     1060 | 2024-06-10 | Permitta          | W   | 0.855      | 0.379        | -                | 0.801 (0.259)    | -         |    10.12 | casey, Flayy, innocent, kisserek, olimp |
|           29 |     1098 | 2024-06-09 | Rhyno             | L   | 0.848      | -            | -                | -                | -         |   -14.68 | casey, Flayy, kisserek, olimp, SZPERO   |
|           28 |     1232 | 2024-06-07 | BLEED             | W   | 0.835      | 0.500        | 0.128 (0.054)    | 0.513 (0.214)    | -         |    23.12 | casey, Flayy, innocent, kisserek, olimp |
|           27 |     1361 | 2024-06-05 | 9INE              | W   | 0.822      | 0.500        | -                | 0.521 (0.214)    | -         |    10.15 | casey, Flayy, innocent, kisserek, olimp |
|           26 |     1553 | 2024-05-30 | PERA              | W   | 0.782      | 0.379        | 0.048 (0.014)    | -                | -         |    10.55 | casey, Flayy, innocent, kisserek, olimp |
|           25 |     1590 | 2024-05-29 | UNiTY             | L   | 0.773      | -            | -                | -                | -         |   -14.87 | casey, Flayy, innocent, kisserek, olimp |
|           24 |     1679 | 2024-05-25 | kONO              | W   | 0.746      | -            | -                | -                | -         |     7.19 | casey, Flayy, innocent, kisserek, olimp |
|           23 |     1809 | 2024-05-21 | UNiTY             | L   | 0.719      | -            | -                | -                | -         |   -13.14 | casey, Flayy, innocent, kisserek, olimp |
|           22 |     1833 | 2024-05-20 | The Prodigies     | W   | 0.715      | -            | -                | -                | -         |     1.45 | casey, Flayy, innocent, kisserek, olimp |
|           21 |     1910 | 2024-05-18 | B8                | L   | 0.699      | -            | -                | -                | -         |    -7.73 | casey, Flayy, innocent, kisserek, olimp |
|           20 |     1938 | 2024-05-17 | Gaimin Gladiators | W   | 0.693      | -            | -                | -                | -         |    11.20 | casey, Flayy, innocent, kisserek, olimp |
|           19 |     2447 | 2024-04-27 | Aurora            | L   | 0.565      | -            | -                | -                | -         |    -0.59 | casey, Flayy, innocent, kisserek, olimp |
|           18 |     2497 | 2024-04-26 | MIBR              | W   | 0.552      | 0.500        | 0.201 (0.056)    | 0.637 (0.176)    | 1 (0.552) |    16.05 | casey, Flayy, innocent, kisserek, olimp |
|           17 |     2499 | 2024-04-25 | Rooster           | W   | 0.551      | -            | -                | -                | 1 (0.551) |     4.45 | casey, Flayy, innocent, kisserek, olimp |
|           16 |     2654 | 2024-04-19 | brazylijski luz   | L   | 0.508      | -            | -                | -                | -         |   -11.49 | casey, Flayy, innocent, kisserek, olimp |
|           15 |     2842 | 2024-04-13 | Monte             | L   | 0.468      | -            | -                | -                | -         |    -7.26 | casey, Flayy, innocent, kisserek, olimp |
|           14 |     2977 | 2024-04-09 | B8                | W   | 0.442      | 0.500        | 0.168 (0.037)    | 0.878 (0.194)    | -         |     8.29 | casey, Flayy, innocent, kisserek, olimp |
|           13 |     3120 | 2024-04-04 | ALTERNATE aTTaX   | W   | 0.407      | -            | -                | -                | -         |     5.92 | casey, Flayy, innocent, kisserek, olimp |
|           12 |     3175 | 2024-04-03 | SINNERS           | L   | 0.399      | -            | -                | -                | -         |    -5.32 | casey, Flayy, innocent, kisserek, olimp |
|           11 |     3258 | 2024-03-28 | ex-Sprout         | W   | 0.361      | -            | -                | -                | -         |     0.74 | casey, Flayy, innocent, kisserek, olimp |
|           10 |     3293 | 2024-03-27 | B8                | L   | 0.355      | -            | -                | -                | -         |    -4.08 | casey, Flayy, innocent, kisserek, olimp |
|            9 |     3302 | 2024-03-27 | Sashi             | W   | 0.355      | -            | -                | -                | -         |     7.74 | casey, Flayy, innocent, kisserek, olimp |
|            8 |     3336 | 2024-03-25 | Aurora            | L   | 0.341      | -            | -                | -                | -         |    -0.23 | casey, Flayy, innocent, kisserek, olimp |
|            7 |     3537 | 2024-03-14 | brazylijski luz   | L   | 0.269      | -            | -                | -                | -         |    -6.32 | casey, Flayy, kisserek, olimp, SZPERO   |
|            6 |     3814 | 2024-03-04 | BLEED             | L   | 0.202      | -            | -                | -                | -         |    -3.50 | casey, Flayy, kisserek, olimp, sNx      |
|            5 |     3847 | 2024-03-03 | Sangal            | W   | 0.194      | 0.500        | 0.221 (0.021)    | -                | -         |     4.21 | casey, Flayy, kisserek, olimp, sNx      |
|            4 |     3863 | 2024-03-02 | Aurora            | L   | 0.188      | -            | -                | -                | -         |    -0.13 | casey, Flayy, kisserek, olimp, sNx      |
|            3 |     3897 | 2024-02-29 | Sangal            | W   | 0.174      | 0.500        | 0.221 (0.019)    | -                | -         |     3.82 | casey, Flayy, kisserek, olimp, sNx      |
|            2 |     4409 | 2024-02-04 | Falcons           | L   | 0.008      | -            | -                | -                | -         |    -0.02 | casey, Flayy, kisserek, olimp, sNx      |
|            1 |     4444 | 2024-02-03 | FaZe              | L   | 0.001      | -            | -                | -                | -         |    -0.00 | casey, Flayy, kisserek, olimp, sNx      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,254.51)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-13 |      0.875 | $1,089.00      | $953.08         |
| 2024-06-09 |      0.848 | $2,000.00      | $1,695.42       |
| 2024-05-18 |      0.701 | $2,000.00      | $1,402.78       |
| 2024-04-28 |      0.566 | $10,000.00     | $5,658.80       |
| 2024-02-11 |      0.054 | $10,000.00     | $544.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
