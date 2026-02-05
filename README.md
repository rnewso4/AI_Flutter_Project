This is a project I completed as a graduate student at LSU for Dr. Ghawaly's Foundational AI class.

**Presentation** can be accessed here: https://www.canva.com/design/DAGmPN1uDL8/AfJfXXG-6l4nM2IgAVjdwA/view?utm_content=DAGmPN1uDL8&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hac0f5ce963

This is a full stack application that utilizes multiple platforms.

# 1. Idea
I title this app Café aux Données. It can be roughly tranlsated to coffee with data, and it's meant to be a play on word to café au lait. Building a coffee shop and managing it can be really difficult because there are many factors that effect the bottom lin.

With this app, I use a trained linear regression model so that users can input their information and see how much they need to earn daily in order to run a successful business. 

# 2. Front-end
The designs for the frontend development were conceptualized using Adobe XD. At the heart of my designs, I wanted the information to be easy to read and for the branding to be centralized to a common theme. 

The app is coded using Flutter and Dart and tested on an iPhone 16. 

The most difficult page to design was the list view, which you can see in the video. I wanted the information to be as simple to read and understand as possible without forcing the user to make additional clicks to view another page.

# 3. Database
The user's information is stored in Firebase. They can calculate their revenue value daily, and it will be stored in Firebase under their username. 

# 4. Back-end
I use http to send the user's information to my computer operating as a server. The model has already been trained using the jupyter notebook. The user's info is used as input to generate a daily revenue value using flask api, and then sent back to the user's application in a post method.

# 5. Linear Regression Model
The model has 2 linear layers with a Mish activation function in betwene. The loss function is Mean Squared Error. An adam optimizer is used with a learning rate of 0.01. The training and loss curve can be seen in the jupyter notebook.

# 6. Dataset
The dataset used to train the linear regression model comes from kaggle. Link: https://www.kaggle.com/datasets/himelsarder/coffee-shop-daily-revenue-prediction-dataset
