# Nano Banana Pro API 中文文档（nano-banana-pro / nanobananapro）

<p align="center">
  <img src="hero.jpg" width="820" alt="Nano Banana Pro sample">
</p>

> 按量计费，$1 起充，OpenAI 兼容接口。 **default $0.03; 4K $0.04**

**[模型页](https://go.apimart.ai/k-43b745) · [实时价格](https://go.apimart.ai/k-76056e) · [获取 API Key](https://go.apimart.ai/k-3559e7)**

## 价格（快照 2026-09-24）

| 档位 | 单价 |
| --- | --- |
| `default` | $0.03 |
| `4K` | $0.04 |

按量计费、**$1 起充**，无订阅、无免费额度；每次任务响应返回 `cost` / `credits_cost`。

## 调用示例

```bash
curl --request POST --url https://api.apimart.ai/v1/images/generations \
  --header "Authorization: Bearer $APIMART_API_KEY" --header 'Content-Type: application/json' \
  --data '{"model":"gemini-3-pro-image-preview","prompt":"海边悬崖的现代别墅，黄昏","size":"16:9","n":1}'
```

## 披露

本仓为第三方中转服务 APIMart 的接入说明，与模型提供方无隶属关系；价格以标注快照为准。
