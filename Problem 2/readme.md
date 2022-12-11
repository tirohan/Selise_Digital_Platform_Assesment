<h1 align="center" id="title">Image Classification Model</h1>

<p id="description">● Preprocess the Data ● Apply augmentation ● Build Classifier which will be able to classify the input photo to one of the 4 classes ● Plot matrices ● Prove that your model is not overfitted ● Build one more classifier and apply any kind of ensemble techniques.</p>

<h2>Project Screenshots:</h2>

<img src="https://github.com/tirohan/Selise_Digital_Platform_Assesment/blob/main/Problem%202/image1.PNG" alt="project-screenshot" width="400" height="400/">

<img src="https://github.com/tirohan/Selise_Digital_Platform_Assesment/blob/main/Problem%202/iamge2.PNG" alt="project-screenshot" width="400" height="400/">

<img src="https://github.com/tirohan/Selise_Digital_Platform_Assesment/blob/main/Problem%202/EAIR%20CM.PNG" alt="project-screenshot" width="400" height="400/">

<h2>🛠️ Installation Steps:</h2>

<p>1. Build The Dockerfile</p>

```
docker build -t dockerfile .
```

<p>2. Check docker images</p>

```
docker images
```

<p>3. Run the image</p>

```
docker run -it -p 8888:8888 dockerfile
```

<p>4. To see which containers are running</p>

```
docker ps -a
```

<p>5. Pushing the image to Docker Hub</p>

```
docker tag  gpipis/dockerfile:first
```

<p>6. Finally push the image</p>

```
docker push gpipis/dockerfile:first
```

<p>7. Pull the image from Docker Hub</p>

```
docker pull gpipis/dockerfile:first
```

<p>8. Run the notebook</p>

```
docker run -it -p 8888:8888 gpipis/dockerfile:first
```

<p>9. Change the port to the url</p>
