UIViewExt

UIView扩展 
直接获取view的方位属性
view.height
view.width


针对不同设备的坐标转换

define SCREEN_WIDTH [[UIScreen mainScreen] bounds].size.width
define SCREENPOINTRESIZE(float) ((float)/320.0f*SCREEN_WIDTH)//320.0f为设计图中屏幕的宽度
