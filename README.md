# CloudsLab
HealthFog
An ensemble deep learning based smart healthcare system for automatic diagnosis of heart diseases in integrated IoT and Fog computing environments


Quick installation guide
HealthFog uses a master-slave design as shown in the figure above. To setup HealthFog in your fog environment follow these steps: Note: You need atleast two windows/linux systems with python 3. Follow the following steps in each fog node (master and worker):

Install xampp and run Apache server in windows or use Install-scripts/fogbus-install-generic.sh script in a linux device.
Clone HealthFog repo at C:/xampp/htdocs/ (in windows) or var/www/html/ (in linux) and rename the folder as HealthFog.
Change directory to the HealthFog repo folder.
Run python3 -m pip install -r requirements.txt.
Run cd HeartModel && python3 MasterInterface.py.
Run Apache service from Xampp control panel.
Follow these steps in master node:

Update config.txt with IP addresses of all worker nodes (each in a new line) after the first line of 'EnableMaster DisableAneka'.
If connected to cloud using VPN add cloud virtual IP, otherwise add public IP addresses in cloud.txt (each in a new line).
Now download and install Android/FastHeartTest.apk in an android device and enter master IP address to begin healthcare analysis!

Developer
Shreshth Tuli (shreshthtuli@gmail.com)

Cite this work
@article{tuli2020healthfog,
  title={{HealthFog: An ensemble deep learning based Smart Healthcare System for Automatic Diagnosis of Heart Diseases in integrated IoT and fog computing environments}},
  author={Tuli, Shreshth and Basumatary, Nipam and Gill, Sukhpal Singh and Kahani, Mohsen and Arya, Rajesh Chand and Wander, Gurpreet Singh and Buyya, Rajkumar},
  journal={Future Generation Computer Systems},
  volume={104},
  pages={187--200},
  year={2020},
  publisher={Elsevier}
}
References
Shreshth Tuli, Redowan Mahmud, Shikhar Tuli, and Rajkumar Buyya, FogBus: A Blockchain-based Lightweight Framework for Edge and Fog Computing. Journal of Systems and Software (JSS), Volume 154, Pages: 22-36, ISSN: 0164-1212, Elsevier Press, Amsterdam, The Netherlands, August 2019.
Shreshth Tuli, Nipam Basumatary, Sukhpal Singh Gill, Mohsen Kahani, Rajesh Chand Arya, Gurpreet Singh Wander, and Rajkumar Buyya, HealthFog: An Ensemble Deep Learning based Smart Healthcare System for Automatic Diagnosis of Heart Diseases in Integrated IoT and Fog Computing Environments, Future Generation Computer Systems (FGCS), Volume 104, Pages: 187-200, ISSN: 0167-739X, Elsevier Press, Amsterdam, The Netherlands, March 2020.
Shreshth Tuli, Nipam Basumatary, and Rajkumar Buyya, EdgeLens: Deep Learning based Object Detection in Integrated IoT, Fog and Cloud Computing Environments, Proceedings of the 4th IEEE International Conference on Information Systems and Computer Networks (ISCON 2019, IEEE Press, USA), Mathura, India, November 21-22, 2019.


