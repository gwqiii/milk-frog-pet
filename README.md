# 奶蛙·惊鸿一瞥

一个适用于 ChatGPT Work 桌宠的黄色奶蛙动画宠物，包含轻轻眨眼、惊鸿一瞥、捧腹大笑和忧郁摇摆等状态。

## 文件

- `spritesheet.png`：v2 动画精灵表（1536 × 2288）
- `pet.json`：桌宠元数据

## 安装到 Windows 桌面客户端

1. 关闭 ChatGPT/Codex 桌面客户端。
2. 新建目录 `%USERPROFILE%\\.codex\\pets\\milk-frog-glimpse`。
3. 将 `spritesheet.png` 和 `pet.json` 放入这个目录。
4. 重新打开客户端，在桌宠选择器中选择“奶蛙·惊鸿一瞥”。

也可以在 PowerShell 中运行：

```powershell
$dir = Join-Path $env:USERPROFILE '.codex\\pets\\milk-frog-glimpse'
New-Item -ItemType Directory -Force $dir | Out-Null
Copy-Item .\\spritesheet.png, .\\pet.json $dir -Force
```

## ChatGPT 分享链接

如果你使用的是 ChatGPT Work 的云端宠物，可以通过分享页添加副本：

https://chatgpt.com/s/sharepet_6acfa72096a88191a8c0baa49da8ea1e

## 说明

这是 ChatGPT Work 桌宠使用的 v2 精灵表。桌面客户端的本地宠物目录和 ChatGPT 网页端宠物库是两套存储位置；安装本地文件后需要重启桌面客户端。
