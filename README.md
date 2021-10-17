# Mechanism-of-action
## Prediction of Mechanism of Action of a drug

A web application using Flask framework. It uses Jinga templating engine.
- The input is a CSV file, which contains gene expression and cell viability values of each drug. 
- The output is the top classes of drugs (with the highest probability). 
- The machine learning model is serialized and de-serialized using the built-in keras ```save``` and ```load_model``` 
  (You can refer: https://keras.io/getting_started/faq/#what-are-my-options-for-saving-models)

- The machine learning model is trained using a Custom Neural network as shown below:

![LayersOfCustomNeuralNetwork](https://user-images.githubusercontent.com/36910708/124378972-0cbeb600-dcd2-11eb-85c4-f5e10525b567.png)

# Sample output of the project:

### Picture 1:
![moa_output_01](https://user-images.githubusercontent.com/36910708/124379000-2fe96580-dcd2-11eb-8f68-dd1dd58f550f.JPG)


### Picture 2:
![moa_output_02](https://user-images.githubusercontent.com/36910708/124379001-3081fc00-dcd2-11eb-91f9-6df3a9ee4674.JPG)


### Picture 3:
![moa_output_03](https://user-images.githubusercontent.com/36910708/124379002-3081fc00-dcd2-11eb-89b1-a96a43cb4532.JPG)

### Picture 4:
Contents of CSV file: 
It contains **three drugs** with the gene expression and cell viablity values.

![moa_output_06_contents_of_csv_file](https://user-images.githubusercontent.com/36910708/124383509-7b0f7280-dcea-11eb-93a6-36252e5f8f25.JPG)

### Picture 5:
![moa_output_04_upload](https://user-images.githubusercontent.com/36910708/124379003-311a9280-dcd2-11eb-9bb9-0d25a25881a6.JPG)

### Picture 6:
![moa_output_05_submit](https://user-images.githubusercontent.com/36910708/124379004-311a9280-dcd2-11eb-9e1b-1bd88f39c67d.jpg)

### Picture 7:
![image](https://user-images.githubusercontent.com/36910708/124466494-55e73680-ddb4-11eb-97fa-78bd83ba71a8.png)

### Picture 8:
![image](https://user-images.githubusercontent.com/36910708/124466584-65ff1600-ddb4-11eb-9b10-9ceec5e38f98.png)

### Picture 9:
![image](https://user-images.githubusercontent.com/36910708/124466653-731c0500-ddb4-11eb-958a-f39aab10e637.png)

### Picture 10:
![image](https://user-images.githubusercontent.com/36910708/124466712-83cc7b00-ddb4-11eb-93a9-a46ad22c11f7.png)

### Picture 11:
![image](https://user-images.githubusercontent.com/36910708/124466758-921a9700-ddb4-11eb-8ce1-bc7615251827.png)

### Picture 12:
![image](https://user-images.githubusercontent.com/36910708/124466787-9941a500-ddb4-11eb-8508-4406c6844d92.png)

