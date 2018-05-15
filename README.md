# verifyCode 图片验证码类  基于THINKPHP3 gd库渲染，兼容手机APP和web
设计思路： 手机使用终端唯一识别码 device_code进行验证取值，通过memecache进行保存值，web使用session记录。
