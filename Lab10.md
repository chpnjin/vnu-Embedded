<h1>嵌入式系統 - 實作10: AI最經典火紅的應用之人臉偵測實作</h1>

![圖片](https://user-images.githubusercontent.com/16370565/144730818-1b4daede-3b0d-444e-907b-9c4d2e8c0a75.png)

![圖片](https://user-images.githubusercontent.com/16370565/144730827-8844a96e-f592-4402-babc-be39863cebc7.png)

![圖片](https://user-images.githubusercontent.com/16370565/144731044-8963395b-91c1-4135-a267-3878456f1264.png)

![圖片](https://user-images.githubusercontent.com/16370565/144731059-d9a38d23-1e94-429f-89a0-d6ac60be028c.png)


<h3>程式碼</h3>

````python
# 000
print('hello AI')

"""##記得要使用GPU (編輯 >> 筆記本設定 >> GPU)"""

# 001 將我們的Google Drive連結上Virtual Machine
from google.colab import drive
drive.mount('/content/drive')

# 002 Check the current working directory
%cd '/content/drive/MyDrive/ES2021/Image'

"""## Topic 1: 人臉數據取得"""

#101 虛擬人造人臉
from IPython.display import Image
print('這都是虛擬人造人臉')
Image('Image/face31.jpg',width=400)

"""## Lab 1"""

"""### Lab1: 讓我們下載2張自選的虛擬人造臉 (VF04.jpg, VF05.jpg), 並且上傳到我們的Google Drive, 並且用以上的指令來顯示出來"""
#102 Lab: 自行下載二張來試試 face generator, https://thispersondoesnotexist.com/

#虛擬人造人臉1
Image('VF04.jpg',width=200)

# 103 虛擬人造人臉2
Image('VF05.jpg',width=200)
````

