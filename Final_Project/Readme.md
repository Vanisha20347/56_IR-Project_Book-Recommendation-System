# Book Recommendation System

### To operate the website, follow the below mentioned steps: -
### 1) Install all the packages and libraries used in the code.
### 2) Install streamlit for the website implementation.
### 3) Download the Datasets used - final_users.csv, final_books.csv, cb_users_accuracy and cf_ratings_matrix.pkl present in the folder named data. Here, due to the very large size of cf_ratings_matrix we could not upload it directly, so we are uploading a .txt file named cf_ratings_matrix.txt containing the link to the drive which contains this file. Download it from there, as this is thoroughly used in the code for collaborative filtering.
### 4) Make sure to download these dataset files in a folder in your current working directory or current project folder and name the folder as data, so as to match the path of these files in the code, or else you need to update the path.
### 5) Run the following command to run the website: - 
### streamlit run <your_filename_here.py>
### 6) Upon running the website, you can select whether you are an existing user or a new user and input the respective user_ids. 
### 7) For the existing users, they will be given a choice to get book recommendations using collaborative, content, hybrid and popularity based filtering using the user-user similarity and past history of the user.
### 8) For the new users, they will be shown the Popular books.
### 9) To run the .ipnyb files, you need the datasets, so upload the datasets in your drive in the same location as in the code or you may update the path. 
### 10) The f70.pkl and cf_users_matrix.pkl are the same files with different names. So, you can use them in each other's place by changing the name.
