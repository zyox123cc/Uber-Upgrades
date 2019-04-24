# Uber-Upgrades

插件需求

TF2Items  https://builds.limetech.io/?project=tf2items

Tf2Attributes https://github.com/FlaminSarge/tf2attributes/releases

TF2ItemsInfo https://github.com/chauffer/tf2itemsinfo 

需自行將 tf2items_manager 編譯
SDKTools (sourcemod本身就包含)

cvar 

uberupgrades_version: 查看插件版本

sm_uu_moneybonuskill : 設定殺人會獲得的金錢: 默認 100

sm_uu_moneyforteam_ratio:設置隊友殺敵 自身會獲得金錢的比例(包括從升級所花費的錢) 默認 0.05


sm_uu_moneyforotherteam_ratio: 當一個玩家被殺時，與被殺團隊相比，其團隊獲得了多少 : 默認 0.5


sm_uu_startmoney: 遊戲開始時的資金 ; 默認是 600

sm_uu_timermoneygive_blueteam: 每過20秒, 藍隊會得到 [x] $

sm_uu_timermoneygive_redteam:  每過20秒, 紅隊會得到  [x] $

sm_uu_automoneyforteam_ratio 1:將在團隊之間提供資金自動平衡系統 默認 1

指令說明 以及qbuy的使用方法
https://zoyx123cc.blogspot.com/2019/04/op.html




若是無法使用請事先
編輯位於 \tf\addons\sourcemod\configs\core.cfg
把: "SlowScriptTimeout" "8"
更改為: "SlowScriptTimeout" "60"
