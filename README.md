
MT_Small_Dataset
================
Breast Cancer's Ultrasound Images Dataset ( Segmentation and Classification )
==============================================================================
This Small Dataset of 1200 images have been designed due to working steps of our paper [2]:
"Efficient Automatic Semantic Segmentation of Breast Tumors in Ultrasound Images Based on Combining Fuzzy Logic and Deep Learning".
----------------------------------------------------------------------------------------------------------------------------
First: a collection of 400 BUS with tumor images and their 400 ground truth images has been selected from [1],
as follow: 

200 images for BUS with a benign breast cancer and their 200 ground truth images.
200 images for BUS with a malignant breast cancer and their 200 ground truth images. 


(((  All of the dataset in [1] has been collected and processed, in 2018,
	for BUS images from a variety of women in ages between 25 and 75 years old,
	by LOGIQ E9 ultrasound and LOGIQ E9 Agile ultrasound system,
	at Baheya Hospital for Early Detection & Treatment of Women's Cancer, Cairo, Egypt  [1] )))


The 800 images taken from [1] has been proceesed and utilized in our paper [2] as follow:
-----------------------------------------------------------------------------------------

1- The 400 BUS images have been resized to 128 by 128 by 3
2- The 400 ground truth images have been processed so that:
the black background (represents normal tissue) has a value of one “1” and the tumor’s region has a value of two “2”, 
on a grayscale [0-255], and resized to 128 by 128 
3- The 400 BUS with tumor images has been enhanced by a Fuzzy method for contrast enhancement (explained in pur paper [2])
producing another 400 enhanced images with size 128 by 128 by 3.

Then MT_Small_Dataset contains 1200 images divided as:
1-	200 BUS images (size: 128 by 128 by 3) with a benign cancer (Original_Benign).
2-	200 Fuzzy-enhanced BUS’ images (size: 128 by 128 by 3) with a benign cancer (Fuzzy_Benign).
3-	200 ground truth images (size: 128 by 128) for benign cancer (Ground_Truth_Benign).
4-	200 BUS images (size: 128 by 128 by 3) with a malignant cancer (Original_Malignant).
5-	200 Fuzzy-enhanced BUS’ images (size: 128 by 128 by 3) with a malignant cancer (Fuzzy_Malignant).
6-	200 ground truth images (size: 128 by 128) for malignant cancer (Ground_Truth_Malignant).
All the 1200 images are arranged each different 200 images in one folder. 
The first 600 images (Original_Benign, Fuzzy_Benign, and Ground_Truth_Benign) are labeled for the same 200 benign BUS images 
and saved in one folder (Benign). 
The last 600 images (Original_Mlignant, Fuzzy_ Mlignant, and Ground_Truth_ Mlignant) are labeled for the same 200 mlignant BUS images
and saved in one folder (Malignant). 



---------------------------------------------------------------------
Any use of our dataset ((MT_Small_Dataset)), Kindly Cite [1] and [2]: 
=====================================================================

[1]	W. Al-Dhabyani, M. Gomaa, H. Khaled, A. Fahmy, "Dataset of breast ultrasound images", Data in brief, 28, 2020, 104863 
	DOI: https://doi.org/10.1016/j.dib.2019.104863 


[2]	Samir M. Badawy, Abd El-Naser A. Mohamed, Alaa A. Hefnawy, Hassan E. Zidan, Mohammed T. GadAllah, and Ghada M. El-Banby, 
	"Efficient Automatic Semantic Segmentation of Breast Tumors in Ultrasound Images Based on Combining Fuzzy Logic and Deep Learning", 
	Under Publishing, 2021


