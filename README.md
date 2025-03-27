# Timelytics
## Optimize your supply chain with advanced forecasting techniques.

Timelytics is an ensemble model that utilizes three powerful machine learning algorithms - XGBoost, Random Forests, and Support Vector Machines (SVM) - to accurately forecast Order to Delivery (OTD) times. By combining the strengths of these three algorithms, Timelytics provides a robust and reliable prediction of OTD times, helping businesses optimize their supply chain operations.

With Timelytics, businesses can identify potential bottlenecks and delays in their supply chain and take proactive measures to address them, reducing lead times and improving delivery times. The model utilizes historical data on order processing times, production lead times, shipping times, and other relevant variables to generate accurate forecasts of OTD times. These forecasts can be used to optimize inventory management, improve customer service, and increase overall efficiency in the supply chain.

## Dataset
### Brazilian E-Commerce Public Dataset by Olist

The dataset consists of real-world delivery details sourced from a Brazilian E-commerce Company, which was scrubbed and anonymized.

In the data folder, execute the following commands to unzip the dataset:

```
sudo apt-get install unzip
unzip brazilian-ecommerce.zip
```

The dataset consists of multiple tables that include relevant information about the customer, seller, order, and location. The individual tables are interconnected as shown in the dataset schema. Relevant features are extracted/designed from this data and then used to train the supervised ML model.

## Installation and Setup
### Prerequisites
- Python 3
- The Python libraries listed in `requirements.txt`

Install the required libraries by running:
```
pip3 install -r requirements.txt
```

### Steps to Run the Application
#### Step 1: Clone this repository
```
git clone https://github.com/Dharmik0712/Timelytics-Optimize-your-supply-chain-with-advanced-forecasting-techniques.
```

#### Step 2: Navigate to the Timelytics directory
```
cd Timelytics
```

#### Step 3: Install the required Python libraries
```
pip install -r requirements.txt
```

#### Step 4: Run the Streamlit application
```
streamlit run streamlitApp.py
```

## References
- [Streamlit 30 Days](https://30days.streamlit.app/)
- [Streamlit Deployment Guide](https://docs.streamlit.io/streamlit-community-cloud/get-started/deploy-an-app)
- [Streamlit Example Apps](https://streamlit-cloud-example-apps-streamlit-app-sw3u0r.streamlit.app/)
- [Streamlit Documentation](https://docs.streamlit.io/library/advanced-features/configuration)

