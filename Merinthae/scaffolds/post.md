---
# 基础配置
title: {{ title }}           # 文章标题
date: {{ date }}            # 发布时间
updated: {{ date }}         # 更新时间

# 分类和标签
categories:                 # 分类，只能设置单个分类
tags: []                    # 标签，可设置多个，用[tag1,tag2]格式

# 文章描述
description:               # 文章描述，用于首页展示和SEO，如不设置则自动使用文章前150字
keywords:                  # SEO关键词

# 文章封面配置
index_img:                # 首页封面图，如果设置，显示在首页轮播图中
banner_img:               # 文章页顶部大图，如不设置则使用主题默认配置
banner_img_height: 70     # banner图高度，70表示70%
banner_mask_alpha: 0.3    # banner图遮罩透明度，0-1之间

# 文章特殊配置
sticky:                  # 文章置顶，数字越大优先级越高（如：1, 2, 3...）
hide: false              # 是否在首页隐藏这篇文章，设为true则隐藏
archive: false           # true则文章仅在归档页面显示，不在首页显示

# 评论设置
comments: true           # 是否开启评论
comment: 'twikoo'        # 指定评论插件，如twikoo, valine等

# 文章版权信息
copyright: true          # 是否显示版权信息
copyright_author:        # 文章作者，默认使用全局配置
copyright_author_href:   # 作者链接
copyright_info:          # 版权声明文字

# 文章功能
toc: true               # 是否显示目录
toc_number: true        # 是否显示目录编号
auto_excerpt: true      # 是否自动截取摘要

# 数学公式与图表
math: false             # 是否启用数学公式
mermaid: false          # 是否启用流程图
katex: false            # 是否启用 katex 数学公式

# 分类栏显示
category_bar: false     # 是否显示分类栏
---



