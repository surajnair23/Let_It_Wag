# LetItWag

Final project for INFO 5100 - Application Engineering Development course at Northeatern University's College of Engineering as a part of it's Masters in Science Information Systems coursework. The course aims at strengthening students knowledge of Java Object Oriented concepts using Java 7(the project has bits of Java 8 which were beyond the scope of the course curriculum at the time of implementation).  

You can find more about the course at http://msis.neu.edu/fall2018/11521.pdf

## Description

• Let It Wag, a project built in JAVA Swing framework using the combination of Singleton and Factory Design Patterns.

• The core concept of the project was the ability to report stray pets across geographical areas and being able to monitor their status after they are taken into shelter homes.

• To make it a feature-rich application, we implemented Splash Screen, JBrowser for consuming Google Maps location features, JFreeCharts for visualization of analytical data, JavaMail for Email using SMTP, Log4J for logging all user and system actions and DB40 database model to store the data with proper validation and authenticity.

• Apart from this, the system had over 18 user roles spanning across multiple networks involving 8 major workflows and was capable to handle multiple employees spanning across the ecosystem, from the user to the pet shelter office administration and field workers. It also had the ability for the pet shelter to access supply chain and medical facilities on a work-request basis.

• The project utilized AbsoluteLayout, BorderLayout and CardLayout at different screens as necessary.

## Design & Considerations

• The project was built upon an ecosystem model which allowed for scalibilty both vertically and horizontally.

• The administrator had the option to include more cities of operation(referred to as network) and additional organizations of type Hospital, NGO and Merchant. There could be multiple organizations belonging to each category thus leveraging the Factory Design Pattern to create them.

• An assumption made was users are not a part of the system as employees of any organization and thus roles are seperate. No employee is allowed to report a pet, similarly users(people who report the pet) are not allowed to raise a direct request for medical attention to a stary pet or request for food etc. This was avoided to ensure we have a simpler implementation with stronger roles for all our entities.

## Running the application locally

You will need to run the file userinterfce.MainJFrame.java in your IDE.
