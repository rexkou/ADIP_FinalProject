## 題目1
正確標示出文件/書本封面

* [IMG_2335.JPG](#IMG_2335.JPG)

<br />

<a name="IMG_2335.JPG"></a> 
### 圖片 IMG_2335.JPG

[圖片1](/doc/ADIP_Final/nolight_lv1/IMG_2335.JPG)

處理順序:

>1. 需修改`Morphology_2-3.cpp`
>先做 Opening 在做 Closing 係數如檔名

>>Ex: IMG_2335-1_1_0_04.jpg(圖片名稱-處理次數_Operator_Element_Kernel size)

>2. 執行`test_findContours.cpp`
>使用 Canny 找出邊界

>>**Parameters**
>>- **threshold1** - 25
>>- **threshold2** - 53

<br />

