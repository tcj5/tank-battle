# 🎮 坦克大战 (Tank Battle)

经典坦克大战游戏的 HTML5 Canvas 版本，使用纯 JavaScript 实现。

![Game Preview](https://img.shields.io/badge/Game-Tank%20Battle-yellow?style=for-the-badge)

## 🕹️ 游戏特性

- 🎯 **经典玩法** - 还原 FC 坦克大战的核心玩法
- 🗺️ **3个关卡** - 不同地图布局，难度递增
- 🎵 **音效系统** - 使用 Web Audio API 实现射击和爆炸音效
- 💥 **粒子特效** - 爆炸和破坏效果
- 🛡️ **无敌保护** - 重生后短暂无敌闪烁
- 🎨 **复古像素风** - 经典游戏视觉风格

## 🎮 操作说明

| 按键 | 功能 |
|------|------|
| W / ↑ | 向上移动 |
| S / ↓ | 向下移动 |
| A / ← | 向左移动 |
| D / → | 向右移动 |
| 空格 / J | 射击 |
| P | 暂停/继续 |
| Enter | 开始游戏 |

## 🗺️ 地图元素

- 🧱 **砖墙** - 可被子弹摧毁
- 🔩 **钢墙** - 无法摧毁（除非获得强力子弹）
- 🌊 **水域** - 坦克无法通过
- 🌲 **树林** - 可穿越，遮挡视野
- 🏠 **基地** - 必须保护！被摧毁则游戏结束

## 🚀 如何运行

### 方法一：直接打开
直接在浏览器中打开 `index.html` 文件即可开始游戏。

### 方法二：本地服务器
```bash
# 使用 Python
python -m http.server 8000

# 使用 Node.js
npx http-server -p 8000
```

然后访问 `http://localhost:8000`

## 🎯 游戏规则

1. 消灭所有敌方坦克以通过关卡
2. 保护基地（鹰标志）不被摧毁
3. 玩家有 3 条生命
4. 被击中后会重生并获得短暂无敌
5. 每消灭一个敌人获得 100 分
6. 通关奖励 1000 分

## 🛠️ 技术栈

- HTML5 Canvas
- JavaScript (ES6+)
- Web Audio API
- CSS3

## 📱 浏览器支持

- ✅ Chrome / Edge
- ✅ Firefox
- ✅ Safari
- ✅ Opera

## 📄 许可证

MIT License - 自由使用和修改

---

**Made with ❤️ and JavaScript**
