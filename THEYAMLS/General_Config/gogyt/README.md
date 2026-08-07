# 📂 gogyt (通用进阶配置)

[🔙 返回上一级](../README.md)

> 🤖 自动技术分析 | 9 个配置文件

## ⚔️ 配置横向对比

| 特性 | `GeoLitePro.yaml` | `Geo.yaml` | `Rule.yaml` | `RulePro.yaml` | `RuleLite.yaml` | `GeoLite.yaml` | `GeoPro.yaml` | `RulePlus.yaml` | `RuleLitePro.yaml` |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **大小** | 26.9 KB | 26.7 KB | 33.6 KB | 44.1 KB | 25.5 KB | 21.5 KB | 35.4 KB | 48.6 KB | 30.6 KB |
| **混合端口** | 7893 | 7893 | 7893 | 7893 | 7893 | 7893 | 7893 | 7893 | 7893 |
| **面板地址** | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 |
| **运行模式** | rule | rule | rule | rule | rule | rule | rule | rule | rule |
| **TUN** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 |
| **策略组** | **63** | **59** | **59** | **91** | **39** | **39** | **91** | **120** | **63** |
| **规则数** | **32** | **55** | **55** | **62** | **32** | **32** | **62** | **62** | **32** |

## 📄 配置详情

#### 📝 GeoLitePro.yaml
- **路径**: `GeoLitePro.yaml` | **大小**: 26.9 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/GeoLitePro.yaml)
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

#### 📝 Geo.yaml
- **路径**: `Geo.yaml` | **大小**: 26.7 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/Geo.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (59个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 🔧 故障转移 | `fallback` |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 Github | `select` |
| 👆 油管视频 | `select` |
| 👆 谷歌服务 | `select` |
| 👆 AI服务 | `select` |
| 👆 国外电商 | `select` |
| 👆 加密货币 | `select` |
| 👆 即时通讯 | `select` |
| 👆 国外娱乐 | `select` |
| 👆 社交媒体 | `select` |
| 👆 TikTok | `select` |
| 👆 奈飞视频 | `select` |
| 👆 迪士尼+ | `select` |
| 👆 HBO | `select` |
| 👆 Prime Video | `select` |
| 👆 Spotify | `select` |
| 👆 Bing | `select` |
| 👆 微软服务 | `select` |
| ... | 还有 39 个 |
</details>

#### 📝 Rule.yaml
- **路径**: `Rule.yaml` | **大小**: 33.6 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/Rule.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (59个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 🔧 故障转移 | `fallback` |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 Github | `select` |
| 👆 油管视频 | `select` |
| 👆 谷歌服务 | `select` |
| 👆 AI服务 | `select` |
| 👆 国外电商 | `select` |
| 👆 加密货币 | `select` |
| 👆 即时通讯 | `select` |
| 👆 国外娱乐 | `select` |
| 👆 社交媒体 | `select` |
| 👆 TikTok | `select` |
| 👆 奈飞视频 | `select` |
| 👆 迪士尼+ | `select` |
| 👆 HBO | `select` |
| 👆 Prime Video | `select` |
| 👆 Spotify | `select` |
| 👆 Bing | `select` |
| 👆 微软服务 | `select` |
| ... | 还有 39 个 |
</details>

#### 📝 RulePro.yaml
- **路径**: `RulePro.yaml` | **大小**: 44.1 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/RulePro.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (91个)</summary>

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
| ... | 还有 71 个 |
</details>

#### 📝 RuleLite.yaml
- **路径**: `RuleLite.yaml` | **大小**: 25.5 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/RuleLite.yaml)
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

#### 📝 GeoLite.yaml
- **路径**: `GeoLite.yaml` | **大小**: 21.5 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/GeoLite.yaml)
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

#### 📝 GeoPro.yaml
- **路径**: `GeoPro.yaml` | **大小**: 35.4 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/GeoPro.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (91个)</summary>

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
| ... | 还有 71 个 |
</details>

#### 📝 RulePlus.yaml
- **路径**: `RulePlus.yaml` | **大小**: 48.6 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/RulePlus.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (120个)</summary>

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
| ... | 还有 100 个 |
</details>

#### 📝 RuleLitePro.yaml
- **路径**: `RuleLitePro.yaml` | **大小**: 30.6 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/RuleLitePro.yaml)
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
