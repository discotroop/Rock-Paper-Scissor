A basic version of the game Rock/Paper/Scissors that allows the user to play against a "random" computer counterpart.

This is an exercise for the Odin Project.

To Do:

1. Write "game" function
    It should call computerPlay every round
        It should pass computerPlay into the game() function.
    It should keep score.
        It should ++ player score when play wins round
        It should ++ pc score when pc wins
        It should ++ no one if no one wins
        It should console.log score(s)
    It should end after round 5
        It should end recursion when countDown === 0
        It should ++ countUp every time game is called
        It should return count Up to the user.
        It should console.log countUp

    It should be able to determine, win, lost, tied (at end of round 5)
        If player score > pc - player win 
        If player score < pc - pc win!
        If tie - tie!
        It should console.log(final score.)



// Notes to improve

1. Put in buttons instead of text
2. Rework switch statements with variables for win/lose/tie
3. Rework result answer with `` quotes to customize returns