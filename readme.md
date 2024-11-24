# Git-test

## 项目简介

**Git-test** 是一个用于测试和学习 Git 版本控制的仓库。本项目主要包含示例代码、分支操作练习，以及一些简单的 Git 命令演示。

------

## 目录结构

```
plaintext复制代码Git-test/  
├── src/             # 源代码目录  
├── docs/            # 文档目录  
├── tests/           # 测试文件  
├── README.md        # 项目说明文件  
└── .gitignore       # Git 忽略规则  
```

------

## 使用说明

### 1. 克隆项目

运行以下命令将项目克隆到本地：

```
bash复制代码git clone https://github.com/Sep459/Git-test.git  
cd Git-test  
```

### 2. 分支管理

#### 查看分支

```
bash


复制代码
git branch -a  
```

#### 切换分支

```
bash


复制代码
git switch <branch-name>  
```

#### 创建分支

```
bash


复制代码
git checkout -b <new-branch-name>  
```

------

## 提交规范

1. **提交格式**：
   每次提交请遵循以下格式：

   ```
   plaintext
   
   
   复制代码
   [类型]: 描述信息  
   ```

   **类型示例**：

   - `feat`：新增功能
   - `fix`：修复问题
   - `docs`：文档修改
   - `refactor`：代码重构
   - `test`：测试相关
