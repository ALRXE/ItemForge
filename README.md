# ItemForge

**物品工坊**

ItemForge 是一个可视化自定义物品制作工具。

无需编写代码，只需填写物品信息、选择功能并上传图片，即可生成可安装的 Mod 物品包。

---

本工具可与 **CharacterForge** 搭配使用。[CharacterForge 下载地址](https://github.com/ALRXE/CharacterForge)

---

## 自制 Mod

### [GoFishing!](https://github.com/ALRXE/GoFishing)

给游戏加入一套简单完整的钓鱼玩法，目前共包含 **13 个自定义物品**。

---

## 主要功能

* 自定义中文名、英文名和物品 ID
* 自动将常见图片转换为游戏可用贴图
* 自定义物品占格大小
* 一个物品可同时拥有多个标签
* 自动匹配顾客货源
* 批量保存多个物品并生成一个 DLL
* 支持食物、饮料、医疗品、工具和刀类武器
* 支持违禁品等级与窃贼赃物状态
* 支持工具拾荒加成与多个目标物品
* 支持钓鱼 / 专属产出模式
* 支持自定义加工配方
* 一键安装、更新和卸载生成的物品包  
  当生成相同 ID 的物品包时，会直接覆盖之前的物品包。

---

## 使用方法

1. 启动 `ProbablyStolenItemForge.exe`
2. 选择游戏根目录
3. 点击 **“安装 / 更新公共 Runtime”**
4. 填写物品名称、ID、说明和价格
5. 上传图片并选择占格大小
6. 根据需要添加标签和扩展功能
7. 将物品保存到列表
8. 可以继续创建其他物品
9. 一键生成并安装物品包 DLL
10. 重启游戏

---

## 分享生成的 Mod

如果想把 ItemForge 生成的 Mod 分享给其他玩家，请将以下两个文件一起提供：

```text
PSItemPack_你的物品包名称.dll
ProbablyStolenItemForgeRuntime.dll
