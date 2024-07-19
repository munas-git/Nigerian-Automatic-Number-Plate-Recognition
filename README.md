# Nigerian-Automatic-Number-Plate-Recognition
Nigerian-Automatic-Number-Plate-Recognition (NANPR) is an advanced project designed to automatically detect and recognize vehicle number plates in Nigeria. Leveraging state-of-the-art computer vision and deep learning techniques, NANPR aims to streamline and enhance the efficiency of traffic management, law enforcement, and vehicle-related data collection in Nigeria.
## Project Overview
The NANPR system is built to accurately identify and read number plates from images and video streams in real-time. This system is tailored specifically for Nigerian number plates, taking into account their unique design and alphanumeric structure. The main features of the NANPR project include:
1. **Real-time number plate detection:** Quickly identifies number plates from live video feeds or pre-recorded footage.
2. **High accuracy recognition:** Utilizes advanced machine learning models to accurately recognize alphanumeric characters on the plates.
3. **Localization and extraction:** Precisely locates the number plate within an image and extracts the relevant region for recognition.
4. **Scalability:** Designed to handle large volumes of data, making it suitable for deployment in urban and rural areas alike.
## Tech Stack
The NANPR project employs a cutting-edge tech stack to ensure high performance and accuracy:
1. **YOLOvX (You Only Look Once - Version X)**: YOLOvX is the core component of the number plate detection system. It is a state-of-the-art object detection algorithm known for its speed and accuracy. YOLOvX processes images and video frames in real-time, making it ideal for dynamic environments like roadways and checkpoints.
2. **Python:** Python is used as the primary programming language for developing the NANPR system. Its extensive libraries and frameworks for computer vision and deep learning, such as OpenCV and TensorFlow, make it an excellent choice for this project.
3. **OpenCV:** OpenCV (Open Source Computer Vision Library) is utilized for image processing tasks, including pre-processing of input images, contour detection, and plate localization. OpenCV provides efficient tools to handle real-time image and video processing.
4. **PyTorch:** PyTorch serves as the backbone for training and deploying the neural networks used in the NANPR system. Its flexibility and scalability make it suitable for both the initial model development phase and large-scale deployment.
5. **Flask**: Flask is used to create a lightweight web server for the NANPR system. It handles HTTP requests, allowing users to upload images or video streams for processing and receive the recognition results.
6. **Docker:** Docker is employed to containerize the NANPR application, ensuring a consistent and reproducible environment across different deployment platforms. Docker facilitates easy scaling and management of the application in production.
7. **SQL/NoSQL Databases:** SQL/NoSQL Databases are used to store and manage the recognized number plate data, along with metadata such as timestamps and geographical locations. This facilitates efficient data retrieval and analysis for reporting and monitoring purposes.
## How It Works
1. **Image/Video Input**: The system takes input from cameras or uploaded files.
2. **Pre-Processing:** Images are pre-processed to enhance quality and isolate regions of interest.
3. **Detection:** YOLOvX detects the number plate within the image.
4. **Recognition:** The detected plate is cropped and passed to a recognition model to identify the alphanumeric characters.
5. **Output:** The recognized number plate data is displayed to the user or stored in the database for further use.
# Advanced Use Cases
The NANPR system offers several significant advantages that extend beyond simple number plate recognition:   

1. **Estate Monitoring**

    NANPR can significantly enhance security and convenience in residential estates by automating vehicle entry monitoring and access control.
    #### Vehicle Entry Monitoring and Access Control
      - ***Registered Vehicles Only:*** NANPR can be integrated with estate entry gates to allow access only to registered or permitted vehicles. This ensures that only authorized vehicles can enter the estate, enhancing security.
      - ***Automated Entry:*** When a registered vehicle approaches the gate, NANPR detects and recognizes the number plate, automatically granting access without the need for manual checks.
    #### Registering New Vehicles
      - ***Seamless Registration:*** New residents or existing residents with new vehicles can register their vehicles easily. Instead of visiting the estate office and spending hours, they simply take a picture of the vehicle and upload it along with other necessary documents via an online portal.
      - ***Automated Verification:*** The uploaded information is automatically processed and verified using the NANPR system, adding the new vehicle to the registered database.

2. **Commercial Parking Management:**

    NANPR can be deployed in commercial parking facilities to streamline operations and improve user experience.
    #### Efficient Parking Management
      - ***Automated Entry and Exit:*** Vehicles entering and exiting the parking facility are automatically detected and recorded, reducing the need for manual ticketing and payment systems.
      - ***Real-Time Availability:*** The system can provide real-time information on available parking spaces, enhancing the efficiency of space utilization.

3. **Toll Collection**

    NANPR can be used to automate toll collection on highways, reducing congestion and improving revenue collection.
    #### Automated Tolling
      - ***Cashless Payments:*** Vehicles passing through toll booths are detected and recognized by NANPR, automatically deducting the toll fee from a pre-registered account, enabling a seamless and cashless tolling experience.
      - ***Traffic Flow Improvement:*** Automated toll collection reduces waiting times and congestion at toll booths, improving traffic flow.

4. **Law Enforcement**

    NANPR can assist law enforcement agencies in various ways to enhance public safety and security.
      - ***Crime Prevention and Investigation:*** The system can instantly identify stolen vehicles from a database and alert law enforcement for immediate action.
      - ***Traffic Violations:*** NANPR can detect vehicles that violate traffic laws, such as speeding or running red lights, and automatically issue fines to the registered owners.

5. **Traffic Analysis and Planning**
    NANPR can provide valuable data for studying and improving traffic management.
    #### Traffic Pattern Analysis
      - ***Data Collection:*** By continuously monitoring vehicle movements, NANPR collects comprehensive data on traffic patterns, helping authorities understand peak travel times, congestion points, and overall traffic flow.
      - ***Infrastructure Development:*** Insights from NANPR data can inform the planning and development of road infrastructure, leading to more efficient traffic management and reduced congestion.

6. **Vehicle Classification**

    NANPR can classify vehicles based on their travel routes, aiding in traffic management and urban planning.
    #### Route-Based Classification
      - ***Travel Patterns:*** Vehicles can be classified based on their travel routes, helping in the identification of common travel patterns and potentially distinguishing between different types of road users, such as commercial vs. private vehicles.
      - ***Resource Allocation:*** This classification can assist in the allocation of resources, such as road maintenance and traffic enforcement, based on the types and volume of vehicles using specific routes.

NANPR is poised to revolutionize the way vehicle number plates are detected and recognized in Nigeria, providing a robust solution for various applications in traffic management, security, and beyond.
