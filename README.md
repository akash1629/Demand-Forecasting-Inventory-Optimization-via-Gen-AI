# Demand-Forecasting-Inventory-Optimization-via-Gen-AI
Forecasting
# Generative AI–Driven Demand Forecasting & Inventory Optimization

## Overview
This project combines traditional time-series forecasting (ARIMA, Prophet) with Generative AI (GPT-4) to predict product demand and optimize inventory. By unifying demand planning processes, we aim to:
- Reduce forecast errors by 18%
- Decrease stockout events by 22%
- Trim inventory holding costs by 15%
- Save approximately INR 2.8 million annually

## Project Structure
- `data/`: Contains input CSV files (sales_data.csv, inventory_data.csv, macroeconomic_data.csv).
- `notebooks/`: Jupyter notebooks for exploratory analysis.
- `src/`: Core Python scripts for data processing, forecasting, optimization, and reporting.
- `models/`: Serialized models (ARIMA, Prophet, GPT embeddings, hybrid model).
- `outputs/`: Forecast and optimization results, generated reports.
- `docs/`: Supplementary documentation and design artifacts.

## Setup Instructions
1. **Clone this repository**:
    ```bash
    git clone https://github.com/YourUserName/generative_ai_demand_forecasting.git
    cd generative_ai_demand_forecasting
    ```
2. **Create a virtual environment** (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # Mac/Linux
    venv\Scripts\activate     # Windows
    ```
3. **Install requirements**:
    ```bash
    pip install -r requirements.txt
    ```
4. **Obtain OpenAI API Key**:
    - Sign up at [OpenAI](https://platform.openai.com/)
    - Create a `.env` file in the project root with your API key:
      ```
      OPENAI_API_KEY=your_api_key_here
      ```
5. **Run scripts**:
    - **Data Preprocessing**:
      ```bash
      python src/data_preprocessing.py
      ```
    - **Traditional Forecasting**:
      ```bash
      python src/forecasting_traditional.py
      ```
    - **Generative AI Forecasting**:
      ```bash
      python src/forecasting_generative_ai.py
      ```
    - **Hybrid Forecast**:
      ```bash
      python src/hybrid_forecasting.py
      ```
    - **Inventory Optimization**:
      ```bash
      python src/inventory_optimization.py
      ```
    - **Dashboard**:
      ```bash
      streamlit run src/visualization_dashboard.py
      ```
    - **Reporting**:
      ```bash
      python src/reporting.py
      ```

## License
This project is available under the MIT License. See [LICENSE](LICENSE) for details.

## Contact
For questions or feedback, please reach out to [akashraut16299@gmail.com](mailto:akashraut16299@gmail.com).

