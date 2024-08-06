### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [181](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [50]( ../standings_americas.md)<br />
<br />
Final Rank Value:  640.6<br />
<br />
Final Rank Value (640.6) = Starting Rank Value (712.7) + Head To Head Adjustments (-72.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.278[<sup>2</sup>](#table1)
- Opponent Network: 0.059[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.7
- 400 + ( ( 0.152 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 712.7


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
|           44 |       46 | 2024-08-04 | Final Form       | L   | 1.000      | -            | -                | -                | -         |   -19.08 | cbass, Grave, jchancE, serv0, z0mb1e |
|           43 |       78 | 2024-08-03 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.26 | cbass, Champ, jchancE, serv0, z0mb1e |
|           42 |      182 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -12.93 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |      187 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.10 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      435 | 2024-07-24 | InControl        | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.038 (0.014)    | 0 (0.000) |     5.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      626 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.03 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      631 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.72 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      688 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.41 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      692 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.69 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      753 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.270 (0.129)    | 0 (0.000) |    15.56 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      759 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.270 (0.129)    | 0 (0.000) |    17.00 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      805 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.88 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      808 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.12 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |     1064 | 2024-06-15 | Akimbo           | W   | 0.856      | 0.143        | 0.015 (0.002)    | 0.263 (0.032)    | 0 (0.000) |    17.42 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1100 | 2024-06-14 | E-Xolos LAZER    | W   | 0.849      | 0.143        | 0.011 (0.001)    | 0.376 (0.046)    | 0 (0.000) |    18.06 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1855 | 2024-05-22 | Wildcard         | L   | 0.696      | -            | -                | -                | -         |    -3.98 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1858 | 2024-05-22 | Wildcard         | L   | 0.696      | -            | -                | -                | -         |    -4.13 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1905 | 2024-05-21 | Elevate          | L   | 0.689      | -            | -                | -                | -         |    -3.30 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1909 | 2024-05-21 | Elevate          | L   | 0.689      | -            | -                | -                | -         |    -3.41 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1942 | 2024-05-20 | MIGHT            | W   | 0.683      | 0.477        | -                | 0.056 (0.018)    | 0 (0.000) |     6.62 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1946 | 2024-05-20 | MIGHT            | L   | 0.682      | -            | -                | -                | -         |   -15.28 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     2071 | 2024-05-16 | Limitless        | L   | 0.656      | -            | -                | -                | -         |    -7.43 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     2072 | 2024-05-16 | Limitless        | L   | 0.656      | -            | -                | -                | -         |    -7.84 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     2111 | 2024-05-15 | M80              | L   | 0.649      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     2118 | 2024-05-15 | M80              | L   | 0.649      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2164 | 2024-05-14 | NRG              | L   | 0.643      | -            | -                | -                | -         |    -4.95 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2169 | 2024-05-14 | NRG              | L   | 0.642      | -            | -                | -                | -         |    -5.16 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2650 | 2024-04-23 | Nouns            | W   | 0.503      | 0.477        | 0.057 (0.014)    | 0.541 (0.130)    | 0 (0.000) |    12.46 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2652 | 2024-04-23 | Nouns            | L   | 0.502      | -            | -                | -                | -         |    -3.35 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2990 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.416      | 0.477        | 0.010 (0.002)    | 0.095 (0.019)    | 0 (0.000) |     7.63 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2995 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.416      | -            | -                | -                | -         |    -5.57 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     3048 | 2024-04-09 | Party Astronauts | L   | 0.409      | -            | -                | -                | -         |    -2.72 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     3054 | 2024-04-09 | Party Astronauts | L   | 0.409      | -            | -                | -                | -         |    -2.79 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3179 | 2024-04-04 | Limitless        | W   | 0.376      | 0.477        | 0.001 (0.000)    | 0.159 (0.028)    | 0 (0.000) |     5.20 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3183 | 2024-04-04 | Limitless        | L   | 0.376      | -            | -                | -                | -         |    -6.78 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3355 | 2024-03-27 | BOSS             | L   | 0.323      | -            | -                | -                | -         |    -3.85 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3358 | 2024-03-27 | BOSS             | W   | 0.323      | 0.477        | 0.014 (0.002)    | 0.319 (0.049)    | 0 (0.000) |     6.44 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3598 | 2024-03-14 | Mythic           | L   | 0.236      | -            | -                | -                | -         |    -2.89 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3601 | 2024-03-14 | Mythic           | L   | 0.236      | -            | -                | -                | -         |    -2.95 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3848 | 2024-03-05 | LAG              | L   | 0.176      | -            | -                | -                | -         |    -1.84 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3850 | 2024-03-05 | LAG              | L   | 0.176      | -            | -                | -                | -         |    -1.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4105 | 2024-02-22 | Party Astronauts | L   | 0.095      | -            | -                | -                | -         |    -0.70 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4347 | 2024-02-13 | Phoenix          | W   | 0.036      | 0.477        | 0.004 (0.000)    | -                | -         |     0.61 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4350 | 2024-02-13 | Phoenix          | L   | 0.036      | -            | -                | -                | -         |    -0.53 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($652.33)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
