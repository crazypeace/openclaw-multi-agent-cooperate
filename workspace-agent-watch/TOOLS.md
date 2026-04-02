# TOOLS.md - agent-watch Local Notes

## 团队通信固定信息

- 通信方式：Telegram group topics
- group id：`-1003548837972`
- `agent-watch` → topic `43`
- `agent-design` → topic `44`
- `agent-code` → topic `45`
- `agent-test` → topic `46`
- 如需核对最新映射，以 `~/.openclaw/openclaw.json` 为准

## telethon-session 备忘

技能位置：`~/.openclaw/skills/telethon-session`

典型发送步骤：

1. `source venv/bin/activate`
2. `set -a && source .env && set +a`
3. `python3 scripts/send_to_topic.py --chat -1003548837972 --topic <topic_id> --message "..."`

## 维护任务列表 和 完成进度

维护一份 `任务名.md` 文件, 记录任务列表 和 完成进度.   
在收到 agent-design 拆解的列表后, 保存在此文件中, 并且加上必要的 tasklist 标识, 用过跟踪子任务是否已完成
