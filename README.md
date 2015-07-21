#### flexbox ����
 ������Ҫѧϰ��Flexbox ���֣�CSS3 �е�һ���µĲ���ģʽ��Ŀ���ǽ�����ӵ��ִ�web���֡�  

+ Flexbox ����Flex Containers �� Flex Items  
	- Flex Containers `display: flex/inline-flex`  
	- Flex Item ����Flex Containers ����Ԫ�أ�����bootstrap�е�դ��ϵͳ  
	- ��Flex Containers������Flex Item�����DomԪ�ػ�������ǰһ������Ⱦ  
	- ��������Page ��direction������rtl  
	- Main Axis��Cross Axis����������ϵ�е�x��y�ᣬ���Ƿ����ǿ��Ըı�ģ�Ĭ�ϵ��Ǵ������£��������ҡ�
+ Flex Containers ������  
	- flex-direction �Ϳ������ı� Axis�ķ���Ĭ��ֵΪrow��������ֵ����row-reverse, column, column-reverse, �˴����Բο�demo  
	- justify-content ����������Main Axis��λ�ã����ܵ�ֵ��flex-start��flex-end��center��space-between��space-around  
	- align-items ��������Cross Axis��λ�ã����ܵ�ֵ��flex-start (default)��flex-end��center��baseline��stretch  
	- flex-wrap�� wrap ��������Flex Containers ��Ϊ multiple Flex Lines������ɶ��У�Ĭ�������һֱ��һ����    
	- align-content ��align-items���ƣ�������������Flex lines��  
	- flex-flow�� ��flex-direction��flex-wrap�ļ�д
+ Flex Items ������
	- һ��Flex Item��ָFlex Containers��ֱ�Ӻ���   
	- order ����ĳһ��Flex Item �Ĵ���Ϊ-1 ʱ�����ȱ���ʾ  
	- margin ����Ϊautoʱ�Ὣ����Ŀհ׶�����    
	- align-self ����align-items  
	- flex: [number] ����ָ��items��ռ�ı��������ÿһ��flex item������flex��������ô�հ׵ĵط��Ͷ��ᱻ����
+ ����align-items justify-content����ʵ�־��ж���  
 
		.demo {
		  height: 300px;
		  display: -webkit-flex;
		  display:         flex;
		  -webkit-align-items: center;
		          align-items: center;
		  -webkit-justify-content: center;
		          justify-content: center;
		}

+ [demo](https://github.com/lihang1870719/flexbox)
+ [�ο�����](https://bocoup.com/weblog/dive-into-flexbox/) 