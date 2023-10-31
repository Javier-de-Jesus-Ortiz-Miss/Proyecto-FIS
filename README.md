# Entrega 2

## What will you find in this document?
In this document you will find the second delivery of project 1 in the subject of Fundamentals of Software Engineering of Group A, with all the aspects to be evaluated in the Rubric of this activity.

## List of contents
* [Product](#item1)
    * [Product description](#item2)
    * [Users/Clients](#item3)
    * [Value proposal](#item4)
* [Requirements](#item5)
    * [Functional Requirements](#item6)
    * [Non-Functional Requirements](#item7)
    * [Priorization](#item8)
    * [Artifacts](#item9)
* [Process](#item10)
    * [Process description](#item11)
    * [Individual Contribution Metric](#item13)
* [Our presentation video](#item12)
* [Preview Presentation](#item15)
    * [Presentation Format](#item16)
* [Competencies](#item17)
    * [Generic Competencies](#item18)
    * [Specific Competencies](#item19)

#
<a Product id="item1"></a>
# Product

<a Product description id="item2"></a>
### Product description

The software product is a comprehensive platform that connects enthusiasts and individuals from the music industry in a collaborative environment. This allows for agility in musician recruitment, creation of groups, and organization of musical events. Additionally, it enables the purchase, sale, or rental of musical products, with parameters tailored to the preferences of both the seller and the interested party.

<a  Users or Clients id="item3"></a>
### Users/Clients 
Our main objective is to help people so that they can interact with musicians or expand their musical knowledge thanks to the teaching system we offer. Our application is mainly aimed at:
* Musicians in general, from the newest to the most experienced.
* Music producers who promote and coordinate artists.
* Sound engineers who are responsible for designing and maintaining equipment and audio systems.
* Teachers who want to share their musical knowledge with those who are looking to learn.
* People focused on more technical roles.

<a Value proposal id="item4"></a>
### Value proposal
#### Videos to share your abilities
Our app offers the posibility to upload videos to help the user easily determine and show what they are good at and what they are looking for, this is made with the idea to help the persons that want to start a band to swiftly find the persons that they want. To complement the video we also allow to pair it with some text that you can use to put a description of your abilities and also add your cv, as an adittional option for people who are more experimented in working with a band or creating by themselves. All this is made with the objective of making easier to find persons and easier to connect with other people that look for your abilities.

#### Sell and buy objects or services
It also implements the ability to let the users post things that they want to sell or offer as a rent service; I want to clarify that the app will provide the ability to post and chat with the persos that offer the services and its made with that in mind, so currently we have not in our plans adding a method in which the users can exchange money.

#### Chat system
Because of that we also implement a messaging system that will help the users swiftly make contact with other persons to organize for buying something, selling or playing together. 

#### Search and filters for improved search
The search option will give the users the power to see only what they want, this tool will show results for things that are being sold, persons, and musicians with that abilities; if you don't want to see certain things, there also the option to filter the results, so you will only see the things that you select.


#
<a Requirements id="item5"></a>
# Requirements

<a Functional Requirements id="item6"></a>
### Functional Requirements


1. **USER/REGISTRATION:**

   * The system allows a simple and verified registration, enabling login through various options.
   * Flexibility is provided, along with clear error messages for an effective user experience.

2. **TINDER CONCEPT (system):**

   * The system aims to facilitate interaction among musicians by allowing them to create detailed profiles that include personal information, photos, videos, and musical preferences.
   * Musicians can post projects where they need collaborators, specifying the type of collaboration required and the relevant location.
   * Users can rate and leave comments about other musicians they have collaborated with, promoting reputation and trust within the community.
   * A calendar feature is included in profiles, enabling musicians to indicate their availability, and users can express their interest in projects.
   * Location is utilized to display potential matches in nearby areas, enriching the musical collaboration experience.

3. **SEARCH:**

   * An efficient search engine for multimedia content and user profiles is implemented.
   * It provides both simple and advanced search options, with suggestions and a clear display of results, including filters and sorting.

4. **CHAT:**

   * The system facilitates direct communication between users through messaging that supports various formats.
   * Real-time notifications and conversation history storage are also offered.

5. **BUY/SELL:**

   * Focused on buying and selling products, the system enables advanced search, publication, and editing of products for sale.
   * It allows ratings and reviews, promoting transparency and trust in the buying and selling process.

<a Non-Functional Requirements id="item7"></a>
### Non-Functional Requirements

<ol>
  <li>Private chat messages and geolocation data must be encrypted (security). </li>
  <li>The intented users can get to their desired function whithout getting lost (usability).</li>
  <li>Advertising within the app has to adhere to the respective advertising standards (legal).</li>
  <li>The service must be avaliable 24/7 (reliability). -For the initial stage the app must be able to support 1,000 concurrent users (perfomance).</li>
  <li>The database must be hosted on a cloud-based service that has scalability (storage).
</ol>


<a Priorization id="item8"></a>
### Priorization
| **Must Have**                                                                                                                                          | **Should Have**                                                              | **Could Have**                                                   | **Won't have**  |
|--------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|------------------------------------------------------------------|-----------------|
| Encryption of geolocation data and private messages                                                                                                    | Various options of login with simple and virified registration               | Clear error messages for an effective user experience            |                 |
| Users are able to switfly and easily get to any function                                                                                               | Search engine counts with simple and advance search with filters and sorting | Calendar implementation so users can indicate their availability |                 |
| Advertisements must be inside the legal margins                                                                                                        | Counts with the ability to buy and sell music related products               |                                                                  |                 |
| 24 / 7 availability                                                                                                                                    | The product buying service has ratings, reviews                              |                                                                  |                 |
| At the start it must be able to hold up to 1000 users                                                                                                  |                                                                              |                                                                  |                 |
| Database hosted on cloud-based service with scalability                                                                                                |                                                                              |                                                                  |                 |
| Eases the interaction between musicians with the creation of detailed profiles containing personal information, photos, videos and musical preferences |                                                                              |                                                                  |                 |
| Musicians can post projects asking for collaborators based on the location                                                                             |                                                                              |                                                                  |                 |
| Ratings and comments about your work with other musicians can be made                                                                                  |                                                                              |                                                                  |                 |
| Location is used to display potential matches your surroundings                                                                                        |                                                                              |                                                                  |                 |
| Efficient search engine for multimedia content and user profiles                                                                                       |                                                                              |                                                                  |                 |
| The messaging facilitates direct comunication with other users, also offering support for different types of formats                                   |                                                                              |                                                                  |                 |
| Real-time notifications and conversations history storage                                                                                              |                                                                              |                                                                  |                 |

<a Artifacts id="item9"></a>
### Artifacts

* [Use cases](https://github.com/Javier-de-Jesus-Ortiz-Miss/Proyecto-FIS/blob/entrega-1/Use_cases.md) 

* [User stories](https://github.com/Javier-de-Jesus-Ortiz-Miss/Proyecto-FIS/blob/entrega-1/User_Stories.md)

* [Survey](https://github.com/Javier-de-Jesus-Ortiz-Miss/Proyecto-FIS/blob/entrega-1/Survey.md)

#
<a Process id="item10"></a>
# Process

<a Process description id="item11"></a>
### Process description

We started this project with the intention of using the scrum methodology, but we did not organize ourselves in the best way, so we failed in some key aspects of this methodology, such as not being able to divide the tasks into small sections or holding daily meetings to see the progress of the project.

That's why we did not get stuck and decided to make a quick change, which was to start using the <b>Agile methodology<b>.

![image](https://github.com/Javier-de-Jesus-Ortiz-Miss/Proyecto-FIS/assets/142443060/18d7f023-843d-47d9-9f57-59848ec85531)

This methodology adapted perfectly to our needs and was very useful when organizing the distribution of roles and tasks that each of the members had to solve.

We first evaluate the best project ideas in a brainstorm. Afterwards, we organized ourselves to distribute the role that each of us was going to play in the development of the project. For this we distribute the tasks by points with equitable values ​​so that we work in equal parts. And finally, we held meetings from time to time virtually or in person to evaluate the progress we were making throughout the days, in order not to fall behind and finish the work on time.





<a Individual Contribution Metric id="item13"></a>
### Individual Contribution Metric


|  **Indicator**                                   |**Level**| **Member**            | **Percent**    |
|--------------------------------------------------|---------|-----------------------|----------------|
|  Product description                             | 1       | Aldo                  | 3.5%           | 
|                                                  |         |                       |                |
|  Users / clients                                 | 1       | Ruben                 | 3.5%           |
|                                                  |         |                       |                |
|  Value proposal                                  | 2       | Adriel                | 7%             | 
|                                                  |         |                       |                |
|  Functional requirements                         | 3       | Aldo                  | 10.5%          |
|                                                  |         |                       |                |
|  Non-funtional requirements                      | 2       | Adrian                | 7%             |
|                                                  |         |                       |                |
|  Priorization                                    | 1       | Adriel                | 3.5%           |
|                                                  |         |                       |                |
|  Artifacts                                       | 3       | Hector                | 10.5%          |
|                                                  |         |                       |                |
| Process description                              | 2       | Ruben                 | 7%             |
|                                                  |         |                       |                |
| Process management                               | 1       | Adrian                | 3.5%           |
|                                                  |         |                       |                |
| Individual contribution metric                   | 1       | Adriel                | 3.5%           |
|                                                  |         |                       |                |
| Documentation and organization of the repository | 1       | Greco                 | 3.5%           | 
|                                                  |         |                       |                |
| Make presentation                                | 3       | Greco                 | 10.5%          |
|                                                  |         |                       |                |
| Record                                           | 3       | Ruben, Adrian, Hector | 3.5 * 3 = 10.5 | 
|                                                  |         |                       |                |
| Edit                                             | 1       | Javier                | 3.5%           |
|                                                  |         |                       |                |
| Generic skills                                   | 3       | Javier                | 10.5%          |
|                                                  |         |                       |                |
| Specific skills                                  |         |                       |                |


#
<a Our presentation video id="item12"></a>
# Our presentation video (Delivery 1)

[Delivery 1 video](https://alumnosuady-my.sharepoint.com/personal/a20204029_alumnos_uady_mx/_layouts/15/stream.aspx?id=%2Fpersonal%2Fa20204029%5Falumnos%5Fuady%5Fmx%2FDocuments%2FEntrega1%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0RpcmVjdCJ9fQ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0RpcmVjdCJ9fQ&ga=1)

#
<a Preview Presentation id="item15"></a>
# Preview Presentation 

<a Presentation Format id="item16"></a>
### Presentation Format
[Canva MusicHub](https://www.canva.com/design/DAFvv-rOFAg/QtrRitfj0D4dnYrAV2s7_A/edit?utm_content=DAFvv-rOFAg&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

[Canva Artifacts](https://www.canva.com/design/DAFvzKIp3Jk/SR9AI5ofsiG-kqxJ17frpQ/edit?ui=eyJHIjp7fX0)

[Word Script](https://1drv.ms/w/s!ApgujU4FYi5Rh5By6amX33y0FyE2WA?e=GQ7JUO)



#
<a Competencies id="item17"></a>
# Competencies

<a Generic Competencies id="item18"></a>
### Generic Competencies

| <font color="red">Generic Competencies</font>                            | Description                                                                                                                     |
|-------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
|1) <font color="green">Team collaboration </font>                            |In the product development process, team collaboration is promoted by assigning clear roles and responsibilities to each team member. This fosters the ability and commitment to work effectively together to achieve the various project objectives.            |
|2) <font color="green">Time management </font>                                |The ability to manage time effectively is done through time allocation and organization of tasks within the team. Deadlines are set and progress is monitored to ensure that established deadlines are met.                             |
|3) <font color="green">Clear and precise communication </font>                |In product development, communication is promoted by creating an environment where team members feel comfortable expressing their ideas, problems, and solutions related to the project.                                  |
|4) <font color="green">Adaptable to changes </font>                           |The ease of adapting to changes is made by facing unexpected situations during the development of the project. Flexibility is promoted by having team members seek creative and proactive solutions when problems or changes arise in the project.

<a Specific Competencies id="item19"></a>
### Specific Competencies
| Specific Competencies                          | Description                                                                                                                     |
|-------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
|1) Software development                     |Achieve the development of a quality software project using tools and methods that help us comply with a systematic, disciplined and quantifiable approach.         |
|2) Innovation in software engineering                              | Achieve the creation of a software product that is applicable in various domains, optimizing resources and satisfying their respective needs                 |

