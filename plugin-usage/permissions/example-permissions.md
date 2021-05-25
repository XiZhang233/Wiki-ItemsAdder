# ↪️基础权限

## 基础设定:

* `ia.user.ia` \(使用 /ia menu 命令打开菜单的权限\)
* `ia.user.ia.*` \(在 /ia menu 命令打开的菜单里显示所有物品的权限\)
* `ia.user.iarecipe` \(使用 /iarecipe 命令的权限\)
* `ia.user.craft.*` \(合成所有的物品的权限\)
* `ia.menu.*` \(在 /ia menu 命令打开的菜单里显示所有物品类型的权限\)
* `ia.user.image.gui` \(使用 /e 命令查看emoji手册的权限\)
* `ia.user.image.hints` \(在使用 /e 命令来使用emoji表情时可以使用TAB补全的权限\)
* `ia.user.image.chat` \(在聊天中使用类似 :smile: 等emoji表情的权限\)
* `ia.user.image.command` \(在命令中使用类似 :smile: 等emoji表情的权限\)
* `ia.user.image.sign` \(在告示牌中使用类似 :smile: 等emoji表情的权限\)
* `ia.user.image.book` \(在书本中使用类似 :smile: 等emoji表情的权限\)
* `ia.user.image.use.*` \(允许使用所有的emoji表情的权限\)

## 我该从哪里获得物品类型权限?

{% hint style="info" %}
### ItemsAdder 的默认物品类型

从这个文件中，你可以看到所有物品类型的权限: `plugins\ItemsAdder\data\items_packs\various_configs\ia_gui_default_categories.yml`

如果你想给予玩家查看所有默认物品类型的权限，则给予 `ia.menu.*` 权限即可。
{% endhint %}

{% hint style="info" %}
### 拓展类型

如果安装了一些 [拓展包 ](https://addons.plugin.ga/itemsadder/)，则你需要在 `ItemsAdder\data\items_packs\ADDON` 文件夹中找到 `categories.yml` 文件 。 大多数情况下，拓展包作者会将拓展的物品类型放在这个文件里，这样你就可以找到对应的 **权限**。
{% endhint %}

{% hint style="info" %}
### 创造一个物品类型

请阅读以下页面获取详情：

{% page-ref page="../ia.md" %}
{% endhint %}

