# 👌🏻权限

* 玩家权限

  * /ia
    * `ia.user.ia`
  * /iarecipe
    * `ia.user.iarecipe`
  * /iatexture \(强制将材质包加载给自己\)
    * `ia.user.iatexture`
  * /iatexture all \(强制将材质包加载给所有人\)
    * `ia.user.iatexture.all`
  * 合成
    * `ia.user.craft.PERMISSION` \(如果想给予所有的合成权限，则可以给予权限 ia.user.craft.\*\)
    * 如果想查看更多关于物品合成权限的信息，请阅读[ 此处](../adding-content/advanced/item-properties/basic/item-permission.md)
  * 使用 /ia menu 查看物品
    * `ia.user.ia.PERMISSION` \(如果你想给予所有的 /ia 权限，则可以给予权限 ia.user.ia.\*\)
    * 如果想查看更多关于物品权限的信息，请阅读[ 此处](../adding-content/advanced/item-properties/basic/item-permission.md)
    * `ia.user.iasearchgui` 权限是在 /ia menu 界面内搜索物品的权限
    * 你还可以按物品类型给予权限，请查看 [/ia GUI ](../ia.md)页面
  * emoji \(字符图片\)
    * **/iaimage /emoji, /iaemoji, /e** 的书本GUI \(打开 emojis/字符图片的书本GUI\)
      * `ia.user.image.gui`
    * **/iaimage** **/emoji &lt;文本&gt;, /iaemoji &lt;文本&gt;, /e &lt;文本&gt;** \(显示基于某些搜索词的emoji列表\)
      * `ia.user.image.hints`
    * 在聊天中使用emoji
      * `ia.user.image.chat`
    * 在命令中使用emoji
      * `ia.user.image.command`
    * 在告示牌中使用emoji
      * `ia.user.image.sign`
    * 在书本中使用emoji
      * `ia.user.image.book`
    * 在铁砧重命名框中使用emoji
      * `ia.user.image.anvil`
    * 使用某个emoji的权限
      * `ia.user.image.use.<字符图片名字>`
      * 示例: `ia.user.image.use.heart`

  ​

* 管理员权限
  * /iaget
    * `ia.admin.iaget`
  * /iagive
    * `ia.admin.iagive`
  * /iadrop
    * `ia.admin.iadrop`
  * /iaremove
    * `ia.admin.iaremove`
  * /iatag
    * `ia.admin.iatag`
  * /iareload
    * `ia.admin.iareload`
  * /iazip
    * `ia.admin.iazip`
  * /iablock _\(查看你正在看向的方块信息\)_
    * `ia.admin.iablock`
  * /ialiquid _\(查看你正在看向的液体信息\)_
    * `ia.admin.ialiquid`
  * /iadurability
    * ia.admin.iadurability
  * Edit permission \(修改 /ia 界面中的按钮\)
    * `ia.admin.edit`
  * /iaplayerstat write _\(编辑某个玩家的自定义属性\)_
    * `ia.admin.iaplayerstat.write`
  * /iaplayerstat read _\(查看某个玩家的自定义属性\)_
    * `ia.admin.iaplayerstat.read`
  * /iainfo \(查看插件信息\)
    * `ia.admin.iainfo`
  * /iakill &lt;mob\|all&gt; \(杀死自定义怪物\)
    * `ia.admin.iakill`
  * /iasummon &lt;mob&gt; \[数量\]
    * `ia.admin.iasummon`
  * /iaexport &lt;命名空间&gt;
    * `ia.admin.iaexport`
  * /iaspawntree &lt;树&gt;
    * `ia.admin.iaspawntree`
  * /iaplaytotemanimation &lt;图腾&gt; &lt;玩家&gt;
    * `ia.admin.iatotemanimation`
  * /iaplaysound &lt;声音&gt; &lt;玩家&gt;
    * `ia.admin.iaplaysound`
  * /iacleancache
    * `ia.admin.iacleancache`
* 其他权限:
  * 绕过如果没有装特定材质，会被踢出服务器的限制
    * `ia.resourcepack.bypasskick`
  * 绕过玩家放置的方块不会掉落物品的限制
    * `ia.admin.bypassblockplaceloot`

