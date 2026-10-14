# 制造计划助手 · AI 供应链计划系统（求职演示版）

**在线演示版：** GitHub Pages 部署完成后，请在此填写网站地址。  
**完整源码仓库：** https://github.com/1468795753hkx-png/scm-planning

## 项目简介

本仓库用于展示制造计划助手的前端交互体验。页面围绕需求与订单、主生产计划（MPS）、物料需求计划（MRP）、库存管理、采购建议与风险预警组织。

## 演示说明

- 本演示版为纯 HTML/CSS/JavaScript 静态网页，无需安装 Python、Node.js 或数据库。
- 所有数据均为**模拟数据**，交互仅更新当前页面中的本地状态。
- 运行计划、MRP 计算和采购建议是前端演示逻辑，不代表后端 API 或真实优化算法的执行结果。
- 刷新页面后，演示数据会恢复初始状态；不会连接或修改真实数据库。

## 在线打开

GitHub 仓库创建完成后，在 **Settings → Pages → Build and deployment** 中选择 **Deploy from a branch**，分支选 `main`，目录选 `/(root)`，保存。部署成功后，GitHub Pages 会显示访问地址。

## 完整源码

后端和原始开发代码保存在独立仓库：

https://github.com/1468795753hkx-png/scm-planning

该仓库包含后端 API、数据模型、计划逻辑及运行配置。请查看原仓库 README 了解本地启动方式和当前实现状态。

## 技术栈

- Frontend demo: HTML, CSS, Vanilla JavaScript
- Original project backend: Python, FastAPI
- Database support in original project: SQLite / PostgreSQL
- Planning and analytics dependencies in original project: PuLP, pandas, NumPy, statsmodels

## 求职展示用途

本项目用于展示本人在供应链计划业务理解、前端交互设计、需求/库存/产能/采购流程建模以及全栈项目探索方面的实践。演示版中的模拟结果已明确标注，不应被视为真实生产系统的计算结果。
