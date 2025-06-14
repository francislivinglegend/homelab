# Francisco's Homelab

This is a simple project where I aim to learn more about homelabs by experimenting with various tools and configurations.

## 📌 Description

This project serves as a personal learning environment focused on building and managing homelab services. It includes a basic Flask service and Nginx Proxy Manager for reverse proxy and access control. The goal is to explore how different components interact within a self-hosted environment.

## 🚀 Getting Started

### 📦 Dependencies

* Flask
* Docker

### 🛠 Installation

Follow the steps below to set up the services.

#### ▶️ Start the Flask Service

Navigate to the `service_hello_world` directory and run the Python script to start the Flask web service.

```
cd service_hello_world
python3 script.py
```

#### ▶️ Start Nginx Proxy Manager

Go to the `Nginx_Proxy_Manager_NPM` directory and use Docker Compose to start the containers. This tool helps you easily manage Nginx reverse proxy configurations.

```
cd Nginx_Proxy_Manager_NPM
sudo docker-compose up -d
```

After launching, add the appropriate configurations as shown below (don't forget to enable ssl):
![Alt text](/documentation/image.png)

### 🌐 Access

- Access your Flask service via:  
  [https://franciscoamaro.xyz/](https://franciscoamaro.xyz/)  
  or  
  [http://franciscoamaro.xyz/](http://franciscoamaro.xyz/)

- Access the Nginx Proxy Manager dashboard at:  
  [http://localhost:81/](http://localhost:81/)

## 👤 Author

**Francisco Amaro**  
Feel free to reach out or contribute to the project!
