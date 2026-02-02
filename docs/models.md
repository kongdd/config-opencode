## 1 授权

```bash
opencode auth list
opencode auth login
opencode auth logout
```

## 2 测试模型

```bash
# opencode models
kimi-for-coding/k2p5
kimi-for-coding/kimi-k2-thinking

minimax-cn-coding-plan/MiniMax-M2
minimax-cn-coding-plan/MiniMax-M2.1

zhipuai-coding-plan/glm-4.5
zhipuai-coding-plan/glm-4.5-air
zhipuai-coding-plan/glm-4.5-flash
zhipuai-coding-plan/glm-4.5v
zhipuai-coding-plan/glm-4.6
zhipuai-coding-plan/glm-4.6v
zhipuai-coding-plan/glm-4.6v-flash
zhipuai-coding-plan/glm-4.7

openai/gpt-5.1-codex
openai/gpt-5.1-codex-max
openai/gpt-5.1-codex-mini
openai/gpt-5.2
openai/gpt-5.2-codex
```

```powershell
opencode run "你是什么模型" --model "minimax-cn-coding-plan/MiniMax-M2"
opencode run "你是什么模型" --model "kimi-for-coding/k2p5"
opencode run "你是什么模型" --model "zai-coding-plan/glm-4.6"
# opencode run "你是什么模型" --model "zhipuai-coding-plan/glm-4.6" # error

opencode run "你是什么模型" --model "openai/gpt-5.2"
```

## 3 网页服务

```bash
opencode serve
```
