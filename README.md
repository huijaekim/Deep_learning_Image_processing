# Deep learning for image processing

For a small project, I built a simple image similarity model. I did a quick test with 20 pieces of infant clothing pictures that I found from google images. I extracted features with VGG16 from the pictures, and calculated cosine similarities to compare pictures. <br/><br/>


Description: If a customer is hoping to buy an infant onesie of a certain style, the customer can use this algorithmia and paste the picture of onesie that he/she desires to purchase. This algorithm analyzes the submission and recommends similar design. Customers can use the result from the algorithm to find the exact product they would like to purchase. 
<br/><br/>
Future Work:<br/> 
&nbsp;&nbsp;&nbsp;1. Need to collect large quantity of images in the database.<br/>
&nbsp;&nbsp;&nbsp;2. Categorize different type of clothes. Customers can choose clothes category first, and then drop pictures. (We will be able to have higher accuracy)<br/>
&nbsp;&nbsp;&nbsp;3. Feature reduction. The current algorithm is built to generate 4096 features for a picture. We can extract features from 4096 using PCA to decrease the model complexity and optimize the model.<br/>
&nbsp;&nbsp;&nbsp;4. Automatically provide webpages that actually sell the product of recommended pictures with the result to lead to direct purchase after search<br/>
