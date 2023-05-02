# 23_Preventive-Adversarial-Attack-Project
Preventive Adversarial Attack Project

## Project Introduction
Artificial intelligence (AI) systems harbor security loopholes that pose an imminent threat to user safety. Consequently, we find ourselves in an era that demands the defense of AI systems from malicious adversaries.

In this project, we aim to undertake research on adversarial AI attacks and defense mechanisms for autonomous ships while concurrently implementing them. Adversarial AI attacks entail deliberately crafting adversarial samples to disrupt and launch an assault on the opponent's AI system. This method is capable of deploying various lethal attack techniques that undermine the integrity of AI systems. The propulsion system of autonomous ships is particularly vulnerable to connectivity issues that arise from integrating and navigating weather patterns such as wave states, rainfall or strong winds, as well as the position and path of surrounding vessels. Such vulnerabilities, if left unattended, could cause navigational challenges for autonomous ships. This project, therefore, seeks to prevent such circumstances and contribute towards accelerating the pace of automation in the maritime industry

## Background and Necessity of the Proposal
Over 95% of Korea's import and export cargo is transported by sea, highlighting the crucial role that maritime transport plays in the country's development. Autonomous ships are the next generation of high-value vessels that combine all digital core technologies, including artificial intelligence (AI), the Internet of Things (IoT), big data, and sensors, to self-determine the optimal route and navigate independently.

AI technology, a core component of autonomous navigation, employs data and knowledge to implement high-level human abilities such as perception, learning, and inference. Machine learning, deep learning, and other AI technologies support unmanned/autonomous shipping by processing vast amounts of data generated by autonomous vessels.

Now, for the safety of autonomous ships, it is necessary to focus not only on the cybersecurity of ship systems but also on the cybersecurity of AI technology. The Ministry of Industry, Trade, and Energy and the Ministry of Oceans and Fisheries have established a task force to develop autonomous ships, with approximately KRW 160 billion allocated for development until 2025. Therefore, this research project could provide excellent opportunities to promote growth that aligns with trends in maritime logistics.

## Main Functions
- Adversarial attack sample generation function for training deep learning models
- Functionality to block attacks through adversarial attack training
- Adversarial attack defense function
- Integrated monitoring of adversarial attacks and alerting function for situational awareness
- AI protection and defense functions for AIS (Automatic Identification System), collision avoidance, and automatic berthing systems
- Real-time defense situation updates on adversarial attacks through dedicated app that receives live on-site footage

## Applied technologies
- Python
  - An interpreted, object-oriented, dynamically-typed, platform-independent language
- Machine learning math
  - Artificial intelligence mathematical theories such as gradient descent, backpropagation, loss function, activation function, etc.
- Adversarial AI
  - Techniques such as adversarial example generation, FGSM, adversarial training, etc. for defensive purposes
- Scikit-learn
  - Machine learning library for Python
- TensorFlow Keras
  - open-source neural network library written in Python
- GAN
  - Generative model where two neural networks, a generator and a discriminator, compete with each other during training
- Deep learning
  - Artificial neural network techniques such as gradient descent, backpropagation, loss function, activation function, CNN, RNN, LSTM, AutoEncoder, GAN
- RNN
  - Recurrent neural network that can model time-varying features by storing state information inside the network
- LSTM
  - RNN technique that uses a cell, input gate, output gate, and forget gate to prevent the vanishing gradient problem
- Pandas
  - Software library written in Python for data manipulation and analysis.
  
## Project Topic
- The focus of this project is on researching adversarial AI attacks and defense mechanisms for autonomous ships. Specifically, we aim to identify security vulnerabilities in AI systems used for autonomous ships, detect and defend against adversarial AI attacks. Our ultimate goal is to ensure the safety of autonomous ships by developing robust defense technologies against adversarial AI.

- To begin, we will analyze the four main types of adversarial AI attacks (poisoning, evasion, model extraction, and data extraction) that commonly occur in AI systems. We will also examine the system architecture of autonomous ships and identify potential security weaknesses. In addition, we will collect information from ocean sensors such as AIS, RADAR, audio, and camera data to train generator and discriminator models using GANs to generate adversarial examples and detect them.

- Based on the above research, we will develop defensive technologies to block and defend against adversarial AI attacks. We plan to expand our efforts by creating an application that receives real-time data from autonomous ships, evaluates AI image and video recognition results, and notifies the coastal control center when an attack is detected. Ultimately, our project aims to enhance the safety and security of autonomous ships through advanced research and innovative defense strategies against adversarial AI attacks.

## Expected deliverables
![image](https://user-images.githubusercontent.com/107015573/235577903-f5018e81-8b59-4f16-aada-b69ad944db1f.png)
- To develop defense capabilities for adversarial attacks on ships, the following process will be undertaken. First, the training data for both the attacker and defender will be updated. Next, adversarial attack examples will be uploaded to clean data to assess whether the resulting changes are detectable by human observation, which will be verified through crowd-sourcing. Finally, a DNN (Deep Neural Network) will be generated as a defense strategy, and testing will be conducted to evaluate the efficacy of the defense
