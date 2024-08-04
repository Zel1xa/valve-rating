### Roster Details<br />
Team Name: TSM<br />
Roster: interz, joel, KWERTZZ, valde, Zyphon<br />
Global Rank: [164](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [105]( ../standings_europe.md)<br />
<br />
Final Rank Value:  678.8<br />
<br />
Final Rank Value (678.8) = Starting Rank Value (670.3) + Head To Head Adjustments (8.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.305[<sup>1</sup>](#table2)
- Bounty Collected: 0.214[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 670.3
- 400 + ( ( 0.132 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 670.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     2666 | 2024-04-19 | Sangal            | L   | 0.492      | -            | -                | -                | -         |    -1.15 | interz, joel, KWERTZZ, valde, Zyphon |
|           12 |     2928 | 2024-04-10 | FORZE             | L   | 0.432      | -            | -                | -                | -         |    -2.63 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           11 |     2987 | 2024-04-09 | Betera            | W   | 0.425      | 0.500        | 0.005 (0.001)    | 0.039 (0.008)    | 0 (0.000) |     7.44 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           10 |     3116 | 2024-04-04 | 9 Pandas          | L   | 0.392      | -            | -                | -                | -         |    -1.63 | joel, KWERTZZ, poizon, valde, Zyphon |
|            9 |     3195 | 2024-04-02 | KOI               | L   | 0.379      | -            | -                | -                | -         |    -1.17 | joel, KWERTZZ, poizon, valde, Zyphon |
|            8 |     3253 | 2024-03-28 | 9INE              | W   | 0.346      | 0.500        | 0.000 (0.000)    | 0.067 (0.012)    | 0 (0.000) |     3.27 | joel, KWERTZZ, poizon, valde, Zyphon |
|            7 |     3414 | 2024-03-20 | VP.Prodigy        | L   | 0.290      | -            | -                | -                | -         |    -2.36 | joel, KWERTZZ, poizon, valde, Zyphon |
|            6 |     3528 | 2024-03-14 | EYEBALLERS        | W   | 0.252      | 0.500        | 0.006 (0.001)    | 0.510 (0.064)    | 0 (0.000) |     6.23 | interz, joel, MoDo, valde, Zyphon    |
|            5 |     3734 | 2024-03-06 | Sangal            | L   | 0.199      | -            | -                | -                | -         |    -0.41 | interz, JACKZ, joel, poizon, valde   |
|            4 |     3816 | 2024-03-03 | The Chosen Few    | L   | 0.179      | -            | -                | -                | -         |    -2.83 | joel, KWERTZZ, poizon, valde, Zyphon |
|            3 |     3827 | 2024-03-03 | Nexus             | W   | 0.178      | 0.143        | 0.014 (0.000)    | 0.465 (0.012)    | 0 (0.000) |     4.01 | joel, KWERTZZ, poizon, valde, Zyphon |
|            2 |     4337 | 2024-02-08 | ex-Preasy         | L   | 0.016      | -            | -                | -                | -         |    -0.18 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|            1 |     4341 | 2024-02-07 | Gaimin Gladiators | L   | 0.010      | -            | -                | -                | -         |    -0.05 | joel, KWERTZZ, MoDo, valde, Zyphon   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,730.97)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.831 | $2,000.00      | $1,662.64       |
| 2024-02-09 |      0.023 | $3,000.00      | $68.33          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
