services:
    ```bash
    docker-compose up --build
    ```

3. **Set Up the Environment**:  
   After building the Docker containers, you can initialize the environment by running the setup script:
    ```bash
    ./setup.sh
    ```

### Additional Setup (Optional)

If you wish to manage Python dependencies locally or develop outside the Docker container, you can install the necessary Python packages using:
```bash
pip install -r requirements.txt
```

## Project Workflow

1. **Data Ingestion**: Collect and load raw game data into the system.

2. **Data Cleaning**: Preprocess the data by handling missing values, formatting data, and normalizing features.

3. **Exploratory Data Analysis (EDA)**: Profile the data to identify key insights, patterns, and potential outliers. This step helps guide feature engineering and model selection.

4. **Model Training**: Train machine learning models to predict player retention or other key game metrics. Experiment with various algorithms and evaluate performance.

5. **Model Evaluation**: Assess model performance using appropriate metrics, such as accuracy, precision, recall, or custom game-specific KPIs.

6. **Deploy and Analyze**: Once validated, the models can be deployed within the Dockerized 
