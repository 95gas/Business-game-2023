# Business-game-2023

## Object: Malware Detection

The rapid growth of app development in the smartphone market has made it an easy and accessible target for Malware.

A Malware is any software intentionally designed to cause disruption to a computer, server, client, or computer network, leak private information, gain unauthorized access to information or systems, deprive access to information, or which unknowingly interferes with the user’s computer security and privacy.

When Malware infects an operating system (OS), it tries to avoid detection by antivirus programs and gain control over the OS by changing Permissions.

Permissions are the authorizations that an app requests from the user to access device features, such as the camera, SMS, location, contacts, and so on.

The increasing number of native OS Permissions and developers’ ability to create custom Permissions provide plenty of options to gain control over devices and private data.

Therefore, Permissions could be of great importance in detecting a Malware. Analyzing Permissions can help identify suspicious apps that may pose a risk to device security.

The challenge is to create an efficient system that curbs the threat of Malware using machine learning techniques to classify benign and malicious Apps.


## Assesment
The quality of your forecasts will be evaluated by calculating the F1 score, given by: 2*Precision*Recall/(Precision+Recall).

## Strategy
We implemented a NN as solution to the problem. 

## Results
The NN performed good but poor. We got a F1 of 0.83378 placing 53 / 62 :(

## Improvements
We can implement the solution by working on the data first by selecting only some features or using the PCA technique. Regarding the model, we might try to implement an SVM. 


