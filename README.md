# **SafetyGear AI: PPE Detection using YOLO**
🚀 **Automated Safety Gear Detection using YOLOv8** 

## **Overview**
SafetyGear AI is a deep-learning-based solution designed to **detect personal protective equipment (PPE)** such as **helmets, gloves, safety vests, and more** using the **YOLOv8 object detection model**. This project is built to enhance workplace safety by ensuring compliance with safety regulations through real-time detection.

## **Features**
✅ **Real-time PPE Detection**: Identifies helmets, gloves, vests, and other safety gear.  
✅ **YOLOv8-powered AI**: Uses state-of-the-art object detection for accuracy.  
✅ **Fast & Lightweight**: Runs efficiently on CPUs and GPUs.  
✅ **Customizable**: Can be trained on custom PPE datasets for specific industries.  

## **Installation**
Ensure you have **Python 3.7+** installed, then run:
```bash
pip install ultralytics opencv-python numpy
```

## **Usage**
1. **Import YOLO and Required Libraries**
   ```python
   from ultralytics import YOLO
   from IPython.display import display, Image
   ```

2. **Load the Pre-trained Model**
   ```python
   model = YOLO("yolov8n.pt")  # Load pre-trained YOLOv8 model
   ```

3. **Run Detection on an Image**
   ```python
   results = model("safety_gear_sample.jpg", save=True)  # Detect PPE in an image
   ```

4. **Display the Output**
   ```python
   display(Image("runs/detect/exp/safety_gear_sample.jpg"))
   ```

## **Future Enhancements**
- ✅ **Train on a Custom PPE Dataset**  
- ✅ **Deploy as a Web Application**  
- ✅ **Integrate with CCTV for Workplace Monitoring**  
