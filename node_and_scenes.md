# 节点和场景
> In Overview of Godot's key concepts, we saw that a Godot game is a tree of scenes and that each scene is a tree of nodes. In this lesson, we explain a bit more about them. You will also create your first scene.

> 在总览Godot的核心概念时，我们已经看到Godot游戏就是一个场景树，并且每一个场景都是一个节点树。在这节课，我们会更详细地介绍他们。你也会创建你的第一个场景。

## 节点
**节点是你的游戏的基本的构建块**。他们就像菜谱中的配料成分。有很多种节点类型，可以展示图像、播放声音、表示相机，远不止如此。

所有的节点都有下列的特性：
* 一个名字
* 可编辑的属性
* 接受回调函数并每帧更新
* 可以用新的属性和函数拓展他们
* 可以把节点作为子节点添加到其他节点下

> The last characteristic is important. Together, nodes form a tree, which is a powerful feature to organize projects. Since different nodes have different functions, combining them produces more complex behavior. As we saw before, you can build a playable character the camera follows using a CharacterBody2D node, a Sprite2D node, a Camera2D node, and a CollisionShape2D node.

> 最后一个特性非常重要。**所有节点一起形成了一棵树**，这是组织项目的一个强大的特性。因为不同的节点有不同的功能(函数?)，将他们组合在一起能产生更复杂的行为。正如我们之前看到的那样，你可以构建一个相机跟随的可游玩的角色，并使用了一个CharacterBody2D节点，一个Sprite2D节点，一个Camera2D节点以及一个CollisionShape2D节点。











