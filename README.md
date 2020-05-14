# 1.はじめに

このドキュメントでは、Scratch 3.0で基本的な部品を使った『猫が歩く』アニメーションの作成方法を説明します。

This document explains how to create a "cat walking" animation using basic item in Scratch 3.0.

ドキュメント作成者：高橋 悦子(NTTテクノクロス株式会社)

Document Author：Etsuko Takahashi(NTT TechnoCross Corporation)

![cat_walking_animation](figure/cat_walking_animation.gif)

# 2.準備

## 2-1.準備①：開発環境(Preparation①:Development environment)

- [Scratch公式サイト(https://scratch.mit.edu/download)](https://scratch.mit.edu/download)から、Scratch 3.0をダウンロード、インストールします。(Scratch 3.0は、Windows、macOS、chromeOS、Androidに対応。(2020/04/13時点))

   Download and install Scratch 3.0 from the [Scratch official website(https://scratch.mit.edu/download)](https://scratch.mit.edu/download).(Scratch 3.0 is compatible with Windows, macOS, chromeOS, Android. (As of 2020/04/13))

# 3.アニメーションの作り方(How to develop animation)

## 3-1.アニメーションを作る前の準備(Preparation before developing the animation)

- Scratch 3.0を起動し、背景を選択します。

　Start Scratch 3.0 and choose a backdrop.

![1_choose-backdrop](figure/1_choose-backdrop.png)

- 「Beach Rio」を選択します。（他の背景でも構いません）

 Choose the "Beach Rio".(There is no problem with other background.)

![2_choose-the-beach-rio](figure/2_choose-the-beach-rio.png)

- 背景が選択されていることを確認してください。

　Confirm backdrop is your choose item.

![3_confirm-backdrop](figure/3_confirm-backdrop.png)

- 猫の大きさを **『100』から『30』に変更** します。

　Change the cat size from "100" to "30".

![4_cat-size-changed](figure/4_cat-size-changed.png)

- 猫を左に移動します。

　Move the cat to the left.

![5_cat-to-left](figure/5_cat-to-left.png)

## 3-2.作り方(How to develop)

### 3-2-1.完成イメージ(Completed image)

![program-complete](figure/program-complete.png)

### 3-2-2.詳細(Details)

- コードの ![event-button](figure/common/event-button.png) を押してください。「動き」についてのブロックが選べるようになります。

   Press ![event-button](figure/common/event-button.png) on the code. You will be able to choose the "motion" block.

![code-motion-button](figure/common/code-motion-button.png)

- ![event-flag](figure/common/event-flag.png) のブロックを画面中央にドラッグ&ドロップします。このブロックは、「![flag-button](figure/common/flag-button.png) を押すと始まります」という意味になります。

   Drag and drop the ![event-flag](figure/common/event-flag.png) to the center of the screen. This block means "press the ![flag-button](figure/common/flag-button.png) button to start the event".

- コードの ![motion-button](figure/common/motion-button.png) を押してください。

   Press ![motion-button](figure/common/motion-button.png) on the code.

- ![6_go-to-coordinate](figure/6_go-to-coordinate.png) のブロックを画面中央にドラッグ&ドロップします。(今、猫がいる座標が数字で設定されています。)

   Drag and drop the ![6_go-to-coordinate](figure/6_go-to-coordinate.png) to the center of the screen. (Now, the coordinates where the cat is are set by numbers.)

- ブロックをくっつけてください。

   Connect the blocks.

![7_connected-blocks](figure/7_connected-blocks.png)

- コードの![costume-button](figure/common/costume-button.png) を押してください。

   Press ![costume-button](figure/common/costume-button.png) on the code.

- ブロック ![8_size-set-percent](figure/8_size-set-percent.png) の **『100』を『30』に変更** してください。

   Click ![8_size-set-percent](figure/8_size-set-percent.png) block and change "100" to "30".

- ブロックをくっつけてください。ここまでで、「旗ボタンを押すと、猫が同じ場所で30%のサイズでスタートする」設定ができました。

   Connect the blocks. Up to this point, you can set up "If you press the flag button, the cat will start at the same place with a size of 30%".

![9_connected-blocks](figure/9_connected-blocks.png)

- コードの![control-button](figure/common/control-button.png) を押してください。

   Press ![control-button](figure/common/control-button.png) on the code.

- ブロック ![10_timer](figure/10_timer.png) の **『1』を『0.5』に変更** してください。

  Click ![10_timer](figure/10_timer.png) block and change "1" to "0.5".

- ブロックを画面中央にドラッグ＆ドロップします。（**ブロックはくっつけません**）

   Drag and drop the block to the center of the screen. (Do not connect blocks.)

![11_non-connected-blocks](figure/11_non-connected-blocks.png)

- コードの ![motion-button](figure/common/motion-button.png) を押してください。

   Press ![motion-button](figure/common/motion-button.png) on the code.

- ブロック ![12_move-steps](figure/12_move-steps.png) の **『10』を『20』に変更** してください。

   click ![12_move-steps](figure/12_move-steps.png) block and change "10" to "20".

- ブロックを画面中央にドラッグ＆ドロップして、![10_time](figure/10_timer.png)にくっつけます。

   Drag and drop the block to the center of the screen and connect to ![10_time](figure/10_timer.png).

![13_connected-to-timer-blocks](figure/13_connected-to-timer-blocks.png)

- コードの![costume-button](figure/common/costume-button.png) を押してください。

   Press ![costume-button](figure/common/costume-button.png) on the code.

- ブロック ![14_next-costume](figure/14_next-costume.png) を画面中央にドラッグ＆ドロップして、ブロックにくっつけます。

   Drag and drop the ![14_next-costume](figure/14_next-costume.png) block to the center of the screen and connect to blocks.

![15_connected-to-blocks](figure/15_connected-to-blocks.png)

- ブロック ![16_change-size-by](figure/16_change-size-by.png) を画面中央にドラッグ＆ドロップして、ブロックにくっつけます。

   Drag and drop the ![16_change-size-by](figure/16_change-size-by.png) block to the center of the screen and connect to blocks.

![17_connected-to-blocks](figure/17_connected-to-blocks.png)

- コードの![control-button](figure/common/control-button.png) を押してください。

   Press ![control-button](figure/common/control-button.png) on the code.

- ブロック ![18_repeat](figure/18_repeat.png) の **『10』を『17』に変更** してください。

  Click ![18_repeat](figure/18_repeat.png) block and change "10" to "17".

- ブロックを画面中央にドラッグ＆ドロップします。（**ブロックはくっつけません**）

   Drag and drop the block to the center of the screen. (Do not connect blocks.)

![19_non-connected-blocks](figure/19_non-connected-blocks.png)

- 以下のブロックを、![18_repeat](figure/18_repeat.png) の中に入れます。

   The following blocks into ![18_repeat](figure/18_repeat.png)

![20_motion-blocks](figure/20_motion-blocks.png)

- 画面中央が以下のようになっていることを確認してください。

   Confirm that the center screen.

![21_control-blocks](figure/21_control-blocks.png)

- ブロックをくっつけてください。これでプログラムは完成です。

   Connect the blocks.The program is complete.

![22_walking-cat](figure/22_walking-cat.png)

# 4.プログラムの保存方法(How to save the program)

Scrachのファイルのメニューから『コンピューターに保存する』を選択し、実行してください。

   From the Scrach file menu, select "Save to computer" and run it.

![save](figure/save.png)

# 5. プログラムの実行・停止(How to run and stop the program)

## 5-1. プログラムを実行(Run the program)

旗のボタンを押してください。

Press the flag button.

![start-app-button](figure/start-app-button.png)

## 5-2. プログラムを停止(Stop the program)

赤いボタンを押してください。

Press the red button.

![stop-app-button](figure/stop-app-button.png)
