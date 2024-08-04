### Roster Details<br />
Team Name: Fearless Cheetahs<br />
Roster: kr4sy, Ksu, t4tty, Victoria, vilga<br />
Global Rank: [154](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [101]( ../standings_europe.md)<br />
<br />
Final Rank Value:  693.0<br />
<br />
Final Rank Value (693.0) = Starting Rank Value (679.0) + Head To Head Adjustments (14.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.281[<sup>1</sup>](#table2)
- Bounty Collected: 0.259[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.136<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 679.0
- 400 + ( ( 0.136 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 679.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     2607 | 2024-04-21 | Astralis W    | L   | 0.502      | -            | -                | -                | -         |    -8.66 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            9 |     2625 | 2024-04-20 | BIG EQUIPA    | L   | 0.496      | -            | -                | -                | -         |    -6.23 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            8 |     2672 | 2024-04-19 | 1WIN Gang     | W   | 0.489      | 0.331        | 0.001 (0.000)    | 0.017 (0.003)    | 0 (0.000) |     6.70 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            7 |     2890 | 2024-04-11 | Crescent fe   | W   | 0.435      | 0.331        | 0.005 (0.001)    | 0.078 (0.011)    | 0 (0.000) |     5.96 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            6 |     3062 | 2024-04-07 | NIP Impact    | L   | 0.407      | -            | -                | -                | -         |    -6.14 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            5 |     3078 | 2024-04-06 | Let Her Cook  | W   | 0.400      | 0.262        | 0.060 (0.006)    | 0.144 (0.015)    | 0 (0.000) |     9.91 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            4 |     3299 | 2024-03-27 | Spirit fe     | W   | 0.336      | 0.331        | 0.005 (0.001)    | 0.141 (0.016)    | 0 (0.000) |     5.02 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            3 |     3384 | 2024-03-21 | Let Her Cook  | W   | 0.296      | 0.331        | 0.060 (0.006)    | 0.144 (0.014)    | 0 (0.000) |     7.47 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            2 |     3741 | 2024-03-06 | NAVI Javelins | L   | 0.196      | -            | -                | -                | -         |    -1.92 | kr4sy, Ksu, t4tty, Victoria, vilga |
|            1 |     3959 | 2024-02-25 | 1WIN Gang     | W   | 0.129      | 0.250        | 0.001 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     1.92 | kr4sy, Ksu, t4tty, Victoria, vilga |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($900.00)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.502 | $1,600.00      | $803.33         |
| 2024-02-25 |      0.129 | $750.00        | $96.67          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
