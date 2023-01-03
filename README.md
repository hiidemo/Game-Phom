# Game-Phỏm
## :dart: Báo cáo Game Phỏm
## :globe_with_meridians: ENV_state
*   [0:900] **Map của maze**: 1 là tường, 0 là đường có thể đi
*   [900:902] **player position**
*   [902:904] **start position** 
*   [904:906] **end position** 
*   [906] **Turn**
*   [907] **Turn  tối ưu**


## :bust_in_silhouette: P_state
*   [0:51] **Lá bài của bản thân**
*   [52:104]] **lá bài của người tiếp theo đánh cho mình**
*   [104:104+52]] **Lá bài rác của người tiếp theo**
*   [104+52:104+52+52]:   **lá bài rác của 2 người khác và bản thân**
*   [104+52+52:104+52+52+52]]:   **lá phỏm của bản thân**
*   [104+52x3:104+526]:   **lá phỏm của 3 người khác**
*   [416:420]:   **lví trí của bản thân**
*   [423:423+52+52+52+52]:   **lá bài trên tay  người chơi  khi hạ phỏm**



## :video_game: Action
* [0]   **action  ăn bài**
* [1]     **action không ăn bài **
* [2:54] **action đánh bài**
