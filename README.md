# Diet Quest
다이어트 퀘스트는 모두에게 무료로 열려있습니다! \
다이어트 퀘스트와 함께하면, 더욱 쉽게 살을 뺄 수 있습니다. \
다이어트에서 재미를 찾아보세요! \
\
Diet Quest is open for everyone, for free! \
With Diet Quest, you can easily reduce your weight. \
You will find fun way to diet.

## User Info Architecture
사용자의 정보는 `user.json`에 다음과 같이 저장됩니다. \
User info saved like this in `user.json`. \
```
{
    "player": {
        "name": "user_name",
        "level": 10,
        "xp": 220,
        "coin": 120,
        "last_login": "2026-05-31"
    },

    "weights": {
        "current_weight": 73.3,
        "target": 65.0
    },

    "quests": {
        "walk": false,
        "snack": true
    }
}
```