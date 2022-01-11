# LiuWei-
Java课程设计-五子棋本地多人客户端对战

## 实现效果
 
### 登录页面
用户正常输入用户名，选择头像后进入游戏大厅页面。

![image](https://user-images.githubusercontent.com/74586515/148904788-a988f0df-8573-430e-a173-6d88f6c44986.png)

### 游戏大厅
用户进入游戏大厅后，左上角将展示自己的个人信息，左下角会有自己或者其他用户的登录信息。用户坐下后，其他用户可显示自己的坐下的信息。若更换位置，原来座位信息将被删除。已经有人坐下的位置不可被点击。右上角的自动落座按钮，能让用户一键落座，增加可玩性。
 
 ![image](https://user-images.githubusercontent.com/74586515/148905069-38c40ec5-cf2d-4487-81e3-d8f91b4b78f1.png)

 
### 游戏大厅页面
消息私聊功能
用户在左下角选择私聊人，填写消息后点击发送，另一方会收到相应信息，而其他人不会收到该信息。
   
 ![image](https://user-images.githubusercontent.com/74586515/148905152-bcee62bb-e530-490e-8e24-26416f319585.png)
![image](https://user-images.githubusercontent.com/74586515/148905167-44b4c55e-d36b-4d70-9e3b-d25650a02add.png)


### 五子棋页面
用户进入五子棋页面后可以展示五子棋对战页面的信息。当第二个用户进入，双方准备后游戏开始。同时准备按钮不可点击。

 ![image](https://user-images.githubusercontent.com/74586515/148905206-dea8ddd7-7a33-46cb-8ec5-197850ffc294.png)


（1） 悔棋
用户点击悔棋按钮后，对方会弹出是否同意悔棋的提示框。同意悔棋后就双方能看到悔棋操作。
 
 ![image](https://user-images.githubusercontent.com/74586515/148905236-4ca4a3b9-0dba-4261-a89f-99af8ecb1158.png)

  
（2）认输
一端用户点击认输按钮后，询问对手是否可以认输。
 
![image](https://user-images.githubusercontent.com/74586515/148905280-99e710d0-6f0b-4c37-aca8-aa225bbe9067.png)


（3）游戏结束 
游戏结束后双方都可以看到输赢的提示框。
   
   ![image](https://user-images.githubusercontent.com/74586515/148905292-1b12d3eb-5b05-4adc-a8b6-bb68c84fb1ad.png)
![image](https://user-images.githubusercontent.com/74586515/148905303-6a89f37e-145f-4b0a-b31d-a17652c8293a.png)


（4）复盘
游戏结束之后，点击复盘按钮后，文字变成“下一步”。点击可以回看整个下棋过程。复盘结束之后，页面弹出消息框提示用户复盘完成。
 
![image](https://user-images.githubusercontent.com/74586515/148905330-366687e1-2d3d-4dca-bc00-06a817ccdfde.png)


（6）音效
为了提升用户游戏体验，系统增加了音效功能。游戏开始之后，背景音效随之响起。同时，当用户放置棋子时，会根据棋子的不同，发出不同的音效。
 ![image](https://user-images.githubusercontent.com/74586515/148905373-a6d86f09-3f2b-477b-afd9-976e9cdc608d.png)


（7）鼠标重绘
  在五子棋对战时，用户鼠标放置在棋盘上，会在鼠标周围展示一个图标，提示用户点击时放置棋子的位置。
  
![image](https://user-images.githubusercontent.com/74586515/148905401-52086ffe-e79d-4503-8eb4-f2ff8eebd34e.png)


## 待完善
1. 观战功能未写完
2. 棋局绘制偏差的问题
3. 音乐停止的问题
