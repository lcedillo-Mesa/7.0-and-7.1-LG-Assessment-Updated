# 评估 — LG 7.0：响应式设计
# Assessment — LG 7.0: Responsive Design


---

## 概述 / Overview

本次评估分为两个部分：

This assessment has two parts:

1. **编程部分 / Coding section** — 你将对现有的 CSS 文件进行修改，使网页具有响应式效果 / you will make changes to an existing CSS file to make a webpage responsive
2. **简答部分 / Short response section** — 你将用自己的话回答关于响应式单位的问题 / you will answer questions about responsive units in your own words

在开始编程之前请先通读所有内容。

Read through everything before you start coding.

---

## 第一部分 — 响应式布局 / Part 1 — Responsive Layout

你获得了一个已经应用了基本 CSS 的简单 HTML 页面。创建这个页面的学生使用了静态像素值来设置所有元素的大小 — 这意味着布局在不同屏幕尺寸下会出现问题。

You have been given a simple HTML page with basic CSS already applied. The student who built it used static pixel values to size everything — which means the layout breaks on different screen sizes.

你的任务是更新现有的 CSS 规则，使页面能够响应任何屏幕尺寸。你不需要修改 HTML 文件。打开 CSS 文件并对已有的规则进行修改。

Your job is to update the existing CSS rules so the page responds to any screen size. You do not need to rewrite the HTML. Open the CSS file and make your changes to the rules that are already there.

---

### 任务 1 — 使图片具有响应式效果 / Task 1 — Make the image responsive

目前图片使用静态像素值来设置大小。更新 CSS，使图片无论在什么屏幕尺寸下都占据其**容器的 50%**。

Right now the image is sized with a static pixel value. Update the CSS so that the image takes up **50% of its container** no matter what screen size it is viewed on.

**你必须使用 `%` 单位。/ You must use a `%` unit.**

---

### 任务 2 — 使文字具有响应式效果 / Task 2 — Make the text responsive

标题和段落文字目前使用静态像素值来设置字体大小。更新 CSS，使文字能够随屏幕尺寸进行缩放。

The heading and paragraph text are currently using static pixel values for font size. Update the CSS so that the text scales with the screen size.

**你必须使用 `vw` 单位。/ You must use a `vw` unit.**

---

### 任务 3 — 使主要内容区域填满屏幕 / Task 3 — Make the main section fill the screen

我们希望主要内容区域始终占据整个屏幕高度，无论浏览器窗口有多高。

We want the main section to always take up the full height of the screen regardless of how tall the browser window is.

编写一个规则使主要内容区域填满整个视口高度。

Write a rule so that the main section fills the full viewport height.

**你必须使用 `vh` 单位。/ You must use a `vh` unit.**

---

## 第二部分 — 简答题 / Part 2 — Short Response

打开 `ShortResponse.md` 并回答里面的三个问题。

Open `ShortResponse.md` and answer the three questions inside.

---

## 评分标准 / Rubric

### LG 7.0 — 动态单位 / Dynamic Units

| 等级 / Level | 描述 / What this looks like |
|-------|-------------|
| **4 — 超越 / Exceeds** | 三个任务全部完成，每个任务都使用了正确的单位。学生还在任务要求之外进行了至少一处额外修改 — 例如对任务中未提及的其他元素应用了响应式单位 — 并且该修改改善了布局。/ All three tasks are complete and use the correct unit for each one. The student also made at least one additional change beyond the tasks and that change improves the layout. |
| **3 — 达标 / Meets** | 三个任务全部完成。每个任务使用了正确的单位 — 图片使用 `%`，文字使用 `vw`，主要内容区域使用 `vh`。当调整浏览器窗口大小时，页面能够明显响应。/ All three tasks are complete. The correct unit is used in each task. The page responds visibly when the browser window is resized. |
| **2 — 接近 / Approaching** | 至少完成了一个任务并使用了正确的单位。其他任务有尝试但使用了错误的单位或没有完全应用。/ At least one task is complete with the correct unit. Other tasks are attempted but use the wrong unit or are not fully applied. |
| **1 — 未尝试 / No attempt** | CSS 文件中除了设置代码外没有任何修改。整个文件中仍然使用静态像素值。/ No changes have been made to the CSS file beyond the setup code. Static pixel values remain throughout. |