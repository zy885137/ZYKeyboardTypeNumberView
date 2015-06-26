# ZYKeyboardTypeNumberView
#简单的数字键盘#
##效果图##
<img src="http://i1.tietuku.com/94c903a0fc936ad3.png">
###用法###

- [ZYCustomKeyboardTypeNumberView customKeyboardViewWithServiceTextField:_numberTextField Delegate:self];

- (void)customKeyboardTypeNumberView_confirmKeyClicked
{
    NSLog(@"--确定按钮点击，并退下键盘--");
}
- (void)customKeyboardTypeNumberView_shrinkKeyClicked
{
    NSLog(@"--键盘退下点击--");
}
