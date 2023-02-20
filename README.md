### Nuts and Bolts classification and tracking
YOLOv7 is used for [given challange](https://stromavision.notion.site/Stroma-Machine-Learning-Engineer-Technical-Interview-19f4573982b64791b14121faddb2f176).

I will provide scripts and most part of the Google Colab project here, still, uploading dataset takes a while. Thus, you can directly run the project on Google Colab via provided [project link](https://drive.google.com/drive/folders/1Ia_qVfvHvH68PijbvDPcEZ1Lge7LauQc?usp=sharing).

```convert_data``` script generates YOLO format dataset by using provided COCO format dataset.

```YOLOv7_train``` script loads YOLOv7 repository and runs custom training for nuts and bolts.

```inference``` runs testing on test.mp4 and display an example output.

Current project tree is below. Dataset folders will be added here.

![image](https://user-images.githubusercontent.com/7215154/220185085-58c2c8a9-90e6-4c12-98f4-c1ff2035f134.png)
