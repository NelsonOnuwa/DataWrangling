Data

Data is a collection of raw facts and figures that we need to process to extract meaning or information
Data can be any number (0 to 9), characters (A to Z, a to z), text, words, statements, special characters (*, /, @, #, etc), pictures, sound, or videos that are context less, meaning little or nothing to a human being.

For Example: Will Turner, 48, link down, blue, junior, ocean, street

The data is raw and there is no meaning to it but if we organize this data:

Will tuner

H.no - 48, blue ocean,

Link down street,

Now, this looks like an Address of the person named Will Turner. Whereas, in the above example it is impossible to make out the meaning of the words.

Data is nothing unless it is processed or is aligned in some context. The data when structured and organized (when the data is processed in some manner) results in Information.

Information is “ processed data that is organized, structured or presented in a given context so that the data deliver some logical meaning that may be further utilized in decision making”.

Data is something that you can consider as a low level of knowledge where you have some scattered, uncategorized, unorganized entities that do not really mean anything. Whereas Information is the second level of knowledge, where you wire up the data and assign it some context so, the data becomes meaningful.



Data Format


There are the four (4) data formats commonly seen in data processing, they include structured, semi structures, quasi-structured and unstructured data format. 

Structured data is highly organized, easily accessible and retrievable from where it is stored. It is machine-readable.

Semi structured data is partially organized and difficult to retrieve. HTML, XML and other markup languages are examples of semi-structured data.

Quasi-structured data involves specifically textual data that has a temporal state and having erratic data formats. Data streams on a social media page or clickstream data from Google searches are examples of quasi-structured data.

Unstructured data is not organized, it is difficult to access and to retrieve from where it is stored. Data from social media posts, emails, and chats are examples of unstructured data. Unstructured data could be stored using XML, JSON, or CSV file formats and It is human-readable.



Data Types


String, Integers, float and boolean are some common examples of data type.



Big Data 


Big Data defines a situation in which data sets have grown to such enormous sizes that conventional information technologies can no longer effectively handle the size of the data set. Big data grows exponentially (becoming more rapid) and is boundless (volume), has varied formats (variety), and has high complexity (voracity and velocity). The four Vs of big data: volume, variety, voracity and velocity.
Big data emerges from a variety of sources comprising of Internet of things (IoTs), factories, enterprise resource planning and customer relations management systems according to industry experts.



Big Data Security


Many big data tools used by enterprises to identify business opportunities, improve performance, and drive decision-making are open source and not designed with security in mind. This huge increase in data consumption leads to many data security concerns, which include Information theft, distributed denial-of-service (DDoS), ransomware etc.
It is difficult to secure big data because of constant access by different users, the presence of open source tools and the multiple feeds of data from sources with different protection needs. Big data security challenges can be experienced both on-premises and in the cloud. It is prevalent in non-relational database, endpoint vulnerabilities, data mining solutions, access distributed data processing and storage task.

Data security threats can he handled using security techniques such as, user access centralized key management, encryption, and intrusion detection and prevention (IDPS). One way that organizations can protect data is through encryption, which applies algorithms to scramble data so that it is readable only by someone who holds the key to decrypt it. Encryption takes a piece of data, commonly called the plaintext, combines it with a cryptographic key. This produces a scrambled version of the data called the cipher text. It is possible to decrypt the data to recover the plaintext using the key, but without the key, the cipher text hides all information about the original data, other than its length.
Using user access control to protect data, we turn to cryptographic techniques to secure data in storage. The primary goal of this technique is to enforce access control to data stored in potentially untrusted repositories. That is, we give authorized parties access to the data they need while ensuring that unauthorized parties, either outsiders trying to gain access or malicious insiders in the organization managing the repository, cannot access sensitive data.
An intrusion detection and prevention system (IDPS) is a solution that monitors network for simpler threats and then takes flag complex threats to alert security teams to stop any threat detected.
Internet of things (IoTs) are physical objects such as our phones, appliances, lighting systems, irrigation systems, security cameras, vehicles and cities equipped with sensors and software, which enable them to interact with each other by collecting and exchanging data via wireless network, with little human intervention. The Internet of things (IoTs) simplifies and automates complicated tasks by uniting the objects under one common infrastructure, transforming them into smart objects and remotely controls them.





Internet of things (IoTs)



Internet of things (IoTs) are physical objects such as our phones, appliances, lighting systems, irrigation systems, security cameras, vehicles and cities equipped with sensors and software, which enable them to interact with each other by collecting and exchanging data via wireless network, with little human intervention.

In the late 1960 and 1970, the inquiry into the idea to connect personal computers (PCs) to other machines began and by 1980s, the invention of local area networks (LANs) provided an effective way to share documents and data across PCs in real time. The invention of the internet by mid 1990s extended LANs capabilities globally and in 1997, a British technologist Kevin Ashton, cofounder of the Auto-ID Center, began working on radio-frequency identification (RFID) technology that would allow physical devices to connect via microchips and wireless signals. During a speech in 1999, Ashton invented the phrase “the Internet of Things”.

The Internet of things (IoTs) simplifies and automates complicated tasks. It unites the objects under one common infrastructure, it transforms them into smart objects and it remotely controls them.

In transportation, the internet of things (IoTs) technologies ensures the proper tracking and delivery of goods from the manufacturer to the end user in real time. This promotes speed, efficiency and reducing personnel costs. It can also provide a medium for checking the integrity of goods through barcode, the location of goods via GPS, the monitoring of parameters and status variables of the assets via sensors and their transmission via Wi-Fi or GSM/GPRS network. Thus preventing losses, ensuring safety in storage of goods and efficiently locating the products needed.

The collection of useful data about food crops and the detection of potential diseases in advance in agriculture, has led to improved agricultural production processes and the ability to meet food demands.

In smart cities, the installation of sensors linked with many other devices over the internet gives information to users about malfunctions, electrical failure and issues with traffic jams, energy supply, water shortage, security incidents, etc. In addition, in smart cars the early detection of potential car failure, tire pressure, fueling needs and regular maintenance increases comfort and upgrade driver’s experience.

The healthcare services can better monitor the heart rate and skin temperature, they can predict different symptoms and prevent potentially life threatening diseases through internet of things (IoTs) technologies.In a global pandemic, fast data collection and diversity is possible.

With internet of things (IoTs) devices, specific challenges ranging from the inadequacy of security protection leading to loss, stolen, or incorrectly used data to the safety concerns in smart cars and and the electronic waste from IoT products. In addition, the insufficient investigation of long-term effects of IoT technologies and its sustainability are bound to have specific potential drawbacks that need careful consideration.






Data Wrangling


When data scientists identify useful data sources for solving the business problem they then proceed to extract, clean, and format the necessary data from those sources. Data wrangling is the process that ensures that the data is in a format that is clean and accurate to yield a data set that is suitable for exploration and analysis. Data wrangling extracts the most valuable information from the dataset.
The process of data wrangling includes first finding the appropriate data that is necessary for the analysis. This data can be from one or multiple sources, such as tweets, bank transaction statements in a relational database, sensor data, and so on. Next, the data is cleaned, where there is missing data, we will either delete or substitute it with the help of several techniques. If there are outliers, we need to first detect them and then handle them appropriately. If data is from multiple sources, we will have to perform join operations to combine it.

The primary challenge of data wrangling stems from the time commitment involved to complete the task and the little amount of automated work that could be carried out on the dataset. Understanding large volume of datasets, the processing of the datasets and combination of different data types possess a significant challenge.
Using the appropriate tools such as python, data wrangler, google data prep, parse hub, excel and talend can overcome the challenges of data wrangling.


