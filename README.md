# live-plus

成人直播合集（TVBox 直播格式），共 126 条：
- INT-XXX 59 条（社区成人分类频道）
- INT-Brands 60 条（Playboy/Penthouse/Hustler/Dorcel/Brazzers 等名牌线，面板转流，寿命不稳）
- JP-Adult 2 条（乐天 TV）
- TW-Adult 5 条（松视 1/2/3、潘朵啦、彩虹，面板转流）

## TVBox 导入
直播地址栏粘贴（任选其一）：
- https://cdn.jsdelivr.net/gh/evenbsies/live-plus@main/adult_all.txt
- https://raw.githubusercontent.com/evenbsies/live-plus/main/adult_all.txt

或在配置 JSON 的 lives 里加：
```json
{"name":"成人直播","type":0,"url":"https://cdn.jsdelivr.net/gh/evenbsies/live-plus@main/adult_all.txt"}
```

静态清单，不自动更新；失效后让 Muse 重新测活刷新。
