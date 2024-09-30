# AutoSense: Autonomous Vehicle & Pedestrian Detection

AutoSense is an innovative project focused on enhancing road safety and optimizing autonomous driving capabilities through advanced vehicle and pedestrian detection. Leveraging semantic segmentation with DeepLabV3 and a ResNet-50 backbone, AutoSense achieves a remarkable accuracy rate of 96%, ensuring reliable and efficient detection in various real-world scenarios.


website link: https://autosense.vercel.app/
---

## Features

- **Semantic Segmentation:** Classify road scenes into meaningful categories such as road, sidewalk, vehicles, and pedestrians.
  
- **Vehicle Detection:** Accurate identification and tracking of vehicles on the road, enhancing autonomous driving capabilities.
  
- **Pedestrian Detection:** Reliable detection of pedestrians near roads or crosswalks, reducing the risk of accidents.
  
- **Real-time Processing:** Efficient algorithms for real-time detection and segmentation with minimal latency.

  

<img width="1512" alt="Screenshot 2024-04-15 at 22 25 30" src="https://github.com/Sukanyasingh3/AutoSense/assets/113462236/1d7d8eb3-c894-4b3c-b273-75d17f7855b4">


---

## Benchmarking

Our model has been benchmarked against various state-of-the-art methods and achieved the following results:

| Model                  | Accuracy (%) | Detection Rate (%) | False Positives (%) |
|------------------------|--------------|--------------------|----------------------|
| DeepLabV3 + ResNet-50  | 96%          | 98%                | 2%                   |
| DeepLabV3 + ResNet-101 | 92%          | 95%                | 5%                   |
| MobileNet              | 88%          | 91%                | 9%                   |
| U-Net                  | 90%          | 93%                | 7%                   |
| Custom Model           | 93%          | 96%                | 4%                   |

---

## Original vs Segmented Images

Explore the difference between original images and their segmented versions processed by our DeepLabV3 with ResNet-50 model.

![image](https://github.com/Sukanyasingh3/AutoSense/assets/113462236/ca3623de-64ec-4693-a4b3-681ae086f907)

![image](https://github.com/Sukanyasingh3/AutoSense/assets/113462236/d77e87c6-ddf3-4d35-9db9-e70cb635044f)



---

### Prerequisites

- Python 3.x
- TensorFlow
- OpenCV


---

## Contributing

We welcome contributions from the community to enhance the features, improve accuracy, and expand the applications of AutoSense. Feel free to fork the repository and submit pull requests with your changes.

For major changes, please open an issue first to discuss the proposed changes and ensure they align with the project's goals.

---
