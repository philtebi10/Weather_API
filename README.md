Weather Dashboard
This project is a Weather Dashboard that fetches real-time weather data for various cities using the OpenWeather API. The application retrieves weather information such as temperature, humidity, conditions, and more. Additionally, it saves the data to an AWS S3 bucket for storage and future reference.
Features:
- Fetches weather data from the OpenWeather API.
- Displays key weather metrics such as temperature, humidity, and conditions.
- Saves weather data to an AWS S3 bucket.
- Supports multiple cities, with the ability to add more.
Technologies Used:
- Python
- OpenWeather API
- AWS S3
- boto3 for AWS interaction
- requests for API requests
- dotenv for environment variable management
How to Run:
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repository-name.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Set up environment variables for OpenWeather API Key and AWS S3 Bucket Name using a .env file.
4. Run the application:
    ```bash
    python weather_dashboard.py
    ```
    Screenshots

Below are some screenshots of the Weather Dashboard in action:

    Dashboard Screenshot
    The first screenshot shows the real-time weather data retrieved from the OpenWeather API. It displays key weather metrics, including temperature, humidity, and conditions for the selected city.

    Weather Data Overview
    This screenshot highlights the full weather data overview for a city, including detailed weather conditions and a timestamp for when the data was fetched. This data is stored in AWS S3 for future reference.

    S3 Bucket Storage
    The following screenshot shows the AWS S3 bucket where the weather data is stored. This data is kept in JSON format, allowing for easy access and analysis.
Struggles & Overcoming Challenges:
When I first started this project, I faced several challenges. One of the main obstacles was interacting with AWS S3 using Python. The AWS SDK (boto3) documentation was vast, and I struggled to figure out the correct methods and credentials. However, I overcame this by breaking down the process into smaller tasks, reading through official documentation, and seeking help from online communities. Eventually, I gained confidence in working with AWS and successfully implemented the storage of weather data.
Connect with Me:
- LinkedIn: Phil Tebi
    [https://www.linkedin.com/in/phil-t-27597125a/](https://www.linkedin.com/in/phil-t-27597125a/)
