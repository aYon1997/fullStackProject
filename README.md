# 基于 Node.js、ElementUI、MySQL 的简单 PC 增删改查项目说明

## 一、项目概述

本项目旨在使用 Node.js 作为后端开发语言，结合 ElementUI 这一流行的前端 UI 框架，以及 MySQL 数据库，构建一个具备基本增删改查功能的 PC 端应用程序，可用于管理各类数据，如员工信息、商品清单、学生成绩等，方便用户进行日常的数据操作与维护。

## 二、技术栈

### 后端

Node.js：作为服务器端运行环境，利用其异步非阻塞的特性，高效处理多个请求，为项目提供稳定的后端支持。

Express：基于 Node.js 的简洁而灵活的 web 应用框架，用于快速搭建后端路由、处理请求和响应，简化开发流程。

MySQL：关系型数据库，用于存储结构化数据，提供强大的数据存储、查询和管理功能，保障数据的持久性与可靠性。

mysql2：MySQL 的高性能驱动，相较于原生驱动，它在性能、易用性上有诸多优势，便于 Node.js 与 MySQL 进行交互。

### 前端

Vue.js：一套构建用户界面的渐进式框架，本项目采用 Vue 来构建前端页面逻辑，与后端 API 进行交互，实现动态页面渲染。

ElementUI：基于 Vue.js 的组件库，提供了丰富、美观且易用的 UI 组件，如表格、表单、按钮等，大大加速前端页面的开发进程，提升用户界面的美观度与交互性。
