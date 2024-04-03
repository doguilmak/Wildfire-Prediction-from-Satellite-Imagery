<h1  align=center  >Wildfire Prediction in Satellite Imagery</h1>

<br>

<img  src="https://raw.githubusercontent.com/doguilmak/Wildfire-Prediction-from-Satellite-Imagery/main/assets/wildfire_canada.png"  width=1000  height=250  alt="github.com/doguilmak/Wildfire-Prediction-from-Satellite-Imagery"/>

<small>Picture Source: <a  href="https://github.com/doguilmak/Wildfire-Prediction-from-Satellite-Imagery">Doğu İlmak GitHub</a></small>

<br>

<h2>Predicting Wildfires with Convolutional Neural Networks (CNNs)</h2>

<p>Wildfires pose a significant threat to ecosystems, wildlife, and human lives, making early detection and prediction crucial for effective wildfire management. Convolutional Neural Networks (CNNs) have emerged as a powerful tool for predicting wildfires due to their ability to extract complex patterns from spatial data, such as satellite images and weather data. CNNs can analyze various factors that contribute to wildfire risk, including vegetation density, temperature, humidity, and wind speed. By training CNNs on historical wildfire data and environmental factors, these models can learn to identify patterns indicative of potential wildfire outbreaks. One of the key advantages of using CNNs for wildfire prediction is their ability to process large-scale, high-resolution satellite imagery quickly. This allows for real-time monitoring of wildfire-prone areas, enabling early detection and timely deployment of firefighting resources.</p>

<br>

<p>Additionally, CNNs can improve the accuracy of wildfire prediction models by integrating data from multiple sources, such as satellite imagery, weather stations, and historical fire records. This holistic approach provides a comprehensive view of wildfire risk factors, leading to more reliable predictions.</p>

<br>

<h2>Wildfire Prediction Dataset</h2>

  <p>This dataset consists of satellite images with a resolution of 350x350 pixels, categorized into two classes: Wildfire and No Wildfire. The dataset contains a total of 42,850 images, with 22,710 images belonging to the Wildfire class and 20,140 images belonging to the No Wildfire class. To facilitate model training and evaluation, the dataset has been divided into three subsets: training, testing, and validation. The distribution of images among these subsets is as follows:</p>  

<ul>

<li><b>Training Set:</b> Approximately 70% of the dataset, used for training the model.</li>

<li><b>Testing Set:</b> Approximately 15% of the dataset, used for evaluating the model's performance.</li>

<li><b>Validation Set:</b> Approximately 15% of the dataset, used for fine-tuning hyperparameters and validating the model's performance.</li>

</ul>  

<p>Each image in the dataset represents a snapshot of the Earth's surface, captured by satellite imagery. These images contain valuable information about vegetation, land cover, and other environmental factors that can be used to predict the likelihood of wildfires.</p>  

<br>  

<h2>Objectives</h2>  

<p>Using <i>longitude</i> and <i>latitude</i> coordinates for each wildfire spot <i>(> 0.01 acres burned)</i> found on the dataset above we extracted satellite images of those areas using MapBox API to create a more convenient format of the dataset for <i>deep learning</i> and building a model that can predict whether an area is at risk of a wildfire or not. <b>Models created with this dataset predict where a fire could potentially occur. It was created on this basis by the Canadian state. This inference was made only through RGB tapes. This should be taken into account.</b></p> 

<br>  

<p>To download the dataset from Kaggle, you need to have a kaggle account.</p>

<ul>

<li>Dataset download link: <a  href='https://www.kaggle.com/datasets/abdelghaniaaba/wildfire-prediction-dataset/download?datasetVersionNumber=1'>Dataset</a></li>

<li>Dataset on Kaggle: <a  href='https://www.kaggle.com/datasets/abdelghaniaaba/wildfire-prediction-dataset'>Wildfire Prediction Dataset (Satellite Images)</a></li>

</ul> 

<h2>Keywords</h2>
<ul>
  <li>Wildfire</li>
  <li>Earth Science</li>
  <li>Classification</li>
  <li>Class Activation Maps</li>
  <li>Deep Learning</li>
  <li>Satellite Imagery</li>
  <li>VGG-16</li>
</ul>

<br>

<h2>Sources</h2>

<ul>
	<li><a href='https://open.canada.ca/data/en/dataset/9d8f219c-4df0-4481-926f-8a2a532ca003'>Refer to Canada's Website for the Original Wildfires Data (Forest Fires - Open Government Portal)</a></li>
	<li><a href='https://www.donneesquebec.ca/fr/licence/'>Original License For the Data (Creative Commons 4.0 Attribution (CC-BY) license – Quebec)</a></li>
</ul>

<br>

<h2>Notebooks</h2>

On below, there are informations about the notebooks created respectively.

<ol>
	<li>In this section, visualizations of the data set were made. <br> Notebook: <a href='https://github.com/doguilmak/Wildfire-Prediction-from-Satellite-Imagery/blob/main/1_load_and_display_data.ipynb'>1_load_and_display_data.ipynb</a></li> <br>
	<li>In this section, I build classification model with <i>VGG-16</i>. (Will be added soon..) <br> Notebook: <a href=''>2_pretrained_vgg16.ipynb</a> - Model has % accuracy.</li> <br>
	<li>In this section, I build classification model with Class Activation Map (CAM). <br> Notebook: <a href='https://github.com/doguilmak/Wildfire-Prediction-from-Satellite-Imagery/blob/main/3_model_with_cam.ipynb'>3_model_with_cam.ipynb</a> - Model has 95.3% accuracy. The results of the model on the test data are in the <a href="https://github.com/doguilmak/Wildfire-Prediction-from-Satellite-Imagery/blob/main/predictions/custom_model_predictions.csv">custom_model_predictions.csv</a> file. Just click the link to view.</p></li>
</ol>

<br>

<h2>Contact Me</h2>

<p>If you have something to say to me please contact me:</p>

<ul>
	 <li>Twitter: <a href="https://twitter.com/Doguilmak">Doguilmak</a></li>
	 <li>Mail address: doguilmak@gmail.com</li>
</ul>
