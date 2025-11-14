<u>3.0 Technical Specifications and Design</u>

3.1 Design

Our main core design prinicple will be:
<br>
<br>
  Balance: Using balance we will be focusing on making the app visually apealing with everything perfectly spaced out and align. This will give the user mushc more enjoyment
           the app rather than it just being an 'eye-sore'. With balance we also allow the user to navigate much easier allowing them to switch between their differnt 'tabs' and 
           'redirection' screens. With balance we can bring in the other subcategories such as allignment and proportion. These will mainly be done in the css style and if                  anything is directly needed only once for that single line then it will be 'in-line' styling
           
  - This core principle will as mentioned before allow the user to naigate the app much easier. This leads to a greater rating and more time spent on the app which can then lead     to sponors and so on. If sponsors are able to be obtained this will give us the oppurtunity to make drastic changes to the app in security enhancements and better UI             upgrades.

  - Our project as mentioned above will be a mobile app. There are actually mobile programming applications that allow this to be done much easier than a normal vscode full-         stack applicaiton.

  - For our framework we plan to use a mix of tsx/python giving us many customization options. For our database I believe we plan to use fastAPI since this is what me and cadet      Jeffers are used to using from our internships.

Include a workflow diagram to visually summarize the design in a way that is accessible to a low-technical audience.

3.2 Architecture Approach
Suggested Word Count: 300-500 words
This section should offer a detailed breakdown of the technical components in your project. Begin with a comprehensive component diagram that shows all the key components and their relationships. This diagram should be more detailed than the one in the Design section.

<img width="1068" height="713" alt="image" src="https://github.com/user-attachments/assets/6403910d-cf9d-4d7f-a0a1-d922105ef071" />


Following the diagram, provide an in-depth explanation of each component in individual sections. Include details such as API endpoint names and their documentation (preferably in OpenAPI format), database schemas, and any necessary sequence or workflow diagrams for each component. If you are using a specific framework or service, explain how it is implemented and what is required for it to function. Additionally, if your project follows an architectural pattern, such as event-driven or microservice architecture, provide a thorough explanation of how it is applied and integrated into the project.

- The backend of our application will deal with the logic related to the server, storing the data given, and the functionality of the application usually knowwn as the brain of the application and like a brain it connects with other systems to work or send requests for vital information like payment, infrastructure of the app and security. The security within the backend ensures that all functions are protected and that nothing can damage the system from outside attacks.

- The reverse proxy also has a system of security policies it follows while completing its main task of being the gateway that deals with client requests ultimatley prioritized for the increase of performance and balancing loads better. The crucial impact the reverse proxy will have is that during the event of a server crash it will detect the issue and reroute the traffic to capable servers while the other is down.

- The frontend is usually what the users base their experience off of due to the capabilities and usability of the application user interface where it is not complex / simple for a new user to travel the page without confusion. This being the main image of the application due to the visual aspects being present will make or break the application because if it does not please the user then they will just find another application for their preference. buttons will be big enough to press without error and not to big where it becomes an inconvenience with casual colors that will not over stimulate or irritate the users eyes following the Aesthetic-Usability Effect mainly increasing the effect the UI has on users.

- We are using python as our main language for our backend due to the reliability of the language while offering multiple features like multiplatform capabilites allowing for all users to get the app no matter the device they own, The simple syntax interaction where if an error occurs we will be able to quickly see the issue and repair it, the extensive libraries that we can use to make the application more compatable with other systems. As well as the easy use of processes where if we need to we can limit users interactions, have a shutdown for some servers while still allowing crucial servers to run, and automations of processes to help increase productivity and decrease the time for a user to get the response they need.

- finally the other required languages that are used for application development like HTML for the actual interface, We will also use TSX or typescript execute for active application alterations needed like a command line interface to run scripts needed, the use of TSX will be vital during the finals steps of our application to help with readability and maintenance of the application's systems to ensure things are working and allowing for possible debugging without possibly changing crucial code that could break the entirety of the application.


3.3 Software Solution
Suggested Word Count: 100-150 words - mostly images
Using a diagramming tool (either one reviewed in class or one of your choice), create a series of wireframes or prototypes that illustrate the flow of your project. Include detailed annotations within the images or use numbered references, with corresponding explanations provided in the document.

For example, if there is an "add" button on a webpage, describe what the "add" action does and which component or requirement it is connected to. If your project requires an overall workflow explanation, start with a high-level diagram that outlines the approach before diving into the specifics.

<img width="1068" height="713" alt="image" src="TechSpecs.drawio"/>
