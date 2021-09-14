# NeuralNetworkTechnologies

## The repository contains folders with tasks to course **"Deep Learning/Neural Network Technologies"** according to book *"Dive into Deep Learning"*. Each folder corresponds to some task. Pytorch is used here.

### **Task 1. Preliminaries**
<br> This chapter contains seven subtopics, which teaches:
<br>1.1. Data Manipulation *(how to acquire and process data)*.
<br>1.2. Data Preprocessing *(how to preprocesse raw data with pandas and converting them into the tensor format)*.
<br>1.3. Linear Algebra *(how to implementate basic mathematical objects, arithmetic, and operations in linear algebra in code.)*.
<br>1.4. Calculus *(brief primer on differential calculus that is commonly used in deep learning)*.
<br>1.5. Automatic Differentiation *(to trace through the computational graph, filling in the partial derivatives with respect to each parameter)*.
<br>1.6. Probability *(to think about the probability of getting a high reward under each of the available actions)*.
<br>1.7. Documentation *(how to exploring the PyTorch API)*.

* **Іnstallation**
	<br> pip install torch torchvision 
	<br> pip install -U d2l 
	
* **Settings up environment and launching jupyter notebook**
	<br> conda create --name d2l python=3.8 -y
	<br> mkdir d2l-en && cd d2l-en
	<br> curl https://d2l.ai/d2l-en.zip -o d2l-en.zip
	<br> unzip d2l-en.zip && rm d2l-en.zip
	<br> conda activate d2l
	<br> jupyter notebook

