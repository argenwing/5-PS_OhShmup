 作品名　　：OhShmup (shoot'em up)
 Work Name
 作成期間　：1day (exclude learning time before start project)
 Time Frame      （作成前の学ぶ時間を除く）

Used Engine
 - Unity 2021.2.8f1

Used Development Environment
 - Microsoft Visual Studio Community 2019 Version 16.11.9


-----------------------------------------------------------------------------------------------------
 The reason I created this program.
 プログラムを作成した理由。
-----------------------------------------------------------------------------------------------------
 This is an assignment in Coursera. For training ObjectPool and Design pattern.

-----------------------------------------------------------------------------------------------------
 The important thing while creating this project
 プログラムを作成する上で注意した事
-----------------------------------------------------------------------------------------------------
 - How to optimize the game(Not use Destroy(gameObject)).
 - Improve performance and memory usage by reusing objects from a pool 
instead of allocating and freeing them individually.
 - What happens when increase capacity or size of the Lists.

 - ゲームを最適化する方法 (Destroy(gameObject)を使用しません)。
 - オブジェクトを個別にアロケートして解放するのではなく、プールからオブジェクトを
再利用することで、パフォーマンスとメモリ使用量を改善します。
 - リストの容量またはサイズを増やすとどのようになります。

-----------------------------------------------------------------------------------------------------
 What do I find difficult
 プログラムを作成する上で大変だった所
-----------------------------------------------------------------------------------------------------
 Using SetActive function of GameObject. 
When not use objects(in the pools) set to false. 
When use objects(remove from pools) set to true.

GameObjectのSetActive関数を使用します。
（プール内の）オブジェクトを使用しない場合、falseに設定します。 
（プールから削除）を使用する場合、trueに設定します。

-----------------------------------------------------------------------------------------------------
 The particular part of this project I concentrated on
 力をいれて作った部分で、「プログラム上」で特に注意した所
-----------------------------------------------------------------------------------------------------
 ObjectPool class, How to manage ObjectPool properly

-----------------------------------------------------------------------------------------------------
**Part of code used as starting point or didn't write on my own. And reference
**プロジェクトの出発点か、自分で作っていなかったコード部分と参考
-----------------------------------------------------------------------------------------------------
**Warning** Executable file has NO exit button
 StartingPoint_OhShmup is where I start this project.
These files wrote by Dr.Tim Chamillard at UCCS on Coursera.

Reference:
Game Programming Patterns by Robert Nystrom
Design Patterns: Elements of Reusable Object-Oriented Software
by Gamma Erich, Helm Richard, Johnson Ralph, Vlissides John

