##JDBC Global Setting
jdbc.driver=com.mysql.jdbc.Driver
jdbc.url=jdbc:mysql://127.0.0.1:3306/zc?useUnicode=true&characterEncoding=utf-8
jdbc.username=root
jdbc.password=123456

##DataSource Global Setting

#配置初始化大小、最小、最大
ds.initialSize=1
ds.minIdle=1
ds.maxActive=20

#配置获取连接等待超时的时间 
ds.maxWait=60000

#配置间隔多久才进行一次检测，检测需要关闭的空闲连接，单位是毫秒
ds.timeBetweenEvictionRunsMillis=60000

#配置一个连接在池中最小生存的时间，单位是毫秒
ds.minEvictableIdleTimeMillis=300000
