+--------------------------+------------------+------------------------+
| ![](ve                   |                  |                        |
| rtopal_000de29da44b4fd9b |                  |                        |
| 761ca4fdaab2b4e/media/im |                  |                        |
| age14.png){width="2.4in" |                  |                        |
| height                   |                  |                        |
| ="0.5881944444444445in"} |                  |                        |
|                          |                  |                        |
| SCHOOL OF INFORMATION    |                  |                        |
| AND TECHNOLOGY           |                  |                        |
+==========================+==================+========================+
| NAME: Ledsey, Shad       | DATE PERFORMED:  | /40                    |
| Warren A.                | 28/11/2024       |                        |
+--------------------------+------------------+------------------------+
| Section: IDC2            | DATE SUBMITTED:  |                        |
|                          | 6/12/2024        |                        |
+--------------------------+------------------+------------------------+

SYSADM1 -- Final Requirement

**Final Project: Comprehensive System Administration &amp; Policy
Integration**

**Objective**: Students will apply their knowledge of system
administration by designing and implementing a comprehensive system
environment while integrating the revised policies from their draft
assignments. This project will demonstrate their understanding of system
management, security protocols, and policy enforcement.

**Project Overview:** Students will create a detailed proposal and
implementation plan for a fictional organization. This plan should
encompass the following elements:

**1. System Architecture Design**

-   Create a network diagram illustrating the layout of the
    > organization\'s IT infrastructure.

![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image10.png){width="9.0in"
height="5.138888888888889in"}

-   Identify and describe key components such as servers, workstations,
    > firewalls, and switches.

**Internet -** an electronic communications network that connects
computer networks and organizational computer facilities around the
world. used with the except when being used attributively.

**firewall** - a network security device that separates a trusted
internal network from an external network deemed untrustworthy

**Router** - a device that connects two or more packet-switched networks
or subnetworks.

**Switch** - Think of this as a central hub inside the organization. It
connects various devices (like servers and computers) so they can share
data within the local network.

**Workstation** - These are the individual computers used by employees
to do their daily tasks.

**Web Server** - software and hardware that uses HTTP (Hypertext
Transfer Protocol) and other protocols to respond to client requests
made over the World Wide Web.

**File Server** - a computer responsible for the storage and management
of data files so that other computers on the same network can access the
files.

**Database** - an organized collection of structured information, or
data, typically stored electronically in a computer system.

**2. Operating System Deployment**

-   Choose at least two operating systems (e.g., Linux and Windows) and
    > explain the rationale for each choice.

## Windows Operating System 

-   Windows is one of the most widely used operating systems in
    > enterprise environments, making it essential for organizations
    > that require compatibility with various business applications and
    > services. Many commercial software solutions are designed
    > specifically for Windows, which can enhance productivity and
    > operational efficiency.

## Linux Operating System

-   Linux offers a high degree of flexibility and customization options.
    > Organizations can tailor their Linux distributions to meet
    > specific needs, whether that involves creating lightweight
    > versions for older hardware or deploying specialized distributions
    > for particular applications like web servers or databases.

```{=html}
<!-- -->
```
-   Detail the installation process, configuration settings, and any
    > automation tools used (e.g.Ansible, Puppet).

## 

## 

## 

## 

## 

## Windows Installation

1.  Change the name to server and insert the ISO file

![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image11.png){width="8.15625in"
height="4.640625546806649in"}

2.  Wait for the installation of windows setup

![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image13.png){width="9.0in"
height="6.140625546806649in"}

3.  Enter a strong password for the built-in Administrator
    > account.Confirm by re-entering the same password. Click **Finish**
    > to complete this step.

![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image16.png){width="9.0in"
height="5.661458880139983in"}

4.  Select server roles to install (ADDS,DNS,DHCP)

![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image2.png){width="8.229166666666666in"
height="5.307292213473316in"}

5.  Change your internet protocol version 4 (TCP/IPv4)

![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image4.png){width="8.354166666666666in"
height="5.046875546806649in"}

![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image8.png){width="9.0in"
height="6.736111111111111in"}

6.  Check is your ip address by entering ipconfig and type nslookup to
    > let users enter a host name and find out the corresponding IP
    > address or domain name system (DNS) record.

![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image5.png){width="6.9375in"
height="3.5520833333333335in"}

## 

## Linux Installation

1.  Change the name to linux and insert the ISO file

![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image17.png){width="8.333333333333334in"
height="5.109375546806649in"}

![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image3.png){width="8.270833333333334in"
height="5.71875in"}

2.  Add more base memory to your linux

![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image18.png){width="8.302083333333334in"
height="5.359375546806649in"}

3.  Make the hard disk file 50GB

![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image12.png){width="8.270833333333334in"
height="5.760416666666667in"}

4.  Go to linux terminal and ping your ip address

![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image9.png){width="9.0in"
height="5.578125546806649in"}

**3. User and Access Management**

-   Outline user roles and access levels, utilizing a least privilege
    > approach.

![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image7.png){width="8.145833333333334in"
height="5.6875in"}

![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image6.png){width="4.21875in"
height="5.520833333333333in"}![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image15.png){width="4.760416666666667in"
height="4.03125in"}

-   Describe how to implement user accounts, groups, and permissions.

Creating a structured user account management system involves defining
user accounts, organizing them into groups, and establishing permissions
that dictate what users can do within a system. Creating User Accounts
can grant Access Control by logging into the administrative interface of
your system

Creating Groups: Create groups based on roles or functions within your
organization (e.g., Admins, Editors, Viewers). This can typically be
done in the same user management section where user accounts are
created.

Setting Permissions for Groups Establish what each group can do within
the system.

-   View: Ability to see content.

-   Edit: Ability to modify content.

-   Delete: Ability to remove content.

-   Administer: Full control over group settings and permissions

**4. Security Measures**

-   Integrate security protocols, such as firewalls, antivirus, and
    > intrusion detection systems.

-   ![](vertopal_000de29da44b4fd9b761ca4fdaab2b4e/media/image1.png){width="9.0in"
    > height="5.723958880139983in"}

-   Draft a basic incident response plan for potential security
    > breaches.

## **RESPONSE PLAN**

1.  **PREPARE** - develop a policy that outlines the roles,
    > responsibilities, and procedures for handling incidents and how
    > you will manage your incident response, what actions must be
    > prioritized, and who will lead incident handling.

2.  **Detection and analysis -** attack surface analytics and continuous
    > monitoring can pinpoint vulnerabilities in your network that
    > attackers look to exploit and help prioritize the most critical
    > risks for proactive remediation. To detect and analyze a potential
    > breach, layer in endpoint monitoring, firewalls, intrusion
    > detection, and security incident event management tools.

3.  **Recovery -** Based on the impact they may have on your operations,
    > the systems or data at risk, and the ability to recover. Don't
    > forget to include a process for documenting the actions you take
    > and any evidence of compromise collected. This will be
    > instrumental in the next step of your incident response plan and
    > future incident response process planning.

4.  **Post-incident activity -** Hold a post mortem meeting to discuss
    > what happened and your organization's response, including what
    > worked, what didn't, and what can be improved. Position it as an
    > open and blameless forum for sharing lessons learned with senior
    > leaders and stakeholders. Invite input and feedback on how the
    > organization can be better prepared if or when another incident
    > occurs.

5.  **Test your incident response process -** Conduct regular drills and
    > simulation exercises. For instance, one month you can have your
    > incident response team simulate their response to a ransomware
    > attack, and in the following month, shift your focus to another
    > security event, such as a supply chain cybersecurity attack.

**5. Backup and Recovery Plan**

-   Develop a strategy for data backup, including frequency and types of
    > backups (full, incremental).

-   Outline the recovery process in case of data loss.

> **DATA BACKUP**

1.  **Onsite backups** - onsite backup is a stored data on a separate
    > hard drive accessible through a local shared network. If your
    > local hard drive cannot store or retrieve data, you can access the
    > onsite backup in order to continue those processes. Onsite backups
    > run through the same network as a local hard drive

2.  ### **External hard drives** - You can typically connect external hard drives through USB ports on a computer to store data similarly to a USB drive. The main difference between USB drives and external hard drives is the amount of storage space available. For example, some external hard drives may be able to store more than a terabyte of data, while USB devices typically cannot.

3.  ### **Cloud backup services** - provide users with automatic data backup and recall through an external system of servers. Cloud service providers work with many businesses to back up and store their information on redundant hard drives in remote locations, allowing them to access it safely ‌using an internet connection. This strategy allows businesses to delegate data backup activities, such as buying hard drives, creating data security systems and programming user permissions to an external company in exchange for a fee.

4.  ###  **Redundancy** - replicating a hard drive into two or more instances and may happen instantaneously as you enter and edit data to ensure that all data is always accessible. These backup drives may be in the same physical location, a remote location or a combination of both.

5.  ### **Removable media** - include a CD, floppy disk or USB drive. USB drives are the most popular form of removable media because they can typically store more data. This strategy involves backing up data into a removable media device and storing that device in an accessible place in case of data loss.

> **RECOVERY PROCESS**

1.  **Optical recovery:** CDs, DVDs, and other laser-written media are
    > called optical storage. Utilizing data recovery solutions
    > specializing in optical storage presents the best possibility of
    > recovering lost data from optical media.

2.  **Hard drive recovery:** Data recovery from hard drives is perhaps
    > the most prevalent data recovery technique, yet it is also the
    > most complicated. Users should seek a hard disc recovery provider
    > and regularly back up essential data.

3.  **Logical data recovery:** Logical data recovery is performed when
    > the issue with data recovery does not impact the hard disc itself
    > but the computer. This occurs when a disc is still functional but
    > some data has been lost.

4.  **File Carving:** An advanced technique that bypasses the file
    > system to detect traces of data and piece them together through
    > pattern recognition. This manual method recovers data directly
    > from the storage's free space.

5.  **Physical data recovery:** This occurs when your hard disc is
    > physically damaged. If physically affected, there are currently
    > organizations specializing in data recovery that can help. They
    > can assist in reconstructing faulty
    > [firmware](https://www.spiceworks.com/tech/devops/articles/what-is-firmware/)
    > so you can read and transfer the data.

**Policy Integration**

-   Incorporate changes made to the policy drafts during the course.

-   Discuss how these policies will be enforced, monitored, and updated
    > as needed.

1.  **Educational Focus:** Rented devices should be used primarily for
    > educational purposes, including coursework, research, and academic
    > collaboration. Any use that disrupts the learning environment or
    > violates local laws is prohibited.

2.  **Proper Handling:** Users must handle rented devices with care to
    > prevent physical damage. This includes avoiding exposure to
    > liquids, extreme temperatures, and rough handling.

3.  **Return Condition:** Devices should be returned in the same
    > condition as received, barring normal wear and tear. Users should
    > document any pre-existing damage upon receipt.

4.  **Secure Personal Information:** Users should avoid storing personal
    > data on rented devices. If necessary, they should use secure
    > methods for data storage and ensure that sensitive information is
    > deleted before returning the device.

5.  **Technical Support:** Users should promptly report any technical
    > issues or malfunctions with rented devices to TechLease's support
    > team. This ensures timely resolution and minimizes disruption to
    > their academic activities.

**7. Documentation**

-   Provide comprehensive documentation for all systems, configurations,
    > and policies.

-   Include a user manual for end-users and system administrators.

**8. Presentation**

-   Prepare a presentation summarizing the project, highlighting key
    > decisions and policies.

-   Be prepared to answer questions regarding the implementation and
    > policy integration.

Grading Rubric

+---------+---------+---------+---------+---------+---------+---------+
| C       | Ex      | Good    | Satis   | Needs   | Unsatis | Points  |
| riteria | cellent |         | factory | Impr    | factory |         |
|         | (90-    | (80-89) |         | ovement | (0-59)  |         |
|         |         |         | (70-79) |         |         |         |
|         | 100\)   |         |         | (60-69) |         |         |
+=========+=========+=========+=========+=========+=========+=========+
| **S     | Clear,  | Mostly  | Basic   | Lacks   | No      | /20     |
| ystem** | de      | clear   | layout; | c       |         |         |
|         | tailed, |         |         | larity; | archi   |         |
| **      | and     | layout; | several |         | tecture |         |
| Archite |         | minor   |         | many    |         |         |
| cture** | logical |         | com     |         | pr      |         |
|         | layout; | details | ponents | com     | ovided. |         |
| **D     |         |         |         | ponents |         |         |
| esign** | i       | m       | m       |         |         |         |
|         | ncludes | issing. | issing. | m       |         |         |
|         | all     |         |         | issing. |         |         |
|         | r       |         |         |         |         |         |
|         | equired |         |         |         |         |         |
|         |         |         |         |         |         |         |
|         | comp    |         |         |         |         |         |
|         | onents. |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **OS**  | Well-ju | Good    | Basic   | Poor    | No      | /20     |
|         | stified | choices |         |         |         |         |
| **Deplo |         | with    | c       | justifi | dep     |         |
| yment** | c       |         | hoices; | cation; | loyment |         |
|         | hoices; | minor   |         |         |         |         |
|         | t       | j       | some    | lacks   | details |         |
|         | horough | ustific |         | detail. |         |         |
|         |         | ations; | details |         | pr      |         |
|         | insta   |         |         |         | ovided. |         |
|         | llation | a       | m       |         |         |         |
|         | and     | dequate | issing. |         |         |         |
|         |         | d       |         |         |         |         |
|         | config  | etails. |         |         |         |         |
|         | uration |         |         |         |         |         |
|         | d       |         |         |         |         |         |
|         | etails. |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **User  | Compre  | Good    | Basic   | Vague   | No      | /15     |
| and**   | hensive | roles   | roles   | roles;  |         |         |
|         | roles   |         |         |         | man     |         |
| **A     |         | d       | with    | sign    | agement |         |
| ccess** | d       | efined; | limited | ificant |         |         |
|         | efined; |         |         |         | plan    |         |
| **Manag | ex      | minor   | access  | access  | pr      |         |
| ement** | cellent | issues  |         | control | ovided. |         |
|         |         |         | c       |         |         |         |
|         | impleme | in      | ontrol. | issues. |         |         |
|         | ntation | access  |         |         |         |         |
|         | of      |         |         |         |         |         |
|         |         | c       |         |         |         |         |
|         | access  | ontrol. |         |         |         |         |
|         | co      |         |         |         |         |         |
|         | ntrols. |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **Sec   | Strong  | Good    | Basic   | Poor    | No      | /15     |
| urity** | inte    | me      |         | me      | s       |         |
|         | gration | asures; | m       | asures; | ecurity |         |
| **Mea   | of      |         | easures |         |         |         |
| sures** |         | minor   | with    | lacks   | m       |         |
|         | s       | gaps in |         | i       | easures |         |
|         | ecurity |         | sign    | ncident |         |         |
|         | pro     | i       | ificant |         | pr      |         |
|         | tocols; | ncident |         | r       | ovided. |         |
|         |         |         | gaps.   | esponse |         |         |
|         | we      | re      |         | plan.   |         |         |
|         | ll-thou | sponse. |         |         |         |         |
|         | ght-out |         |         |         |         |         |
|         |         |         |         |         |         |         |
|         | i       |         |         |         |         |         |
|         | ncident |         |         |         |         |         |
|         | re      |         |         |         |         |         |
|         | sponse. |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **B     | D       | Good    | Basic   | Vague   | No      | /10     |
| ackup** | etailed |         |         |         |         |         |
|         | and     | str     | stra    | str     | b       |         |
| **and** | pr      | ategies | tegies; | ategies | ackup/r |         |
|         | actical |         |         |         | ecovery |         |
| **Rec   |         | with    | lacks   | with    |         |         |
| overy** | b       | minor   | c       | major   | plan    |         |
|         | ackup/r |         | larity. |         | pr      |         |
| *       | ecovery | gaps in |         | gaps.   | ovided. |         |
| *Plan** |         | detail. |         |         |         |         |
|         | stra    |         |         |         |         |         |
|         | tegies; |         |         |         |         |         |
|         | t       |         |         |         |         |         |
|         | horough |         |         |         |         |         |
|         |         |         |         |         |         |         |
|         | expla   |         |         |         |         |         |
|         | nation. |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **P     | T       | Good    | Basic   | Vague   | No      | /10     |
| olicy** | horough |         |         |         | policy  |         |
|         | inte    | Int     | integ   | Integ   |         |         |
| *       | gration | egratio | ration; | ration; | integ   |         |
| *Integr |         | n;minor | lacks   | unclear | ration. |         |
| ation** | of      | issues  | depth.  | enfor   |         |         |
|         | po      | in      |         | cement. |         |         |
|         | licies; |         |         |         |         |         |
|         | clear   | c       |         |         |         |         |
|         | enfo    | larity. |         |         |         |         |
|         | rcement |         |         |         |         |         |
|         |         |         |         |         |         |         |
|         | stra    |         |         |         |         |         |
|         | tegies. |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **D     | Compre  | Good    | Basic   | Poor    | No      | /5      |
| ocument | hensive |         |         |         |         |         |
| ation** |         | documen | documen | documen | docume  |         |
|         | and     | tation; | tation; | tation; | ntation |         |
|         | clear   |         |         |         |         |         |
|         |         | minor   | some    | lacks   | pr      |         |
|         | documen |         | clarity |         | ovided. |         |
|         | tation; | organiz |         | organi  |         |         |
|         |         | ational | issues. | zation. |         |         |
|         | w       |         |         |         |         |         |
|         | ell-org | issues. |         |         |         |         |
|         | anized. |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **      | En      | Good    | Basic   | Poor    | No      | /5      |
| Present | gaging, |         |         |         |         |         |
| ation** | clear,  | presen  | presen  | presen  | prese   |         |
|         |         | tation; | tation; | tation; | ntation |         |
|         | and     |         |         |         |         |         |
|         | t       | minor   | st      | lacks   | given.  |         |
|         | horough |         | ruggles | clarity |         |         |
|         |         | eng     | with    | and     |         |         |
|         | presen  | agement |         |         |         |         |
|         | tation; |         | Q       | enga    |         |         |
|         |         | issues. | &amp;A. | gement. |         |         |
|         | ex      |         |         |         |         |         |
|         | cellent |         |         |         |         |         |
|         | Q&amp;A |         |         |         |         |         |
|         |         |         |         |         |         |         |
|         | ha      |         |         |         |         |         |
|         | ndling. |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+

**REFERENCE**

[[https://www.indeed.com/career-advice/career-development/data-backup-strategies]{.underline}](https://www.indeed.com/career-advice/career-development/data-backup-strategies)

[[https://www.spiceworks.com/tech/data-management/articles/what-is-data-recovery-types-process-and-software/]{.underline}](https://www.spiceworks.com/tech/data-management/articles/what-is-data-recovery-types-process-and-software/)
