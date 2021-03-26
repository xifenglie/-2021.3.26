#!name=LXK9301 iOS Tasks&Cookies Module
#!desc=iOS Tasks&Cookies 模块配置

# Task&Cookies模块配置 By LXK9301
# GitHub主页(https://gitee.com/lxk0301/jd_scripts/tree/master)
# TG讨论组 (https://t.me/JD_fruit_pet)
# TG通知频道 (https://t.me/jdfruit)
# Surge的Task&Cookies脚本模块地址: https://gitee.com/lxk0301/jd_scripts/raw/master/Surge/lxk0301_Task.sgmodule.sgmodule

[Script]
京东资产变动通知 = type=cron,cronexp=2 9 * * *,wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_bean_change.js
领京豆额外奖励 = type=cron,cronexp="10 7 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_bean_home.js
东东超市兑换奖品 = type=cron,cronexp="0 0 0 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_blueCoin.js
口袋书店 = type=cron,cronexp="1 8,12,18 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_bookshop.js
京东汽车 = type=cron,cronexp="10 7 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_car.js
京东汽车兑换 = type=cron,cronexp="0 0 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_car_exchange.js
签到领现金 = type=cron,cronexp="2 0-23/4 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_cash.js
京喜财富岛 = type=cron,cronexp="5 0,8,13,19 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_cfd.js
摇京豆 = type=cron,cronexp="5 0 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_club_lottery.js
crazyJoy任务 = type=cron,cronexp="10 7 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_crazy_joy.js
监控crazyJoy分红 = type=cron,cronexp="10 12 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_crazy_joy_bonus.js
crazyJoy挂机 = type=cron,cronexp="10 1,12 * * *",wake-system=1,timeout=20,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_crazy_joy_coin.js
天天提鹅 = type=cron,cronexp="10 * * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_daily_egg.js
京喜工厂 = type=cron,cronexp="10 * * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_dreamFactory.js
获取多账号京东Cookie = type=http-request,pattern=^https:\/\/me-api\.jd\.com\/user_new\/info\/GetJDUserInfoUnion,requires-body=1,max-size=0,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/JD_extra_cookie.js,script-update-interval=0
京东家庭号 = type=cron,cronexp="1 12,23 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_family.js
东东农场 = type=cron,cronexp="5 6-18/6 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_fruit.js
获取互助码 = type=cron,cronexp="20 13 * * 6",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_get_share_code.js
环球挑战赛 = type=cron,cronexp="0 9,12,20,21 8-31 3 *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_global.js
京东国际盲盒 = type=cron,cronexp="0 9,12,20,21 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_global_mh.js
东东工厂 = type=cron,cronexp="10 * * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_jdfactory.js
京东赚赚 = type=cron,cronexp="10 0 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_jdzz.js
京东宠汪汪 = type=cron,cronexp="15 0-23/2 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_joy.js
京东宠汪汪喂食 = type=cron,cronexp="15 0-23/1 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_joy_feedPets.js
宠汪汪强制为别人助力= type=http-request,pattern=^https:\/\/draw\.jdfcloud\.com\/\/common\/pet\/enterRoom\/h5\?invitePin=.*(&inviteSource=task_invite&shareSource=\w+&inviteTimeStamp=\d+&openId=\w+)?&reqSource=weapp|^https:\/\/draw\.jdfcloud\.com(\/mirror)?\/\/pet\/helpFriend\?friendPin,requires-body=1,max-size=0,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_joy_help.js
宠汪汪积分兑换奖品 = type=cron,cronexp="0 0-16/8 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_joy_reward.js
宠汪汪邀请助力与赛跑助力 = type=cron,cronexp="15 10 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_joy_run.js
宠汪汪助力更新Token = type=http-response,pattern=^https:\/\/draw\.jdfcloud\.com(\/mirror)?\/\/api\/user\/addUser\?code=, requires-body=1, max-size=0, script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_joy_run.js
宠汪汪助力获取Token = type=http-request,pattern=^https:\/\/draw\.jdfcloud\.com(\/mirror)?\/\/api\/user\/user\/detail\?openId=, max-size=0, script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_joy_run.js
京小兑 = type=cron,cronexp="40 8,16,20 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_jxd.js
京喜农场 = type=cron,cronexp="0 9,12,18 * * *",timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_jxnc.js
京东快递签到 = type=cron,cronexp="10 0 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_kd.js
京东直播 = type=cron,cronexp="10-20/5 12 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_live.js
超级直播间红包雨 = type=cron,cronexp="30,31 20-23/1 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_live_redrain.js
5G超级盲盒 = type=cron,cronexp="0 0,1-23/3 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_mohe.js
京东摇钱树 = type=cron,cronexp="3 0-23/2 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_moneyTree.js
京东秒秒币 = type=cron,cronexp="10 7 * * *",wake-system=1,timeout=200,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_ms.js
点点券 = type=cron,cronexp="10 0,20 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_necklace.js
女装盲盒 = type=cron,cronexp="0 8 22-31/1 3 *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_nzmh.js
东东萌宠 = type=cron,cronexp="15 6-18/6 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_pet.js
京东金融养猪猪 = type=cron,cronexp="12 * * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_pigPet.js
京东种豆得豆 = type=cron,cronexp="1 7-21/2 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_plantBean.js
京东保价 = type=cron,cronexp="0 2 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_price.js
京东全民开红包 = type=cron,cronexp=1 1 * * *,wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_redPacket.js
闪购盲盒 = type=cron,cronexp="20 8 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_sgmh.js
进店领豆 = type=cron,cronexp="10 0 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_shop.js
东东小窝 = type=cron,cronexp="16 22 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_small_home.js
天天加速 = type=cron,cronexp="8 0-23/3 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_speed.js
京东极速版 = type=cron,cronexp="0 7 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_speed_sign.js
东东超市 = type=cron,cronexp="11 * * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_superMarket.js
赚京豆 = type=cron,cronexp="10 7 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_syj.js
取关京东店铺商品 = type=cron,cronexp="55 23 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jd_unsubscribe.js
京喜签到 = type=cron,cronexp="5 0 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/jx_sign.js
小米运动 = type=cron,cronexp="15 17 * * *",wake-system=1,timeout=3600,script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/backUp/xmSports.js
小米运动获取Token = type=http-response,pattern=^https:\/\/account\.huami\.com\/v2\/client\/login, requires-body=1, max-size=0, script-path=https://gitee.com/lxk0301/jd_scripts/raw/master/backUp/xmSports.js

[MITM]
hostname = %APPEND% me-api.jd.com, draw.jdfcloud.com, jdjoy.jd.com, account.huami.com
