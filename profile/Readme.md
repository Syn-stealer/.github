

# ๐ฌ Syn-stealer Hackathon Project

**๋ชจ๋์ ์ฐ๊ตฌ์ AIFFEL**
<br>```๋ณธ ํ๋ก์ ํธ๋ ๊ธฐ์กด์ SIM2REAL์ด๋ผ๋ ๊ธฐ์์ด ํจ๊ป ์ฐธ์ฌํ์ฌ ์ ์ํ ๊ณผ์ ์ฃผ์ ๋ก ์งํ๋์ด์ผ ํ์ผ๋, ํ์ ๋ ์๊ฐ๊ณผ ๊ธฐ์ ์ธก์ ํ์กฐ ๋ฑ์ ๋ฌธ์ ๋ฅผ ๊ณ ๋ คํ์ฌ ์ฐ๊ตฌ ์ฃผ์ ์ ๋ฐฉํฅ์ ์๋กญ๊ฒ ํ์์์ ๋ฏธ๋ฆฌ ์๋ฆฝ๋๋ค.```
<br>

## ๐ฆ ํ ์๊ฐ
<img src="https://user-images.githubusercontent.com/96896676/166176230-16a667b6-6d43-47c3-9337-eae2c504a9d9.png" width="500">

๐ ์ฃผ์ฐ์ ์๋์ง๋ง ๊ด๊ฐ๋ค์๊ฒ ์ฃผ์ฐ์ฒ๋ผ ์ฃผ๋ชฉ์ ๋ฐ๋ **์  ์คํธ๋ฌ(Scene stealer)** ์ฒ๋ผ<br>์ค์  ๋ฐ์ดํฐ๋งํผ์ด๋ ์ข์ ์ฑ๋ฅ์ ๋ณด์ฌ์ฃผ์ด ์ฃผ๋ชฉ์ ๋ฐ์ ์ ์๋ **ํฉ์ฑ ๋ฐ์ดํฐ(Synthetic data)** ์ ๊ดํ ์ฐ๊ตฌ๋ฅผ ์งํํ๊ณ ์ ํฉ๋๋ค.
<br>
<br>

## ๐ฅ ๊ตฌ์ฑ์
|์ง์ฑ|์ด๋ฆ|์ญํ |
|:--:|:--:|:--:|
|ํ์ฅ|๋ฌธ๋์ข|ํ๋ก์ ํธ ๋ฆฌ๋ฉ, ๋ผ๋ฌธ ์์น, ๋ฐ์ดํฐ ์ ์ฒ๋ฆฌ ๋ฐ ๊ฐ๊ณต, ๋ชจ๋ธ ๋ฆฌ์์น ๋ฐ ํ์ต|
|ํ์|๊ถ์ธํ|๋ผ๋ฌธ ์์น, ๋ฐ์ดํฐ ์์ง, ๋ชจ๋ธ ๋ฆฌ์์น ๋ฐ ํ์ต|
|ํ์|๊น๋ด๊ฒฝ|๋ผ๋ฌธ ์์น, ๋ฐ์ดํฐ ๋ถ์ ๋ฐ ๊ฐ๊ณต, ๋ชจ๋ธ ๋ฆฌ์์น ๋ฐ ํ์ต|


<br><br>
## ๐ป ํ๋ก์ ํธ ๊ฐ์
### ๐น ๊ธฐ๊ฐ
- 2022.04.25~2022.06.09

### ๐น ๋ด์ฉ
ํฉ์ฑ๋ฐ์ดํฐ๊ฐ ๋ชจ๋ธ ํ์ต๊ณผ ์ฑ๋ฅ์ ์ด๋ค ์ํฅ์ ๋ผ์น๋์ง ์์๋ณด๊ธฐ ์ํด<br>
Object Detection ๋ชจ๋ธ ์ค ๋ํ์ ์ธ ์ธ ๊ฐ์ง ๋ชจ๋ธ์ธ YOLOv5, RetinaNet, EfficientDet์ ์ฌ์ฉํ์ฌ <br>์ค์  ๋ฐ์ดํฐ์ ํฉ์ฑ ๋ฐ์ดํฐ์ ์ฌ๋ฌ ์กฐํฉ์ ํ์ต์ํค๊ณ  ๋ชจ๋ธ๋ณ, ๋ฐ์ดํฐ์ ๋ณ ๊ฒ์ถ ์ฑ๋ฅ์ ๋น๊ต



### ๐น ๋ฐ์ดํฐ์
- [KITTI](http://www.cvlibs.net/datasets/kitti/)
- [VKITTI2](https://europe.naverlabs.com/research/computer-vision/proxy-virtual-worlds-vkitti-2/)
- [AI Hub ์์จ์ฃผํ Dataset](https://aihub.or.kr/aidata/8007)

<br>

## โ๏ธ ์งํ ๊ณผ์ 
์ถํ ์ถ๊ฐ ์์ 

<br><br>
## ๐ References
|์ ๋ชฉ|๋ถ๋ฅ|๋น๊ณ |
|:--|:--:|--|
|[Training Deep Networks with Synthetic Data](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/3a5f1dc2-4ac7-4ab8-ac30-2a0e3673ede7/Training_Deep_Networks_with_Synthetic_Data.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220502%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220502T023835Z&X-Amz-Expires=86400&X-Amz-Signature=931102fc38d0be955c1c82015141f794bbeb6182d8da8c0beb288d51822a38c5&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Training%2520Deep%2520Networks%2520with%2520Synthetic%2520Data.pdf%22&x-id=GetObject)|๋ผ๋ฌธ||
|[์์จ์ฃผํ ์ฐจ๋์ ํ์ต ๋ฐ์ดํฐ ์๋ ์์ฑ ์์คํ ๊ฐ๋ฐ](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/d05d19ec-9059-478b-b494-21b7dfc1a8f4/MoraiSim.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220502%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220502T024007Z&X-Amz-Expires=86400&X-Amz-Signature=8dff1fadb2049a797743040bbcba52d9c41389700b8d6d089ed6af1a8000c8e2&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22MoraiSim.pdf%22&x-id=GetObject)|๋ผ๋ฌธ||
|[Realistic Blur Synthesis for Learning Image Deblurring](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/a1fa4ac3-3053-4f70-9644-9109d2ac596a/Realistic_Blur_Synthesis_for_Learning_Image_Deblurring.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220502%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220502T024047Z&X-Amz-Expires=86400&X-Amz-Signature=b17b4e44dbba6ecdd052db8b82e68d97bb86efd9140875a79752df931fd06903&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Realistic%2520Blur%2520Synthesis%2520for%2520Learning%2520Image%2520Deblurring.pdf%22&x-id=GetObject)|๋ผ๋ฌธ||
|[Stereo R-CNN based 3D Object Detection for Autonomous Driving](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/a69707ab-d159-420b-8775-94884805b58f/Stereo_R-CNN_based_3D_Object_Detection_for_Autonomous_Driving.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220502%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220502T024124Z&X-Amz-Expires=86400&X-Amz-Signature=b1eab9761497a0c3ae9523ffaa0d4d606c9055a18abef043339269e4d21c047d&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Stereo%2520R-CNN%2520based%25203D%2520Object%2520Detection%2520for%2520Autonomous%2520Driving.pdf%22&x-id=GetObject)|๋ผ๋ฌธ||
|[S2R-DepthNet: Learning a Generalizable Depth-specific Structural Representation](https://arxiv.org/pdf/2104.00877v2.pdf)|๋ผ๋ฌธ||
