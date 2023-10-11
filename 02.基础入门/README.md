# 02. 基础入门



## 输入指令生成图片



```
/imagine prompt A group of children playing in the garden, high definition, detailed, warm light, --ar 9:5
```



示例，



```
A group of children playing in the garden, high definition, detailed, warm light, --ar 9:5
```

![img](images/chacha1154_A_group_of_children_playing_in_the_garden_high_defin_f05f9ee5-d3ac-4835-8203-7a08018f1739.png)



## U1~U4

U1~U4 可以放大相应的图片，放大后的图像分辨率会提升，默认比例下，会达到 1024x1024 的分辨率。

![image-20231011092358986](images/image-20231011092358986.png)





以 U2 为例，第2张图片被放大了。



![img](images/chacha1154_A_group_of_children_playing_in_the_garden_high_defin_f824ce48-552f-432d-b2ee-156d360f6615.png)



（功能没有了）单击 "Make Variations" 这一选项，会弹出调整图片描述关键词的提示框，修改提示词后单击 "提交" 按钮可以根据当前图片生成相似风格的其他4张图片。



## V1~V4



V1~V4 可以衍生相应的图片，生成整体风格相似的4张衍生图片，



![image-20231008173814039](images/image-20231008173814039.png)

我们以V3为例，效果如下，

![img](images/chacha1154_A_group_of_children_playing_in_the_garden_high_defin_6ccd2e1b-00d5-4e3c-ad60-673e27905efd.png)



## 重新生成图片

蓝色旋转按钮的功能是根据初始指令重新进行图片生成，得到与最初的4张图片风格不同但符合描述指令的4张新图片。

![image-20231008174417427](images/image-20231008174417427.png)



## Vary(Strong) 和 Vary(Subtle) 



Vary(Strong) 和 Vary(Subtle) 是重新绘制，

![image-20231008172550926](images/image-20231008172550926.png)



Vary(Subtle) 的效果，变化小，

![img](images/chacha1154_A_group_of_children_playing_in_the_garden_high_defin_a844090b-c607-4c9a-b178-ea2a72cd67aa.png)

Vary(Strong) 的效果，变化大，

![img](images/chacha1154_A_group_of_children_playing_in_the_garden_high_defin_cff59ff4-9ac7-4fca-9566-c82338cb8e0f.png)

## Vary(Region) 局部重绘



Vary(Region) 局部重绘，

![image-20231008172810946](images/image-20231008172810946.png)



使用 矩形工具("Rectangle Tool") 或 套索工具("Lasso Tool") 选择要重绘的区域，

![image-20231008173118558](images/image-20231008173118558.png)

示例，

![image-20231008173350318](images/image-20231008173350318.png)

示例效果，

![img](images/chacha1154_A_group_of_children_playing_in_the_garden_high_defin_8ac14ffc-a8f2-48d1-877d-0c446bf6fa7c.png)



## "Zoom Out 2x"，"Zoom Out 1.5x"，和 "Custom Zoom"



"Zoom Out 2x"，"Zoom Out 1.5x"，和 "Custom Zoom" 可以对图片进行缩放，

![image-20231008180401517](images/image-20231008180401517.png)

原始图片效果，

![img](images/chacha1154_A_group_of_children_playing_in_the_garden_high_defin_657075b6-4a46-4ec4-89f4-eaf996e78235.png)



"Zoom Out 1.5x"效果，

![img](images/chacha1154_A_group_of_children_playing_in_the_garden_high_defin_41ed2a07-fb42-42e8-a4a4-98d6b066b925.png)

"Zoom Out 2x" 效果，

![img](images/chacha1154_A_group_of_children_playing_in_the_garden_high_defin_cd485ad6-27b7-4cca-8b17-b94208a6bbf0.png)



## "Make Square"



"Make Square"，会在4个方向补绘图片，

![image-20231008180846346](images/image-20231008180846346.png)



![img](images/chacha1154_A_group_of_children_playing_in_the_garden_high_defin_98001f42-41fb-4e4a-a5f9-109b4a4248ad.png)





## "Pan Left"，"Pan Right"，"Pan Up"，"Pan Down"



镜头转向左方("Pan Left")，镜头转向右方("Pan Right")，镜头转向上方("Pan Up")，镜头转向下方("Pan Down") 会在相应的方向补绘图片，

![image-20231008180934753](images/image-20231008180934753.png)

"Pan Left" 效果，

![img](images/chacha1154_A_group_of_children_playing_in_the_garden_high_defin_70c15c7c-3b63-4791-9db1-ccdaa68ddcf7.png)

"Pan Right" 效果，

![img](images/chacha1154_A_group_of_children_playing_in_the_garden_high_defin_66005618-7252-4862-857d-982f1b8117c6.png)

"Pan Up" 效果，

![img](images/chacha1154_A_group_of_children_playing_in_the_garden_high_defin_40f48266-1051-4cdc-964f-074fa5f78496.png)

"Pan Down" 效果，

![img](images/chacha1154_A_group_of_children_playing_in_the_garden_high_defin_04caa492-44ff-4ca2-a63d-e5bb9c0c53f0.png)



## 提供参考图



您可以在 Midjourney 中添加一张或多张参考图，



双击对话指令框左侧的 "+" 加号图标，在弹出的窗口中选择想要上传的图片，并点击"打开"按钮。

按 "Enter" 键将图片发送给 Midjourney。

![image-20231008182157583](images/image-20231008182157583.png)



单击发送的图片将其放大，单击复制图像链接。

![image-20231008215940608](images/image-20231008215940608.png)



将复制的链接粘贴到 prompt 输入框中，空一个，加上描述语，即可生成我们想要的图片。

示例，

```
The little boy is standing under the tree --ar 9:5
```



![image-20231008220224524](images/image-20231008220224524.png)

![img](images/chacha1154_The_little_boy_is_standing_under_the_tree_6c271843-9061-45b0-8205-7346639fd244.png)



## 权重说明



关键词后面输入 --iw x，x 指的是数值，权重的默认值为 0.5，最大值则是 2，权重值越高，生成图像与参考图的相似度越高。



权重为 0.5 时示例效果，

```
https://s.mj.run/Vp78f2Mhgk4 clay style, light purple jacket, purple eyes, light purple hair, cute, octane rendering, high definition, details --iw 0.5
```



![img](images/chacha1154_clay_style_light_purple_jacket_purple_eyes_light_pur_fb33ccce-d057-4230-bcc7-cf5132401358.png)





权重为 1 时示例效果，

```
https://s.mj.run/Vp78f2Mhgk4 clay style, light purple jacket, purple eyes, light purple hair, cute, octane rendering, high definition, details --iw 1
```





![img](images/chacha1154_clay_style_light_purple_jacket_purple_eyes_light_pur_7d39c78f-f4e4-43d8-8b6a-edb6d603a270.png)

权重为 2 时示例效果，

```
https://s.mj.run/Vp78f2Mhgk4 clay style, light purple jacket, purple eyes, light purple hair, cute, octane rendering, high definition, details --iw 2
```



![img](images/chacha1154_clay_style_light_purple_jacket_purple_eyes_light_pur_8e80c14a-ceb7-4fe0-8c4a-37533fe9a40a.png)



## 一键换脸



添加 insightface bot 小机器人，

```
https://discord.com/api/oauth2/authorize?client_id=1090660574196674713&permisssions=274877945856&scope=bot
```



输入 `/saveid`，这一模块的功能是按名称和图像保存身份特征。随后，在 idname 中输入名称就可以上传了。



上传 ID 后，选择 `/swapid` 模式。输入刚刚设置的 ID 名称，并上传想要替换的主题照片。

按回车键，换脸成功。





![img](images/20231008_4_ins-169698411370029.jpg)

![img](images/20231008_2_ins.jpg)





## prompt 的灵感武器



OpenArt 网站上有相当全的 prompt 及 AI 作品，可以把它当作一个很大的关键词库，复制、参考其中的关键词。

[https://openart.ai/discovery](https://openart.ai/discovery)



## 设置



在对话框中输入 `/settings`，按回车键，即可进入设置界面。



![image-20231008224247720](images/image-20231008224247720.png)



风格：V1、V2、V3、V4、V5、V5.2 版本偏向于写实风，数字越大的版本，生成的图片越逼真；Niji 模式的 V4、V5 版本这属于二次元风格。

图片质量：分为低、基础、高三个等级。质量越低，渲染时间越短。

风格化：风格化越低，与 prompt 描述越接近；风格化越高，生成的图像越天马行空。

输出模式：有分公开、密码、混合、快速、慢速 5 个选项。设置输出模式，需要在图像生成之前进行。



用户也可以直接使用 `--q <0.25, 0.5, 1, or 2>` `--v 1-5` `--s 0-750` 分别代表图片质量、版本和风格化。



## 混合模式



进入 `settings`，选择开启 `Remix model`。

![image-20231008225059390](images/image-20231008225059390.png)

输入示例，`crystal ball`，

![img](images/chacha1154_crystal_ball_d057a639-ace9-4c22-ab7b-edc9fe14f554.png)

![img](images/chacha1154_crystal_ball_07329af7-5279-429d-9f18-01b9733189f4.png)

单击 V1~V4，系统会弹出一个 "Remix Prompt" 对话框。在原基础上添加 "magic" 和 `--q 2`。

![image-20231008225410724](images/image-20231008225410724.png)

从生成的图片中可以看出，以上操作在原图的基础上添加了魔法效果。

![image-20231008225459113](images/image-20231008225459113.png)

![img](images/chacha1154_magic_crystal_ball_5e3de1bb-e1ba-429a-af48-af08304d0238.png)



在原有的基础上将 "crystal ball" 修改为 "football"，如果不想原图中的 "手" 出现，可以添加一个 `--no hand`,

![image-20231008225813615](images/image-20231008225813615.png)

![img](images/chacha1154_football_83fac9cd-b641-4812-937e-cc299bb6bfbc.png)

```
football --s 50 --no hand --no backgroud
```

![img](images/chacha1154_football_minimalism_8a0bf489-80a7-4255-9d2c-7eea469e9cdf.png)

![img](images/chacha1154_football_minimalism_b972f919-cfcb-4c82-b4be-e9a0063afbbd.png)



## 以图生图



想要以图生图，可以使用 `/blend` 指令，单击上传图片按钮，最多可以添加 5 张图片。



## 以图生文



输入 `/describe` 后上传所保存的图片，按回车键发送。AI 会自动 4 个与该图片相关的 prompt。

选择图像下方任意一个序号按钮，系统会弹出 "Imagine This!" 提醒对话框，可以选择修改对话框中的描述，也可以选择直接单击 "Submit" 按钮，提交后即可生成相似的图片。