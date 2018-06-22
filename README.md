# xianzfb
xian zfb
1. 此为开发版本，不作为正式版本
2. 需要在支付宝环境下打开（调用了支付宝的sdk）
3. 编码都为utf-8
4. 
  *index.html* ---- 首页
  *guide.html* ---- 证件列表页(办事指南)
  *detail.html* ---- 证件详情页（办事指南详情）
  *online_step_1.html* ---- 阅读须知页（在线办理第一步）
  *online_step_2.html* ---- 申报信息（在线办理第二步）
  *online_step_3.html* ---- 申报告知（在线办理第三步）
  *search.html* ---- 搜索页
  
  ****************************
  ***---已完成和未完成说明---***
  ****************************
  
 4. guide.html 已经使用了约定的json数据完成了 ajax动态添加dom的工作
    后续需要删掉写死数据，改写ajax请求地址，添加一些必要的参数在html上
 5. 其他页面暂时没有进行json数据来填充，为页面写死
 6. 首页的搜索栏是 search.html的入口，search.html的搜索为页面内搜索
 7. 申报信息页的图片预览暂时没有做，并且规定最多传5张图片
 8. 页面内应用的js和css大部分为CDN引用，如需本地引用，请自行下载
 9. 上线前请进行代码压缩
 
 
  ****************************
  ********---参考---***********
  ****************************
  
  1. 支付宝H5开放文档： https://myjsapi.alipay.com/alipayjsapi/index.html
  2. AntUi地址： https://antui.alipay.com/10.1.10/index.html#Usage%20%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95  
  3. swiper3.0 参考: http://3.swiper.com.cn/api/index.html
  4. 其他UI设计参考: https://mobile.ant.design/components/steps-cn/
  5. 如需完美贴合支付宝应用，建议使用ant design mobile，需配合react webpack 使用
 
