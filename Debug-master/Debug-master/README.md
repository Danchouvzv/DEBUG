# Debug, a Pest-Classifier🐞
![GitHub Logo](img/DebugLogo.png)
Inspiration
Farmers rely heavily on crop yields as their main source of income. However, many pests can get in the way of optimal production yields as they can eat and harm the field crops. Pesticides are commonly used by many farmers to get rid of them. Despite that, the large quantities of pesticides used to spray on acres of farmland can be expensive, and many times, farmers misuse pesticides on the wrong bugs. The overuse of pesticides has many consequences which can cost farmers money, time, and resources:

First, the EPA estimates up to 70 million pounds of pesticides are lost to drift each year, a common issue in which extra pesticide chemicals are carried by the wind, hurting the ecosystems, the farmer's wallet, and human health.
Second, an overabundance of pesticides on the wrong species can lead to pesticide resistance. As a result, pesticide costs should be expected to increase as new variations of the pesticide are more expensive.
Third, spraying pesticides on beneficial pests can negatively impact the production rate of the farmer's crops, which is a waste of money.
These effects worsen each year, causing rural/small farmers to lose thousands of dollars, as on average, they spend around $21,000 on pesticides alone as of 2019. This number will only increase in the coming years.

What it does
This is where the Debug application comes into play. Using Debug, farmers can upload a picture of a recurrent bug they observe in their fields. Once uploaded, they are provided with a summary of the pest and whether it is harmful or not, along with some potential pesticides or alternatives they could use. This way, the farmers can reduce the money spent on warding away bugs that appear to be pests but are not.

How I built it
HTML5 and CSS3 were used for structure and styling. Javascript was implemented for responsiveness, in particular for the drag and drop/upload feature. Tensorflow.js was used for the image classification machine learning feature. To obtain the images used for training, a mixture of the ImageNet library and Google Images were used. The datasets were trained using Teachable Machine. I used Cordova (an open-source software that creates mobile applications using the HTML, CSS, and Javascript code of web applications) to make the Android version of Debug.

Challenges I ran into
The most challenging component of this project was definitely the machine learning aspect. There were many image Javascript libraries available, so it took time to find the best fit for this application, which turned out to be TensorFlow. Another complicated feature turned out to be the drag and drop feature. There were not many resources online. Despite this, I found a way to implement it with some scrounging. Overall, many of my issues were quickly solved as I had varied skills and an open mind.

Accomplishments that I'm proud of
I am proud to have implemented an image classification model to real-world applications such as the ongoing food crisis and the overuse of pesticides in a short amount of time. I applied my strengths and learned lots of new skills along the way!

What I learned
This was the first time I have attempted machine learning, so I learned a lot about model training, incorporating datasets, and integrating it into a user-friendly platform.

What's next for Debug
As of now, Debug can only classify locusts, armyworms, honey bees, and earwigs. I am planning on expanding the database of bugs and making the algorithm more accurate.
Additionally, I will include an option for farmers to input the crop on which they found the insect so pesticide recommendations do not harm the crops.
I will also develop an iOS version of Debug.

Contributor
Debug was created between June 5th and 7th, 2020 during the "Hack the Northeast" hackathon.

Contributor:

Doni Poni (owner of this repository): https://github.com/Danchouvzv
