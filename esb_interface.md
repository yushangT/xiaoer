# xiaoer
01 获取职位列表接口 :http://140.207.168.154:9588/xiaoer/getJobListFromType                   
:type=00010001热门,00010002推荐(默认不填是推荐=00010002)

name:职位名称
salary:薪水
weal:福利
cnameAddr:公司名+地址
distance:距离
positionLevel:职位紧急程度 (一般,加急,火急)
sPic:职位介绍缩率图

eg:[ {
  "id" : 1,
  "version" : null,                             
  "createDate" : null,                          
  "createUserId" : null,                        
  "editDate" : null,                            
  "editUserId" : null,                        
  "name" : "洗碗工",                                                                          
  "salary" : "3500元/月",                                                                     
  "weal" : "餐补,住房补",                                                                     
  "cnameAddr" : "麦德龙 (张江店)",                                                           
  "distance" : "1.3km",                                                                       
  "positionLevel" : null,                                                                     
  "sPic" : "http://tupian.baike.com/a4_48_54_01300000184180121751549799188_jpg.html",         
  "memo2" : null,
  "memo3" : null
}]
