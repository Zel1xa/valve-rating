### Roster Details<br />
Team Name: Intense<br />
Roster: ckzao, diozera, fREQ, keiz, mxa<br />
Global Rank: [116](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [29]( ../standings_americas.md)<br />
<br />
Final Rank Value:  818.6<br />
<br />
Final Rank Value (818.6) = Starting Rank Value (751.2) + Head To Head Adjustments (67.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.274[<sup>1</sup>](#table2)
- Bounty Collected: 0.307[<sup>2</sup>](#table1)
- Opponent Network: 0.099[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 751.2
- 400 + ( ( 0.170 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 751.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |       81 | 2024-07-29 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -7.90 | ckzao, diozera, fREQ, keiz, mxa |
|           22 |      120 | 2024-07-28 | Fluxo          | W   | 1.000      | 0.143        | 0.126 (0.018)    | 0.685 (0.098)    | 0 (0.000) |    27.11 | ckzao, diozera, fREQ, keiz, mxa |
|           21 |      281 | 2024-07-23 | Vikings KR     | W   | 1.000      | 0.371        | 0.008 (0.003)    | 0.458 (0.170)    | 0 (0.000) |    17.71 | ckzao, diozera, fREQ, keiz, mxa |
|           20 |      308 | 2024-07-22 | Case           | L   | 1.000      | -            | -                | -                | -         |   -10.82 | ckzao, diozera, fREQ, keiz, mxa |
|           19 |      358 | 2024-07-20 | inSanitY       | L   | 1.000      | -            | -                | -                | -         |    -6.45 | ckzao, diozera, fREQ, keiz, mxa |
|           18 |      400 | 2024-07-19 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |    -3.21 | ckzao, diozera, fREQ, keiz, mxa |
|           17 |      434 | 2024-07-18 | Bounty Hunters | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.471 (0.175)    | 0 (0.000) |    23.25 | ckzao, diozera, fREQ, keiz, mxa |
|           16 |      587 | 2024-07-16 | Galorys        | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.553 (0.205)    | 0 (0.000) |    18.08 | ckzao, diozera, fREQ, keiz, mxa |
|           15 |      662 | 2024-07-13 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -6.68 | ckzao, diozera, fREQ, keiz, mxa |
|           14 |      677 | 2024-07-12 | paiN Academy   | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.47 | ckzao, diozera, fREQ, keiz, mxa |
|           13 |      749 | 2024-07-08 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -5.86 | ckzao, diozera, fREQ, keiz, mxa |
|           12 |     1191 | 2024-06-07 | RED Canids     | L   | 0.839      | -            | -                | -                | -         |    -2.31 | ckzao, diozera, fREQ, keiz, mxa |
|           11 |     1394 | 2024-06-03 | Galorys        | W   | 0.813      | 0.371        | 0.030 (0.009)    | 0.553 (0.166)    | 0 (0.000) |    17.15 | ckzao, diozera, fREQ, keiz, mxa |
|           10 |     1467 | 2024-05-31 | Bounty Hunters | W   | 0.794      | 0.371        | 0.022 (0.006)    | 0.471 (0.139)    | 0 (0.000) |    17.07 | ckzao, diozera, fREQ, keiz, mxa |
|            9 |     1509 | 2024-05-30 | inSanitY       | L   | 0.785      | -            | -                | -                | -         |    -5.85 | ckzao, diozera, fREQ, keiz, mxa |
|            8 |     1544 | 2024-05-28 | FURIA Academy  | W   | 0.774      | 0.371        | 0.000 (0.000)    | 0.103 (0.030)    | 0 (0.000) |     5.91 | ckzao, diozera, fREQ, keiz, mxa |
|            7 |     2018 | 2024-05-13 | Case           | L   | 0.673      | -            | -                | -                | -         |    -6.56 | bsd, ckzao, diozera, fREQ, mxa  |
|            6 |     2040 | 2024-05-12 | ODDIK          | L   | 0.666      | -            | -                | -                | -         |    -4.62 | bsd, ckzao, diozera, fREQ, mxa  |
|            5 |     2115 | 2024-05-09 | RED Canids     | L   | 0.647      | -            | -                | -                | -         |    -2.37 | bsd, ckzao, diozera, fREQ, mxa  |
|            4 |     2144 | 2024-05-08 | Yawara         | W   | 0.638      | 0.435        | 0.000 (0.000)    | 0.049 (0.013)    | 0 (0.000) |     4.37 | bsd, ckzao, diozera, fREQ, mxa  |
|            3 |     2179 | 2024-05-06 | RED Canids     | L   | 0.625      | -            | -                | -                | -         |    -2.28 | bsd, ckzao, diozera, fREQ, mxa  |
|            2 |     3440 | 2024-03-13 | Fluxo          | L   | 0.267      | -            | -                | -                | -         |    -1.31 | bsd, ckzao, diozera, mxa, roz   |
|            1 |     4112 | 2024-02-14 | Fluxo          | L   | 0.081      | -            | -                | -                | -         |    -0.42 | bsd, ckzao, diozera, mxa, roz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($750.00)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
