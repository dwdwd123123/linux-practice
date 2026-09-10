# linux‑practice
> 个人Linux运维练习仓库，CentOS Stream9实操记录，包含实验复现、故障模拟、排错过程。

## 学习环境
- OS：Rocky-9
- - 工具：FinalShell、VSCode、Git
- 初始化脚本：setup.sh，补齐基础依赖、关闭MySQL初始密码

## 本仓库包含实验
1. 用户与权限管理实验
2. 磁盘管理、磁盘占满故障模拟
3. firewalld防火墙规则练习
4. Nginx完整部署实验，多场景故障复现与排错
    - 配置文件语法错误
    - 端口被占用冲突
    - 防火墙拦截访问
5. crontab定时任务实操

## 仓库目录说明
- `permission‑practice.md`：用户与权限管理实验
- `disk‑practice.md`：磁盘管理、磁盘占满故障模拟
- `firewalld‑practice.md`：firewalld防火墙规则练习
- `nginx‑practice.md`：Nginx部署、故障复现与排错
- `notes/`：日常零散命令笔记（后续新建）

## 本月验收标准
拿到全新Rocky-9虚拟机，独立完成Nginx部署；复现故障，通过日志、命令定位问题并修复。

## 学习说明
所有文档记录：现象 → 排查命令 → 根因 → 修复步骤。

## 本地使用
```bash
git clone https://github.com/dwdwd123123/linux‑practice.git
cd linux‑practice
