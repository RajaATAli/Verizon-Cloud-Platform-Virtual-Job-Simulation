### INTRODUCTION

- This python project is aimed at showcasing some characteristics of cloud-native web applications - `redundancy, resilience and least-privileged. `
- There is no actual cloud resources associated with the exercise as this is just a simulation.
- Look into the `k8s project` for a real-life example of interacting with live environment. 

**Followed is the explanation of the terms**

- Redundancy: Kill an instance (VM or Container) of the App while it's running, and check if the App continues to work & provide service
*Note: This is to test that the system is stable enough for parts of its underlying resources to fail and not affect up time.*

- Resiliency: Kill an instance (VM or Container) of the App while it's running, and check if the instance (VM or Container) restarts/recovers with no human intervention, and continues to provide service
*Note: This is to test the ability of the system to recover from failures and continue to function with minimal interaction.*

- Least-Privilege: Check if the App is not using admin or root level access
*Note: This is to ensure that the application is secure enough so that should there be a security breach it will likely be limited due to the restricted access and permission of the user running the external facing application.*

### DEPENDENCIES AND REQUIREMENTS

You will need to have python2.7 or python3 installed on your machine in order to
run this task.

[Python for Windows](https://www.python.org/downloads/windows/)
[Python for Linux](https://www.python.org/downloads/source/)
[Python for MacOS](https://www.python.org/downloads/macos/)
[Python Installation Tutorial](https://www.tutorialsteacher.com/python/install-python)

### USAGE

After you have made sure that python is installed on your system, you can run this exercise by simply running the python script `cloud-app.py` in this folder and follow the prompts.

##### Windows
Press “Window+R” to open the “Run” box and type “cmd” in the drop-down menu to
open Command Prompt
`$ python /path/to/downdloaded/project/files/cloud-app.py`

##### Linux
Open the terminal/console application on your Linux machine
`$ [python|python3] /path/to/downdloaded/project/files/cloud-app.py`

Using commands suggested in the prompt you can test the 3 characteristics
mentioned in the introduction section.

---
 Author: Lan Kostrikin
 Date:   20 Feb 2023
