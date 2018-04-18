# Android Studio 翻译组项目

## 最新汉化包集
[release](https://github.com/AndroidStudioTranslate/Android-Studio-Translate/blob/master/jar/ "release")

## 翻译库规则
1. resources_en文件夹请勿随意修改(当前版本AI-141.2240497)
2. 文件夹命名方式'resources_'+'语言英文'，翻译请在相应语言文件夹内文件中进行修改，例如，英文为resources_en，中文为resources_zh
3. 目前，先翻译.properties后缀文件
4. 重点来了，也是翻译的关键，翻译后请转换成Unicode

## 工具
1. 工具地址：https://github.com/AndroidStudioTranslate/Android-Studio-Translate-Tool
2. 工具使用命令：java -jar TranslationAS.jar(新建lib文件夹,并复制相关的库到lib)
3. 工具说明：该工具直接选择resources_en.jar,点击获取jar包目录，勾选翻译，双击列表会自动翻译成中文，翻译完一个属性文件后点击保存属性值文件，翻译完后，请从新生成的jar包中将相应的属性文件在该库中进行修改。（工具会自动进行编码转换，使用netbeans开发）
4. jdk版本: 1.7+
