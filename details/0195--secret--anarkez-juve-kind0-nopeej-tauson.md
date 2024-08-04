### Roster Details<br />
Team Name: Secret<br />
Roster: anarkez, Juve, Kind0, NOPEEJ, Tauson<br />
Global Rank: [195](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [124]( ../standings_europe.md)<br />
<br />
Final Rank Value:  534.4<br />
<br />
Final Rank Value (534.4) = Starting Rank Value (538.4) + Head To Head Adjustments (-4.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.068<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 538.4
- 400 + ( ( 0.068 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 538.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     2130 | 2024-05-14 | WOPA          | L   | 0.653      | -            | -                | -                | -         |    -8.02 | anarkez, Juve, Kind0, NOPEEJ, Tauson   |
|           19 |     2142 | 2024-05-13 | LEON          | L   | 0.648      | -            | -                | -                | -         |    -6.34 | anarkez, Juve, Kind0, NOPEEJ, Tauson   |
|           18 |     2686 | 2024-04-19 | Portugal      | L   | 0.488      | -            | -                | -                | -         |    -4.92 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           17 |     2741 | 2024-04-18 | Nemiga        | L   | 0.481      | -            | -                | -                | -         |    -0.54 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           16 |     2752 | 2024-04-18 | 500           | W   | 0.480      | 0.143        | 0.001 (0.000)    | 0.098 (0.007)    | 0 (0.000) |    11.29 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           15 |     2775 | 2024-04-17 | Illuminar     | L   | 0.475      | -            | -                | -                | -         |    -8.12 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           14 |     2825 | 2024-04-16 | Sampi         | L   | 0.465      | -            | -                | -                | -         |    -1.75 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           13 |     2840 | 2024-04-15 | PGE Turow     | W   | 0.460      | 0.371        | 0.001 (0.000)    | 0.020 (0.003)    | 0 (0.000) |     9.36 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           12 |     2912 | 2024-04-11 | ENCE Academy  | L   | 0.433      | -            | -                | -                | -         |    -3.80 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           11 |     3099 | 2024-04-05 | 9 Pandas      | W   | 0.393      | 0.384        | 0.082 (0.012)    | 0.690 (0.104)    | 0 (0.000) |    11.57 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           10 |     3618 | 2024-03-12 | Endpoint      | L   | 0.233      | -            | -                | -                | -         |    -0.90 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|            9 |     3703 | 2024-03-08 | Metizport     | L   | 0.207      | -            | -                | -                | -         |    -0.71 | anarkez, innocent, Kind0, Maze, Tauson |
|            8 |     3733 | 2024-03-07 | ex-Preasy     | L   | 0.199      | -            | -                | -                | -         |    -1.21 | anarkez, innocent, Kind0, Maze, Tauson |
|            7 |     3814 | 2024-03-04 | Fraud5        | L   | 0.180      | -            | -                | -                | -         |    -2.01 | anarkez, innocent, Kind0, Maze, Tauson |
|            6 |     3850 | 2024-03-03 | Zero Tenacity | L   | 0.173      | -            | -                | -                | -         |    -0.23 | anarkez, innocent, Kind0, Maze, Tauson |
|            5 |     3870 | 2024-03-02 | Zero Tenacity | L   | 0.166      | -            | -                | -                | -         |    -0.22 | anarkez, innocent, Kind0, Maze, Tauson |
|            4 |     3912 | 2024-02-28 | Permitta      | W   | 0.147      | 0.143        | 0.024 (0.000)    | 0.876 (0.018)    | 0 (0.000) |     4.20 | anarkez, innocent, Kind0, Maze, Tauson |
|            3 |     3971 | 2024-02-25 | Entropiq      | L   | 0.127      | -            | -                | -                | -         |    -1.95 | anarkez, innocent, Kind0, Maze, Tauson |
|            2 |     4167 | 2024-02-17 | Sampi         | L   | 0.073      | -            | -                | -                | -         |    -0.29 | anarkez, innocent, Kind0, Maze, Tauson |
|            1 |     4322 | 2024-02-10 | 500           | W   | 0.027      | 0.358        | 0.001 (0.000)    | 0.098 (0.001)    | 0 (0.000) |     0.59 | anarkez, innocent, Kind0, Maze, Tauson |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
