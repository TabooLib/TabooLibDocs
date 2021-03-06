========
版本关系
========

.. note::

    在 2021 年 7 月我们发布了 TabooLib ``6`` 以及新的版本规范和设计。
    
这会直接导致所有基于 TabooLib ``5`` 的插件无法直接升级，但是我们依旧保持对 TabooLib ``5`` 的维护和更新，以避免任何不可逆的后果。开发者们可以继续使用 TabooLib ``5`` 版本进行开发。

那些基于 TabooLib ``5`` 开发的插件能够与基于 TabooLib ``6`` 的插件共存且不会发生任何冲突。

.. csv-table::
   :header: "版本", "简介"
   :widths: 2, 15
   
   "``4.X``", "基于 Bukkit 开发，以插件为载体运行的类库，于 2020 年停止更新，最高支持到 Minecraft ``1.12``。"
   "``5.X``", "基于 Bukkit 开发，动态加载的非插件类库。由依赖插件联网下载到服务端中，每个服务端只会同时运行一个版本的 TabooLib ``5``，最高支持到 Minecraft ``1.16.5``。"
   "``6.X``", "基于多平台开发的纯类库，随插件本体同时加载到服务端中，每个服务端允许同时存在多个不同版本的的 TabooLib ``6``，目前支持到 Minecraft ``1.8`` 到 ``最新``。"
