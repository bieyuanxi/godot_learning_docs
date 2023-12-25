# 节点和场景
> In Overview of Godot's key concepts, we saw that a Godot game is a tree of scenes and that each scene is a tree of nodes. In this lesson, we explain a bit more about them. You will also create your first scene.

> 在总览Godot的核心概念时，我们已经看到Godot游戏就是一个场景树，并且每一个场景都是一个节点树。在这节课，我们会更详细地介绍他们。你也会创建你的第一个场景。

## 节点
**节点是你的游戏的基本的构建块**。他们就像菜谱中的配料成分。有很多种节点类型，可以展示图像、播放声音、表示相机，远不止如此。

![image](https://github.com/bieyuanxi/godot_learning_docs/assets/103763399/920e34e6-337b-4aeb-9181-730446d663f1)

所有的节点都有下列的特性：
* 一个名字
* 可编辑的属性
* 接受回调函数并每帧更新
* 可以用新的属性和函数拓展他们
* 可以把节点作为子节点添加到其他节点下

> The last characteristic is important. Together, nodes form a tree, which is a powerful feature to organize projects. Since different nodes have different functions, combining them produces more complex behavior. As we saw before, you can build a playable character the camera follows using a CharacterBody2D node, a Sprite2D node, a Camera2D node, and a CollisionShape2D node.

> 最后一个特性非常重要。**所有节点一起形成了一棵树**，这是组织项目的一个强大的特性。因为不同的节点有不同的功能(函数?)，将他们组合在一起能产生更复杂的行为。正如我们之前看到的那样，你可以构建一个相机跟随的可游玩的角色，并使用了一个CharacterBody2D节点，一个Sprite2D节点，一个Camera2D节点以及一个CollisionShape2D节点。
![image](https://github.com/bieyuanxi/godot_learning_docs/assets/103763399/c7ffe270-62bb-4f63-8072-ff25aaa3188f)


## 场景
> When you organize nodes in a tree, like our character, we call this construct a scene. Once saved, scenes work like new node types in the editor, where you can add them as a child of an existing node. In that case, the instance of the scene appears as a single node with its internals hidden.

> 当你在一棵树中组织节点时，就如我们之前提到的角色一样，我们称这种构成是一个场景。一旦保存之后，场景在编辑器中就像新的节点类型一样工作，并且可以把场景作为子节点插入到已存在的节点。在这种情况下，这个场景的实例作为单一的节点出现，而它的内部构造是不可见的。

> Scenes allow you to structure your game's code however you want. You can compose nodes to create custom and complex node types, like a game character that runs and jumps, a life bar, a chest with which you can interact, and more.

> 场景允许你去结构化你自己的游戏代码，不管你怎么想。你可以**组合节点**以创建自定义的、复杂的节点类型，比如创建一个游戏角色，可以奔跑、跳跃，有一个生命条，或者有一个可以交互的盒子(chest?)等。

![image](https://github.com/bieyuanxi/godot_learning_docs/assets/103763399/5f9c351a-d55f-4220-b6b6-a918bc0dcd86)







