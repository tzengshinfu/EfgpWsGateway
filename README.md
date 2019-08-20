**必要元件:**  
適用於EasyFlow GP。  

**功能:**  
讓EasyFlow流程Invoke關卡能傳值到其他非EasyFlow的web service(如Tiptop)及取值。  
(web service回傳值只支援基本型態,不支援複合型態。)  

**安裝**  
1.Jboss 4.2.3.GA  
2.Apache Axis 1.3  
3.將Gateway.jws複製到<Jboss主機路徑>\server\default\deploy\axis.war下  
4.新增要呼叫的web service方法即可  