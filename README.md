# Skin-Cancer-Segmentation_
# Brain Tumor Detection using Python and Sklearn


<!-- wp:paragraph -->
<p>In this post we are demonstrating about brain tumor detection using sklearn and python.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>Requirements:</h3>
<!-- /wp:heading -->

<!-- wp:list -->
<ul><li>python (<a href="https://www.python.org/downloads/"><em>https://www.python.org/downloads/</em></a>)</li><li>sklearn (<em>pip install sklearn</em>)</li><li>openCV (<em>pip install opencv-python</em>)</li><li>numpy (<em>pip install numpy</em>)</li><li>matplotlib (<em>pip install matplotlib</em>)</li></ul>
<!-- /wp:list -->

<!-- wp:heading {"level":3} -->
<h3>DOWNLOAD CODE :</h3>
<!-- /wp:heading -->

<!-- wp:list {"ordered":true} -->
<ol><li>Download the code from github</li><li>Download all above mentioned dependencies.</li><li>Open downloaded folder inside jupyter notebook.</li><li>Now cells as per your requirements.</li></ol>
<!-- /wp:list -->

<!-- wp:heading {"level":3} -->
<h3>STEP 1: Load Dependencies</h3>
<!-- /wp:heading -->


<!-- wp:heading {"level":3} -->
<h3>STEP 2: Load and prepare data</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Note: You can find dataset directory inside github repository link (given below) or download dataset from  <a href="https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri" data-type="URL" data-id="https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri">kaggle</a></p>
<!-- /wp:paragraph -->



<!-- wp:heading {"level":3} -->
<h3>STEP 3: Data Analysis</h3>
<!-- /wp:heading -->
<!-- wp:heading {"level":3} -->
<h3>STEP 4: Data Visualization</h3>
<!-- /wp:heading -->


<!-- wp:heading {"level":3} -->
<h3>STEP 5: Split Data</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>In this step, we are going to split data in two parts (training and testing), so that we can train our model on training dataset and test its accuracy on unseen (test) data.</p>
<!-- /wp:paragraph -->



<!-- wp:heading -->
<h2>STEP 6: Feature Scaling</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>In this step, we are going to use minmax scaling technique to bring all the feature values to less than or equal to 1. In order to do so, we have divided the training data by its maximum value.</p>
<!-- /wp:paragraph -->


<!-- wp:heading {"level":3} -->
<h3>STEP 7: Model Training</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>As we have done with preprocessing part, it is time to train our model. I am going to train model using SVM (Support Vector Machine) and Logistic Regression algorithms and then we will compare the performance of these two different models.</p>
<!-- /wp:paragraph -->



<!-- wp:heading {"level":3} -->
<h3>STEP 8: Evaluation</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>In this part, we will compare the scores of above two models.</p>
<!-- /wp:paragraph -->



<!-- wp:paragraph -->
<p>As we can observe, <strong>SVM </strong>showed a great balance among training an testing score as compared to Logistic Regression. So we can reach to the conclusion that it is ideal model for this particular dataset</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>STEP 9: Prediction</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>In this step we are going to predict test dataset. Afterwards, I have checked the total number of misclassified samples out of total test samples.</p>
<!-- /wp:paragraph -->



<!-- wp:heading {"level":3} -->
<h3>STEP 10: TESTING (On test dataset)</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Finally, it is the time to examine the results.</p>
<!-- /wp:paragraph -->


<!-- wp:heading {"level":4} -->
<h4>OUTPUT</h4>
<!-- /wp:heading -->

<!-- wp:gallery {"ids":[49,50],"linkTo":"none"} -->
<figure class="wp-block-gallery columns-2 is-cropped"><ul class="blocks-gallery-grid"><li class="blocks-gallery-item"><figure><img src="https://cwadtech.files.wordpress.com/2021/07/img-13.png?w=649" alt="" data-id="49" data-link="https://cwadtech.wordpress.com/img-13/" class="wp-image-49"/></figure></li><li class="blocks-gallery-item"><figure><img src="https://cwadtech.files.wordpress.com/2021/07/img-14.png?w=639" alt="" data-id="50" data-full-url="https://cwadtech.files.wordpress.com/2021/07/img-14.png" data-link="https://cwadtech.wordpress.com/img-14/" class="wp-image-50"/></figure></li></ul></figure>
<!-- /wp:gallery -->

<!-- wp:paragraph -->
<p>So, this is all about creating a predictive model using sklearn on brain tumor dataset. Thanks for reading!</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p></p>
<!-- /wp:paragraph -->
