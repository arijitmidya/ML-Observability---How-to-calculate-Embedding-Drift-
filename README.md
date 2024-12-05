# ML-Observability---How-to-calculate-Embedding-Drift-

# Embedding 
When you work with texts, images, or other unstructured data, it is common to use embeddings. In this case, you create a numerical representation of the input data.For example, you can take pre-trained models like BERT to convert your raw texts into vectors. This process maps each object in the dataset (say, a text that the model should classify) to a multi-dimensional space and represents it as a set of numbers.

![image](https://github.com/user-attachments/assets/c5e47e90-6253-4da9-b0d8-c12f898f269b)

Monitoring data drift is just as relevant when you work with embeddings. When an NLP or LLM-based application is in production, you can detect when the data become too different or unusual and react before it affects the model quality. 

## How can data drift in texts look? Here are a few examples:
    a. A new popular topic or word. Say, a model analyzes social media data: a new popular meme or a world event might confuse the model.
    b. A new class or change in balance. You might classify texts into five topics, but then a 6th topic arises, or an existing one becomes more prevalent.
    c. Outliers or spam. Imagine a spike in unrelated content, automatically generated or corrupted texts. 
    d. Shift in text sentiment.
    e. Texts in a new language.


 # Steps of Implementation : 

 ## Step 1 : Import necessary libraries

 ## Step 2 : Prepare the dataset

 ## Step 3 : Embedding drift report 

 ![image](https://github.com/user-attachments/assets/977032cb-92f0-415c-a124-e382a1fd00f1)

 ## Step 4 : Embeddings drift detection 
      a. drift method = model 
      b. drift method = mmd
      c. drift method = ratio
      d. drift method = distance ( euclidian , cosine , cityblock , chebyshev )

![image](https://github.com/user-attachments/assets/2676b971-d9b1-45aa-88f3-f75385c1c6f2)

## Step 5 : Data drift metric preset

![image](https://github.com/user-attachments/assets/19640869-857a-4be8-93b5-6728a8370f83)

## Step 6 : Embedding drift test 

![image](https://github.com/user-attachments/assets/4b301cb3-0d75-41ad-a2c5-dc8206812d54)

## Step 7 : Data drift test preset

![image](https://github.com/user-attachments/assets/570ce15d-d970-4b58-ab51-be48aa76255e)

## Step 8 : No target performance test preset

![image](https://github.com/user-attachments/assets/8c3b4c2e-8ab0-4394-bc81-248dffce6e74)

Happy coding :)







