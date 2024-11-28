![image](https://github.com/user-attachments/assets/8ceb06d7-79d7-4faa-a6f2-1df7a2b679c6)


# SYSADM1 -- Managing Services in Windows

# Requirement: 

-   A virtual machine running Linux and Windows OS

    **Services** are background processes that run independently of user
    interactions in Windows. They provide essential system functions,
    such as network connectivity, printing, and time synchronization.
    This lab will guide you through the process of managing services
    using the Services app.

# Instructions:  {#instructions .list-paragraph}

1.  Open the Start menu and search for \"Services\"

2.  Familiarize yourself with the columns, including Service Name,
    Display Name, Status, and Startup type.

3.  Right-click on a service and select \"Start\", \"Stop\", or
    \"Restart\". Fill out the table below

+-----+----------+----------------------------------------------------+
| *   | **Name   | **Screenshot**                                     |
| *St | of       |                                                    |
| atu | S        |                                                    |
| s** | ervice** |                                                    |
+=====+==========+====================================================+
| St  | App      | ![](vertopal_13e08d5133f74958aad33a230893          |
| art | lication | e461/media/image2.png){width="3.373682195975503in" |
|     | ma       | height="0.2514271653543307in"}                     |
|     | nagement |                                                    |
+-----+----------+----------------------------------------------------+
|     | AppX     | ![](vertopal_13e08d5133f74958aad33a230893e         |
|     | De       | 461/media/image3.png){width="3.1918285214348208in" |
|     | ployment | height="0.2830150918635171in"}                     |
|     | Service  |                                                    |
|     | (        |                                                    |
|     | AppXSVC) |                                                    |
+-----+----------+----------------------------------------------------+
| S   | Windows  | Before                                             |
| top | Push     |                                                    |
|     | Notif    | ![](vertopal_13e08d5133f74958aad33a230893          |
|     | ications | e461/media/image4.png){width="4.361642607174104in" |
|     | User     | height="0.2920089676290464in"}                     |
|     | Servic   |                                                    |
|     | e_87782f | After                                              |
|     |          |                                                    |
|     |          | ![](vertopal_13e08d5133f74958aad33a230893          |
|     |          | e461/media/image5.png){width="4.440376202974628in" |
|     |          | height="0.22945538057742781in"}                    |
+-----+----------+----------------------------------------------------+
| R   | App      | ![](vertopal_13e08d5133f74958aad33a230893e         |
| est | lication | 461/media/image6.png){width="3.8087215660542433in" |
| art | inf      | height="2.6990496500437446in"}                     |
|     | ormation |                                                    |
+-----+----------+----------------------------------------------------+
| Pa  | Windows  | ![](vertopal_13e08d5133f74958aad33a230893          |
| use | ma       | e461/media/image7.png){width="4.646481846019247in" |
|     | nagement | height="0.19794400699912512in"}                    |
|     | instrum  |                                                    |
|     | entation |                                                    |
+-----+----------+----------------------------------------------------+

4.  Select five network services, right-click to view its properties.
    Modify the startup setting to Manual.

> **SS**:
> ![](vertopal_13e08d5133f74958aad33a230893e461/media/image8.png){width="2.446794619422572in"
> height="2.8566951006124235in"}
> ![](vertopal_13e08d5133f74958aad33a230893e461/media/image9.png){width="2.4812609361329834in"
> height="2.925955818022747in"}
> ![](vertopal_13e08d5133f74958aad33a230893e461/media/image10.png){width="2.4619181977252844in"
> height="2.892279090113736in"}
> ![](vertopal_13e08d5133f74958aad33a230893e461/media/image11.png){width="2.305277777777778in"
> height="2.6371423884514438in"}
> ![](vertopal_13e08d5133f74958aad33a230893e461/media/image12.png){width="2.4640343394575677in"
> height="2.8851826334208224in"}

5.  Explore the \"General\", \"Recovery\", and \"Log On\" tabs to
    understand additional service settings.

6.  Create a batch file that will be added as a new service later on.
    Refer to the batch file code below.

> ![](vertopal_13e08d5133f74958aad33a230893e461/media/image13.png){width="4.808325678040245in"
> height="2.0055664916885387in"}

7.  Save the batch file in Z:\\lastname_timer.bat

8.  Use the sc command to add timer.bat service in the command line
    interface.

> *sc create BatchTimerService binPath= \"path_to_your_batch_file.bat\"
> start= auto*
>
> *net start BatchTimerService*
>
> **Replace path_to_your_batch_file.bat with the actual path to your
> batch file.**

9.  Verify that BatchTimerService has been added to the services.

> **SS:**
> ![](vertopal_13e08d5133f74958aad33a230893e461/media/image14.png){width="2.7679768153980753in"
> height="3.293818897637795in"}

10. **Testing the Service:** Now, if you open a new command prompt, you
    should see the timer countdown without requiring your interaction.
    Once the timer finishes, you\'ll see the \"Timer finished!\"
    message.

> **SS:**
> ![](vertopal_13e08d5133f74958aad33a230893e461/media/image15.png){width="4.594390857392826in"
> height="4.386029090113736in"}

**Rubric**

  ---------------------------------------------------------------------------------------
  **Criteria**      **Excellent       **Good (7)**    **Needs          **Unsatisfactory
                    (10)**                            Improvement      (1)**
                                                      (3)**            
  ----------------- ----------------- --------------- ---------------- ------------------
  Understanding of  Demonstrates a    Shows a solid   Has a basic      Shows little or no
  Services          deep              understanding   understanding of understanding of
                    understanding of  of services,    services, but    services.
                    the concept of    but may lack    may struggle     
                    services, their   some depth in   with specific    
                    roles, and their  specific areas. concepts.        
                    importance in                                      
                    Windows.                                           

  Service           Successfully      Demonstrates    Can perform      Struggles to
  Management Skills starts, stops,    proficiency in  basic service    perform even basic
                    restarts, and     managing        management       service management
                    configures        services, but   tasks, but may   tasks.
                    services using    may encounter   need assistance  
                    the Services app. minor           or guidance.     
                                      difficulties.                    

  Custom Service    Successfully      Can create a    Has limited      Cannot create a
  Creation          creates and       custom service, experience with  custom service.
                    manages a custom  but may         creating custom  
                    service using the encounter minor services.        
                    appropriate tools difficulties or                  
                    and techniques.   require                          
                                      assistance.                      

  Problem-Solving   Demonstrates      Can effectively May require      Struggles to
                    strong            troubleshoot    assistance to    troubleshoot and
                    problem-solving   and resolve     troubleshoot     resolve issues.
                    skills when       most issues     some issues.     
                    encountering      related to                       
                    challenges or     service                          
                    errors.           management.                      

  Documentation and Provides clear    Documents the   Provides basic   Does not provide
  Reporting         and concise       lab activities  documentation,   any documentation
                    documentation of  adequately, but but may be       or reporting.
                    the lab           may lack some   disorganized or  
                    activities,       detail or       incomplete.      
                    including         clarity.                         
                    relevant                                           
                    screenshots and                                    
                    observations.                                      

  **Score:**        **/50**                                            
  ---------------------------------------------------------------------------------------
