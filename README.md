# Wake
Android如何做到相互唤醒的一个示例代码。代码非常简单，通过广播和服务两种方式唤醒。通过PackageManager.queryIntentActivities（用Action过滤）来获取需要被启动的App包名称，然后启动目标App。被启动App只要集成项目里的lib即可被唤醒。代码仅供大家学习交流。
