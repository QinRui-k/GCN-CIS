# GCN-CIS

## ✈️ Highlights
🔥 A novel segmentation network named GCN-CIS, which is enhanced with a Prior Boundary Attention Module.  
🔥 A Geometrically Constrained Loss function tailored specifically to the unique morphological characteristics of the optic cup and disc.  
🔥 GCN-CIS achieves outstanding performance on our self-constructed Glaucoma Screening Dataset and three other public datasets.  
🔥 A Website based on this network can assist doctors in diagnosis. 

## 👉 Framework
<img src="https://github.com/QinRui-k/GCN-CIS/assets/139854014/4e46819a-3274-4548-aca7-2f28ac8159a4">
Architecture of GCN-CIS. The network incorporates a multi-scale input strategy to capture details across various resolutions. It utilizes a series of encoders for extracting features at multiple levels of abstraction. Subsequently, the deep feature maps undergo refinement through the Prior Boundary Attention Module (PBAM), which significantly enhances edge delineation. These refined features are then integrated into the decoder, thereby improving the representation of the optic boundaries. Notably, the final segmentation map is crucial for calculating the signed distance and assessing the ISNT metrics of the image, with an integrated loss function that sharpens the segmentation accuracy.

## 👉 Evaluation  
<img src="https://github.com/QinRui-k/GCN-CIS/assets/139854014/764d7de2-c741-4f5a-9f45-52cb7446ab71">
<p align="center">  
Visulization Results
</p>  


<img src="https://github.com/QinRui-k/GCN-CIS/assets/139854014/ac25f5e3-78ef-4d43-a0d5-2522048fb9ee">   
<p align="center">  
Quantitative Results 
</p> 

## 👉 Train
```
cd ./GCN-CIS
train.py
```

## 👉 Test
```
cd ./GCN-CIS
test.py
```

## 🎥 Demo
https://github.com/QinRui-k/GCN-CIS/assets/139854014/ae24c9a0-af45-49ce-89a2-79f4228798c3

## 🤝 Acknowledgement
* We thank all medical workers and dataset owners for making public datasets available to the community.
