# JxbRemark
纯记录备忘

#ReactiveCocoa
##1.RACSubject
###可以代替代理：subscribeNext & sendNext

##2.RACSequence:RAC
###遍历NSArray,NSDictionary
//对NSDictionary解包
RACTupleUnpack(NSString *key,NSString *value) = x;

##3. rac_liftSelector:withSignalsFromArray:Signals
###处理当界面有多次请求时，需要都获取到数据时，才能展示界面

##4.RAC(TARGET, [KEYPATH, [NIL_VALUE]])
###//只要文本框文字改变，就会修改label的文字
###RAC(self.labelView,text) = _textField.rac_textSignal;
