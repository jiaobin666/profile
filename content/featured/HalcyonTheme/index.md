---
date: '1'
title: 'MC 联机中继'
cover: './demo.png'
github: 'https://github.com/jiaobin666'
external: ''
cta: ''
tech:
  - FRP
  - Nginx
  - CrowdSec
  - vnstat
  - Tailscale
  - Shell Script
---

基于阿里云 ECS 自建的 Minecraft 联机加速中继服务。使用 FRP 内网穿透 + 令牌认证实现安全稳定的联机体验，配合 vnstat 流量监控和 CrowdSec 入侵防御，在 15G 免费流量限额内实现零故障运行两个月。后续扩展 Tailscale DERP 中继节点，将整个 Tailnet 网络延迟从 80ms 降至 3ms。
