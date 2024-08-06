### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [180](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [50]( ../standings_americas.md)<br />
<br />
Final Rank Value:  640.6<br />
<br />
Final Rank Value (640.6) = Starting Rank Value (712.8) + Head To Head Adjustments (-72.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.278[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.8
- 400 + ( ( 0.152 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 712.8


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
|           44 |       31 | 2024-08-04 | Final Form       | L   | 1.000      | -            | -                | -                | -         |   -19.07 | cbass, Grave, jchancE, serv0, z0mb1e |
|           43 |       63 | 2024-08-03 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.26 | cbass, Champ, jchancE, serv0, z0mb1e |
|           42 |      167 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -12.93 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |      172 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.10 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      420 | 2024-07-24 | InControl        | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.038 (0.014)    | 0 (0.000) |     5.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      611 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.03 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      616 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.72 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      673 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.40 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      677 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.68 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      738 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.271 (0.129)    | 0 (0.000) |    15.57 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      744 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.271 (0.129)    | 0 (0.000) |    17.00 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      790 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.88 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      793 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.12 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |     1049 | 2024-06-15 | Akimbo           | W   | 0.857      | 0.143        | 0.015 (0.002)    | 0.263 (0.032)    | 0 (0.000) |    17.45 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1085 | 2024-06-14 | E-Xolos LAZER    | W   | 0.851      | 0.143        | 0.011 (0.001)    | 0.376 (0.046)    | 0 (0.000) |    18.09 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1840 | 2024-05-22 | Wildcard         | L   | 0.698      | -            | -                | -                | -         |    -3.98 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1843 | 2024-05-22 | Wildcard         | L   | 0.698      | -            | -                | -                | -         |    -4.13 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1890 | 2024-05-21 | Elevate          | L   | 0.691      | -            | -                | -                | -         |    -3.31 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1894 | 2024-05-21 | Elevate          | L   | 0.691      | -            | -                | -                | -         |    -3.41 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1927 | 2024-05-20 | MIGHT            | W   | 0.684      | 0.477        | -                | 0.056 (0.018)    | 0 (0.000) |     6.64 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1931 | 2024-05-20 | MIGHT            | L   | 0.684      | -            | -                | -                | -         |   -15.31 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     2056 | 2024-05-16 | Limitless        | L   | 0.657      | -            | -                | -                | -         |    -7.44 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     2057 | 2024-05-16 | Limitless        | L   | 0.657      | -            | -                | -                | -         |    -7.85 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     2096 | 2024-05-15 | M80              | L   | 0.651      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     2103 | 2024-05-15 | M80              | L   | 0.651      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2149 | 2024-05-14 | NRG              | L   | 0.644      | -            | -                | -                | -         |    -4.95 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2154 | 2024-05-14 | NRG              | L   | 0.644      | -            | -                | -                | -         |    -5.17 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2635 | 2024-04-23 | Nouns            | W   | 0.504      | 0.477        | 0.057 (0.014)    | 0.541 (0.130)    | 0 (0.000) |    12.51 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2637 | 2024-04-23 | Nouns            | L   | 0.504      | -            | -                | -                | -         |    -3.36 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2975 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.418      | 0.477        | 0.010 (0.002)    | 0.095 (0.019)    | 0 (0.000) |     7.66 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2980 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.417      | -            | -                | -                | -         |    -5.59 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     3033 | 2024-04-09 | Party Astronauts | L   | 0.411      | -            | -                | -                | -         |    -2.73 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     3039 | 2024-04-09 | Party Astronauts | L   | 0.411      | -            | -                | -                | -         |    -2.79 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3164 | 2024-04-04 | Limitless        | W   | 0.378      | 0.477        | 0.001 (0.000)    | 0.159 (0.029)    | 0 (0.000) |     5.22 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3168 | 2024-04-04 | Limitless        | L   | 0.377      | -            | -                | -                | -         |    -6.81 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3340 | 2024-03-27 | BOSS             | L   | 0.324      | -            | -                | -                | -         |    -3.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3343 | 2024-03-27 | BOSS             | W   | 0.324      | 0.477        | 0.014 (0.002)    | 0.319 (0.049)    | 0 (0.000) |     6.47 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3583 | 2024-03-14 | Mythic           | L   | 0.238      | -            | -                | -                | -         |    -2.91 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3586 | 2024-03-14 | Mythic           | L   | 0.237      | -            | -                | -                | -         |    -2.97 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3833 | 2024-03-05 | LAG              | L   | 0.178      | -            | -                | -                | -         |    -1.85 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3835 | 2024-03-05 | LAG              | L   | 0.177      | -            | -                | -                | -         |    -1.88 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4090 | 2024-02-22 | Party Astronauts | L   | 0.097      | -            | -                | -                | -         |    -0.71 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4332 | 2024-02-13 | Phoenix          | W   | 0.038      | 0.477        | 0.004 (0.000)    | -                | -         |     0.64 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4335 | 2024-02-13 | Phoenix          | L   | 0.037      | -            | -                | -                | -         |    -0.55 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($653.56)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />