cmake_minimum_required(VERSION 3.10)
project(src)

find_package(OpenCV REQUIRED)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(CMAKE_CXX_STANDARD 11)
add_executable(src
        【10】第十章/【85】cornerHarris函数用法示例/85_cornerHarris函数用法示例/85_cornerHarris.cpp
        【10】第十章/【86】Harris角点检测/86_Harris角点检测/86_cornerHarris.cpp
        【10】第十章/【87】Shi-Tomasi角点检测/87_Shi-Tomasi角点检测/87_goodFeaturesToTrack.cpp
        【10】第十章/【88】亚像素级角点检测/88_亚像素级角点检测/88_cornerSubPix.cpp
        【1】第一章/【1】OpenCV开发环境的配置/1_HelloOpenCV/1_HelloOpenCV.cpp
        【1】第一章/【2】图像显示/2_图像显示/2_ShowImage.cpp
        【1】第一章/【3】图像腐蚀/3_图像腐蚀/3_ImageErode.cpp
        【1】第一章/【4】blur图像模糊/4_blur图像模糊/4_BlurImage.cpp
        【1】第一章/【5】canny边缘检测/5_canny边缘检测/5_Canny.cpp
        【1】第一章/【6】播放视频/6_播放视频/6_PlayVideo.cpp
        【1】第一章/【7】调用摄像头/7_调用摄像头/7_UseCamera.cpp
        【2】第二章/【10】点追踪/10_点追踪/10_lkdemo.cpp
        【2】第二章/【11】人脸识别/11_人脸识别/11_ObjectDetection.cpp
        【2】第二章/【12】支持向量机之SVM引导/12_支持向量机之SVM引导/12_SupportVectorMachines.cpp
        【2】第二章/【13】支持向量机之处理线性不可分数据/13_支持向量机之处理线性不可分数据/13_SVMForNonLinearlySeparableData.cpp
        【2】第二章/【14】printf函数用法示例/14_printf函数用法示例/14_Use_printf.cpp
        【2】第二章/【8】彩色目标跟踪/8_彩色目标跟踪/8_CamShiftDemo.cpp
        【2】第二章/【9】用光流法进行运动目标检测/9_用光流法进行运动目标检测/9_OpticalFlow.cpp
        【3】第三章/【15】利用imwrite生成透明png图像/15_利用imwrite生成透明png图像/15_Use_imwrite.cpp
        【3】第三章/【16】图像的载入，显示和输出/16_图像的载入，显示和输出/16_LoadShowOutputImage.cpp
        【3】第三章/【17】为程序界面添加滑动条/17_为程序界面添加滑动条/17_CreateTrackbar.cpp
        【3】第三章/【18】基本鼠标操作/18_基本鼠标操作/18_UseMouse.cpp
        【4】第四章/【19】基础图像容器Mat/19_基础图像容器Mat/19_UseMat.cpp
        【4】第四章/【20】用OpenCV进行基本绘图/20_用OpenCV进行基本绘图/20_DrawImage.cpp
        【5】第五章/【21】用指针访问像素/21_用指针访问像素/21_UsePointerAccessPixel.cpp
        【5】第五章/【22】用迭代器访问像素/22_用迭代器访问像素/22_UseIteratorAccessPixel.cpp
        【5】第五章/【23】用动态地址计算配合at访问像素/23_用动态地址计算配合at访问像素/23_UseAtAccessPixel.cpp
        【5】第五章/【24】遍历图像像素的14种方法/24_遍历图像像素的14种方法/24_14WaysToAccessPixel.cpp
        【5】第五章/【25】初级图像混合/25_初级图像混合/25_ImageBlending.cpp
        【5】第五章/【26】多通道图像混合/26_多通道图像混合/26_MultiChannelImageBlending.cpp
        【5】第五章/【27】图像对比度、亮度值调整/27_图像对比度、亮度值调整/27_ChangeContrastAndBright.cpp
        【5】第五章/【28】离散傅里叶变换/28_离散傅里叶变换/28_DFT.cpp
        【5】第五章/【29】XML和YAML文件的写入/29_XML和YAMl文件的写入/29_Write_XML_and_YAML_File.cpp
        【5】第五章/【30】XML和YAML文件的读取/30_XML和YAMl文件的读取/30_Read_XML_and_YAML_File.cpp
        【6】第六章/【31】boxFilter函数用法示例/31_方框滤波boxFilter函数的使用/31_boxFilter.cpp
        【6】第六章/【32】blur函数用法示例/32_均值滤波blur函数的使用/32_blur.cpp
        【6】第六章/【33】GaussianBlur函数用法示例/33_高斯模糊GaussianBlur函数的用法/33_GaussianBlur.cpp
        【6】第六章/【34】线性图像滤波综合示例/34_线性图像滤波综合示例/34_LinearImageFilter.cpp
        【6】第六章/【35】MedianBlur函数用法示例/35_MedianBlur函数用法示例/35_medianBlur.cpp
        【6】第六章/【36】bilateralFilter函数用法示例/36_双边滤波bilateralFilter函数使用示例/36_bilateralFilter.cpp
        【6】第六章/【37】图像滤波综合示例/37_图像滤波综合示例/37_ImageFiltering.cpp
        【6】第六章/【38】dilate函数用法示例/38_图像膨胀dilate函数用法示例/38_dilate.cpp
        【6】第六章/【39】erode函数用法示例/39_图像腐蚀erode函数用法示例/39_erode.cpp
        【6】第六章/【40】图像腐蚀与膨胀综合示例/40_图像腐蚀与膨胀综合示例/40_dilate_And_erode.cpp
        【6】第六章/【41】用morphologyEx进行图像膨胀/41_用morphologyEx进行图像膨胀/41_DilationEX.cpp
        【6】第六章/【42】用morphologyEx进行图像腐蚀/42_用morphologyEx进行图像腐蚀/ErodeEX.cpp
        【6】第六章/【43】用morphologyEx进行图像开运算/43_用morphologyEx进行图像开运算/43_Opening.cpp
        【6】第六章/【44】用morphologyEx进行图像闭运算/44_用morphologyEx进行图像闭运算/44_Closing.cpp
        【6】第六章/【45】用morphologyEx进行形态学梯度运算/45_用morphologyEx进行形态学梯度运算/45_Gradient.cpp
        【6】第六章/【46】用morphologyEx进行形态学顶帽运算/46_用morphologyEx进行形态学顶帽运算/46_TopHat.cpp
        【6】第六章/【47】用morphologyEx进行形态学黑帽运算/47_用morphologyEx进行形态学黑帽运算/47_BlackHat.cpp
        【6】第六章/【48】形态学图像处理综合示例/48_形态学图像处理综合示例/48_Morphology.cpp
        【6】第六章/【49】floodFill函数用法示例/49_漫水填充floodFill函数用法示例/49_floodFill.cpp
        【6】第六章/【50】漫水填充算法综合示例/50_漫水填充算法综合示例/50_floodFill2.cpp
        【6】第六章/【51】resize函数用法示例/51_resize函数用法示例/resize.cpp
        【6】第六章/【52】pyrUp函数用法示例/52_pyrUp函数用法示例/52_pyrUp.cpp
        【6】第六章/【53】pyrDown函数用法示例/53_pyrDown函数用法示例/53_pyrDown.cpp
        【6】第六章/【54】图像金字塔和resize综合示例/54_图像金字塔和resize综合示例/54_PyrAndResize.cpp
        【6】第六章/【55】基本阈值操作/55_基本阈值操作/55_threshold.cpp
        【7】第七章/【56】canny函数用法示例/56_canny函数用法示例/56_canny.cpp
        【7】第七章/【57】sobel函数用法示例/57_sobel函数用法示例/57_sobel.cpp
        【7】第七章/【58】Laplacian函数用法示例/58_Laplacian函数用法示例/58_Laplacian.cpp
        【7】第七章/【59】Scharr函数用法示例/59_Scharr函数用法示例/59_Scharr.cpp
        【7】第七章/【60】边缘检测综合示例/60_边缘检测综合示例/EdgeDetection.cpp
        【7】第七章/【61】HoughLines函数用法示例/61_HoughLines函数用法示例/61_HoughLines.cpp
        【7】第七章/【62】HoughLinesP函数用法示例/62_HoughLinesP函数用法示例/62_HoughLinesP.cpp
        【7】第七章/【63】HoughCircles函数用法示例/63_HoughCircles函数用法示例/63_HoughCircles.cpp
        【7】第七章/【64】霍夫线变换综合示例/64_霍夫线变换综合示例/64_HoughLines.cpp
        【7】第七章/【65】remap函数用法示例/65_remap函数用法示例/65_remap.cpp
        【7】第七章/【66】实现多种重映射综合示例/66_实现多种重映射综合示例/66_remap2.cpp
        【7】第七章/【67】仿射变换综合示例/67_仿射变换综合示例/67_AffineTransform.cpp
        【7】第七章/【68】直方图均衡化/68_直方图均衡化/68_equalizeHist.cpp
        【8】第八章/【69】轮廓查找基础/69_基础轮廓查找/69_findContours.cpp
        【8】第八章/【70】查找并绘制轮廓综合示例/70_查找并绘制轮廓综合示例/70_FindAndDrawContours.cpp
        【8】第八章/【71】凸包检测基础/71_凸包检测基础/71_convexHull.cpp
        【8】第八章/【72】寻找和绘制物体的凸包/72_寻找和绘制物体的凸包/72_convexHull2.cpp
        【8】第八章/【73】创建包围轮廓的矩形边界/73_创建包围轮廓的矩形边界/73_minAreaRect.cpp
        【8】第八章/【74】创建包围轮廓的圆形边界/74_创建包围轮廓的圆形边界/74_minEnclosingCircle.cpp
        【8】第八章/【75】创建包围轮廓的矩形和圆形边界框/75_创建包围轮廓的矩形和圆形边界框/75_approxPolyDP.cpp
        【8】第八章/【76】_查找和绘制图片轮廓矩/76_查找和绘制图片轮廓矩/76_ContourMoment.cpp
        【8】第八章/【77】分水岭算法/77_分水岭算法/77_watershed.cpp
        【8】第八章/【78】图像修补/78_图像修补/78_inpaint.cpp
        【9】第九章/【79】H-S二维直方图的绘制/79_H-S二维直方图的绘制/79_H-S-Histogram.cpp
        【9】第九章/【80】一维直方图的绘制/80_一维直方图的绘制/80_Histogram2.cpp
        【9】第九章/【81】RGB三色直方图的绘制/81_RGB三色直方图的绘制/81_histogram3.cpp
        【9】第九章/【82】直方图对比/82_直方图对比/82_compareHist.cpp
        【9】第九章/【83】反向投影/83_反向投影/83_calcBackProject.cpp
        【9】第九章/【84】模板匹配/84_模板匹配/84_matchTemplate.cpp)

include_directories(${OpenCV_INCLUDE_DIRS})
target_link_libraries(src ${OpenCV_LIBS})