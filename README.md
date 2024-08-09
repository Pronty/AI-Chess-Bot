# AI-Chess-Bot
AI-Chess-Bot
Overview
AI-Chess-Bot is a Python-based chess engine designed to offer an engaging and challenging chess experience. Using the minimax algorithm with alpha-beta pruning, the AI evaluates board positions to find the best possible move, making it a competitive opponent for both beginners and advanced players.

Key Features
Minimax Algorithm with Alpha-Beta Pruning: The AI searches possible moves efficiently, aiming to maximize its advantage while minimizing the opponent’s options.
Board Evaluation: The engine evaluates positions based on material value, potential checkmate opportunities, and strategic heuristics to make informed decisions.
Adjustable Difficulty: Set the AI’s search depth to control the difficulty, allowing for a range of challenges from quick games to deep strategic play.
User-Friendly Interaction: Play by entering moves in standard chess notation, with the ability to undo the last move for added flexibility.
Automatic Game Reset: After each game, the board resets, making it easy to start a new match.
How It Works
Minimax Algorithm
The AI employs the minimax algorithm, evaluating potential moves and their outcomes. Alpha-beta pruning optimizes this process by cutting off moves that won't affect the final decision, improving efficiency.

Board Evaluation
The AI’s evaluation function scores board positions based on:

Material Value: Piece values are based on Hans Berliner's system.
Checkmate Opportunities: The AI checks for possible checkmates, heavily influencing the score.
Opening Strategy: In the early game, moves that develop pieces and control the center are favored.
Random Factor: A small random element is included to make the AI’s play less predictable.
User Interaction
Move Input: Enter moves in standard chess notation (e.g., e2e4).
Undo Feature: Type undo to retract the last two moves.
Continuous Play: After a game ends, the board resets automatically, encouraging new games.
Customization
Search Depth: Adjust the AI's search depth for different difficulty levels.
Evaluation Function: Advanced users can tweak the evaluation parameters to change the AI’s playstyle.
