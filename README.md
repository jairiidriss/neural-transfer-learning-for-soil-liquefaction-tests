# NeuralTransferLearningForSoilLiquefactionTests
<h2>Neural Transfer Learning For Soil Liquefaction Tests</h2>
<hr>
<ul>
  <li>This code is developed to transfer learning across different soil liquefaction test (Vs, CPT, CPT, and SPT)</li>
  <li>The main model (aka: the pre-trained model) is built using the comprehensive Vs test dataset for different sources including two features (Vs1 and CSR)</li>
  <li>The knowledge gained why classifying soil liquefaction using Vs test dataset is reused for CPT, SPT, and DPT as starting point and 20% of each test is used to fine-tune the pre-trained model</li>
</ul>
<h2>Run the Code</h2>
<hr>
<ul>
  <li>The source code is built using python programming language, you can easily run it using Jupyter notebook (anaconda3)</li>
  <li>Download the latest release and unzip to use. The unzipped folder contains all the files + datasets that the main codes will need to run.</li>
  <li>main_model.ipynb contains the source code of the main model(pre-trained model) based on the Vs test dataset, you can easily run it on jupyter notebook by clicking Cell > Run All</li>
  <li>main_model.h5 contains the saved model weights from the main_model.ipynb</li>
  <li>The three other .ipynb files contain the predictions of soil liquefaction using other tests based on the pre-trained model (main_model.h5), you can run the code easily on jupyter notebook by clicking Cell > Run All <li>
</ul>
<h2>Datasets</h2>
<hr>
<p>
  You can find all the datasest in the folder ./Datasets.
</p>
<ul>
  <li>The datasets from D1 to D7 are the Vs test datasets used to build the main model(pre-trained model)</li>
  <li>The other tests datasets(CPT, DPT, and DPT) are used to evaluate and compare the pre-trained model predictions to other well-known models</li>
</ul>
