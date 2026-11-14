# 李朝阳

**Linux 运维工程师** · 高可用 / 容器化 / 可观测性

我主要做 Linux 业务系统的接入层和基础环境：用 Nginx + Keepalived 保证入口稳定，用 Docker 负责服务部署与发布，用 Prometheus/Grafana、Zabbix 关注系统和服务状态。比起把组件跑起来，我更关心它能不能长期稳定地支撑业务。

最近在把日常运维中的脚本、配置和排查笔记整理成可复用的项目。

## 技术栈

- **系统与接入**：Linux、Nginx、Keepalived、TCP/IP
- **容器与部署**：Docker、Docker Compose、镜像构建与发布
- **数据与缓存**：MySQL、Redis 日常运维与问题处理
- **监控告警**：Prometheus、Grafana、Zabbix、Alertmanager
- **自动化**：Shell、Ansible、GitHub Actions、Jenkins、CI/CD

## 精选项目

### 运维工具

- [ops-scripts](https://github.com/Ricardorich33/ops-scripts)：服务健康检查、容器状态、MySQL/Redis 备份、日志清理等日常脚本
- [server-init](https://github.com/Ricardorich33/server-init)：新服务器初始化与 SSH、内核参数安全加固
- [ansible-playbooks](https://github.com/Ricardorich33/ansible-playbooks)：主机初始化、Nginx 和 Docker 的自动化部署

### 稳定性与可观测性

- [nginx-keepalived-ha](https://github.com/Ricardorich33/nginx-keepalived-ha)：Nginx + Keepalived 高可用配置与故障排查
- [monitoring-alerts](https://github.com/Ricardorich33/monitoring-alerts)：Prometheus 告警规则、Alertmanager 路由和 Grafana 看板
- [docker-compose-stacks](https://github.com/Ricardorich33/docker-compose-stacks)：监控、Web 应用、MySQL/Redis 的 Compose 模板

### 学习与记录

- [ops-notes](https://github.com/Ricardorich33/ops-notes)：Nginx、MySQL、Redis、Docker、Prometheus 实践笔记
- [ci-cd-examples](https://github.com/Ricardorich33/ci-cd-examples)：GitHub Actions 与 Jenkins 发布示例

## 开源参与

- [devops-exercises #10675](https://github.com/bregman-arie/devops-exercises/pull/10675)：补充容器 OOM kill 与应用退出的排查题
- [Orbit #165](https://github.com/jianghailong-xy/orbit/pull/165)：补充 Compose 网关的 Caddy / nginx TLS 反向代理文档

以上 PR 目前处于 review 阶段。

## 联系

- GitHub：[@Ricardorich33](https://github.com/Ricardorich33)
- Email：Ricardorich33@users.noreply.github.com

欢迎交流 Linux 运维、监控告警和自动化。
