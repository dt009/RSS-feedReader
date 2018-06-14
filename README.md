# RSS-feedReader
优达学城 订阅阅读器测试

## Link && Link not empty 的测试

- `allFeeds` 变量
-  对每一项进行判断

## Name && Name not empty 的测试
 
- `allFeeds` 变量
-  对每一项进行判断

# The menu

## the menu element is hidden by default 的测试

- 使用 JQ 的 API 获取 body 的 class 属性

- 判断 是否有 'menu-hidden' 这个 class 名


## the menu change status 的测试

- 使用 JQ 提供的方法, 触发对应事件

- 判断事件发生后的 body 的 className 有没有变化

# Initial Entries

## loadFeed not problem 的测试

- 异步测试, 借助 done 函数确保测试时, 异步执行完毕

- 判断对应的 dom 是否有生成


# New Feed Selection

## reload success 的测试

- 先获取未重新加载的数据第一条的 title

- 调用 loadFeed 加载新的数据(借助 done)

- 在获取新的 title

- 对比两次的 title