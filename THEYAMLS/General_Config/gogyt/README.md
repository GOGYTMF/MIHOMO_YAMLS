# 📂 gogyt (通用进阶配置)

[🔙 返回上一级](../README.md)

> 🤖 自动技术分析 | 9 个配置文件

## ⚔️ 配置横向对比

| 特性 | `GeoAIOPro.yaml` | `RuleLitePro.yaml` | `RuleLite.yaml` | `GeoAIO.yaml` | `GeoLite.yaml` | `RuleAIO.yaml` | `GeoLitePro.yaml` | `RuleAIOPlus.yaml` | `RuleAIOPro.yaml` |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **大小** | 37.3 KB | 32.2 KB | 27.1 KB | 32.2 KB | 23.1 KB | 40.6 KB | 28.6 KB | 50.3 KB | 45.9 KB |
| **混合端口** | 7893 | 7893 | 7893 | 7893 | 7893 | 7893 | 7893 | 7893 | 7893 |
| **面板地址** | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 |
| **运行模式** | rule | rule | rule | rule | rule | rule | rule | rule | rule |
| **TUN** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 |
| **策略组** | **93** | **63** | **39** | **69** | **39** | **69** | **63** | **122** | **93** |
| **规则数** | **70** | **39** | **39** | **70** | **39** | **70** | **39** | **70** | **70** |

## 📄 配置详情

#### 📝 GeoAIOPro.yaml
- **路径**: `GeoAIOPro.yaml` | **大小**: 37.3 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/GeoAIOPro.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (93个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 🔧 故障转移 | `fallback` |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 Github | `select` |
| 👆 油管视频 | `select` |
| 👆 国外娱乐 | `select` |
| 👆 谷歌FCM | `select` |
| 👆 谷歌服务 | `select` |
| 👆 Gemini | `select` |
| 👆 Claude | `select` |
| 👆 ChatGPT | `select` |
| 👆 Grok | `select` |
| 👆 AI服务 | `select` |
| 👆 国外电商 | `select` |
| 👆 即时通讯 | `select` |
| 👆 社交媒体 | `select` |
| 👆 TikTok | `select` |
| 👆 奈飞视频 | `select` |
| 👆 迪士尼+ | `select` |
| 👆 HBO | `select` |
| ... | 还有 73 个 |
</details>

#### 📝 RuleLitePro.yaml
- **路径**: `RuleLitePro.yaml` | **大小**: 32.2 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/RuleLitePro.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (63个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 🔧 故障转移 | `fallback` |
| 👆 漏网之鱼 | `select` |
| 👆 网络测试 | `select` |
| 👆 直接连接 | `select` |
| 👆 狮城策略 | `select` |
| 👆 香港策略 | `select` |
| 👆 日本策略 | `select` |
| 👆 美国策略 | `select` |
| 👆 台湾策略 | `select` |
| 👆 欧盟策略 | `select` |
| 👆 韩国策略 | `select` |
| 👆 冷门策略 | `select` |
| ⚖️ [主] 香港-散列 | `load-balance` |
| ⚖️ [主] 台湾-散列 | `load-balance` |
| ⚖️ [主] 狮城-散列 | `load-balance` |
| ⚖️ [主] 日本-散列 | `load-balance` |
| ⚖️ [主] 韩国-散列 | `load-balance` |
| ⚖️ [主] 美国-散列 | `load-balance` |
| ... | 还有 43 个 |
</details>

#### 📝 RuleLite.yaml
- **路径**: `RuleLite.yaml` | **大小**: 27.1 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/RuleLite.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (39个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 🔧 故障转移 | `fallback` |
| 👆 漏网之鱼 | `select` |
| 👆 网络测试 | `select` |
| 👆 直接连接 | `select` |
| 👆 狮城策略 | `select` |
| 👆 香港策略 | `select` |
| 👆 日本策略 | `select` |
| 👆 美国策略 | `select` |
| 👆 台湾策略 | `select` |
| 👆 欧盟策略 | `select` |
| 👆 韩国策略 | `select` |
| 👆 冷门策略 | `select` |
| ⚖️ 香港均衡-散列 | `load-balance` |
| ⚖️ 台湾均衡-散列 | `load-balance` |
| ⚖️ 狮城均衡-散列 | `load-balance` |
| ⚖️ 日本均衡-散列 | `load-balance` |
| ⚖️ 韩国均衡-散列 | `load-balance` |
| ⚖️ 美国均衡-散列 | `load-balance` |
| ... | 还有 19 个 |
</details>

#### 📝 GeoAIO.yaml
- **路径**: `GeoAIO.yaml` | **大小**: 32.2 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/GeoAIO.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (69个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 🔧 故障转移 | `fallback` |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 Github | `select` |
| 👆 油管视频 | `select` |
| 👆 国外娱乐 | `select` |
| 👆 谷歌FCM | `select` |
| 👆 谷歌服务 | `select` |
| 👆 Gemini | `select` |
| 👆 Claude | `select` |
| 👆 ChatGPT | `select` |
| 👆 Grok | `select` |
| 👆 AI服务 | `select` |
| 👆 国外电商 | `select` |
| 👆 即时通讯 | `select` |
| 👆 社交媒体 | `select` |
| 👆 TikTok | `select` |
| 👆 奈飞视频 | `select` |
| 👆 迪士尼+ | `select` |
| 👆 HBO | `select` |
| ... | 还有 49 个 |
</details>

#### 📝 GeoLite.yaml
- **路径**: `GeoLite.yaml` | **大小**: 23.1 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/GeoLite.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (39个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 🔧 故障转移 | `fallback` |
| 👆 漏网之鱼 | `select` |
| 👆 网络测试 | `select` |
| 👆 直接连接 | `select` |
| 👆 狮城策略 | `select` |
| 👆 香港策略 | `select` |
| 👆 日本策略 | `select` |
| 👆 美国策略 | `select` |
| 👆 台湾策略 | `select` |
| 👆 欧盟策略 | `select` |
| 👆 韩国策略 | `select` |
| 👆 冷门策略 | `select` |
| ⚖️ 香港均衡-散列 | `load-balance` |
| ⚖️ 台湾均衡-散列 | `load-balance` |
| ⚖️ 狮城均衡-散列 | `load-balance` |
| ⚖️ 日本均衡-散列 | `load-balance` |
| ⚖️ 韩国均衡-散列 | `load-balance` |
| ⚖️ 美国均衡-散列 | `load-balance` |
| ... | 还有 19 个 |
</details>

#### 📝 RuleAIO.yaml
- **路径**: `RuleAIO.yaml` | **大小**: 40.6 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/RuleAIO.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (69个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 🔧 故障转移 | `fallback` |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 Github | `select` |
| 👆 油管视频 | `select` |
| 👆 国外娱乐 | `select` |
| 👆 谷歌FCM | `select` |
| 👆 谷歌服务 | `select` |
| 👆 Gemini | `select` |
| 👆 Claude | `select` |
| 👆 ChatGPT | `select` |
| 👆 Grok | `select` |
| 👆 AI服务 | `select` |
| 👆 国外电商 | `select` |
| 👆 即时通讯 | `select` |
| 👆 社交媒体 | `select` |
| 👆 TikTok | `select` |
| 👆 奈飞视频 | `select` |
| 👆 迪士尼+ | `select` |
| 👆 HBO | `select` |
| ... | 还有 49 个 |
</details>

#### 📝 GeoLitePro.yaml
- **路径**: `GeoLitePro.yaml` | **大小**: 28.6 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/GeoLitePro.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (63个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 🔧 故障转移 | `fallback` |
| 👆 漏网之鱼 | `select` |
| 👆 网络测试 | `select` |
| 👆 直接连接 | `select` |
| 👆 狮城策略 | `select` |
| 👆 香港策略 | `select` |
| 👆 日本策略 | `select` |
| 👆 美国策略 | `select` |
| 👆 台湾策略 | `select` |
| 👆 欧盟策略 | `select` |
| 👆 韩国策略 | `select` |
| 👆 冷门策略 | `select` |
| ⚖️ [主] 香港-散列 | `load-balance` |
| ⚖️ [主] 台湾-散列 | `load-balance` |
| ⚖️ [主] 狮城-散列 | `load-balance` |
| ⚖️ [主] 日本-散列 | `load-balance` |
| ⚖️ [主] 韩国-散列 | `load-balance` |
| ⚖️ [主] 美国-散列 | `load-balance` |
| ... | 还有 43 个 |
</details>

#### 📝 RuleAIOPlus.yaml
- **路径**: `RuleAIOPlus.yaml` | **大小**: 50.3 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/RuleAIOPlus.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (122个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 Github | `select` |
| 👆 油管视频 | `select` |
| 👆 谷歌FCM | `select` |
| 👆 谷歌服务 | `select` |
| 👆 Gemini | `select` |
| 👆 Claude | `select` |
| 👆 ChatGPT | `select` |
| 👆 Grok | `select` |
| 👆 AI服务 | `select` |
| 👆 即时通讯 | `select` |
| 👆 国外电商 | `select` |
| 👆 加密货币 | `select` |
| 👆 社交媒体 | `select` |
| 👆 国外娱乐 | `select` |
| 👆 TikTok | `select` |
| 👆 奈飞视频 | `select` |
| 👆 迪士尼+ | `select` |
| 👆 HBO | `select` |
| ... | 还有 102 个 |
</details>

#### 📝 RuleAIOPro.yaml
- **路径**: `RuleAIOPro.yaml` | **大小**: 45.9 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/RuleAIOPro.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (93个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 🔧 故障转移 | `fallback` |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 Github | `select` |
| 👆 油管视频 | `select` |
| 👆 国外娱乐 | `select` |
| 👆 谷歌FCM | `select` |
| 👆 谷歌服务 | `select` |
| 👆 Gemini | `select` |
| 👆 Claude | `select` |
| 👆 ChatGPT | `select` |
| 👆 Grok | `select` |
| 👆 AI服务 | `select` |
| 👆 国外电商 | `select` |
| 👆 即时通讯 | `select` |
| 👆 社交媒体 | `select` |
| 👆 TikTok | `select` |
| 👆 奈飞视频 | `select` |
| 👆 迪士尼+ | `select` |
| 👆 HBO | `select` |
| ... | 还有 73 个 |
</details>
