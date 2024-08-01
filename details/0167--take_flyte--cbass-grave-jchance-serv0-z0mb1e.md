### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [167](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [48]( ../standings_americas.md)<br />
<br />
Final Rank Value:  677.3<br />
<br />
Final Rank Value (677.3) = Starting Rank Value (715.3) + Head To Head Adjustments (-38.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.272[<sup>1</sup>](#table2)
- Bounty Collected: 0.280[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 715.3
- 400 + ( ( 0.153 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 715.3


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
|           42 |       10 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -13.20 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |       15 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.40 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      261 | 2024-07-24 | The Nomads       | W   | 1.000      | 0.371        | 0.000 (0.000)    | -                | 0 (0.000) |     4.83 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      460 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.23 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      466 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.50 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      526 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.15 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      530 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.41 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      591 | 2024-07-16 | Perseverance     | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.247 (0.118)    | 0 (0.000) |    15.47 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      597 | 2024-07-16 | Perseverance     | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.247 (0.118)    | 0 (0.000) |    16.90 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      648 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.82 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      652 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.05 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |      908 | 2024-06-15 | Akimbo           | W   | 0.890      | 0.143        | 0.016 (0.002)    | 0.275 (0.035)    | 0 (0.000) |    18.26 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |      940 | 2024-06-14 | E-Xolos LAZER    | W   | 0.884      | 0.143        | 0.011 (0.001)    | 0.386 (0.049)    | 0 (0.000) |    18.82 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1709 | 2024-05-22 | Wildcard         | L   | 0.731      | -            | -                | -                | -         |    -3.48 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1712 | 2024-05-22 | Wildcard         | L   | 0.731      | -            | -                | -                | -         |    -3.60 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1769 | 2024-05-21 | Elevate          | L   | 0.724      | -            | -                | -                | -         |    -3.33 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1774 | 2024-05-21 | Elevate          | L   | 0.724      | -            | -                | -                | -         |    -3.44 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1812 | 2024-05-20 | MIGHT            | W   | 0.717      | 0.477        | -                | 0.061 (0.021)    | 0 (0.000) |     7.05 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1816 | 2024-05-20 | MIGHT            | L   | 0.717      | -            | -                | -                | -         |   -15.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     1951 | 2024-05-16 | Limitless        | L   | 0.691      | -            | -                | -                | -         |    -7.64 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     1952 | 2024-05-16 | Limitless        | L   | 0.690      | -            | -                | -                | -         |    -8.09 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     1991 | 2024-05-15 | M80              | L   | 0.684      | -            | -                | -                | -         |    -0.83 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     1998 | 2024-05-15 | M80              | L   | 0.684      | -            | -                | -                | -         |    -0.84 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2050 | 2024-05-14 | NRG              | L   | 0.677      | -            | -                | -                | -         |    -5.03 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2055 | 2024-05-14 | NRG              | L   | 0.677      | -            | -                | -                | -         |    -5.25 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2544 | 2024-04-23 | Nouns            | W   | 0.537      | 0.477        | 0.058 (0.015)    | 0.557 (0.143)    | 0 (0.000) |    13.46 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2546 | 2024-04-23 | Nouns            | L   | 0.537      | -            | -                | -                | -         |    -3.43 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2895 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.451      | 0.477        | 0.010 (0.002)    | 0.105 (0.022)    | 0 (0.000) |     8.38 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2900 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.450      | -            | -                | -                | -         |    -5.91 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     2953 | 2024-04-09 | Party Astronauts | L   | 0.444      | -            | -                | -                | -         |    -2.80 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     2959 | 2024-04-09 | Party Astronauts | L   | 0.444      | -            | -                | -                | -         |    -2.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3084 | 2024-04-04 | Limitless        | W   | 0.411      | 0.477        | 0.001 (0.000)    | 0.170 (0.033)    | 0 (0.000) |     5.71 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3088 | 2024-04-04 | Limitless        | L   | 0.410      | -            | -                | -                | -         |    -7.39 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3268 | 2024-03-27 | BOSS             | L   | 0.357      | -            | -                | -                | -         |    -4.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3271 | 2024-03-27 | BOSS             | W   | 0.357      | 0.477        | 0.014 (0.002)    | 0.334 (0.057)    | 0 (0.000) |     7.26 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3516 | 2024-03-14 | Mythic           | L   | 0.271      | -            | -                | -                | -         |    -3.25 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3519 | 2024-03-14 | Mythic           | L   | 0.271      | -            | -                | -                | -         |    -3.32 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3772 | 2024-03-05 | LAG              | L   | 0.211      | -            | -                | -                | -         |    -2.00 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3774 | 2024-03-05 | LAG              | L   | 0.211      | -            | -                | -                | -         |    -2.03 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4042 | 2024-02-22 | Party Astronauts | L   | 0.130      | -            | -                | -                | -         |    -0.92 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4286 | 2024-02-13 | Perseverance     | W   | 0.071      | 0.477        | 0.004 (0.000)    | 0.247 (0.008)    | -         |     1.21 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4289 | 2024-02-13 | Perseverance     | L   | 0.071      | -            | -                | -                | -         |    -1.03 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($680.00)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
