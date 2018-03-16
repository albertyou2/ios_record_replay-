# ios_record_replay-
This Repo. is a library for recording and replaying user touch event in one app.
You have to build these code in your APP with source code . 
The purpose is for IOS app ui autotest. 
It can also give the test result by comparing screen: once you record a test case ,(you have to input a case name first)it save a pictrue for screen automaticlly;when you  relay a case,afer relpay all ui touch events,it automactily cut screen and compare  it with the picture you captured in record session according to case name. 
It also record and replay http request and response automaticlly if you use afnetworking 2.0 ( if you use other  this network framework, UI record / replay will still work fine ) ,you need do nothing 


这是一个IOS的UI录制回放测试系统，必须有APP源码。
这个库的目的是为了IOSAPP的UI自动化测试
这个库录制case的时候会根据你输入的测试用例名字记录UI操作，最后会截图一张；回放这个CASE的时候回在所有UI事件播放完成后，截图并和录制时的图片比较，得出测试结果
这个库同时也录制了全部的HTTP请求和响应，（APP必须使用AFNETWORKING2.0才可以，如过你没有使用这个框架，；录制回放功能不会受到影响）
这个库已经很久没有维护了，近期（2018。3月）——在IOS11下真机测试没有问题，有需要可以联系我



