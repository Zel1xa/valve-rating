### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, L00m1, nilo, Plopski, Sapec<br />
Global Rank: [121](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [86]( ../standings_europe.md)<br />
<br />
Final Rank Value:  818.2<br />
<br />
Final Rank Value (818.2) = Starting Rank Value (786.2) + Head To Head Adjustments (32.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.294[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.122[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 786.2
- 400 + ( ( 0.189 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 786.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      130 | 2024-08-01 | ALTERNATE aTTaX   | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.557 (0.080)    | 0 (0.000) |    18.23 | adamb, L00m1, nilo, Plopski, Sapec    |
|           14 |      140 | 2024-08-01 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -9.86 | adamb, Jackinho, nilo, Plopski, Sapec |
|           13 |      244 | 2024-07-30 | QUAZAR            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.87 | adamb, Jackinho, nilo, Plopski, Sapec |
|           12 |      290 | 2024-07-28 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -9.82 | adamb, Jackinho, nilo, Plopski, Sapec |
|           11 |      458 | 2024-07-23 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -12.41 | adamb, Jackinho, nilo, Plopski, Sapec |
|           10 |      476 | 2024-07-22 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -11.53 | adamb, Jackinho, nilo, Plopski, Sapec |
|            9 |      577 | 2024-07-19 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    18.36 | adamb, Jackinho, nilo, Plopski, Sapec |
|            8 |      636 | 2024-07-18 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -12.81 | adamb, Jackinho, nilo, Plopski, Sapec |
|            7 |      755 | 2024-07-16 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.520 (0.226)    | 0 (0.000) |    17.77 | adamb, Jackinho, nilo, Plopski, Sapec |
|            6 |     1819 | 2024-05-23 | Space             | L   | 0.705      | -            | -                | -                | -         |    -9.93 | abdi, adamb, Jackinho, nilo, Plopski  |
|            5 |     1925 | 2024-05-20 | Zero Tenacity     | L   | 0.688      | -            | -                | -                | -         |    -4.26 | adamb, Jackinho, nilo, Plopski, ztr   |
|            4 |     1977 | 2024-05-18 | Ninjas in Pyjamas | W   | 0.675      | 0.500        | 0.254 (0.086)    | 0.551 (0.186)    | 0 (0.000) |    20.97 | adamb, Jackinho, nilo, Plopski, ztr   |
|            3 |     2063 | 2024-05-16 | Rare Atom         | W   | 0.660      | 0.500        | 0.009 (0.003)    | 0.480 (0.158)    | 0 (0.000) |    12.23 | adamb, Jackinho, nilo, Plopski, ztr   |
|            2 |     2249 | 2024-05-11 | BetBoom           | L   | 0.626      | -            | -                | -                | -         |    -0.72 | adamb, Jackinho, nilo, Plopski, ztr   |
|            1 |     2263 | 2024-05-10 | EYEBALLERS        | W   | 0.621      | 0.435        | 0.005 (0.001)    | 0.507 (0.137)    | 0 (0.000) |    12.91 | adamb, Jackinho, nilo, Plopski, ztr   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,268.75)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
