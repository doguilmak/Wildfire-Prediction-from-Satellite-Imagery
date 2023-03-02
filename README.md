<h1 align=center >Wildfire Prediction from Satellite Imagery</h1>  

<br>  

<img  src="https://raw.githubusercontent.com/doguilmak/Wildfire-Prediction-from-Satellite-Imagery/main/assets/wildfire_canada.png" width=1000  height=250 alt="github.com/doguilmak/Wildfire-Prediction-from-Satellite-Imagery"/>

<small>Picture Source: <a href="https://github.com/doguilmak/Wildfire-Prediction-from-Satellite-Imagery">Doğu İlmak GitHub</a></small>

<br> 

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

<h2>Objective</h2>  

<p>Using <i>longitude</i> and <i>latitude</i> coordinates for each wildfire spot <i>(> 0.01 acres burned)</i> found on the dataset above we extracted satellite images of those areas using <b>MapBox API</b> to create a more convenient format of the dataset for <i>deep learning</i> and building a model that can predict whether an area is at <b>risk of a wildfire</b> or <b>not</b>.</p>

<br> 

<h2>About Dataset</h2> 

<p>This dataset contains satellite images <i>(350x350px)</i> in 2 classes:</p> 

<ul>
	<li>Wildfire : 22710 images</li>
	<li>No wildfire : 20140 images</li>
</ul>  

<p>The data was divided into train, test and validation with these percentages:</p>

<ul>
	<li>Train : ~70%</li>
	<li>Test : ~15%</li>
	<li>Validation : ~15%</li>
</ul>  

<p>To download the dataset from Kaggle, you need to have a kaggle account.</p>

<ul>
	<li>Dataset download link: <a  href='https://www.kaggle.com/datasets/abdelghaniaaba/wildfire-prediction-dataset/download?datasetVersionNumber=1'>Dataset</a></li>
	<li>Dataset on Kaggle: <a  href='https://www.kaggle.com/datasets/abdelghaniaaba/wildfire-prediction-dataset'>Wildfire Prediction Dataset (Satellite Images)</a></li>
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
