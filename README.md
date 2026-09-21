# GitHub Challenge

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="200px" />

Hey there!

Your challenge is ready.
Follow the instructions provided for this challenge and complete the required tasks in this repository.

Make sure your work is committed and pushed to your repository before submission.

Good luck!

From the given repository, we can tell that the service which is being monitored is of a Payment Gateway. It basically processes the payment and projects the information and the status of the payment. In the given project we will be using AI operations to manage and automate the given data pipeline and to find out the anomalies with minimal efforts with the help of AIOps. We'll be using AIOps to automate, manage, detect anomalies and correlate the data pipeline.

From the given data we can tell that there are seven fields in the data log which are as follows: timestamp, service, response_time_ms, cpu_percentage, memory_percentage, log_level, message. In which the actual logs are timestamp, response_time_ms, cpu_percentage, memory_percentage and service, log_level, message are the outputs or the messgaes of the logs which justifies the scenario such that what is actually being processed by a particular log.

According to the logs we can tell that there are three scenarios in the log data, one is the normal INFO output which confirms that the payment has been successfully done and the other two are ERROR messages one for 'Payment servuce timout' and other for the 'Database connection timeout'.

By executing the pipeline we can see that the pipeline is reading all the logs and is able to identify all the present anomalies in the log file. But the pipeline is not able to show the detected events and also its not consuming and projecting the events that is being detected. Now the code detects 2 number of anomalies. Now after checking and correcting the files anomaly-detector.py and the aiops_pipeline.py we can see that noe the events are correctly being produced, anomalies are detected and the topics are being consumed sucessfully.

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

