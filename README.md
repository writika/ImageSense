# ImageSense
Create a deep learning model to generate image captions with an attention mechanism using the Flickr8K. The project combines CNN and RNN models for effective caption generation. dataset. 
This model, designed for the visually impaired, converts captions to speech, helping users understand images through audio descriptions. 


**Data Source
**
The dataset for this project is sourced from Kaggle (https://www.kaggle.com/adityajn105/flickr8k) and comprises 8,000 images, each paired with five distinct captions that describe the key elements and events depicted. The Flickr8K dataset is ideal for this project due to its manageable size, which allows for training on lower-end hardware such as CPUs.
The dataset comes in a ZIP file named flickr8k.zip and includes:
•	Images/: A folder containing 8,091 images.
•	captions.txt: A text file listing image IDs along with five associated captions per image, separated by commas.
The dataset has been further divided into training and test sets for model development.
**Libraries Used
**
This project utilizes the following libraries:
•	numpy: For numerical operations and computations.
•	pandas: For data manipulation and handling CSV files.
•	time: For managing time-related tasks.
•	matplotlib: For image visualization and plotting.
•	seaborn: For creating statistical graphics and visualizations.
•	collections: For advanced data structures beyond Python's built-in options.
•	PIL (Python Imaging Library): For image processing tasks.
•	glob: For pattern matching and file path retrieval.
•	sklearn: For machine learning and statistical modeling.
•	nltk (Natural Language Toolkit): For natural language processing and text handling.
•	tensorflow: For data preprocessing and model building.
•	keras: For constructing and training deep learning models.
•	tqdm: For displaying progress bars during data processing.
•	gTTS (Google Text-to-Speech): For converting text descriptions into spoken words.
To install the necessary libraries, run the following command:
!pip install numpy pandas matplotlib seaborn pillow glob2 scikit-learn nltk tensorflow keras tqdm gTTS

**Project Workflow
**
The project is structured into five main phases:
1.	Data Acquisition and Understanding: Load the dataset and gain insight into its structure and content.
2.	Data Preprocessing: Prepare the images and captions for use in the model by transforming them into a suitable format.
3.	Train-Test Split: Organize the data into training and testing sets to facilitate model development and evaluation.
4.	Model Building: Construct and train the image captioning model, incorporating Encoder, Attention, and Decoder components.
5.	Model Evaluation: Assess the model’s performance using techniques such as greedy search and BLEU score to measure the quality of the generated captions.
![image](https://github.com/user-attachments/assets/d55833db-bd2c-473f-a8db-50c1aa3ac274)
