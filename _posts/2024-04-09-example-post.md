---
layout: post
title: 示例文章
date: 2024-04-09
author: Your Name
tags: [示例, 博客, 技术]
---

# 示例文章

这是一篇示例文章，展示了极简主题的文章样式。

## 小标题

你可以在这里写一些内容。

### 代码示例

```python
def hello_world():
    print("Hello, World!")
```

## 列表示例

- 项目 1
- 项目 2
- 项目 3

## 引用示例

### MerMaide支持测试

这是一个类图示例：

```mermaid
classDiagram
    class Animal {
        +String name
        +makeSound()
    }
    class Dog {
        +bark()
    }
    class Cat {
        +meow()
    }
    Animal <|-- Dog
    Animal <|-- Cat
```

或者序列图：

```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts<br/>prevail...
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```

```mermaid
sequenceDiagram
    participant Client
    participant Server
    participant Database
    
    Client->>Server: 发送请求
    Server->>Database: 查询数据
    Database-->>Server: 返回数据
    Server-->>Client: 响应结果
```

> 这是一段引用文字。
> 可以写多行。 