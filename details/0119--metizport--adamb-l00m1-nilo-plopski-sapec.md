### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, L00m1, nilo, Plopski, Sapec<br />
Global Rank: [119](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
<br />
Final Rank Value:  818.6<br />
<br />
Final Rank Value (818.6) = Starting Rank Value (786.0) + Head To Head Adjustments (32.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.294[<sup>1</sup>](#table2)
- Bounty Collected: 0.338[<sup>2</sup>](#table1)
- Opponent Network: 0.121[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.188<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 786.0
- 400 + ( ( 0.188 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 786.0


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
|           15 |      146 | 2024-08-01 | ALTERNATE aTTaX   | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.549 (0.078)    | 0 (0.000) |    18.27 | adamb, L00m1, nilo, Plopski, Sapec    |
|           14 |      155 | 2024-08-01 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -9.75 | adamb, Jackinho, nilo, Plopski, Sapec |
|           13 |      258 | 2024-07-30 | QUAZAR            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.87 | adamb, Jackinho, nilo, Plopski, Sapec |
|           12 |      305 | 2024-07-28 | Insilio           | L   | 1.000      | -            | -                | -                | -         |    -9.70 | adamb, Jackinho, nilo, Plopski, Sapec |
|           11 |      473 | 2024-07-23 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -12.28 | adamb, Jackinho, nilo, Plopski, Sapec |
|           10 |      491 | 2024-07-22 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -11.36 | adamb, Jackinho, nilo, Plopski, Sapec |
|            9 |      592 | 2024-07-19 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    18.46 | adamb, Jackinho, nilo, Plopski, Sapec |
|            8 |      651 | 2024-07-18 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -12.74 | adamb, Jackinho, nilo, Plopski, Sapec |
|            7 |      770 | 2024-07-16 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.513 (0.223)    | 0 (0.000) |    17.83 | adamb, Jackinho, nilo, Plopski, Sapec |
|            6 |     1834 | 2024-05-23 | Space             | L   | 0.699      | -            | -                | -                | -         |    -9.83 | abdi, adamb, Jackinho, nilo, Plopski  |
|            5 |     1940 | 2024-05-20 | Zero Tenacity     | L   | 0.682      | -            | -                | -                | -         |    -4.22 | adamb, Jackinho, nilo, Plopski, ztr   |
|            4 |     1992 | 2024-05-18 | Ninjas in Pyjamas | W   | 0.669      | 0.500        | 0.254 (0.085)    | 0.543 (0.182)    | 0 (0.000) |    20.79 | adamb, Jackinho, nilo, Plopski, ztr   |
|            3 |     2078 | 2024-05-16 | Rare Atom         | W   | 0.654      | 0.500        | 0.009 (0.003)    | 0.475 (0.155)    | 0 (0.000) |    12.16 | adamb, Jackinho, nilo, Plopski, ztr   |
|            2 |     2264 | 2024-05-11 | BetBoom           | L   | 0.621      | -            | -                | -                | -         |    -0.72 | adamb, Jackinho, nilo, Plopski, ztr   |
|            1 |     2278 | 2024-05-10 | EYEBALLERS        | W   | 0.615      | 0.435        | 0.005 (0.001)    | 0.499 (0.133)    | 0 (0.000) |    12.83 | adamb, Jackinho, nilo, Plopski, ztr   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,257.08)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
