# Health-management-and-analysis-system
## System Description
With the rapid development of society, the increase in material living standards has brought about an increase in the incidence of obesity, diabetes, hypertension and other cardiovascular and cerebrovascular diseases. 
At the same time, the development of information technology and the popularization of miniaturized home medical equipment, the realization of personal health management is no longer a castle in the air. In this paper, we first analyse the requirements of the health management analysis software, and through the analysis of the current situation of health management software at home and abroad, we initially determine the functional requirements of the health management analysis system, and on this basis, we determine the performance and compatibility requirements of the system, and then carry out the overall design of the system architecture and implementation mode. 
The system adopts a `B/S architecture`, with a `browser` on the user side and a `database layer`, application service layer and web service layer on the server side. The application server is developed using the `Django framework` based on the Python language, and the web service layer uses `the NGINX web server`. The system evaluates the health status through various indicators of the health condition and generates health recommendations for the effective management of health information.

## System subsystems division
The system is divided into the following six subsystems according to the categories of users and for their functions: health information management subsystem, health assessment subsystem, health criteria management subsystem, health analysis subsystem, user rights management subsystem and system setting subsystem.

## System business process
Through the individual user through the entry of personal health information, using health evaluation model through health evaluation criteria for personal health assessment, the assessment results using health intervention strategy for personal behavior and living habits of health intervention, the final results through the personal health indicators of the change of feedback to the system of personal health information.
The health management user uses the health evaluation model to analyse the group health information, summarise the rules through the health evaluation criteria, adjust the health intervention strategy, and finally feedback the changes in personal health indicators to the system's personal health information.

