### Roster Details<br />
Team Name: Secret<br />
Roster: anarkez, Juve, Kind0, NOPEEJ, Tauson<br />
Global Rank: [197](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [125]( ../standings_europe.md)<br />
<br />
Final Rank Value:  534.2<br />
<br />
Final Rank Value (534.2) = Starting Rank Value (538.4) + Head To Head Adjustments (-4.3)<br />

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
- 400 + ( ( 0.068 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 538.4


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
|           20 |     2180 | 2024-05-14 | WOPA          | L   | 0.645      | -            | -                | -                | -         |    -7.89 | anarkez, Juve, Kind0, NOPEEJ, Tauson   |
|           19 |     2192 | 2024-05-13 | LEON          | L   | 0.640      | -            | -                | -                | -         |    -6.24 | anarkez, Juve, Kind0, NOPEEJ, Tauson   |
|           18 |     2736 | 2024-04-19 | Portugal      | L   | 0.480      | -            | -                | -                | -         |    -4.84 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           17 |     2791 | 2024-04-18 | Nemiga        | L   | 0.472      | -            | -                | -                | -         |    -0.47 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           16 |     2802 | 2024-04-18 | 500           | W   | 0.471      | 0.143        | 0.001 (0.000)    | 0.094 (0.006)    | 0 (0.000) |    11.08 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           15 |     2825 | 2024-04-17 | Illuminar     | L   | 0.467      | -            | -                | -                | -         |    -7.96 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           14 |     2875 | 2024-04-16 | Sampi         | L   | 0.457      | -            | -                | -                | -         |    -1.72 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           13 |     2890 | 2024-04-15 | PGE Turow     | W   | 0.451      | 0.371        | 0.001 (0.000)    | 0.019 (0.003)    | 0 (0.000) |     9.19 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           12 |     2962 | 2024-04-11 | ENCE Academy  | L   | 0.425      | -            | -                | -                | -         |    -3.73 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           11 |     3149 | 2024-04-05 | 9 Pandas      | W   | 0.385      | 0.384        | 0.081 (0.012)    | 0.717 (0.106)    | 0 (0.000) |    11.32 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           10 |     3668 | 2024-03-12 | Endpoint      | L   | 0.224      | -            | -                | -                | -         |    -0.87 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|            9 |     3753 | 2024-03-08 | Metizport     | L   | 0.198      | -            | -                | -                | -         |    -0.95 | anarkez, innocent, Kind0, Maze, Tauson |
|            8 |     3783 | 2024-03-07 | ex-Preasy     | L   | 0.191      | -            | -                | -                | -         |    -1.18 | anarkez, innocent, Kind0, Maze, Tauson |
|            7 |     3864 | 2024-03-04 | Fraud5        | L   | 0.172      | -            | -                | -                | -         |    -1.92 | anarkez, innocent, Kind0, Maze, Tauson |
|            6 |     3900 | 2024-03-03 | Zero Tenacity | L   | 0.164      | -            | -                | -                | -         |    -0.21 | anarkez, innocent, Kind0, Maze, Tauson |
|            5 |     3920 | 2024-03-02 | Zero Tenacity | L   | 0.158      | -            | -                | -                | -         |    -0.20 | anarkez, innocent, Kind0, Maze, Tauson |
|            4 |     3962 | 2024-02-28 | Permitta      | W   | 0.138      | 0.143        | 0.024 (0.000)    | 0.902 (0.018)    | 0 (0.000) |     4.00 | anarkez, innocent, Kind0, Maze, Tauson |
|            3 |     4021 | 2024-02-25 | Entropiq      | L   | 0.118      | -            | -                | -                | -         |    -1.82 | anarkez, innocent, Kind0, Maze, Tauson |
|            2 |     4217 | 2024-02-17 | Sampi         | L   | 0.065      | -            | -                | -                | -         |    -0.26 | anarkez, innocent, Kind0, Maze, Tauson |
|            1 |     4372 | 2024-02-10 | 500           | W   | 0.018      | 0.358        | 0.001 (0.000)    | 0.094 (0.001)    | 0 (0.000) |     0.41 | anarkez, innocent, Kind0, Maze, Tauson |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
