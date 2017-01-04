# Android_Face_Verification-
face verification used in android which is simple to use with only three functions 

训练库及Demo下载地址：http://pan.baidu.com/s/1qYSyyrq

说明：
1、此版本为android版本人脸识别 ，其中FaceData文件夹为训练库，Android_Face_Verification为接口调用Demo，依赖的so库在libs文件夹中。
2、当前训练库124M，初步估计对算法进行升级训练可将训练库缩至50M以内。
3、相似度参考阈值：0.68，若返回值小于0，说明未能找到人脸或图像加载路径有误。
4、比对时间：1s-2s，不同性能的手机略有差别。
5、在被拍照人配合的情况下可取得较好效果，支持身份证芯片照和现场照比对，初步测试等错误率情况下识别率在93%左右。
6、初始化略慢，后期可解决。因只需初始化一次，基本不影响实际使用。
7、如有疑问，请联系zhangchuanfeng2008@163.com。
