# Welcome to our Weather Dashboard Demo Project 

## This project is part of 30 Day DevOps Challenge - Day1

### Project Overview
This project is a Weather Data Collection System that demonstrates core DevOps principles by combining:
- External API Integration (OpenWeather API)
- Cloud Storage (AWS S3)
- Infrastructure as Code
- Version Control (Git)
- Python Development
- Error Handling
- Environment Management
  
### Features
- Fetches real-time weather data for multiple cities
- Displays temperature (°F), humidity, and weather conditions
- Automatically stores weather data in AWS S3
- Supports multiple city tracking
- Timestamps all data for historical tracking

### Technical Architecture
- Language: Python 3.x
- Cloud Provider: AWS (S3)
- External API: OpenWeather API
- Dependencies:
    * boto3 (AWS SDK)
    * python-dotenv
    * requests

#### Project Structure

![image](https://github.com/user-attachments/assets/1291bacb-812f-436e-9058-1b33c16281f1)

```
### Setup Instructions
1. Clone the repository:
--bash
git clone https://github.com/mazin990/weather-dashboard-demo.git

3. Install dependencies:
bashCopypip install -r requirements.txt

4. Configure environment variables (.env):
CopyOPENWEATHER_API_KEY=your_api_key
AWS_BUCKET_NAME=your_bucket_name

4. Configure AWS credentials:
bashCopyaws configure

5. Run the application:
python src/weather_dashboard.py

What I Learned

AWS S3 bucket creation and management
Environment variable management for secure API keys
Python best practices for API integration
Git workflow for project development
Error handling in distributed systems
Cloud resource management

```
#### Final result from aws console

![image](https://github.com/user-attachments/assets/1dc72508-c0d5-4f71-b285-2f6e2277ab17)
