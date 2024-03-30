# Chest-Disease-Classification-from-Chest-CT-Scan-Image

Project Overview: I have developed a state-of-the-art system for classifying Chest Diseases from Chest CT Scan Images using deep learning. This solution leverages cutting-edge technologies and tools to provide accurate and efficient diagnoses, aiding in the early detection and treatment of chest diseases.

Technologies Used for CI/CD: To ensure seamless integration and continuous delivery of the project, I utilized a robust CI/CD pipeline. The following technologies played a pivotal role:

1️⃣ Jenkins: Our reliable automation server, Jenkins, enabled us to automate our project's building, testing, and deployment, ensuring efficiency and reliability.

2️⃣ GitHub: As the foundation of our version control system, GitHub provided us with collaborative features, enabling seamless teamwork and efficient code management.

3️⃣ AWS ECR: Amazon Elastic Container Registry (ECR) facilitated our Docker container images' secure storage and management, ensuring easy access and scalability.

4️⃣ AWS ElastiCache: I leveraged AWS ElastiCache to enhance the application's performance and scalability by caching frequently accessed data, reducing latency, and improving response times.

5️⃣ AWS EC2: Amazon EC2 served as the backbone of our project, providing scalable and reliable computing capacity in the cloud. It allowed us to deploy and run applications quickly.

Development Technologies: During the development phase, we utilized a robust set of technologies and tools, including:

✅ Python: The core programming language for deep learning projects, Python, offers flexibility, robustness, and an extensive library ecosystem.

✅ Jupyter Notebook: Jupyter Notebook provided an interactive and exploratory development environment, allowing us to prototype and experiment efficiently.

✅ Visual Studio Code: As our preferred integrated development environment (IDE), It enhanced our coding experience with its rich features and seamless integration with other tools.

✅ MLflow: MLflow was our reliable platform for managing the machine learning lifecycle. It enabled us to track experiments, package code, and deploy models easily.

✅ DVC: Data Version Control (DVC) helped us manage large datasets efficiently by providing a Git-like interface for data versioning and collaboration.

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 




## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

## How to run?

```bash
conda create -n chest python=3.8 -y
```

```bash
conda activate chest
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```

### Mlflow dagshub connection uri

> Connect your repository on github with dagshub
> Click on the remote button 
> copy and export the credentials given on experiments tab to your system
> once everything is executed , on experiments tab itself, you can see "go to mlflow UI",click on it for visualization

```bash
MLFLOW_TRACKING_URI= get from dagshub
MLFLOW_TRACKING_USERNAME= get from dagshub
MLFLOW_TRACKING_PASSWORD= get from dagshub

python script.py
```


### RUN from bash terminal

```bash
export MLFLOW_TRACKING_URI=get from dagshub

export MLFLOW_TRACKING_USERNAME=get from dagshub

export MLFLOW_TRACKING_PASSWORD=get from dagshub


```



### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag