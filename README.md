## ITsecurity

<details> 
  <summary>About courses and resourses</summary>

  **Security triad (also called the AIC or CIA)** The security triad mandates protection against the loss of confidentiality, the loss of integrity, and the loss of availability of IT systems and data. Other principles include defense-in-depth and the principle of least privilege

  Step you take to reduce weaknesses reduces your risks:

  * Enforce the principle of least privilege.
  * Implement strong authentication mechanisms.
  * Train employees on risks of social engineering.
  * Regularly remind employees about their security responsibilities.
  * Implement multiple layers of security (defense-in-depth).
  * Remove or disable unneeded services and protocols.
  * Implement host-based and network-based firewalls.
  * Keep all systems up to date with patches.
  * Install and update antivirus software.
  * Add redundancies for critical systems.
  * Secure access to data with permissions.
  * Back up data and store a backup copy off-site.
  * Track access to data and systems with audit trails.
  * Encrypt critical data at rest and when transmitted on the wire.
  * Protect systems, data, and facilities with strong physical security.
  >Note 
  >Although this book isn't a comprehensive source for mitigating all risks, it does include basic information you can use as a foundation.

  Books:
  >Microsoft Windows Security: Essentials - Darril Gibson
  >Computer Network Security - Ali Sadiqui 
  >Information Technology Security Fundamentals - Glen Sagers, Bryan Hosack 
  >Foundations of Information Security: A Straightforward Introduction - Jason Andress 

  PracticeLabs - Configure Real Devices in a Virtual Environment  

  - [] Practice Labs: Security Fundamentals URL
  - [] Cyber Security Fundamentals URL
  - [] Practice Labs: Security Concepts and Management on Windows 10 URL
  - [] Linux Fundamentals URL
  - [] Network Security Tools - NMAP URL
  - [] Extra Resources
  - [] How To Create and Use Virtual Machines URL
  - [] Splunk Fundamentals - 1 hour 22 mins
  
  ![Risk](/imgformyconspect/fig1-1.jpg)


</details>

<details> 
  <summary>Topic 1</summary>
Security Fundamentals: Core Security

  * recognize the characteristics of confidentiality
  * recognize the characteristics of integrity
  * recognize the characteristics of availability
  * distinguish risk management strategies
  * recognize the characteristics of the least privilege principle
  * identify techniques for avoiding social engineering
  * distinguish between the different components of attack surfaces
  * describe the use of the new threat modeling tool
  * identify characteristics of site security
  * distinguish between the equipment used for securing computers
  * identify the security challenges of removable devices and drives
  * distinguish between the different technologies for securing mobile devices
  * identify characteristics of keyloggers

The CIA triad:
* Confidentiality
* Integrity
* Availability

Confidentiality as relates to data/information security:
* Mitigating unauthorized accsess to sensitive network assets

Accompished though vrious levels of: 
* Encryption
* Authentication
* Access controls
Confidentiality classifications
Common confidentially classifications - as exsemple:
* Public
* Internal
* Condfidential

Governmental agencies:
* Unclassified
* Restricted
* Secret
* Nop secret

The Core Concept of Integrity
* To protect data/information against unauthorized of accidental change
Encomprasses data/information
* Consistency
* Accuracy
* Validity

Data/information integrity accopmpished throught:
* Security programs which manage and detected change
* Permissions control access to assets
* Auditing and accounting processes to record change

Availability as relates to datd/information security
* the generally unfettered accessibility of recourses to users, systens and/or applications as required

Treats to Data/Information availability
* Two commons threats to data/infomation availability:
* * Natural disasters
* * Equipment failure
* * Unplanned outages
* Deliberate
* * DoS attacks
* * Network worms

The Impact of Threats and Risks
Risk managment:
* Identyfying. assessing and ptioritizing threats and risks wit focus on negative risks
Risk:
* The likelyhood of an event occuring
Threat:
* A specific risk that could result in an unwatched breach by exploiting system vulnerabilities

The purpose of a risk managment plan:
- Remove risk where possible
- Mitigate consequences of those risks which can't be prevented
The steps of a risk management plan:
- Perform a risk assessment
- - Identify risks may harm your environment
- Evaluete risks against two factors:
- - the likelihood the risks will occur
- - What impact the risks will have on your environment
- Prioritize identified risks:
- - Utilize a risk matrix to assist in risk ranking
- - Outline risk ranking/risk score
![Diagrams](/imgformyconspect/fig1-2.png)
- Respond to risks using typical methods:
- - Avoidance
- - Mitigation
- - Accertance
- - Transfer
![Diagrams](imgformyconspect/fif1-3.png)
- Risk avoidance:
- - Risk is removed by choocing to not participate in an event or activity
- Risk Mitigation:
- - Risk is minimized throught interventions which lower likelihood and/or impact of the risk
- Risk Accetace:
- - Knowing the risk and accepting the likelihood and/or impact of the risk
- Risk Transfer:
- - Shifting risk responsibility to a third perty
- Important to be of any residual risk:
- - What remains subsequent to implementing measures to lessen likelihood or impact of a negative incidient
  
Residual Risl
- Important be aware of any residual risk:
-  - What remains subsequent to implementing to lessen likelihood or impact of a negative incident

Principle Of Least Privilege
  A securirty measure than can apply to user, sysytem, program or process that defines the least amount of "rigts", or access, required to effectively accomplish its function.
  ![Diagrams](/imgformyconspect/fig1-5.png) 
  - Has been around for a long time
  - Organizations have driven organizations to focus on its implementation and ensure principle is folowed
  - - Sarbanes-Oxley
  - - HIPAA
  - - HITECH
  ![Diagrams](imgformyconspect/fig1-4.png) 
  - Difficultes lie within the diversity corporate work enviropments:
  - - Hundred thousands of users
  - - Dispersed over numerous geographical locations
  - - Require access to multiple application, file server and printers
  - - Access requirements may very by location. user type and department security levels
  - - Application and systam permitions also hve to bee taken into account
  - - Regulatory requirment auditing to ensuresuccesful implementation akros the enterprise
  - Use grouprs:
  - - Ensure user and applications are effectively placed into groups streamline permissions assignment
  - Use accounts as intended
  - - Ensure administrators only use admin accounts for admin tasks
  - Standardize accounts
  - - Define a number of account types based on user roles and assign as appropriate
  - Third-party applications:
  - - There are third-party apps available to help streamline and assist in permissions managment
  - Processes and procedures:
  - - Establish a framework for acount managment which defines creation, attributes, assignment and maintenance of all accounts


</details>