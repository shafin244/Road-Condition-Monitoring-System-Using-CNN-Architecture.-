# Road-Condition-Monitoring-System-Web APP-establishment- using- Python-&- Machine-Learning.
This research presents an automated system that uses artificial intelligence to monitor road conditions, 
specifically detecting potholes and water accumulation during rainy seasons. The system employs a 
Convolutional Neural Network (CNN) to analyze aerial images captured by surveillance drones, enabling 
cities to better plan and prioritize road maintenance activities. The AI model processes these images to 
classify roads as either in good condition or requiring maintenance, allowing for more efficient allocation 
of resources. 

<img width="1949" height="1032" alt="image" src="https://github.com/user-attachments/assets/d3b477b9-2d1e-4223-9ba0-f06003eabbdd" />

Training was conducted on a dataset of 4,200 road images, with validation performed on 900 additional 
images. The CNN architecture follows a VGG-like structure with five convolutional blocks of increasing 
filter sizes (32→64→128→256→512), each followed by max pooling operations. The network includes 
dropout layers to prevent overfitting and uses binary cross-entropy as the loss function. By optimizing the 
decision threshold to 0.3 instead of the conventional 0.5, the model achieved classification accuracy 
exceeding 95%, representing a significant improvement over comparable study. 
Unlike most existing approaches that focus solely on structural defects, this system successfully identifies 
both potholes and water accumulation issues, providing a more comprehensive assessment of road 
maintenance needs. According to research cited, poor road conditions cost billions annually in vehicle 
repairs and operating costs, highlighting the economic importance of timely maintenance. 
The proposed solution addresses several limitations of traditional inspection methods: subjective 
assessment, inefficient resource allocation, delayed response times, and limited coverage. The integration 
of GPS-tagged imagery with AI analysis creates a practical framework for municipal authorities to 
implement proactive maintenance strategies. The system is designed to operate with images collected by 
drone surveillance systems that capture aerial footage of city roads, with the data sent to a central server 
for processing. 
