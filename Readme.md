目前支持tomcat 7，**暂不支持tomcat 8**。因为RedisSessionManager.java中用到tomcat-catalina.jar（7.*）中的import org.apache.catalina.util.LifecycleSupport.