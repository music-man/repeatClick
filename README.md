# repeatClick
1集成过GIO的SDK，可能会使之前的防重复失效 ，请使用这个防止重复点击

2如果需要针对某个按钮设置防重复 可以把下边这个判断打开 只要设置了btnTag的值即可，默认是666可以自己更改
//    if ([self isKindOfClass:[UIButton class]]) {
//        UIButton *btn = (UIButton *)self ;
//        if (btn.tag != btnTag) {
//            [self dj_repeat_sendAction:action to:target forEvent:event];
//            return ;
//        }
//    }

3目前针对tabbar的点击不处理
