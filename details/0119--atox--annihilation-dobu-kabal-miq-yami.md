### Roster Details<br />
Team Name: ATOX<br />
Roster: Annihilation, dobu, kabal, MiQ, yAmi<br />
Global Rank: [119](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [7]( ../standings_asia.md)<br />
<br />
Final Rank Value:  781.7<br />
<br />
Final Rank Value (781.7) = Starting Rank Value (782.1) + Head To Head Adjustments (-0.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.356[<sup>1</sup>](#table2)
- Bounty Collected: 0.304[<sup>2</sup>](#table1)
- Opponent Network: 0.029[<sup>2</sup>](#table1)
- LAN Wins: 0.099[<sup>2</sup>](#table1)

The average of these factors is 0.197<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 782.1
- 400 + ( ( 0.197 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 782.1


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
|           22 |      238 | 2024-08-30 | GR                | L   | 1.000      | -            | -                | -                | -         |   -20.21 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           21 |      248 | 2024-08-30 | Chinggis Warriors | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.187 (0.027)    | 0 (0.000) |    18.07 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           20 |      277 | 2024-08-29 | THE               | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.113 (0.016)    | 0 (0.000) |     6.10 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           19 |      298 | 2024-08-28 | IHC               | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.164 (0.023)    | 0 (0.000) |     4.86 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           18 |      345 | 2024-08-28 | GR                | L   | 1.000      | -            | -                | -                | -         |   -21.66 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           17 |      356 | 2024-08-28 | NomadS            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.069 (0.010)    | 0 (0.000) |     5.00 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           16 |     1252 | 2024-08-02 | Rare Atom         | L   | 0.952      | -            | -                | -                | -         |   -11.01 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           15 |     1283 | 2024-08-01 | CatEvil           | W   | 0.947      | 0.143        | 0.000 (0.000)    | 0.237 (0.032)    | 0 (0.000) |     8.29 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           14 |     1293 | 2024-08-01 | Rare Atom         | L   | 0.945      | -            | -                | -                | -         |   -10.96 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           13 |     2414 | 2024-06-09 | Lynn Vision       | L   | 0.593      | -            | -                | -                | -         |    -6.46 | Annihilation, dobu, kabal, MiQ, Zesta |
|           12 |     2594 | 2024-06-06 | Lynn Vision       | W   | 0.573      | 0.416        | 0.073 (0.017)    | 0.114 (0.027)    | 0 (0.000) |    11.89 | Annihilation, dobu, kabal, MiQ, Zesta |
|           11 |     2653 | 2024-06-05 | GR                | W   | 0.566      | 0.416        | 0.006 (0.001)    | 0.169 (0.040)    | 0 (0.000) |     6.00 | Annihilation, dobu, kabal, MiQ, Zesta |
|           10 |     2692 | 2024-06-04 | -72c              | W   | 0.560      | 0.416        | 0.003 (0.001)    | 0.110 (0.026)    | 0 (0.000) |     5.03 | Annihilation, dobu, kabal, MiQ, Zesta |
|            9 |     2781 | 2024-05-31 | Lynn Vision       | L   | 0.537      | -            | -                | -                | -         |    -5.75 | Annihilation, dobu, kabal, MiQ, Zesta |
|            8 |     2834 | 2024-05-29 | BLEED             | L   | 0.524      | -            | -                | -                | -         |    -1.49 | Annihilation, dobu, kabal, MiQ, Zesta |
|            7 |     2857 | 2024-05-29 | OG                | W   | 0.518      | 0.500        | 0.118 (0.030)    | 0.352 (0.091)    | 1 (0.518) |    11.96 | Annihilation, dobu, kabal, MiQ, Zesta |
|            6 |     3150 | 2024-05-18 | The MongolZ       | L   | 0.445      | -            | -                | -                | -         |    -0.03 | Annihilation, dobu, kabal, MiQ, Zesta |
|            5 |     3181 | 2024-05-17 | The Huns          | W   | 0.439      | -            | -                | -                | 1 (0.439) |     1.42 | Annihilation, dobu, kabal, MiQ, Zesta |
|            4 |     4415 | 2024-04-02 | The MongolZ       | L   | 0.140      | -            | -                | -                | -         |    -0.01 | Annihilation, dobu, kabal, MiQ, Zesta |
|            3 |     4420 | 2024-04-02 | Lynn Vision       | L   | 0.139      | -            | -                | -                | -         |    -1.45 | Annihilation, dobu, kabal, MiQ, Zesta |
|            2 |     4778 | 2024-03-13 | -72c              | W   | 0.006      | 0.143        | 0.003 (0.000)    | 0.110 (0.000)    | -         |     0.06 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            1 |     4788 | 2024-03-13 | ROUX              | W   | 0.006      | -            | -                | -                | -         |     0.02 | dobu, FlyNN, kabal, MiQ, Zesta        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,740.00)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
