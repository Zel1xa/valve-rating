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
|           44 |       39 | 2024-08-04 | Final Form       | L   | 1.000      | -            | -                | -                | -         |   -19.08 | cbass, Grave, jchancE, serv0, z0mb1e |
|           43 |       71 | 2024-08-03 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.26 | cbass, Champ, jchancE, serv0, z0mb1e |
|           42 |      175 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -12.93 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |      180 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.10 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      428 | 2024-07-24 | InControl        | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.038 (0.014)    | 0 (0.000) |     5.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      619 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.03 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      624 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.72 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      681 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.40 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      685 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.69 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      746 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.270 (0.129)    | 0 (0.000) |    15.56 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      752 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.270 (0.129)    | 0 (0.000) |    17.00 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      798 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.88 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      801 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.12 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |     1057 | 2024-06-15 | Akimbo           | W   | 0.856      | 0.143        | 0.015 (0.002)    | 0.263 (0.032)    | 0 (0.000) |    17.43 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1093 | 2024-06-14 | E-Xolos LAZER    | W   | 0.850      | 0.143        | 0.011 (0.001)    | 0.376 (0.046)    | 0 (0.000) |    18.07 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1848 | 2024-05-22 | Wildcard         | L   | 0.697      | -            | -                | -                | -         |    -3.98 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1851 | 2024-05-22 | Wildcard         | L   | 0.697      | -            | -                | -                | -         |    -4.13 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1898 | 2024-05-21 | Elevate          | L   | 0.690      | -            | -                | -                | -         |    -3.30 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1902 | 2024-05-21 | Elevate          | L   | 0.690      | -            | -                | -                | -         |    -3.41 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1935 | 2024-05-20 | MIGHT            | W   | 0.683      | 0.477        | -                | 0.056 (0.018)    | 0 (0.000) |     6.62 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1939 | 2024-05-20 | MIGHT            | L   | 0.683      | -            | -                | -                | -         |   -15.29 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     2064 | 2024-05-16 | Limitless        | L   | 0.657      | -            | -                | -                | -         |    -7.43 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     2065 | 2024-05-16 | Limitless        | L   | 0.656      | -            | -                | -                | -         |    -7.84 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     2104 | 2024-05-15 | M80              | L   | 0.650      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     2111 | 2024-05-15 | M80              | L   | 0.650      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2157 | 2024-05-14 | NRG              | L   | 0.643      | -            | -                | -                | -         |    -4.95 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2162 | 2024-05-14 | NRG              | L   | 0.643      | -            | -                | -                | -         |    -5.16 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2643 | 2024-04-23 | Nouns            | W   | 0.503      | 0.477        | 0.057 (0.014)    | 0.541 (0.130)    | 0 (0.000) |    12.48 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2645 | 2024-04-23 | Nouns            | L   | 0.503      | -            | -                | -                | -         |    -3.35 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2983 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.417      | 0.477        | 0.010 (0.002)    | 0.095 (0.019)    | 0 (0.000) |     7.64 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2988 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.416      | -            | -                | -                | -         |    -5.58 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     3041 | 2024-04-09 | Party Astronauts | L   | 0.410      | -            | -                | -                | -         |    -2.73 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     3047 | 2024-04-09 | Party Astronauts | L   | 0.410      | -            | -                | -                | -         |    -2.79 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3172 | 2024-04-04 | Limitless        | W   | 0.377      | 0.477        | 0.001 (0.000)    | 0.159 (0.029)    | 0 (0.000) |     5.21 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3176 | 2024-04-04 | Limitless        | L   | 0.376      | -            | -                | -                | -         |    -6.79 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3348 | 2024-03-27 | BOSS             | L   | 0.324      | -            | -                | -                | -         |    -3.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3351 | 2024-03-27 | BOSS             | W   | 0.323      | 0.477        | 0.014 (0.002)    | 0.319 (0.049)    | 0 (0.000) |     6.45 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3591 | 2024-03-14 | Mythic           | L   | 0.237      | -            | -                | -                | -         |    -2.90 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3594 | 2024-03-14 | Mythic           | L   | 0.237      | -            | -                | -                | -         |    -2.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3841 | 2024-03-05 | LAG              | L   | 0.177      | -            | -                | -                | -         |    -1.84 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3843 | 2024-03-05 | LAG              | L   | 0.177      | -            | -                | -                | -         |    -1.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4098 | 2024-02-22 | Party Astronauts | L   | 0.096      | -            | -                | -                | -         |    -0.71 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4340 | 2024-02-13 | Phoenix          | W   | 0.037      | 0.477        | 0.004 (0.000)    | -                | -         |     0.62 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4343 | 2024-02-13 | Phoenix          | L   | 0.037      | -            | -                | -                | -         |    -0.54 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($652.81)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
