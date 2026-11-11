# SWYNEX Internship – Task 3
## Monitoring and Cost Awareness

### 1. Project Overview
This document describes a basic monitoring, alerting, cost-awareness, and access-control plan for the Titanic Passenger Survival Prediction machine learning project developed using Python and Scikit-learn.

### 2. Monitoring and Status Checks

The following checks can help monitor the project:

- **Application status:** Check whether the machine learning application or notebook runs successfully.
- **Model status:** Verify that the trained Logistic Regression and Random Forest models are available.
- **Prediction status:** Check whether the model produces valid predictions.
- **Error logs:** Record errors and exceptions to identify problems.
- **Performance monitoring:** Monitor prediction time and model evaluation metrics.

For a notebook-based project, Python print statements and error messages can be used for basic monitoring.

### 3. Simple Alert Idea

A simple alert system can be designed to identify problems.

- Generate an alert if model prediction fails.
- Display an error message if required input data is missing.
- Notify the developer if the application becomes unavailable.
- Check model performance regularly to identify unexpected changes.

For the current project, error messages and notebook outputs can be used as basic alerts.

### 4. Cost Awareness Checklist

- Use free or low-cost development tools such as Google Colab and GitHub.
- Stop unused cloud notebook sessions.
- Avoid running unnecessary training processes repeatedly.
- Monitor cloud storage and computing resource usage.
- Delete unnecessary temporary files.
- Use suitable dataset sizes and efficient code.

### 5. Security and Access-Control Checklist

- Keep passwords, API keys, and secret credentials private.
- Never upload sensitive information to a public GitHub repository.
- Use strong passwords for online accounts.
- Enable two-factor authentication where available.
- Give repository access only to authorized users.
- Review file permissions before sharing project files.
- Avoid storing personal or confidential information in the dataset.

### 6. Conclusion

Monitoring helps identify errors and maintain reliable machine learning operations. Cost awareness helps avoid unnecessary resource usage, while access control protects project files and information.

This task helped me understand the importance of monitoring, basic alerting, cost management, and security practices in machine learning projects.
