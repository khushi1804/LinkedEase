Auto Job Applier for LinkedIn

Overview

This project automates the LinkedIn job application process using Selenium and Python. It filters job listings based on user preferences and automatically fills out application forms, including answering common questions.

Features

Automated Job Application: Apply for jobs with a single click.

Easy Apply Support: Fills in application details for jobs with the "Easy Apply" feature.

Customizable Inputs: Users can specify answers for common job application questions.

Resume & Cover Letter Upload: Automatically uploads the latest resume and cover letter.

Salary & Notice Period Handling: Handles salary expectations, notice period, and citizenship questions.

Manual Review Option: Allows users to review applications before submission.

Technologies Used

Python

Selenium

Chrome WebDriver

LinkedIn API (Future Development)

Setup Instructions

1. Clone the Repository

git clone https://github.com/khushi1804/LinkedEase.git
cd LinkedEase

2. Install Dependencies

pip install -r requirements.txt

3. Configure Application Inputs

Modify the config.py file to set your preferences:

# Default Resume Path
default_resume_path = "D:\\Resume\\Khushi_Resume.pdf"

# Years of Experience
years_of_experience = "0"

# Visa Requirement
require_visa = "Yes"

# LinkedIn Profile URL
linkedIn = "https://www.linkedin.com/in/khushi-singh-3003951bb/"

# Expected Salary
desired_salary = 2400000  # Example: 2400000 for 24 LPA

# Notice Period
notice_period = 0  # Example: 30 for 1 month

4. Run the Script

python auto_job_applier.py

How It Works

Launches LinkedIn: Logs into your LinkedIn account.

Filters Jobs: Uses your preferences to filter job listings.

Auto-Fills Applications: Enters details like experience, salary, and citizenship status.

Uploads Resume & Cover Letter: Ensures your latest resume and cover letter are used.

Submits Applications: Can pause for manual review or submit automatically.

Future Enhancements

Integration with AI-based Resume Selection

Better Error Handling & Logging

Enhanced Filtering Options for Job Preferences

Contributing

Feel free to fork the repository and create pull requests for improvements!

License

This project is licensed under the MIT License.


