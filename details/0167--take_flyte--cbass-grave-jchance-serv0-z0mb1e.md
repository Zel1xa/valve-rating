### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [167](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [48]( ../standings_americas.md)<br />
<br />
Final Rank Value:  676.8<br />
<br />
Final Rank Value (676.8) = Starting Rank Value (714.8) + Head To Head Adjustments (-38.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.272[<sup>1</sup>](#table2)
- Bounty Collected: 0.280[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 714.8
- 400 + ( ( 0.153 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 714.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |       14 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -13.20 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |       19 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.40 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      265 | 2024-07-24 | The Nomads       | W   | 1.000      | 0.371        | 0.000 (0.000)    | -                | 0 (0.000) |     4.84 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      464 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.23 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      470 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.50 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      530 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.15 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      534 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.41 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      595 | 2024-07-16 | Perseverance     | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.247 (0.118)    | 0 (0.000) |    15.47 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      601 | 2024-07-16 | Perseverance     | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.247 (0.118)    | 0 (0.000) |    16.90 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      652 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.82 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      656 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.05 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |      912 | 2024-06-15 | Akimbo           | W   | 0.889      | 0.143        | 0.016 (0.002)    | 0.275 (0.035)    | 0 (0.000) |    18.23 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |      944 | 2024-06-14 | E-Xolos LAZER    | W   | 0.882      | 0.143        | 0.011 (0.001)    | 0.386 (0.049)    | 0 (0.000) |    18.78 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1713 | 2024-05-22 | Wildcard         | L   | 0.729      | -            | -                | -                | -         |    -3.48 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1716 | 2024-05-22 | Wildcard         | L   | 0.729      | -            | -                | -                | -         |    -3.60 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1773 | 2024-05-21 | Elevate          | L   | 0.723      | -            | -                | -                | -         |    -3.33 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1778 | 2024-05-21 | Elevate          | L   | 0.722      | -            | -                | -                | -         |    -3.44 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1816 | 2024-05-20 | MIGHT            | W   | 0.716      | 0.477        | -                | 0.061 (0.021)    | 0 (0.000) |     7.03 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1820 | 2024-05-20 | MIGHT            | L   | 0.716      | -            | -                | -                | -         |   -15.92 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     1955 | 2024-05-16 | Limitless        | L   | 0.689      | -            | -                | -                | -         |    -7.63 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     1956 | 2024-05-16 | Limitless        | L   | 0.689      | -            | -                | -                | -         |    -8.07 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     1995 | 2024-05-15 | M80              | L   | 0.682      | -            | -                | -                | -         |    -0.83 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     2002 | 2024-05-15 | M80              | L   | 0.682      | -            | -                | -                | -         |    -0.83 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2054 | 2024-05-14 | NRG              | L   | 0.676      | -            | -                | -                | -         |    -5.02 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2059 | 2024-05-14 | NRG              | L   | 0.676      | -            | -                | -                | -         |    -5.25 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2548 | 2024-04-23 | Nouns            | W   | 0.536      | 0.477        | 0.058 (0.015)    | 0.557 (0.142)    | 0 (0.000) |    13.42 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2550 | 2024-04-23 | Nouns            | L   | 0.536      | -            | -                | -                | -         |    -3.42 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2899 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.449      | 0.477        | 0.010 (0.002)    | 0.104 (0.022)    | 0 (0.000) |     8.35 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2904 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.449      | -            | -                | -                | -         |    -5.90 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     2957 | 2024-04-09 | Party Astronauts | L   | 0.443      | -            | -                | -                | -         |    -2.79 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     2963 | 2024-04-09 | Party Astronauts | L   | 0.442      | -            | -                | -                | -         |    -2.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3088 | 2024-04-04 | Limitless        | W   | 0.409      | 0.477        | 0.001 (0.000)    | 0.170 (0.033)    | 0 (0.000) |     5.69 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3092 | 2024-04-04 | Limitless        | L   | 0.409      | -            | -                | -                | -         |    -7.36 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3272 | 2024-03-27 | BOSS             | L   | 0.356      | -            | -                | -                | -         |    -4.13 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3275 | 2024-03-27 | BOSS             | W   | 0.356      | 0.477        | 0.014 (0.002)    | 0.334 (0.057)    | 0 (0.000) |     7.23 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3520 | 2024-03-14 | Mythic           | L   | 0.269      | -            | -                | -                | -         |    -3.23 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3523 | 2024-03-14 | Mythic           | L   | 0.269      | -            | -                | -                | -         |    -3.30 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3776 | 2024-03-05 | LAG              | L   | 0.210      | -            | -                | -                | -         |    -1.99 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3778 | 2024-03-05 | LAG              | L   | 0.209      | -            | -                | -                | -         |    -2.02 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4046 | 2024-02-22 | Party Astronauts | L   | 0.128      | -            | -                | -                | -         |    -0.91 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4290 | 2024-02-13 | Perseverance     | W   | 0.069      | 0.477        | 0.004 (0.000)    | 0.247 (0.008)    | -         |     1.18 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4293 | 2024-02-13 | Perseverance     | L   | 0.069      | -            | -                | -                | -         |    -1.01 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($678.89)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
