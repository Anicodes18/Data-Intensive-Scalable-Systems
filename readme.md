 ---- The two required .json data files have been provided but the code to retrieve data using an API call is present in the Jupyter notebook. Run the jupyter notebook on Google Colab for running smoothly.

---- Note ----

PySpark was run on Google Colab and hence, some parts of the code have been modified as per the setup required specifically for google colab. Hence, if the code file is run on google colab itself, the entire process of retrieving the data via API, uploading it to blob storage, retrieving for processing in PySpark, and finally, uploading to MongoDB runs smoothly inside one notebook.



Requirements:

A "gcs\_key.json" is required to connect to the blob storage and it is required to be uploaded to colab for connecting to the Google Cloud Storage. Hence, after running the cell for it, in the output section of that cell, an option to upload the "gcs\_key" pops-up. After uploading that key the entire process runs smoothly. So, ensure to download the key for your GCS blob storage and upload it to colab for connecting.



----------------------------------------------------

from google.colab import files

uploaded = files.upload()  # Uploading the `gcs\_key.json` required for connecting to google cloud storage

----------------------------------------------------



Given above are the code lines , under which the option to upload the gcs\_key will pop-up.



Apart from this, once the gcs\_key is uploaded all the other cells execute smoothly and all the required **JAVA-11 and HADOOP versions have been setup as per colab's PySpark 3.4.1 version.**



Id and password will be required for connecting to **"MongoDB"** database.

id - Your_userid

password - Your_password

full uri link - mongodb uri for connecting to the database



The **"Power BI"** file also has been added. **Note: For the visualizations to be visible a connection with MongoDB database will have to be established.**

