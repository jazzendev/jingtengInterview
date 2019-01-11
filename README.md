# 作业要求
## 碰撞检测
1. 扳手碰撞桌面时，可以准确检测，并且会“卡”在碰撞处    
![Sample 1](/SampleImages/Sample1.gif)
2. 扳手卡住时，手部依然可以移动，可以通过键盘或手柄按键来把扳手“召回”到手的位置。
3. 分别用红色和蓝色的虚拟扳手来展示当前位置下，是否可以“召回”。红色表示依然会碰撞，不可召回。蓝色表示可以召回。    
![Sample 2](/SampleImages/Sample2.gif)
4. 扳手空心位置可以穿过螺丝，扳手边缘碰到螺丝依然会检测碰撞。    
![Sample 3](/SampleImages/Sample3.gif)
5. 扳手空心位置移动到螺帽位置时，可以用扳手去扭转螺帽，顺时针旋紧，逆时针旋松。（提示，不用完全相同位置，可以在接近到一定距离时，将扳手吸附至螺帽上。    
![Sample 3](/SampleImages/Sample4.gif)

## 资源说明
1. 需要用到的模型都在Resources文件夹中
2. hand.fbx是人手模型，扳手和底座模型都在spanner.fbx中
3. spanner.jpg是底座以及扳手模型的贴图
4. Wireframe_Transparent是虚拟手柄需要用到的材质文件

## 其它要求
1. 在VR头显中展示为最佳
2. 面试时需要携带制作完成的unity项目文件、编译后的程序包
