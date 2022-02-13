# zero-im based on [go-zero]()

## Architecture

## structure 
client -> websocket -> rpc -> pubsub 

### account
 - 添加账号
 - 禁用账号
 - 删除账号
 - 获取账号
 - 断开账号

### group
 - 添加群组
 - 禁用群组
 - 删除群组
 - 获取群组
 - 解散群组
 - 添加群员
 - 查询群员
 - 踢除群员
 - 禁言群员
 - 发送消息
 - 撤回消息
 - 历史消息
 - 未读消息
 
### chat
 - 发送消息
 - 查询消息
 - 撤回消息
 - 设置已读
 - 查询未读

## conversation
 - 创建会话
 - 删除会话