weixin4j  | ΢�źͶ�������SDK
===============

  
���°汾�� 2.0.0���������ڣ�2025-02-11��

[![AUR](https://img.shields.io/badge/license-Apache%20License%202.0-blue.svg)](https://github.com/zhangdaiscott/jeecg-boot/blob/master/LICENSE)
[![](https://img.shields.io/badge/Author-�����������-orange.svg)](http://jeecg.com/aboutusIndex)
[![](https://img.shields.io/badge/Blog-�ٷ�����-blue.svg)](https://jeecg.blog.csdn.net)
[![](https://img.shields.io/badge/version-2.0.0-brightgreen.svg)](https://github.com/zhangdaiscott/jeecg-boot)
[![GitHub stars](https://img.shields.io/github/stars/zhangdaiscott/jeecg-boot.svg?style=social&label=Stars)](https://github.com/zhangdaiscott/jeecg-boot)
[![GitHub forks](https://img.shields.io/github/forks/zhangdaiscott/jeecg-boot.svg?style=social&label=Fork)](https://github.com/zhangdaiscott/jeecg-boot)






WeiXin4j ��Ŀ˵��
-----------------------------------

΢�źͶ�������JAVA��SDK,��Ҫ�ṩ΢�š���ҵ΢�š�������JAVA��װ�����ͼ����Ѷȣ���API���
֧��΢�Ź��ںš�΢����ҵ�š�΢��С���򡢶�����֧��������ź�΢��SDK������Ի����������ٵ�ɵ�ϻ��Ľ���΢�ſ�����������֧������΢��������

* 	���������� www.jeecg.com
* 	����bug������ [github��issue](https://github.com/jeecgboot/weixin4j/issues)

weixin4j ���ټ���
-----------------------------------
    ��pom.xml ��� weixin4j ����
    <dependency>
		<groupId>org.jeecgframework</groupId>
		<artifactId>weixin4j</artifactId>
		<version>2.0.0</version>
	</dependency>
	



��Ԫ����API
-----------------------------------

    public static void main(String[] args) {
		try {
			String accesstoken = "?";
			String user_openid = "o8QKAuAyDxxfyuBZ9ugSMR4SR5XQ";
			JwUserAPI.getWxuser(accesstoken, user_openid);
		} catch (WexinReqException e) {
			// TODO Auto-generated catch block
			e.printStackTrace();
		}
		
	}