### 1.定制推送消息内容，主要是推送内容的定制
`ChatViewController 中， - (void)sendMsg:(IMAMsg *)msg`

### 2.ChatViewController, 一下方法中定义了系统消息的展示方式
`- (UITableViewCell *)tableView:(UITableView *)tableView cellForRowAtIndexPath:(NSIndexPath *)indexPath`,
`ChatSysMsgCell`
