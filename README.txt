# Fine-grained-sentiment-classification
## 训练和测试结果
【Train】 CV score for class location_traffic_convenience is 0.8964714096794445  
【Test】 CV score for class location_traffic_convenience is 0.9093333333333333  
【Train】 CV score for class location_distance_from_business_district is 0.8221345147683973  
【Test】 CV score for class location_distance_from_business_district is 0.8374  
【Train】 CV score for class location_easy_to_find is 0.9025239931813195  
【Test】 CV score for class location_easy_to_find is 0.8631333333333333  
【Train】 CV score for class service_wait_time is 0.8943213961367021  
【Test】 CV score for class service_wait_time is 0.8880666666666667  
【Train】 CV score for class service_waiters_attitude is 0.8966602851113622  
【Test】 CV score for class service_waiters_attitude is 0.7666  
【Train】 CV score for class service_parking_convenience is 0.9577172056289415  
【Test】 CV score for class service_parking_convenience is 0.9426666666666667  
【Train】 CV score for class service_serving_speed is 0.9108526916307597  
【Test】 CV score for class service_serving_speed is 0.8798  
【Train】 CV score for class price_level is 0.8731454727870557  
【Test】 CV score for class price_level is 0.6571333333333333  
【Train】 CV score for class price_cost_effective is 0.8943526379085563  
【Test】 CV score for class price_cost_effective is 0.8265333333333333  
【Train】 CV score for class price_discount is 0.8873864855467458  
【Test】 CV score for class price_discount is 0.7649333333333334  
【Train】 CV score for class environment_decoration is 0.8628417596721764  
【Test】 CV score for class environment_decoration is 0.7822  
【Train】 CV score for class environment_noise is 0.8779419403264449  
【Test】 CV score for class environment_noise is 0.7841333333333333  
【Train】 CV score for class environment_space is 0.8667841130210876  
【Test】 CV score for class environment_space is 0.7249333333333333  
【Train】 CV score for class environment_cleaness is 0.87829452074611  
【Test】 CV score for class environment_cleaness is 0.7844  
【Train】 CV score for class dish_portion is 0.8356820046319272  
【Test】 CV score for class dish_portion is 0.6863333333333334  
【Train】 CV score for class dish_taste is 0.8866803588407416  
【Test】 CV score for class dish_taste is 0.7202666666666667  
【Train】 CV score for class dish_look is 0.7970811825100224  
【Test】 CV score for class dish_look is 0.7547333333333334  
【Train】 CV score for class dish_recommendation is 0.8741871531690292  
【Test】 CV score for class dish_recommendation is 0.8329333333333333  
【Train】 CV score for class others_overall_experience is 0.8139040014948208  
【Test】 CV score for class others_overall_experience is 0.7738666666666667  
【Train】 CV score for class others_willing_to_consume_again is 0.8849609018754124  
【Test】 CV score for class others_willing_to_consume_again is 0.7881333333333334  
【Test】 Total CV score is 0.7983766666666667  
# 数据标注说明
层次一(The first layer)	层次二(The second layer)
位置(location)	交通是否便利(traffic convenience)
	距离商圈远近(distance from business district)
	是否容易寻找(easy to find)
服务(service)	排队等候时间(wait time)
	服务人员态度(waiter’s attitude)
	是否容易停车(parking convenience)
	点菜/上菜速度(serving speed)
价格(price)	价格水平(price level)
	性价比(cost-effective)
	折扣力度(discount)
环境(environment)	装修情况(decoration)
	嘈杂情况(noise)
	就餐空间(space)
	卫生情况(cleaness)
菜品(dish)	分量(portion)
	口感(taste)
	外观(look)
	推荐程度(recommendation)
其他(others)	本次消费感受(overall experience)
	再次消费的意愿(willing to consume again)
