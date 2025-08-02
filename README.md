# Court-Data-Fetcher-Mini-Dashboard
CourtTask built in Google Colab that automates and manages court-related tasks using modern Python tools. It combines web automation , a local Flask server for endpoint control, tunneling with Ngrok, and data handling with pandas. Ideal for building prototypes of legal tech tools, data extractors, or automation workflows for case processing.
## 🚀 Features

- 🔁 Web automation with **Playwright**
- 🌐 Public-facing endpoints using **Ngrok**
- 🖥️ Local API server using **Flask**
- 📊 Data processing with **pandas**
- ☁️ Runs seamlessly in **Google Colab**
## 📦 Requirements

Make sure the following Python packages are available (install via `pip install -r requirements.txt`):
asyncio
flask
google
nest_asyncio
pandas
playwright
pyngrok
sqlite3


> 📝 Note: `sqlite3` is built into Python. `playwright` requires an extra setup step.

## 🛠️ Setup Instructions

### 🔁 Clone the Repository

git clone https://github.com/yourusername/courttask.git
cd courttask
## Create a Virtual Environment (Optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

## Install Dependencies
pip install -r requirements.txt
#  Install Playwright Browsers
playwright install

## 📓 Running the Notebook

➤ On Google Colab
Upload courttask.ipynb to your Google Drive.

Open it via Google Colab.

Run all cells.
## 📌 Notes
- Ngrok is used to expose local endpoints to the internet. Make sure to sign in to your Ngrok account or add your token if needed.

- If you plan to use Google APIs, proper authentication and credentials are required.
## 📄 License
This project is licensed under the MIT License. Feel free to modify and adapt it to suit your own needs.
#🙌 Contributing
Contributions are welcome! Feel free to fork the repository, submit issues, or open pull requests.


