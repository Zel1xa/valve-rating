### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Champ, jchancE, serv0, z0mb1e<br />
Global Rank: [174](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [49]( ../standings_americas.md)<br />
<br />
Final Rank Value:  659.7<br />
<br />
Final Rank Value (659.7) = Starting Rank Value (712.8) + Head To Head Adjustments (-53.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.8
- 400 + ( ( 0.153 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 712.8


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
|           43 |       27 | 2024-08-03 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.26 | cbass, Champ, jchancE, serv0, z0mb1e |
|           42 |      131 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -12.94 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |      136 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.11 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      384 | 2024-07-24 | The Nomads       | W   | 1.000      | 0.371        | 0.000 (0.000)    | -                | 0 (0.000) |     5.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      575 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.04 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      580 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.73 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      637 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.35 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      641 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.63 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      702 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.283 (0.135)    | 0 (0.000) |    15.57 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      708 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.283 (0.135)    | 0 (0.000) |    17.01 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      754 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.83 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      757 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.06 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |     1013 | 2024-06-15 | Akimbo           | W   | 0.869      | 0.143        | 0.015 (0.002)    | 0.274 (0.034)    | 0 (0.000) |    17.71 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1049 | 2024-06-14 | E-Xolos LAZER    | W   | 0.862      | 0.143        | 0.011 (0.001)    | 0.389 (0.048)    | 0 (0.000) |    18.30 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1804 | 2024-05-22 | Wildcard         | L   | 0.710      | -            | -                | -                | -         |    -3.99 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1807 | 2024-05-22 | Wildcard         | L   | 0.709      | -            | -                | -                | -         |    -4.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1854 | 2024-05-21 | Elevate          | L   | 0.703      | -            | -                | -                | -         |    -3.34 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1858 | 2024-05-21 | Elevate          | L   | 0.702      | -            | -                | -                | -         |    -3.45 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1891 | 2024-05-20 | MIGHT            | W   | 0.696      | 0.477        | -                | 0.060 (0.020)    | 0 (0.000) |     6.79 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1895 | 2024-05-20 | MIGHT            | L   | 0.696      | -            | -                | -                | -         |   -15.54 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     2020 | 2024-05-16 | Limitless        | L   | 0.669      | -            | -                | -                | -         |    -7.53 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     2021 | 2024-05-16 | Limitless        | L   | 0.669      | -            | -                | -                | -         |    -7.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     2060 | 2024-05-15 | M80              | L   | 0.663      | -            | -                | -                | -         |    -0.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     2067 | 2024-05-15 | M80              | L   | 0.662      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2113 | 2024-05-14 | NRG              | L   | 0.656      | -            | -                | -                | -         |    -5.01 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2118 | 2024-05-14 | NRG              | L   | 0.656      | -            | -                | -                | -         |    -5.23 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2599 | 2024-04-23 | Nouns            | W   | 0.516      | 0.477        | 0.057 (0.014)    | 0.561 (0.138)    | 0 (0.000) |    12.85 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2601 | 2024-04-23 | Nouns            | L   | 0.516      | -            | -                | -                | -         |    -3.38 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2939 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.429      | 0.477        | 0.010 (0.002)    | 0.101 (0.021)    | 0 (0.000) |     7.89 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2944 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.429      | -            | -                | -                | -         |    -5.74 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     2997 | 2024-04-09 | Party Astronauts | L   | 0.423      | -            | -                | -                | -         |    -2.77 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     3003 | 2024-04-09 | Party Astronauts | L   | 0.422      | -            | -                | -                | -         |    -2.84 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3128 | 2024-04-04 | Limitless        | W   | 0.389      | 0.477        | 0.001 (0.000)    | 0.167 (0.031)    | 0 (0.000) |     5.39 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3132 | 2024-04-04 | Limitless        | L   | 0.389      | -            | -                | -                | -         |    -7.03 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3304 | 2024-03-27 | BOSS             | L   | 0.336      | -            | -                | -                | -         |    -4.01 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3307 | 2024-03-27 | BOSS             | W   | 0.336      | 0.477        | 0.014 (0.002)    | 0.332 (0.053)    | 0 (0.000) |     6.71 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3547 | 2024-03-14 | Mythic           | L   | 0.250      | -            | -                | -                | -         |    -3.05 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3550 | 2024-03-14 | Mythic           | L   | 0.249      | -            | -                | -                | -         |    -3.11 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3797 | 2024-03-05 | LAG              | L   | 0.190      | -            | -                | -                | -         |    -1.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3799 | 2024-03-05 | LAG              | L   | 0.189      | -            | -                | -                | -         |    -1.98 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4054 | 2024-02-22 | Party Astronauts | L   | 0.109      | -            | -                | -                | -         |    -0.80 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4296 | 2024-02-13 | Phoenix          | W   | 0.050      | 0.477        | 0.004 (0.000)    | 0.283 (0.007)    | -         |     0.84 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4299 | 2024-02-13 | Phoenix          | L   | 0.049      | -            | -                | -                | -         |    -0.73 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($663.02)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
