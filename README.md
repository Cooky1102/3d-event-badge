## [使用 React Three Fiber 构建交互式 3D 活动徽章](https://vercel.com/blog/building-an-interactive-3d-event-badge-with-react-three-fiber)

React Three Fiber生态，帮助开发者在React应用中使用Three.js进行3D图形渲染和交互。

### 核心

[react-three-fiber](https://github.com/pmndrs/react-three-fiber)

@react-three/fiber 是React Three Fiber的核心库，它提供了一种使用React的方式来编写Three.js场景。通过@react-three/fiber，开发者可以使用React的组件模型来创建和管理Three.js的场景对象、光源、摄像机、渲染器等，而不需要直接操作Three.js的API。这使得开发者能够更自然地在React应用中集成3D图形，并且可以利用React的生命周期和状态管理来控制3D场景的行为。

### 物理

[@react-three/rapier](https://pmndrs.github.io/react-three-rapier/index.html)

@react-three/rapier是一个用于@react-three/fiber的物理引擎库，它集成了Rapier物理引擎，使得开发者可以在React Three Fiber的场景中添加物理交互和效果。Rapier是一个高性能的、用于WebGL的物理引擎，它支持碰撞检测、刚体动力学、软体模拟等多种物理效果。通过@react-three/rapier，开发者可以轻松地在3D场景中添加物体的物理行为，如重力、碰撞、刚体动力学等。

### 工具

[@react-three/drei](https://github.com/pmndrs/drei#readme)

@react-three/drei是一个扩展库，它提供了一系列的React组件和工具，用于简化@react-three/fiber的使用。这些组件和工具包括预设的场景、灯光、摄像机设置、动画、粒子系统等，可以帮助开发者快速构建和美化3D场景。@react-three/drei旨在提供一些常见的3D场景构建和美化的最佳实践，使得开发者可以更专注于创意和功能的实现，而不是底层的3D渲染细节。
