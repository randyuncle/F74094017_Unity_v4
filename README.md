# Viking run

## Compile Environment 
* Unity 2020.3.23f1(LTE)
* Microsoft Visual Studio 2017 
	
## How to play this game
1. Keyboard events :
	* Press 'A': rotate left 90 degrees
	* Press 'D': rotate right 90 degrees
	* Press 'Space': jump
	p.s. the character you control is always walking forward, so you don't need to press anything to move forward.
2. Start the game :
	* Press "start" button on the initial menu to enter the game.
3. Ways to trigger game over :
	* When you fall out of the path, you are dead.
	* When you're caught from the enemy, which is determined as a ghost, you are dead.
	After you died, press "return menu" button to return menu.
4. Exit the game :
	* Press "exit" button to exit this game.
		
## About my game

This is a game which is a kind of infinite run games.

Do your best to escape from the ghost, but beware of the traps that are been set on the path !

Traps on the path includes holes and walls, so jump overthemt to prevent you from falling in the trap made from the ghost.

Once you died, the system will show you the scores you get in this turn, including serviving time and the coins you get.

Enjoy~

## Feedback

對於本次的 Unity 程式遊戲實作帶給我許多新奇的體驗。以前對於 Unity 的接觸僅限於看其他人撰寫它，或給中小學生上的那種超簡單暑期課程（例如說改一行 Unity 程式碼之類的）。而現在真正接觸到它後，我覺得他非常的直覺，不用還要在那邊手刻一些難寫的功能，特別是 Animation、如何偵測物件並移動等都已經寫在函式了，只要呼叫就可以使用。也難怪世上很多遊戲都會選擇用 Unity 製作，他實在是整合得太好了。

而對於本次課程的內容，講師講得著實不錯。不過因為我的筆電無法再負荷這麼多 Compiler，所以選擇遠距上課，用放在住處的桌機來運行它，不然在現場的體驗應該是很不錯的。

最後，關於這次的作業，我覺得有些地方沒有寫得很好。例如說敵人追蹤那邊，我本來放的 NavMesh 型的 AI 物件都沒有運行成功，所以到最後只能設定敵人是一個幽靈要來追殺玩家，不然可以讓敵人直接跑在道路上。還有我的玩家死掉的畫面實在是醜到炸。

在最後，感謝本次課程的助教和講師，讓我學到許多。
