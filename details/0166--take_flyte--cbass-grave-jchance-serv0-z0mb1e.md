### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [166](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [47]( ../standings_americas.md)<br />
<br />
Final Rank Value:  671.9<br />
<br />
Final Rank Value (671.9) = Starting Rank Value (712.2) + Head To Head Adjustments (-40.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.2
- 400 + ( ( 0.153 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 712.2


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
|           42 |       74 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -13.15 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |       79 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.35 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      326 | 2024-07-24 | The Nomads       | W   | 1.000      | 0.371        | 0.000 (0.000)    | -                | 0 (0.000) |     4.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      517 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.35 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      522 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.63 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      579 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.33 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      583 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.61 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      641 | 2024-07-16 | Perseverance     | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.253 (0.121)    | 0 (0.000) |    15.62 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      647 | 2024-07-16 | Perseverance     | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.253 (0.121)    | 0 (0.000) |    17.06 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      693 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.99 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      696 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.23 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |      939 | 2024-06-15 | Akimbo           | W   | 0.876      | 0.143        | 0.015 (0.002)    | 0.284 (0.036)    | 0 (0.000) |    18.08 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |      969 | 2024-06-14 | E-Xolos LAZER    | W   | 0.869      | 0.143        | 0.011 (0.001)    | 0.367 (0.046)    | 0 (0.000) |    18.26 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1704 | 2024-05-22 | Wildcard         | L   | 0.716      | -            | -                | -                | -         |    -3.52 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1707 | 2024-05-22 | Wildcard         | L   | 0.716      | -            | -                | -                | -         |    -3.64 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1754 | 2024-05-21 | Elevate          | L   | 0.709      | -            | -                | -                | -         |    -3.83 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1758 | 2024-05-21 | Elevate          | L   | 0.709      | -            | -                | -                | -         |    -3.97 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1791 | 2024-05-20 | MIGHT            | W   | 0.703      | 0.477        | -                | 0.062 (0.021)    | 0 (0.000) |     6.88 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1795 | 2024-05-20 | MIGHT            | L   | 0.702      | -            | -                | -                | -         |   -15.65 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     1919 | 2024-05-16 | Limitless        | L   | 0.676      | -            | -                | -                | -         |    -7.53 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     1920 | 2024-05-16 | Limitless        | L   | 0.676      | -            | -                | -                | -         |    -7.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     1959 | 2024-05-15 | M80              | L   | 0.669      | -            | -                | -                | -         |    -0.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     1966 | 2024-05-15 | M80              | L   | 0.669      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2012 | 2024-05-14 | NRG              | L   | 0.662      | -            | -                | -                | -         |    -4.99 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2017 | 2024-05-14 | NRG              | L   | 0.662      | -            | -                | -                | -         |    -5.21 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2496 | 2024-04-23 | Nouns            | W   | 0.523      | 0.477        | 0.057 (0.014)    | 0.566 (0.141)    | 0 (0.000) |    12.93 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2498 | 2024-04-23 | Nouns            | L   | 0.522      | -            | -                | -                | -         |    -3.51 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2836 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.436      | 0.477        | 0.010 (0.002)    | 0.106 (0.022)    | 0 (0.000) |     8.04 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2841 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.436      | -            | -                | -                | -         |    -5.79 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     2894 | 2024-04-09 | Party Astronauts | L   | 0.429      | -            | -                | -                | -         |    -2.70 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     2900 | 2024-04-09 | Party Astronauts | L   | 0.429      | -            | -                | -                | -         |    -2.76 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3025 | 2024-04-04 | Limitless        | W   | 0.396      | 0.477        | 0.001 (0.000)    | 0.174 (0.033)    | 0 (0.000) |     5.50 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3029 | 2024-04-04 | Limitless        | L   | 0.396      | -            | -                | -                | -         |    -7.12 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3201 | 2024-03-27 | BOSS             | L   | 0.343      | -            | -                | -                | -         |    -4.09 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3204 | 2024-03-27 | BOSS             | W   | 0.343      | 0.477        | 0.014 (0.002)    | 0.344 (0.056)    | 0 (0.000) |     6.84 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3438 | 2024-03-14 | Mythic           | L   | 0.256      | -            | -                | -                | -         |    -3.10 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3441 | 2024-03-14 | Mythic           | L   | 0.256      | -            | -                | -                | -         |    -3.17 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3686 | 2024-03-05 | LAG              | L   | 0.196      | -            | -                | -                | -         |    -1.92 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3688 | 2024-03-05 | LAG              | L   | 0.196      | -            | -                | -                | -         |    -1.94 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     3943 | 2024-02-22 | Party Astronauts | L   | 0.115      | -            | -                | -                | -         |    -0.82 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4184 | 2024-02-13 | Perseverance     | W   | 0.056      | 0.477        | 0.004 (0.000)    | 0.253 (0.007)    | -         |     0.95 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4187 | 2024-02-13 | Perseverance     | L   | 0.056      | -            | -                | -                | -         |    -0.82 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($668.26)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
