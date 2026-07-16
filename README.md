# Maven-Dependency-Search
A Maven dependency search and management plugin for IntelliJ IDEA. 
# Solrsearch
# Maven Dependency Search Changelog

## Unreleased

## 2026.1.0-20260714

### Added

- Maven Central 依赖搜索（支持 groupId / artifactId 关键词搜索）
- 项目依赖管理（自动检测 pom.xml / build.gradle* 中的依赖，检查版本更新）
- 智能版本解析（Maven `${property}` / Gradle `extra["key"]` 变量引用，定位并修改变量定义位置）
- 版本历史浏览（点击版本列下拉菜单查看所有可用版本）
- 依赖片段复制（Maven POM / Gradle Kotlin DSL / Gradle Groovy DSL）
- 一键添加依赖到项目
- 打开组件文档链接
