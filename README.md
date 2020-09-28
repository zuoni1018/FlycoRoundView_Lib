###说明

https://jitpack.io/

该库原文地址 https://github.com/H07000223/FlycoRoundView

#FlycoRoundView

一个扩展原生控件支持圆角矩形框背景的库,可以减少相关shape资源文件使用.

##Gradle

```groovy
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

	dependencies {
	    implementation 'com.github.zuoni1018:FlycoRoundView_Lib:1.1.5'
	}
```

###Attributes

|name|format|description|版本号|
|------------------|------------------|------------------|------------------|
| rv_backgroundColor | color | background color|1.1.5|
| rv_backgroundPressColor | color | background press color|1.1.5|
| rv_cornerRadius | dimension | background rectangle corner radius,unit dp|1.1.5|
| rv_strokeWidth | dimension | background rectangle stroke width,unit dp|1.1.5|
| rv_strokeColor | color |background rectangle stroke color|1.1.5|
| rv_strokePressColor | color |background rectangle stroke press color|1.1.5|
| rv_textPressColor | color |text press color|1.1.5|
| rv_isRadiusHalfHeight | boolean | corner radius is half of height|1.1.5|
| rv_isWidthHeightEqual | boolean | width and height is the same size which is the max value of them|1.1.5|
| rv_cornerRadius_TL | dimension | corner radius top left,unit dp|1.1.5|
| rv_cornerRadius_TR | dimension | corner radius top right,unit dp|1.1.5|
| rv_cornerRadius_BL | dimension | corner radius bottom left,unit dp|1.1.5|
| rv_cornerRadius_BR | dimension | corner radius bottom right,unit dp|1.1.5|
| rv_isRippleEnable | boolean | is ripple effect enable for Api21+ |1.1.5|
| rv_isDrawOutParent | boolean | 对超出父布局的内容是否裁剪 (默认true  允许绘制到父布局外边) |1.1.5|

##更新日志

##2020-09-28
新增属性
rv_isDrawOutParent --> 对超出父布局的内容是否裁剪






