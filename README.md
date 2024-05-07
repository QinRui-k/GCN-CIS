# GCN-CIS

## ✈️ Highlights
🔥 A novel segmentation network named GCN-CIS, which is enhanced with a Prior Boundary Attention Module.  
🔥 A Geometrically Constrained Loss function tailored specifically to the unique morphological characteristics of the optic cup and disc.  
🔥 GCN-CIS achieves outstanding performance on our self-constructed Glaucoma Screening Dataset and three other public datasets.  
🔥 A Website based on this network can assist doctors in diagnosis. 

## 👉 Framework
<img src="https://github.com/QinRui-k/GCN-CIS/files/15231902/Architecture.pdf">
Architecture of GCN-CIS. The network incorporates a multi-scale input strategy to capture details across various resolutions. It utilizes a series of encoders for extracting features at multiple levels of abstraction. Subsequently, the deep feature maps undergo refinement through the Prior Boundary Attention Module (PBAM), which significantly enhances edge delineation. These refined features are then integrated into the decoder, thereby improving the representation of the optic boundaries. Notably, the final segmentation map is crucial for calculating the signed distance and assessing the ISNT metrics of the image, with an integrated loss function that sharpens the segmentation accuracy.

https://github.com/QinRui-k/GCN-CIS/assets/139854014/ae24c9a0-af45-49ce-89a2-79f4228798c3
