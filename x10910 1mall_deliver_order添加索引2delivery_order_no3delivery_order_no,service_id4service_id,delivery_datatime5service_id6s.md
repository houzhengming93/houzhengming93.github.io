```
mall_deliver_order添加索引
delivery_order_no
delivery_order_no,service_id
service_id,delivery_datatime
service_id
service-id,type

mall_delivery_good添加索引
delivery_order_no




```





定时任务配置：

每天仓库费用计算，BEAN：computeDeliveryOrderByDayHandler 

