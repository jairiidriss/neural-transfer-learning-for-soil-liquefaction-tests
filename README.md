<h1>Neural Transfer Learning For Soil Liquefaction Tests</h1>
<p>Paper Link: https://www.sciencedirect.com/science/article/abs/pii/S009830042200231X</p>
<hr>
<ul>
  <li>This code is developed to transfer learning across different soil liquefaction tests (Vs, CPT, CPT, and SPT)</li>
  <li>The main model (aka the pre-trained model) is built using the comprehensive share-wave velocity (Vs) test dataset for different sources including two features (Vs1 and CSR)</li>
  <li>The knowledge gained while classifying soil liquefaction using the shear-wave velocity (Vs) test dataset is reused for CPT, SPT, and DPT as starting points, and 20% of each other soil liquefaction test dataset is used to fine-tune the pre-trained model</li>
</ul>
<h2>Run the Code</h2>
<hr>
<ul>
  <li>The source code is built using Python programming language, you can easily run it using Jupyter Notebook (anaconda3)</li>
  <li>Download the latest release and unzip to use. The unzipped folder contains all the files + datasets the main codes will need to run.</li>
  <li>main_model.ipynb contains the source code of the main model (pre-trained model) based on the Vs test dataset, you can easily run it on Jupyter Notebook by clicking Cell > Run All</li>
  <li>main_model.h5 contains the saved model weights from the main_model.ipynb</li>
  <li>The three other .ipynb files contain the predictions of soil liquefaction using other soil liquefaction tests based on the pre-trained model (main_model.h5), you can run the code easily on Jupyter notebook by clicking Cell > Run All </li>
</ul>
<h2>Datasets</h2>
<hr>
<p>
  You can find all the datasets in the folder ./Datasets.
</p>
<ul>
  <li>The datasets from D1 to D7 are the shear-wave velocity test datasets used to build the main model (pre-trained model)</li>
  <li>The other datasets (CPT, DPT, and DPT) are used to evaluate and compare the pre-trained model predictions on the other soil liquefaction tests datasets to other well-known models</li>
</ul>

<p>For questions and inquiries, please, contact me at <b>idriss.jairi@univ-lille.fr</b></p>
