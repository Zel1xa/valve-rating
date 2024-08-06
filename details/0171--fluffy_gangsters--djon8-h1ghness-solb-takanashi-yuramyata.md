### Roster Details<br />
Team Name: FLuffy Gangsters<br />
Roster: Djon8, h1ghnesS, SoLb, takanashi, yuramyata<br />
Global Rank: [171](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [109]( ../standings_europe.md)<br />
<br />
Final Rank Value:  664.8<br />
<br />
Final Rank Value (664.8) = Starting Rank Value (567.9) + Head To Head Adjustments (97.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.284[<sup>2</sup>](#table1)
- Opponent Network: 0.044[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.082<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 567.9
- 400 + ( ( 0.082 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 567.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      499 | 2024-07-22 | 9INE              | L   | 1.000      | -            | -                | -                | -         |    -5.13 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|           13 |      514 | 2024-07-21 | Grannys Knockers  | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.128 (0.018)    | 0 (0.000) |    20.65 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|           12 |      549 | 2024-07-20 | GenOne            | L   | 1.000      | -            | -                | -                | -         |   -21.51 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|           11 |      591 | 2024-07-19 | ADEPTS            | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.026 (0.004)    | 0 (0.000) |    14.57 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|           10 |      857 | 2024-07-12 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -1.44 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            9 |      939 | 2024-07-08 | TSM               | W   | 1.000      | 0.358        | 0.040 (0.014)    | 0.431 (0.154)    | 0 (0.000) |    27.58 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            8 |      941 | 2024-07-08 | Insilio           | W   | 1.000      | 0.358        | 0.023 (0.008)    | 0.552 (0.198)    | 0 (0.000) |    27.84 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            7 |     1027 | 2024-06-16 | WOPA              | L   | 0.864      | -            | -                | -                | -         |   -12.87 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            6 |     1061 | 2024-06-15 | TÓR               | W   | 0.857      | 0.143        | 0.024 (0.003)    | 0.114 (0.014)    | 0 (0.000) |    22.57 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            5 |     1101 | 2024-06-14 | CPH Wolves        | L   | 0.851      | -            | -                | -                | -         |    -6.47 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            4 |     1147 | 2024-06-13 | TÓR               | W   | 0.842      | 0.143        | 0.024 (0.003)    | 0.114 (0.014)    | 0 (0.000) |    22.86 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            3 |     1572 | 2024-06-03 | Aurora Young Blud | L   | 0.778      | -            | -                | -                | -         |    -4.27 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            2 |     1615 | 2024-06-01 | Portugal          | W   | 0.765      | 0.372        | 0.003 (0.001)    | 0.118 (0.034)    | 0 (0.000) |    15.39 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            1 |     1706 | 2024-05-29 | Enterprise        | L   | 0.745      | -            | -                | -                | -         |    -2.83 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
