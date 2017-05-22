# js-err-collector
web前端异常采集


##使用方法
初始化操作
jsErrCollector({

        url:'/admin/user/add', //发送到后台的url *必须

        data:{version : '1.0.1'}, //自定义参数，如版本号等 可省略

        success:function(response, xml){
            alert(response);

            // 成功回调，可省略
        },

        fail:function(error){
            alert(error);

            // 失败回调，可省略
        }
});

要确保初始化操作在所有js代码执行之前执行