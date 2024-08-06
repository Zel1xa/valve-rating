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
- Opponent Network: 0.060[<sup>2</sup>](#table1)
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
|           44 |       34 | 2024-08-04 | Final Form       | L   | 1.000      | -            | -                | -                | -         |   -19.08 | cbass, Grave, jchancE, serv0, z0mb1e |
|           43 |       66 | 2024-08-03 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.26 | cbass, Champ, jchancE, serv0, z0mb1e |
|           42 |      170 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -12.93 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |      175 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.10 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      423 | 2024-07-24 | InControl        | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.038 (0.014)    | 0 (0.000) |     5.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      614 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.03 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      619 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.72 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      676 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.40 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      680 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.68 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      741 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.270 (0.129)    | 0 (0.000) |    15.57 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      747 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.270 (0.129)    | 0 (0.000) |    17.00 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      793 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.88 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      796 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.12 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |     1052 | 2024-06-15 | Akimbo           | W   | 0.857      | 0.143        | 0.015 (0.002)    | 0.263 (0.032)    | 0 (0.000) |    17.45 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1088 | 2024-06-14 | E-Xolos LAZER    | W   | 0.850      | 0.143        | 0.011 (0.001)    | 0.376 (0.046)    | 0 (0.000) |    18.09 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1843 | 2024-05-22 | Wildcard         | L   | 0.697      | -            | -                | -                | -         |    -3.98 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1846 | 2024-05-22 | Wildcard         | L   | 0.697      | -            | -                | -                | -         |    -4.13 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1893 | 2024-05-21 | Elevate          | L   | 0.690      | -            | -                | -                | -         |    -3.31 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1897 | 2024-05-21 | Elevate          | L   | 0.690      | -            | -                | -                | -         |    -3.41 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1930 | 2024-05-20 | MIGHT            | W   | 0.684      | 0.477        | -                | 0.056 (0.018)    | 0 (0.000) |     6.63 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1934 | 2024-05-20 | MIGHT            | L   | 0.684      | -            | -                | -                | -         |   -15.30 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     2059 | 2024-05-16 | Limitless        | L   | 0.657      | -            | -                | -                | -         |    -7.43 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     2060 | 2024-05-16 | Limitless        | L   | 0.657      | -            | -                | -                | -         |    -7.85 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     2099 | 2024-05-15 | M80              | L   | 0.650      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     2106 | 2024-05-15 | M80              | L   | 0.650      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2152 | 2024-05-14 | NRG              | L   | 0.644      | -            | -                | -                | -         |    -4.95 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2157 | 2024-05-14 | NRG              | L   | 0.644      | -            | -                | -                | -         |    -5.17 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2638 | 2024-04-23 | Nouns            | W   | 0.504      | 0.477        | 0.057 (0.014)    | 0.541 (0.130)    | 0 (0.000) |    12.49 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2640 | 2024-04-23 | Nouns            | L   | 0.504      | -            | -                | -                | -         |    -3.35 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2978 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.417      | 0.477        | 0.010 (0.002)    | 0.095 (0.019)    | 0 (0.000) |     7.65 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2983 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.417      | -            | -                | -                | -         |    -5.59 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     3036 | 2024-04-09 | Party Astronauts | L   | 0.410      | -            | -                | -                | -         |    -2.73 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     3042 | 2024-04-09 | Party Astronauts | L   | 0.410      | -            | -                | -                | -         |    -2.79 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3167 | 2024-04-04 | Limitless        | W   | 0.377      | 0.477        | 0.001 (0.000)    | 0.159 (0.029)    | 0 (0.000) |     5.22 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3171 | 2024-04-04 | Limitless        | L   | 0.377      | -            | -                | -                | -         |    -6.80 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3343 | 2024-03-27 | BOSS             | L   | 0.324      | -            | -                | -                | -         |    -3.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3346 | 2024-03-27 | BOSS             | W   | 0.324      | 0.477        | 0.014 (0.002)    | 0.319 (0.049)    | 0 (0.000) |     6.46 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3586 | 2024-03-14 | Mythic           | L   | 0.237      | -            | -                | -                | -         |    -2.91 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3589 | 2024-03-14 | Mythic           | L   | 0.237      | -            | -                | -                | -         |    -2.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3836 | 2024-03-05 | LAG              | L   | 0.177      | -            | -                | -                | -         |    -1.85 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3838 | 2024-03-05 | LAG              | L   | 0.177      | -            | -                | -                | -         |    -1.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4093 | 2024-02-22 | Party Astronauts | L   | 0.096      | -            | -                | -                | -         |    -0.71 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4335 | 2024-02-13 | Phoenix          | W   | 0.037      | 0.477        | 0.004 (0.000)    | -                | -         |     0.63 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4338 | 2024-02-13 | Phoenix          | L   | 0.037      | -            | -                | -                | -         |    -0.55 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($653.26)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
