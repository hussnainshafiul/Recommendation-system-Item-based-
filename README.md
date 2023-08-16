# Recommendation-system-Item-based-
This repository contains code for building a fashion product recommendation system using text-based similarity analysis. The system is built using Python and popular data analysis libraries such as NumPy, pandas, scikit-learn, and difflib. It utilizes the concept of cosine similarity to find similar fashion products based on their textual attributes.

## Usage

Data Setup: Ensure the 'fashion.csv' dataset is in the same directory as the script. The dataset should contain columns such as 'Gender', 'Category', 'SubCategory', 'ProductType', 'Colour', 'Usage', and 'ProductTitle'.
Running the Script: Run the provided Python script in a suitable environment with the necessary libraries installed.
Input: Upon execution, the script will prompt you to input a product title for which you want recommendations.
Output: The script will display a list of recommended products along with their similarity scores.

## Note

The code is organized and documented to enhance readability and understanding.
Ensure the required libraries (numpy, pandas, sklearn, and difflib) are installed in your environment.

### To integrate this ML code, into your app Use the flask_server.ipynb

First, install the below Libraries

```sh
!pip install pyngrok
```

```sh
!pip install ngrok
```

```sh
!pip install flask_ngrok
```

### Running the function

There will be link generated at the end, "----.ngrok" use that link along with the link name to make client request

```sh
"https/-----.ngrok/getrecommendation" 
```

Conclusion

This fashion product recommendation system leverages text similarity analysis to provide users with personalized recommendations. By utilizing cosine similarity and considering multiple textual attributes of products, the system offers valuable insights to enhance the shopping experience and assist users in discovering similar fashion items.




