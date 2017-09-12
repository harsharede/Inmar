# Inmar

Exercise 1: chessercise.py

      A list of all the potential board positions the given piece could advance to, with one move, from the given position, with the assumption there are no other pieces on the board.
      
  Test Cases:
  
       python chessercise.py -piece QUEEN -position d2 
       python chessercise.py -piece QUEEN -position a1 
       python chessercise.py -piece QUEEN -position a7 
       python chessercise.py -piece QUEEN -position g8   
       python chessercise.py -piece QUEEN -position g3   
       python chessercise.py -piece QUEEN -position e5  

       python chessercise.py -piece ROOK -position d2 
       python chessercise.py -piece ROOK -position a1 
       python chessercise.py -piece ROOK -position a7 
       python chessercise.py -piece ROOK -position g8   
       python chessercise.py -piece ROOK -position g3   
       python chessercise.py -piece ROOK -position e5   

       python chessercise.py -piece KNIGHT -position d2 
       python chessercise.py -piece KNIGHT -position a1 
       python chessercise.py -piece KNIGHT -position a7 
       python chessercise.py -piece KNIGHT -position g8   
       python chessercise.py -piece KNIGHT -position g3   
       python chessercise.py -piece KNIGHT -position e5   


Exercise 2: LongPath.py

      Implement a “Target” mode with --target parameter. Calculate and output the minimum set of moves which the given piece Type could take to the most distant
      
   Test Cases:
    
       python LongPath.py -piece QUEEN -position d2 --target a1 e5 g5 h8 b6 f3 d3 h3
       python LongPath.py -piece QUEEN -position a1 --target a1 e5 g5 h8 b6 f3 d3 h3
       python LongPath.py -piece QUEEN -position a7 --target a1 e5 g5 h8 b6 f3 d3 h3
       python LongPath.py -piece QUEEN -position g8 --target a1 e5 g5 h8 b6 f3 d3 h3  
       python LongPath.py -piece QUEEN -position g3 --target a1 e5 g5 h8 b6 f3 d3 h3  
       python LongPath.py -piece QUEEN -position e5 --target a1 e5 g5 h8 b6 f3 d3 h3 

       python LongPath.py -piece ROOK -position d2 --target a1 e5 g5 h8 b6 f3 d3 h3
       python LongPath.py -piece ROOK -position a1 --target a1 e5 g5 h8 b6 f3 d3 h3
       python LongPath.py -piece ROOK -position a7 --target a1 e5 g5 h8 b6 f3 d3 h3
       python LongPath.py -piece ROOK -position g8 --target a1 e5 g5 h8 b6 f3 d3 h3  
       python LongPath.py -piece ROOK -position g3 --target a1 e5 g5 h8 b6 f3 d3 h3  
       python LongPath.py -piece ROOK -position e5 --target a1 e5 g5 h8 b6 f3 d3 h3  

       python LongPath.py -piece KNIGHT -position d2 --target a1 e5 g5 h8 b6 f3 d3 h3
       python LongPath.py -piece KNIGHT -position a1 --target a1 e5 g5 h8 b6 f3 d3 h3
       python LongPath.py -piece KNIGHT -position a7 --target a1 e5 g5 h8 b6 f3 d3 h3
       python LongPath.py -piece KNIGHT -position g8 --target a1 e5 g5 h8 b6 f3 d3 h3  
       python LongPath.py -piece KNIGHT -position g3 --target a1 e5 g5 h8 b6 f3 d3 h3  
       python LongPath.py -piece KNIGHT -position e5 --target a1 e5 g5 h8 b6 f3 d3 h3
       
 Exercise 2: Kill_IT.py
      Calculate and output the minimum set of moves which the given pieceType could take to captureall opposing pieces.
      
    Test Cases:
    
      python Kill_IT.py -piece QUEEN -position d2 --target a1 e5 g5 h8 b6 f3 d3 h3

