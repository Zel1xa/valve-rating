### Roster Details<br />
Team Name: ATOX<br />
Roster: Annihilation, dobu, kabal, MiQ, yAmi<br />
Global Rank: [95](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [4]( ../standings_asia.md)<br />
<br />
Final Rank Value:  858.2<br />
<br />
Final Rank Value (858.2) = Starting Rank Value (864.6) + Head To Head Adjustments (-6.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.372[<sup>1</sup>](#table2)
- Bounty Collected: 0.325[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.196[<sup>2</sup>](#table1)

The average of these factors is 0.227<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 864.6
- 400 + ( ( 0.227 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 864.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |       55 | 2024-08-02 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -18.20 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           19 |       85 | 2024-08-01 | CatEvil     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.235 (0.034)    | 0 (0.000) |     6.45 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           18 |       94 | 2024-08-01 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -18.76 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           17 |     1211 | 2024-06-09 | Lynn Vision | L   | 0.830      | -            | -                | -                | -         |    -9.71 | Annihilation, dobu, kabal, MiQ, Zesta |
|           16 |     1391 | 2024-06-06 | Lynn Vision | W   | 0.810      | 0.416        | 0.078 (0.026)    | 0.153 (0.052)    | 0 (0.000) |    16.24 | Annihilation, dobu, kabal, MiQ, Zesta |
|           15 |     1450 | 2024-06-05 | GR          | W   | 0.804      | 0.416        | 0.008 (0.003)    | 0.076 (0.025)    | 0 (0.000) |     5.94 | Annihilation, dobu, kabal, MiQ, Zesta |
|           14 |     1489 | 2024-06-04 | -72c        | W   | 0.797      | 0.416        | 0.003 (0.001)    | 0.039 (0.013)    | 0 (0.000) |     5.47 | Annihilation, dobu, kabal, MiQ, Zesta |
|           13 |     1578 | 2024-05-31 | Lynn Vision | L   | 0.774      | -            | -                | -                | -         |    -8.54 | Annihilation, dobu, kabal, MiQ, Zesta |
|           12 |     1631 | 2024-05-29 | BLEED       | L   | 0.761      | -            | -                | -                | -         |    -1.51 | Annihilation, dobu, kabal, MiQ, Zesta |
|           11 |     1654 | 2024-05-29 | OG          | W   | 0.756      | 0.500        | 0.140 (0.053)    | 0.129 (0.049)    | 1 (0.756) |    17.24 | Annihilation, dobu, kabal, MiQ, Zesta |
|           10 |     1947 | 2024-05-18 | The MongolZ | L   | 0.682      | -            | -                | -                | -         |    -0.07 | Annihilation, dobu, kabal, MiQ, Zesta |
|            9 |     1978 | 2024-05-17 | The Huns    | W   | 0.676      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 1 (0.676) |     1.40 | Annihilation, dobu, kabal, MiQ, Zesta |
|            8 |     3211 | 2024-04-02 | The MongolZ | L   | 0.377      | -            | -                | -                | -         |    -0.04 | Annihilation, dobu, kabal, MiQ, Zesta |
|            7 |     3216 | 2024-04-02 | Lynn Vision | L   | 0.376      | -            | -                | -                | -         |    -3.96 | Annihilation, dobu, kabal, MiQ, Zesta |
|            6 |     3573 | 2024-03-13 | -72c        | W   | 0.243      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     0.53 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            5 |     3583 | 2024-03-13 | ROUX        | W   | 0.243      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.53 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            4 |     3904 | 2024-02-27 | FlyQuest    | L   | 0.148      | -            | -                | -                | -         |    -0.75 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            3 |     3928 | 2024-02-26 | TYLOO       | W   | 0.142      | 0.143        | 0.019 (0.000)    | 0.092 (0.002)    | 1 (0.142) |     1.61 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            2 |     3931 | 2024-02-26 | MAG         | W   | 0.141      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 1 (0.141) |     0.48 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            1 |     3944 | 2024-02-25 | FlyQuest    | L   | 0.134      | -            | -                | -                | -         |    -0.68 | AccuracyTG, dobu, kabal, MiQ, Zesta   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,637.78)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
