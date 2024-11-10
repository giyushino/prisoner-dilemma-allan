My proposed solution to @joeeliang prisoner's dilemma. The first 3 moves played is identical to tit for tat. However, by the 4th move, I collect the last 4 moves played by the enemy. If they have played 4 straight moves of "defect", my bot will "defect". If they have played 4 straight moves of "cooperate", my bot will "defect". If the opponent did not play identical moves for the last 4 turns, if the last move the enemy played was "cooperate", my bot chooses to "cooperate". Otherwise my bot will play a random move from the enemy's last 4 moves.

My bot lost to "Always Defect" 99-104, beat "Always Cooperate" 492-12, beat "Tit for Tat" 255-250, and lost to "Random" 178-258

Total scores 

Always Defect: 992
Always Cooperate: 471
Tit for Tat: 879
Random: 936
Giyusino: 1024
