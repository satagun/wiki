<p align="center">
    <a name="_Hlk482179127"></a>
    <strong>CANKAYA UNIVERSITY</strong>
</p>
<p align="center">
    <strong>FACULTY OF ENGINEERING</strong>
</p>
<p align="center">
    <strong>COMPUTER ENGINEERING DEPARTMENT</strong>
</p>
<p>
    <strong> </strong>
</p>
<p align="center">
    <strong>
        <img
            width="146"
            height="145"
            src="http://i63.tinypic.com/1079pit.png"
        />
    </strong>
    <strong></strong>
</p>
<p align="center">
    <strong> </strong>
</p>
<p align="center">
    <strong>
        CENG 407
        <br/>
    </strong>
    Innovative System Design and Development I<strong></strong>
</p>
<p align="center">
    <strong> </strong>
</p>
<p align="center">
    <strong>
        SDD FOR PROJECT MANAGEMENT ASISTANT
        <br/>
        Version 4
    </strong>
</p>
<p align="center">
    <strong> </strong>
</p>
<p align="center">
    <strong><em> </em></strong>
</p>
<p align="center">
    <strong><em>Hakan İREN 201411211</em></strong>
</p>
<p align="center">
    <strong><em>Selçuk ATAGÜN 201411204 </em></strong>
</p>
<p align="center">
    <strong><em> </em></strong>
</p>
<p align="center">
    <strong><em>Advisor: Prof. Dr. Erdoğan DOĞDU </em></strong>
</p>
<p align="center">
    <strong> </strong>
</p>
<p align="center">
    <strong> </strong>
</p>
<p>
    <strong>Word Count: 3174</strong>
</p>
<p>
    <strong>PREFACE</strong>
</p>
<p>
    Software Design Document is a technical definition about the system. This
    documentation mentions that architecture and design of the project. Before
    preparing the SDD, Software Requirement System was examined by team
    members. SRS includes more information about the Project and SDD is an
    organization, behavior and collaborations between modules. Project
    Management Asistant has many requirements and they are mentioned in SRS.
    SDD includes technology of the requirements and its architecture. The
    documentation provides an understandable guide for developer. It was
    prepared acoocrding to IEEE 1016.
</p>
<div>
    <h1>
        <a name="_Toc484227085">LIST OF FIGURES</a>
    </h1>
</div>
<p>
    Figure 1-System Overview……………………………………………………………...…11
</p>
<p>
    Figure 2- Project Organization ………………………………….……………………..…12
</p>
<p>
    Figure 3- Login………………………………………………………………………..…….15
</p>
<p>
    Figure 4- Risk &amp; Cost Management…………………………………………………..….16
</p>
<p>
    Figure 5 –User Profiles …………………………………………………..………………..20
</p>
<p>
    Figure 6 – Task Management ……………………………………………….……………22
</p>
<p>
    Figure 7- Database Design ………………………………………………...……………. 28
</p>
<p>
    Figure 8 – Cost-Follow up…………………………………………………………………30
</p>
<p>
    Figure 9 –Cost-Task…………………………………………………………………..…...30
</p>
<p>
    Figure 10- Project-Task…………………………………………………………..………..31
</p>
<p>
    Figure 11- Risk-Cost…………………………………………………………...…………..31
</p>
<p>
    Figure 12- Project-Risk ………………………………………………………….………..32
</p>
<p>
    Figure 13- Project-Task ………………………………………………………………….32
</p>
<p>
    Figure 14- Statu-Follow up…………………………………...……………………………33
</p>
<p>
    Figure 15- Login Page…………………………………………………..…………………34
</p>
<p>
    Figure 16- Admin Home Page……………………………………………………….……35
</p>
<p>
    Figure 17- Admin Project Cost Page………..……………………………………………36
</p>
<p>
    Figure 18- Project Upgrade Page…………………………….…………………………..37
</p>
<p>
    Figure 19- Member Lists Page…………………………………………………….……...38
</p>
<p>
    Figure 20- Timeline Page ……………………..…………………………………..………39
</p>
<p>
    Figure 22-Admin Login Module Activity Diagram………………………………...……..40
</p>
<p>
    Figure 23-Task Assign Module Activity Diagram………………………………………..41
</p>
<p>
    Figure 24-Risk Module Activity Diagram…………………………………………………42
</p>
<p>
    Figure 25-Cost Module Activity Diagram…………………………………………………42
</p>
<p>
    Figure 26-Time Schedule………………………………………………………………….47
</p>
<div>
    <h1>
        <a name="_Toc484227086">LIST OF TABLES</a>
    </h1>
</div>
<p>
    <strong> </strong>
</p>
<p>
    Table 1 – User Responsibilities…………………………………..……………………..11
</p>
<p>
    Table 2- Project Organization…………………………………………………………...13
</p>
<p>
    Table 3 – New Project……………………………………………………………………13
</p>
<p>
    Table 4 – Project Manager Assignment………………………………………….…….14
</p>
<p>
    Table 5- Login……………………………………………………………………………..15
</p>
<p>
    Table 6- Risk &amp; Cost Management…………………………………..…………….……16
</p>
<p>
    Table 7-Display of Risks……………………………………………………….…………17
</p>
<p>
    Table 8- Risk Creation……………………………………………………………………18
</p>
<p>
    Table 9- Risk &amp; Cost Addition……………………………………………………………..18
</p>
<p>
    Table 10-New Report Creation…………………………………………………….……..19
</p>
<p>
    Table 11 – Profile……………………………………….………………………………….20
</p>
<p>
    Table 12 – Profile Edition………………………………………………………...……..…21
</p>
<p>
    Table 13- Display Profie……………………………………………………….….……….21
</p>
<p>
    Table 14- Profile Creation………………………………………………………………….22
</p>
<p>
    Table 15- Task Management………………………………………...……………………23
</p>
<p>
    Table 16-Display Tasks…………………………………………………………….……...24
</p>
<p>
    Table 17-Task Assignment………………………………………………………………..24
</p>
<p>
    Table 18-Edit &amp; Remove Task……………………………………………….……………24
</p>
<p>
    Table 19 – Reporting……………………………………………………………………….25
</p>
<p>
    Table 20- Rewarding…………………………………………………...…………..……...25
</p>
<p>
    Table 21 – Project Information…………………………………………………………….26
</p>
<p>
    Table 22-TasksInformation………..………………………………………………………26
</p>
<p>
    Table 23- Risk Information…………………………………………………………….…..26
</p>
<p>
    Table 24- Cost Information ….…………………………………………………………....26
</p>
<p>
    Table 25- Personal Information…………………...………………...…………………….27
</p>
<p>
    Table 26- Follow up Hours………………………………………………………………...27
</p>
<p>
    Table 27- Statu Information …….………………………………………………………...29
</p>
<p>
    Table28- IntermoduleDescription…………………………..………………………..…..30
</p>
<p>
    Table 29- Cost Information .………………………………………………………………31
</p>
<p>
    Table 30- Project Information ………………………...…………………………………..32
</p>
<p>
    Table 31- Task Information ……………………………………………………………....32
</p>
<p>
    Table 32- Follow-up Hours ..……………………………………………………………...41
</p>
<p>
    Table 33- Project Information ………………………..…………………………………...41
</p>
<p>
    Table 34- Task Information ………………………………………………………...…….42
</p>
<p>
    Table 35- Risk Information …………………………………………………………….….42
</p>
<p>
    Table 36- Cost Information ………….…………………………………………….……..42
</p>
<p>
    Table 37- Personal Information ………………………………………………….……….43
</p>
<p>
    Table 38- Role Information ……………………..…………………….…………………..43
</p>
<p>
    Table 39- Follow-up Hours ……………………………………………….…………..45-46
</p>
<p>
    Table 40- RTM………………………………..…………………………….………….…..47
</p>
<div>
    <h1>
    </h1>
    <h1>
        <a name="_Toc484227087"><em>TABLE OF CONTENTS</em></a>
        <em></em>
    </h1>
</div>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227085"
    >
        LIST OF FIGURES.. 3
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227086"
    >
        LIST OF TABLES.. 4
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227087"
    >
        TABLE OF CONTENTS.. 6
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227088"
    >
        1. INTRODUCTION.. 7
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227089"
    >
        1.1. Purpose. 7
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227090"
    >
        1.2. Scope. 7
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227091"
    >
        1.3. Definitions, Acronyms and Abbreviations. 8
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227092"
    >
        1.3.1. Definitions. 8
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227093"
    >
        1.3.2. Acronyms. 8
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227094"
    >
        1.3.3. Abbreviations. 8
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227095"
    >
        1.4 REFERENCES.. 9
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227096"
    >
        2. SYSTEM OVERVIEW... 10
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227097"
    >
        3. SYSTEM COMPONENTS.. 11
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227098"
    >
        3.1. Decomposition Description. 11
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227099"
    >
        3.1.1. Module Decomposition. 11
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227100"
    >
        3.1.2 Data Decomposition. 25
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227101"
    >
        3.2 Dependency Description. 28
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227102"
    >
        3.2.2. Data Dependencies. 29
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227103"
    >
        3.3 INTERFACE DESCRIPTION.. 33
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227104"
    >
        3.3.2 User Interface. 33
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227105"
    >
        4 DETAILED DESIGN.. 40
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227106"
    >
        4.1 Module Detailed Design. 40
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227107"
    >
        4.1.1 Class Diagram... 40
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227108"
    >
        4.1.2 Project Organization Activity Diagram... 41
    </a>
</p>
<p>
    <a
        href="file:///C:/Users/satag/Desktop/407-408/407-408/SDD_v4.doc#_Toc484227109"
    >
        4.2 Data Detailed Design. 43
    </a>
</p>
<h1>
    <a name="_Hlk484382629"></a>
    <a name="_Toc484227088"></a>
    <a name="_Toc311920406"></a>
    <a name="_Toc311915528">1. INTRODUCTION</a>
</h1>
<h1>
    <a name="_Toc484227089"></a>
    <a name="_Toc311920407">1.1. Purpose</a>
</h1>
<p>
    Software Design Document describes the design and architecture of Project
    Management System. The aim of documentation examines decompositon of the
    system, Technologies and responsibilites into modules. SDD is an
    implementation for before coding. A person, who does not know anything
    about the project, can learn everything about Project Management System.
</p>
<h1>
    <a name="_Toc484227090"></a>
    <a name="_Toc311920408">1.2. Scope</a>
</h1>
<p>
    The system architecture and software design are details of the description
    in this documentation. Project Management System is like preparing to the
    implementation. When we look at the Softare Requirement System, we
    seperated simple parts according to individual who enters the system. This
    part contributes to the Project that some of them has only its own pages.
    It can be made some changes, updates, deleting with helping a database.
    Database is useful for holding the all information about the Project
    Management System. So that, this documentation brings user information
    which has more reality and more visual. And also, it is a contribution for
    software.
</p>
<h1>
    <a name="_Toc484227091"></a>
    <a name="_Toc311920409">1.3. Definitions, Acronyms and Abbreviations</a>
</h1>
<h4>
    <a name="_Toc484227092">1.3.1. Definitions</a>
</h4>
<p>
    <strong>Employee List: </strong>
    It is the document given by the senior management to the admin, including
    the company’s employee list.
</p>
<p>
    <strong> </strong>
</p>
<p>
    <strong>Report: </strong>
    It is document formed by all of the users in order to inform senior
    personel about the costs, working hours and works that are done.
</p>
<h4>
    <a name="_Toc484227093">1.3.2. Acronyms</a>
</h4>
<p>
    <strong></strong>
</p>
<p>
    <strong>API: </strong>
    Application Programming Interface
</p>
<p>
    <strong>DB: </strong>
    Database<strong></strong>
</p>
<p>
    <strong>GUI: </strong>
    Graphical User Interface
</p>
<p>
    <strong>PM:</strong>
    Project Manager
</p>
<p>
    <strong>RTM:</strong>
    Requirement Traceability Matrix
</p>
<p>
    <strong>SRS: </strong>
    Software Requirement System<strong></strong>
</p>
<p>
    <strong>SDD: </strong>
    Software Design System
</p>
<p>
    <strong>IEEE:</strong>
    Institute of Electrical and Electronics Engineers
</p>
<h4>
    <a name="_Toc484227094">1.3.3. Abbreviations</a>
</h4>
<p>
    <strong> </strong>
</p>
<p>
    There is no abbreviation.
</p>
<h1>
    <a name="_Toc311920410">1.4 </a>
    <a name="_Toc484227095">REFERENCES</a>
</h1>
<p>
    <strong>1</strong>
    .IEEE SDD 1016 - IEEE Recommended Practice for Software Design Descriptions
</p>
<p>
    <strong>2.</strong>
    Somerville, I., 2004. “Software Engineering”, USA: ADDISON-WESLEY, seventh
    edition.
</p>
<p>
    <strong>3.</strong>
    Pressman, Roger S., Software Engineering, 4th edition, McGraw-Hill, 1997
</p>
<p>
    For Project Management SDD Version1.0
</p>
<p>
    <strong>4.</strong>
    Fairley, R. E.,Workbreakdown Structure, Software Engineering Project
    Management, IEEE CS Press, 1997
</p>
<h1>
    <a name="_Toc311920411"></a>
    <a name="_Toc484227096">2. SYSTEM OVERVIEW</a>
</h1>
<p>
    <strong>Figure 1: System Overview</strong>
</p>
<p>
    <img
        width="605"
        height="422"
        src="http://i65.tinypic.com/rk7tj8.jpg"
    />
</p>
<p>
    <strong>Figure 1</strong>
    : System Overwiew
</p>
<table border="1" cellspacing="0" cellpadding="0" width="678">
    <tbody>
        <tr>
            <td width="205" valign="top">
                <p align="center">
                    <strong>Admin</strong>
                </p>
            </td>
            <td width="255" valign="top">
                <p align="center">
                    <strong>Project Manager</strong>
                </p>
            </td>
            <td width="217" valign="top">
                <p align="center">
                    <strong>Team Member</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="205" valign="top">
                <ul>
                    <li>
                        Project Creation
                    </li>
                    <li>
                        User Creation
                    </li>
                    <li>
                        Assign project manager
                    </li>
                    <li>
                        Rewarding
                    </li>
                </ul>
            </td>
            <td width="255" valign="top">
                <ul>
                    <li>
                        Entering risks
                    </li>
                    <li>
                        Reject or approve new risk
                    </li>
                    <li>
                        Reporting risk
                    </li>
                    <li>
                        Update personal information
                    </li>
                    <li>
                        Task, role, time period assign.
                    </li>
                    <li>
                        Updating cost and report
                    </li>
                    <li>
                        Changing password.
                    </li>
                </ul>
            </td>
            <td width="217" valign="top">
                <ul>
                    <li>
                        Report Creation &amp; Forwarding
                    </li>
                    <li>
                        Enter new risk
                    </li>
                    <li>
                        Update cost information
                    </li>
                    <li>
                        Update personal information.
                    </li>
                    <li>
                        Change password
                    </li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong>Table 1:</strong>
    User Responsibilities<strong></strong>
</p>
<h1>
    <a name="_Toc484227097">3. SYSTEM COMPONENTS</a>
</h1>
<h2>
    <a name="_Toc484227098"></a>
    <a name="_Toc311920412">3.1. Decomposition Description</a>
</h2>
<p>
    <strong></strong>
</p>
<h4>
    <a name="_Toc484227099">3.1.1. Module Decomposition</a>
</h4>
<p>
    Our project, the Project Management Assistant has following modules.
</p>
<ul>
    <li>
        Project Organization Module
    </li>
    <li>
        Login Module
    </li>
</ul>
<p>
    · Risk &amp; Cost Management Module
</p>
<ul>
    <li>
        Task Management Module
    </li>
    <li>
        Profile Module
    </li>
</ul>
<p>
    <strong>3.1.1.1 Project Organization Module</strong>
</p>
<p>
    <strong>
        <img
            width="507"
            height="319"
            src="http://i67.tinypic.com/5b1t2w.jpg"
        />
    </strong>
    <strong></strong>
</p>
<p>
    <strong>Figure 2: </strong>
    Project Organization<strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<table cellpadding="0" cellspacing="0">
    <tbody>
        <tr>
            <td width="520" height="371">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <h5>
                                        <strong>Identification</strong>
                                        : Project Organization Module
                                    </h5>
                                    <p>
                                        <strong>Purpose: </strong>
                                        Establishing new projects and
                                        administrative operations is mainly
                                        functions of this module. In addition,
                                        Project managers and team members
                                        assignments also will be done in this
                                        module.
                                    </p>
                                    <p>
                                        <strong>Functions: </strong>
                                    </p>
                                    <p>
                                        · New project is established by admin.
                                    </p>
                                    <p>
                                        · Project manager is assigned to the
                                        projects by admin.
                                    </p>
                                    <p>
                                        <strong>Sub-modules:</strong>
                                    </p>
                                    <ul>
                                        <li>
New Project Creation                                            <strong></strong>
                                        </li>
                                        <li>
Project Manager Assignment                                            <strong></strong>
                                        </li>
                                    </ul>
                                    <p>
                                        <strong></strong>
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<strong></strong>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<br clear="ALL"/>
<p>
    <strong>Table 2: </strong>
    Project Organization<strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong>3.1.1.1.1 New Project Creation Sub-Module</strong>
</p>
<table cellpadding="0" cellspacing="0">
    <tbody>
        <tr>
            <td width="435" height="240">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <h6>
                                        <strong>Identification: </strong>
                                        New Project Creation Sub-Module
                                    </h6>
                                    <p>
                                        <strong>Purpose: </strong>
                                        Allowance of admin to create new
                                        projects.
                                    </p>
                                    <p>
                                        <strong>Functions: </strong>
                                    </p>
                                    <p>
                                        · New projects name is entered by
                                        admin.
                                    </p>
                                    <p>
                                        · New project is added by admin.
                                    </p>
                                    <p>
                                        <strong>Sub-ordinates: </strong>
                                        Connection to DB.
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong></strong>
</p>
<br clear="ALL"/>
<p>
    <strong>Table 3: </strong>
    New Project<strong> </strong>
</p>
<h6>
</h6>
<h6>
    <strong>3.1.1.1.1. </strong>
    <strong> Project Manager AssignmentSub-Module</strong>
</h6>
<table cellpadding="0" cellspacing="0" align="left">
    <tbody>
        <tr>
            <td width="23" height="25">
            </td>
        </tr>
        <tr>
            <td>
            </td>
            <td width="411" height="335">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <h6>
                                        <strong>Identification: </strong>
                                        Project Manager Assignment Sub Module
                                    </h6>
                                    <p>
                                        <strong>Purpose: </strong>
                                        Allowance of admin to assign Project
                                        managers to the projects:
                                    </p>
                                    <p>
                                        <strong>Functions: </strong>
                                    </p>
                                    <p>
                                        · Project is selected from list by
                                        admin.
                                    </p>
                                    <p>
                                        · Project manager is selected from list
                                        by admin.
                                    </p>
                                    <p>
                                        · Project manager is assigned to the
                                        project by admin.
                                    </p>
                                    <p>
                                        <strong>Sub-ordinates: </strong>
                                        Connection to DB.
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<h6>
    <strong></strong>
</h6>
<h6>
    <strong></strong>
</h6>
<h6>
    <strong></strong>
</h6>
<h6>
    <strong></strong>
</h6>
<br clear="ALL"/>
<p>
    <strong>Table 4: </strong>
    Project Manager Assignment<strong></strong>
</p>
<h6>
    <strong></strong>
</h6>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong>3.1.1.2 </strong>
    <strong>Login Module</strong>
</p>
<p>
    <strong>
        <img
            width="396"
            height="240"
            src="http://i68.tinypic.com/2ai0xlt.png"
        />
    </strong>
</p>
<p>
    <strong>Figure 3:</strong>
    Login<strong></strong>
</p>
<p>
    <strong></strong>
</p>
<table cellpadding="0" cellspacing="0" align="left">
    <tbody>
        <tr>
            <td width="16" height="16">
            </td>
        </tr>
        <tr>
            <td>
            </td>
            <td width="455" height="324">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>Identification: </strong>
                                        Login Module<strong></strong>
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        Allowance of admin, Project managers
                                        and team members to log in the system.
                                    </p>
                                    <p>
                                        <strong>Functions: </strong>
                                    </p>
                                    <p>
                                        · Admin project managers and team
                                        members will be able to log in system.
                                    </p>
                                    <ul>
                                        <li>
                                            Users types username.
                                        </li>
                                        <li>
                                            User types password.
                                        </li>
                                    </ul>
                                    <p>
                                        · Users checked in database whether
                                        they are authorized to log in or not.
                                    </p>
                                    <p>
                                        <strong>Sub-ordinates:</strong>
                                        Connection to DB.
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<strong></strong>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<br clear="ALL"/>
<p>
    <strong>Table 5:</strong>
    Login<strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<h5>
    <strong>3.1.1.3 </strong>
    <strong>Risk &amp; Cost Management Module</strong>
</h5>
<p>
    <img
        width="558"
        height="281"
        src="http://i65.tinypic.com/1zp4gly.png"
    />
</p>
<p>
    <strong>Figure 4: </strong>
    Risk &amp; Cost Management<strong></strong>
</p>
<table cellpadding="0" cellspacing="0" align="left">
    <tbody>
        <tr>
            <td width="7" height="13">
            </td>
        </tr>
        <tr>
            <td>
            </td>
            <td width="432" height="499">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>Identification: </strong>
                                        Risk &amp; Cost Mangement Module
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        Give permission to Project managers to
                                        creating new risks, editing &amp;
                                        changing existing risks and displaying
                                        the same risks. In addition it also
                                        gives permission to team members to
                                        create new risks for their project
                                        managers approval.
                                    </p>
                                    <p>
                                        <strong>Functions: </strong>
                                    </p>
                                    <p>
                                        · Project Managers will be able to
                                        select a project from list to edit
                                        costs &amp; risks of the project
                                    </p>
                                    <p>
                                        · Monitoring existing risks and current
                                        both actual cost and planned cost will
                                        be provided.
                                    </p>
                                    <p>
                                        · Project Managers will be able to
                                        approve or reject received risks from
                                        team members.
                                    </p>
                                    <p>
                                        · Team members will be able to create
                                        and forward new risks.
                                    </p>
                                    <p>
                                        <strong>Sub-modules:</strong>
                                    </p>
                                    <p>
· Display &amp; Edit Risks &amp; Costs                                        <strong></strong>
                                    </p>
                                    <ul>
                                        <li>
Create New Risk Risk                                            <strong></strong>
                                        </li>
                                    </ul>
                                    <p>
· Approve Forwarded Risk (Only PM)                                        <strong></strong>
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<strong></strong>
<p>
    <strong></strong>
</p>
<br clear="ALL"/>
<p>
    <strong>Table 6: Risk &amp; Cost Management</strong>
</p>
<p>
    <strong></strong>
</p>
<h6>
    <strong>3.1.1.3.1 </strong>
    <strong>Display Risks &amp; CostsSub-Module</strong>
</h6>
<table cellpadding="0" cellspacing="0" align="left">
    <tbody>
        <tr>
            <td width="16" height="22">
            </td>
        </tr>
        <tr>
            <td>
            </td>
            <td width="418" height="480">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>Identification: </strong>
                                        Display Risks Sub-Module
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        Make Project managers and team members
                                        able to monitor actual risks and costs
                                        that have been recieved or sent.
                                    </p>
                                    <p>
                                        <strong>Functions: </strong>
                                    </p>
                                    <p>
                                        · Project manager will be able to see
                                        all risks and cost information for a
                                        specified project that is selected from
                                        a list. In addition they also will be
                                        able to see updated or newly created
                                        risks or changed cost of a project.
                                    </p>
                                    <p>
                                        · Project Managers will be able to edit
                                        or terminate risks and update costs
                                    </p>
                                    <p>
                                        · Team members will be able to see risk
                                        and cost updates that have been done by
                                        them
                                    </p>
                                    <p>
                                        <strong>Sub-ordinates: </strong>
                                        Connection to DB.
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<br clear="ALL"/>
<p>
    <strong>Table 7: Display of Risk</strong>
</p>
<p>
    <strong></strong>
</p>
<h6>
    <strong>3.1.1.3.2 </strong>
    <strong>Create Risk Sub-Module</strong>
</h6>
<table cellpadding="0" cellspacing="0" align="left">
    <tbody>
        <tr>
            <td width="14" height="8">
            </td>
        </tr>
        <tr>
            <td>
            </td>
            <td width="420" height="343">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>Identification:</strong>
                                        Create Risk Sub-Module
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        Make project managers and team members
                                        able to create new risks and forwarding
                                        and approving them.
                                    </p>
                                    <p>
                                        <strong>Functions: </strong>
                                    </p>
                                    <p>
                                        · Project managers will be able to
                                        create new risks, with their brief
                                        description for a specified project.
                                    </p>
                                    <p>
                                        · Team members will be able to create
                                        new risks and forwarding them to
                                        project managers for approval.
                                    </p>
                                    <p>
                                        <strong>Sub-ordinates: </strong>
                                        Connection to DB.
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<strong></strong>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<br clear="ALL"/>
<p>
    <strong>Table 8: Risk Creation</strong>
</p>
<p>
    <strong></strong>
</p>
<h6>
    <strong>3.1.1.3.3 </strong>
    <strong>Edit &amp; Update Risk Cost Sub-Module</strong>
</h6>
<table cellpadding="0" cellspacing="0" align="left">
    <tbody>
        <tr>
            <td width="19" height="18">
            </td>
        </tr>
        <tr>
            <td>
            </td>
            <td width="375" height="339">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>Identification:</strong>
                                        Edit Risk Sub-Module
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        Make Project managers and team members
                                        able to edit existing risks and update
                                        actual cost.
                                    </p>
                                    <p>
                                        <strong>Functions: </strong>
                                    </p>
                                    <p>
                                        · Project managers will be able to edit
                                        risks and update costs of a project
                                        that is selected from a list.
                                    </p>
                                    <p>
                                        · Team members will be able to edit
                                        cost and risk information which will be
                                        invalid till project managers approval
                                    </p>
                                    <p>
                                        <strong>Sub-ordinates: </strong>
                                        Connection to DB.
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<br clear="ALL"/>
<h5>
    <strong>3.1.1.4 </strong>
    <strong>ReportingModule</strong>
</h5>
<p>
    <strong>Table 9: Risk &amp; Cost Edition</strong>
</p>
<h6>
    <strong>3.1.1.3.4 </strong>
    <strong>Reporting Sub-Module</strong>
</h6>
<table cellpadding="0" cellspacing="0" align="left">
    <tbody>
        <tr>
            <td width="11" height="15">
            </td>
        </tr>
        <tr>
            <td>
            </td>
            <td width="394" height="283">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>Identification:</strong>
                                        Create New Report Sub-Module
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        Allow team members to create reports
                                        for briefly describing updates and
                                        changes about cost and risk done by
                                        them to Project managers.
                                    </p>
                                    <p>
                                        <strong>Functions:</strong>
                                    </p>
                                    <p>
                                        · Team members will be able to create
new reports and forwarding them.                                        <strong></strong>
                                    </p>
                                    <p>
                                        · Project Managers will be able to
display forwarded reports                                        <strong></strong>
                                    </p>
                                    <p>
                                        <strong>Sub-ordinates: </strong>
                                        Connection to DB.
                                    </p>
                                    <p>
                                        <strong></strong>
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<strong></strong>
<p>
    <strong></strong>
</p>
<br clear="ALL"/>
<p>
    <strong>Table 10: New Report Creation</strong>
</p>
<h5>
    <strong>3.1.1.4 </strong>
    <strong> Profile Module</strong>
</h5>
<p>
    <img
        width="536"
        height="500"
        src="http://i68.tinypic.com/6zyjgx.png"
    />
</p>
<p>
    <strong>Figure 5: </strong>
    User Profiles<strong></strong>
</p>
<table cellpadding="0" cellspacing="0" align="left">
    <tbody>
        <tr>
            <td width="6" height="20">
            </td>
        </tr>
        <tr>
            <td>
            </td>
            <td width="381" height="380">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>Identification:</strong>
                                        Profile Module
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        Allow admin to create new accounts for
                                        Project managers and team members. In
                                        addition allow users to edit their
                                        personal profile pages.
                                    </p>
                                    <p>
                                        <strong>Functions: </strong>
                                    </p>
                                    <p>
                                        · Admin will be able to create new
                                        account.<strong></strong>
                                    </p>
                                    <p>
                                        · All users will be able to edit
                                        profile settings.<strong></strong>
                                    </p>
                                    <p>
                                        <strong>Sub-Modules: </strong>
                                    </p>
                                    <ul>
                                        <li>
                                            Edit Profile<strong></strong>
                                        </li>
                                        <li>
                                            Display Profile<strong></strong>
                                        </li>
                                        <li>
                                            Create Profile<strong></strong>
                                        </li>
                                    </ul>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong></strong>
</p>
<br clear="ALL"/>
<h6>
    <strong>Table 11: Profile</strong>
</h6>
<h6>
    <strong>3.1.1.4.1 </strong>
    <strong>Edit Profile Sub-Module</strong>
</h6>
<table cellpadding="0" cellspacing="0" align="left">
    <tbody>
        <tr>
            <td width="16" height="13">
            </td>
        </tr>
        <tr>
            <td>
            </td>
            <td width="352" height="286">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>Identification:</strong>
                                        Edit Profile Sub-Module
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        Allow non-admin users to edit their
                                        personal profile page.
                                    </p>
                                    <p>
                                        <strong>Functions:</strong>
                                    </p>
                                    <ul>
                                        <li>
                                            Edit address<strong></strong>
                                        </li>
                                        <li>
                                            Edit phone number<strong></strong>
                                        </li>
                                        <li>
                                            Edit e-mail<strong></strong>
                                        </li>
                                    </ul>
                                    <p>
                                        <strong>Sub-ordinates: </strong>
                                        Connection to DB.
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<br clear="ALL"/>
<p>
    <strong>Table 12: Profile Edition</strong>
</p>
<p>
    <strong></strong>
</p>
<h6>
    <strong>3.1.1.4.2 </strong>
    <strong>Display Profile Sub-Module</strong>
</h6>
<table cellpadding="0" cellspacing="0" align="left">
    <tbody>
        <tr>
            <td width="8" height="21">
            </td>
        </tr>
        <tr>
            <td>
            </td>
            <td width="405" height="322">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>Identification: </strong>
Display Profile Sub-Module                                        <strong></strong>
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        To allow users monitor other user
                                        sprofile page.
                                    </p>
                                    <p>
                                        <strong>Functions:</strong>
                                    </p>
                                    <p>
                                        · TC , name, surname, email, address,
number, of user will be displayed.                                        <strong></strong>
                                    </p>
                                    <p>
                                        · TC, name, surname, email, address,
                                        number, of a project manager or a team
                                        member selected from a list will be
                                        displayed.<strong></strong>
                                    </p>
                                    <p>
                                        <strong>Sub-ordinates: </strong>
                                        Connection to DB.
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<br clear="ALL"/>
<p>
    <strong>Table 13: Display Profile </strong>
</p>
<h6>
    <strong>3.1.1.4.3 </strong>
    <strong>Create Profile Sub-Module</strong>
</h6>
<table cellpadding="0" cellspacing="0" align="left">
    <tbody>
        <tr>
            <td width="24" height="22">
            </td>
        </tr>
        <tr>
            <td>
            </td>
            <td width="364" height="222">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>
                                            Identification: Create Profile
                                            Sub-Module
                                        </strong>
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        To allow admin create new user profile.
                                    </p>
                                    <p>
                                        <strong>Functions:</strong>
                                    </p>
                                    <p>
                                        · TC, name, surname of a user will be
                                        entered by admin<strong></strong>
                                    </p>
                                    <p>
                                        <strong>Sub-ordinates: </strong>
                                        Connection to DB.
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong></strong>
</p>
<br clear="ALL"/>
<p>
    <strong>Table 14: Profile Creation</strong>
</p>
<p>
    <strong></strong>
</p>
<h5>
    <strong>3.1.1.5 </strong>
    <strong>Task Management Module</strong>
</h5>
<p>
    <img
        width="604"
        height="447"
        src="http://i68.tinypic.com/1zqys9j.png"
    />
</p>
<p>
    <strong>Figure 6: </strong>
    Task Management<strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<table cellpadding="0" cellspacing="0">
    <tbody>
        <tr>
            <td width="390" height="429">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>Identification: </strong>
                                        Task Management Module
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        To allow Project managers assign tasks
                                        to team members. In addition allow to
                                        team members to display received tasks.
                                    </p>
                                    <p>
                                        <strong>Functions:</strong>
                                    </p>
                                    <p>
                                        · Project manager assign tasks to team
                                        members<strong></strong>
                                    </p>
                                    <p>
                                        · Team members can display received
                                        tasks<strong></strong>
                                    </p>
                                    <p>
                                        <strong>Sub-Modules:</strong>
                                    </p>
                                    <ul>
                                        <li>
                                            Display Tasks<strong></strong>
                                        </li>
                                    </ul>
                                    <p>
                                        · Create New Task (only available for
                                        Project Managers)<strong></strong>
                                    </p>
                                    <ul>
                                        <li>
Edit &amp; Remove Task                                            <strong></strong>
                                        </li>
                                    </ul>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<strong></strong>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<br clear="ALL"/>
<p>
    <strong>Table 15:Task Management</strong>
</p>
<p>
    <strong></strong>
</p>
<h6>
    <strong>3.1.1.5.1 </strong>
    <strong>DisplayTasksSub-Module</strong>
</h6>
<table cellpadding="0" cellspacing="0" align="left">
    <tbody>
        <tr>
            <td width="17" height="24">
            </td>
        </tr>
        <tr>
            <td>
            </td>
            <td width="416" height="313">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>Identification: </strong>
                                        Display Tasks Sub-Module
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        To allow team members and Project
                                        managers monitor tasks.
                                    </p>
                                    <p>
                                        <strong>Functions:</strong>
                                    </p>
                                    <p>
                                        · Project manager and Team member will
                                        be able to see all taks in a list. In
                                        addition team members will be able to
see recently added new tasks.                                        <strong></strong>
                                    </p>
                                    <p>
                                        · Information about selected task is
                                        displayed.<strong></strong>
                                    </p>
                                    <p>
                                        <strong>Sub-ordinates: </strong>
                                        Connection to DB.
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<strong></strong>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<br clear="ALL"/>
<p>
    <strong>Table 16: Display Task</strong>
</p>
<h6>
    <strong>3.1.1.5.2 </strong>
    <strong>Create New TaskSub-Module</strong>
</h6>
<table cellpadding="0" cellspacing="0" align="left">
    <tbody>
        <tr>
            <td width="16" height="1">
            </td>
        </tr>
        <tr>
            <td>
            </td>
            <td width="388" height="388">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>Identification:</strong>
                                        Create New Task Sub-Module
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        To allow Project managers assign tasks
                                        to team members.
                                    </p>
                                    <p>
                                        <strong>Functions:</strong>
                                    </p>
                                    <p>
· Project manager creates a task                                        <strong></strong>
                                    </p>
                                    <p>
                                        · Project manager defines start and
finish date for the task                                        <strong></strong>
                                    </p>
                                    <p>
· Project manager enters cost                                        <strong></strong>
                                    </p>
                                    <p>
                                        · Project manager select a team member
                                        from a list<strong></strong>
                                    </p>
                                    <p>
                                        · Project manager assign task to team
                                        member<strong></strong>
                                    </p>
                                    <p>
                                        <strong>Sub-ordinates: </strong>
                                        Connection to DB.
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<br clear="ALL"/>
<p>
    <strong>Table 17: Task Assignment</strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong>3.1.1.5.3 Edit &amp; Remove Task Sub-Module</strong>
</p>
<table cellpadding="0" cellspacing="0" align="left">
    <tbody>
        <tr>
            <td width="16" height="1">
            </td>
        </tr>
        <tr>
            <td>
            </td>
            <td width="388" height="303">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>Identification:</strong>
                                        Edit &amp; Remove Task Sub-Module
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        To allow Project managers edition and
                                        removal of tasks.
                                    </p>
                                    <p>
                                        <strong>Functions:</strong>
                                    </p>
                                    <p>
                                        · Project manager select a task from
                                        list<strong></strong>
                                    </p>
                                    <p>
                                        · Project manager sign selected task as
                                        cancelled or finished.<strong></strong>
                                    </p>
                                    <ul>
                                        <li>
Task is terminated.                                            <strong></strong>
                                        </li>
                                    </ul>
                                    <p>
                                        <strong>Sub-ordinates: </strong>
                                        Connection to DB.
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<br clear="ALL"/>
<p>
    <strong>Table 18: Edit &amp; Remove Task</strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong>3.1.1.5.4 Reporting Sub-Module</strong>
</p>
<table cellpadding="0" cellspacing="0">
    <tbody>
        <tr>
            <td width="388" height="303">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>Identification:</strong>
                                        Reporting Sub-Module
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        To allow team members create and send
                                        reports to their Project managers about
                                        a selected task.
                                    </p>
                                    <p>
                                        <strong>Functions:</strong>
                                    </p>
                                    <p>
· Team Member selects a task form list                                        <strong></strong>
                                    </p>
                                    <p>
                                        · Team member types definition and
                                        descriptions to <strong></strong>
                                    </p>
                                    <p>
                                        · Project managers will be able to see
                                        forwarded reports<strong></strong>
                                    </p>
                                    <p>
                                        <strong>Sub-ordinates: </strong>
                                        Connection to DB.
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<br clear="ALL"/>
<p>
    <strong>Table 19:</strong>
    Reporting<strong></strong>
</p>
<p>
    <strong>3.1.1.5.5 Rewarding Module</strong>
</p>
<table cellpadding="0" cellspacing="0" align="left">
    <tbody>
        <tr>
            <td width="15" height="26">
            </td>
        </tr>
        <tr>
            <td>
            </td>
            <td width="388" height="303">
                <table cellpadding="0" cellspacing="0" width="100%">
                    <tbody>
                        <tr>
                            <td>
                                <div>
                                    <p>
                                        <strong>Identification:</strong>
                                        Rewarding Module
                                    </p>
                                    <p>
                                        <strong>Purpose: </strong>
                                        Only the administrator can reward the
                                        team member with extra fee or
                                        permission.
                                    </p>
                                    <p>
                                        <strong>Functions:</strong>
                                    </p>
                                    <p>
                                        · The administrator selects a member
                                        form list<strong></strong>
                                    </p>
                                    <ul>
                                        <li>
Select member’s reward                                            <strong></strong>
                                        </li>
                                    </ul>
                                    <p>
                                        · Project managers will be able to see
                                        rewarding team members<strong></strong>
                                    </p>
                                    <p>
                                        <strong>Sub-ordinates: </strong>
                                        Connection to DB.
                                    </p>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </td>
        </tr>
    </tbody>
</table>
<br clear="ALL"/>
<p>
    <strong> </strong>
</p>
<p>
    <strong>Table 20: Rewarding</strong>
</p>
<p>
    <strong></strong>
</p>
<h4>
    <a name="_Toc246349788"></a>
    <a name="_Toc484227100">3.1.2 Data Decomposition</a>
</h4>
<p>
    This section is about describing each data entity and its logical
    structure. All data are saved in the database. We will take information
    from the database thanks to the query. We described a data dictionary.
</p>
<table border="1" cellspacing="0" cellpadding="0">
    <tbody>
        <tr>
            <td width="187" valign="top">
                <p>
                    <strong> Column name</strong>
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    <strong>Type </strong>
                </p>
            </td>
            <td width="217" valign="top">
                <p>
                    <strong>Column statu</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Project_name
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar(60)
                </p>
            </td>
            <td width="217" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Project_id
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Number(6)
                </p>
            </td>
            <td width="217" valign="top">
                <p>
                    Not null (primary key)
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Project_manager
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(60)
                </p>
            </td>
            <td width="217" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Start_day
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Date
                </p>
            </td>
            <td width="217" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Finish_day
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Date
                </p>
            </td>
            <td width="217" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    %completed
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Number(2)
                </p>
            </td>
            <td width="217" valign="top">
                <p>
                    Not nul
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Planned_cost
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Float
                </p>
            </td>
            <td width="217" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Actual_cost
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Float
                </p>
            </td>
            <td width="217" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    New_actual_cost
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    flaot
                </p>
            </td>
            <td width="217" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    T_date
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    date
                </p>
            </td>
            <td width="217" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong>Table 21:</strong>
    project_information
</p>
<table border="1" cellspacing="0" cellpadding="0">
    <tbody>
        <tr>
            <td width="187" valign="top">
                <p>
                    <strong>Column name</strong>
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    <strong>Type </strong>
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    <strong>Column statu</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Project_id
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Number(6)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null(foreign key)
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Task_name
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(60)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Task_id
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Number(12)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null(primary key9
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Person
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(80)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Start_day
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Date
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Finish_day
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Date
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    %completed
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Number(2)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not nul
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Specific_cost
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Float(13)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Role
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(30)
                </p>
            </td>
            <td width="238" valign="top">
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong></strong>
</p>
<p>
    <strong>Table 22:</strong>
    task_information
</p>
<table border="1" cellspacing="0" cellpadding="0">
    <tbody>
        <tr>
            <td width="192" valign="top">
                <p>
                    <strong>Column name</strong>
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    <strong>Type </strong>
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    <strong>Column statu</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="192" valign="top">
                <p>
                    Project_id
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Number(6)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null(foreign key)
                </p>
            </td>
        </tr>
        <tr>
            <td width="192" valign="top">
                <p>
                    Risk
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(255)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not Null
                </p>
            </td>
        </tr>
        <tr>
            <td width="192" valign="top">
                <p>
                    Probability
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Number(3)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not Null
                </p>
            </td>
        </tr>
        <tr>
            <td width="192" valign="top">
                <p>
                    Impact
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(255)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not Null
                </p>
            </td>
        </tr>
        <tr>
            <td width="192" valign="top">
                <p>
                    Mitigation
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(255)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not Null
                </p>
            </td>
        </tr>
        <tr>
            <td width="192" valign="top">
                <p>
                    New_risk
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(255)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Null
                </p>
            </td>
        </tr>
        <tr>
            <td width="192" valign="top">
                <p>
                    Acceptance_of_new_risk
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(70)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Null
                </p>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong>Table 23:</strong>
    risk_information
</p>
<table border="1" cellspacing="0" cellpadding="0">
    <tbody>
        <tr>
            <td width="187" valign="top">
                <p>
                    <strong>Column name</strong>
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    <strong>Type </strong>
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    <strong>Column statu</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Project_id
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Number(6)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null(foreign key)
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Task_id
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Number(12)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null(foreign key)
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Actual_cost
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Float(13)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Planned_cost
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Float(13)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not nul
                </p>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong>Table 24:</strong>
    cost_information
</p>
<table border="1" cellspacing="0" cellpadding="0">
    <tbody>
        <tr>
            <td width="187" valign="top">
                <p>
                    <strong>Column name</strong>
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    <strong>Type </strong>
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    <strong>Column statu</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Tc
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Number(11)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Name
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(60)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    b-date
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    date
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Phone_no
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Number(12)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    e-mail
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(30)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    undergraduate
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(100)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Graduate
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(100)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Experiences
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(100)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Null
                </p>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong></strong>
</p>
<p>
    <strong>Table 25:</strong>
    personal_information
</p>
<table border="1" cellspacing="0" cellpadding="0">
    <tbody>
        <tr>
            <td width="187" valign="top">
                <p>
                    <strong>Column name </strong>
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    <strong>Type </strong>
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    <strong>Column statu</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Tc
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Number(11)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null(foreign key)
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Role
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(20)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Task_id
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Number(15)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Hourly_cost
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Float(13)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong>Table 26:</strong>
    follow_up_hours
</p>
<table border="1" cellspacing="0" cellpadding="0">
    <tbody>
        <tr>
            <td width="187" valign="top">
                <p>
                    <strong>Column name</strong>
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    <strong>Type</strong>
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    <strong>Column statu</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    Role_name
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Varchar2(50)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null
                </p>
            </td>
        </tr>
        <tr>
            <td width="187" valign="top">
                <p>
                    role_id
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    Number(5)
                </p>
            </td>
            <td width="238" valign="top">
                <p>
                    Not null (primary key)
                </p>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong>Table 27:</strong>
    ROLE_information
</p>
<p>
    <img
        width="602"
        height="539"
        src="http://i65.tinypic.com/10i5635.png"
    />
</p>
<p>
    <strong>Figure 7: </strong>
    Database Design<strong></strong>
</p>
<h2>
    <a name="_Toc484227101"></a>
    <a name="_Toc311920413">3.2 Dependency Description</a>
</h2>
<p>
    <strong>3.2.1. </strong>
    <strong>Intermodule Description</strong>
</p>
<table border="1" cellspacing="0" cellpadding="0">
    <tbody>
        <tr>
            <td width="121" valign="top">
                <p>
                    <strong>PMA Modules</strong>
                </p>
            </td>
            <td width="85" valign="top">
                <p>
                    Login Module
                </p>
            </td>
            <td width="105" valign="top">
                <p>
                    Project Organization Module
                </p>
            </td>
            <td width="108" valign="top">
                <p>
                    Task Management Module
                </p>
            </td>
            <td width="85" valign="top">
                <p>
                    Profile Module
                </p>
            </td>
            <td width="108" valign="top">
                <p>
                    Risk &amp; Cost Management Module
                </p>
            </td>
        </tr>
        <tr>
            <td width="121" valign="top">
                <p>
                    Login Module<strong></strong>
                </p>
            </td>
            <td width="85" valign="top">
                <p>
                    <strong>X1</strong>
                </p>
            </td>
            <td width="105" valign="top">
                <p>
                    <strong> </strong>
                </p>
            </td>
            <td width="108" valign="top">
                <p>
                    <strong> </strong>
                </p>
            </td>
            <td width="85" valign="top">
                <p>
                    <strong> </strong>
                </p>
            </td>
            <td width="108" valign="top">
                <p>
                    <strong> </strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="121" valign="top">
                <p>
                    Project Organization Module<strong></strong>
                </p>
            </td>
            <td width="85" valign="top">
                <p>
                    <strong>X2</strong>
                </p>
            </td>
            <td width="105" valign="top">
                <p>
                    <strong> </strong>
                </p>
            </td>
            <td width="108" valign="top">
                <p>
                    <strong> </strong>
                </p>
            </td>
            <td width="85" valign="top">
                <p>
                    <strong>X3</strong>
                </p>
            </td>
            <td width="108" valign="top">
                <p>
                    <strong> </strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="121" valign="top">
                <p>
                    Task Management Module<strong></strong>
                </p>
            </td>
            <td width="85" valign="top">
                <p>
                    <strong>X4</strong>
                </p>
            </td>
            <td width="105" valign="top">
                <p>
                    <strong>X5</strong>
                </p>
            </td>
            <td width="108" valign="top">
                <p>
                    <strong> </strong>
                </p>
            </td>
            <td width="85" valign="top">
                <p>
                    <strong> </strong>
                </p>
            </td>
            <td width="108" valign="top">
                <p>
                    <strong> </strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="121" valign="top">
                <p>
                    Profile Module<strong></strong>
                </p>
            </td>
            <td width="85" valign="top">
                <p>
                    <strong>X6</strong>
                </p>
            </td>
            <td width="105" valign="top">
                <p>
                    <strong> </strong>
                </p>
            </td>
            <td width="108" valign="top">
                <p>
                    <strong> </strong>
                </p>
            </td>
            <td width="85" valign="top">
                <p>
                    <strong>X7</strong>
                </p>
            </td>
            <td width="108" valign="top">
                <p>
                    <strong> </strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="121" valign="top">
                <p>
                    Risk &amp; Cost Management Module
                </p>
            </td>
            <td width="85" valign="top">
                <p>
                    <strong>X8</strong>
                </p>
            </td>
            <td width="105" valign="top">
                <p>
                    <strong>X9</strong>
                </p>
            </td>
            <td width="108" valign="top">
                <p>
                    <strong>X10</strong>
                </p>
            </td>
            <td width="85" valign="top">
                <p>
                    <strong> </strong>
                </p>
            </td>
            <td width="108" valign="top">
                <p>
                    <strong> </strong>
                </p>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong>Table 28: </strong>
    Intermodule description
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    X1,X2,X4,X6,X8 means that user must be authorized to login to use all
    modules of the system.
</p>
<p>
    X5,x9 means that task, risk and cost management cannot be done unless the
    project is created
</p>
<p>
    X10 means risk &amp; cost management cannot be done unless task management
    is planned
</p>
<p>
    X3,x7 means that some functions in project organization module and profile
    module cannot be done unless user has some special authorization. Such as
    admin’s user creation or project organization.
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<h4>
    <a name="_Toc484227102">3.2.2. Data Dependencies</a>
</h4>
<p>
    There are relations between data entities. These relationships are provided
    in detail below.
</p>
<table border="1" cellspacing="0" cellpadding="0">
    <tbody>
        <tr>
            <td width="111" valign="top">
                <p>
                    <strong> Name </strong>
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    <strong> Type </strong>
                </p>
            </td>
            <td width="95" valign="top">
                <p>
                    <strong> Size </strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="111" valign="top">
                <p>
                    Project_id
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    number
                </p>
            </td>
            <td width="95" valign="top">
                <p>
                    6
                </p>
            </td>
        </tr>
        <tr>
            <td width="111" valign="top">
                <p>
                    Task_id
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    number
                </p>
            </td>
            <td width="95" valign="top">
                <p>
                    12
                </p>
            </td>
        </tr>
        <tr>
            <td width="111" valign="top">
                <p>
                    Planned_cost
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    float
                </p>
            </td>
            <td width="95" valign="top">
                <p>
                    13
                </p>
            </td>
        </tr>
        <tr>
            <td width="111" valign="top">
                <p>
                    Actual_cost
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    float
                </p>
            </td>
            <td width="95" valign="top">
                <p>
                    13
                </p>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong>Table 29</strong>
    :cost_information
</p>
<p>
    <strong>
        <img
            width="391"
            height="143"
            src="http://i63.tinypic.com/2zstbg6.png"
        />
    </strong>
    <strong></strong>
</p>
<p>
    <strong>Attributes :</strong>
    project_id,task_id,planned_cost,actual_cost<strong></strong>
</p>
<p>
    <strong>RelationshipType:</strong>
    One - to – one
</p>
<p>
    <strong>Figure 8:</strong>
    cost-follow up
</p>
<p>
    <strong>
        <img
            width="418"
            height="128"
            src="http://i64.tinypic.com/8zh4qw.png"
        />
    </strong>
    <strong></strong>
</p>
<p>
    <strong>Attributes :</strong>
    project_id,task_id,planned_cost,actual_cost<strong></strong>
</p>
<p>
    <strong>RelationshipType:</strong>
    One - to – many
</p>
<p>
    <strong>Figure 9:</strong>
    cost-task
</p>
<p>
    <strong> </strong>
</p>
<p>
    <strong> </strong>
</p>
<p>
    <strong> </strong>
</p>
<p>
    <strong> </strong>
</p>
<p>
    <strong> </strong>
</p>
<table border="1" cellspacing="0" cellpadding="0">
    <tbody>
        <tr>
            <td width="140" valign="top">
                <p>
                    <strong> Name</strong>
                </p>
            </td>
            <td width="142" valign="top">
                <p>
                    <strong> Type</strong>
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    <strong> Size</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="140" valign="top">
                <p>
                    Project_name
                </p>
            </td>
            <td width="142" valign="top">
                <p>
                    Varchar2
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    60
                </p>
            </td>
        </tr>
        <tr>
            <td width="140" valign="top">
                <p>
                    Project_id
                </p>
            </td>
            <td width="142" valign="top">
                <p>
                    Number
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    6
                </p>
            </td>
        </tr>
        <tr>
            <td width="140" valign="top">
                <p>
                    Project_manager
                </p>
            </td>
            <td width="142" valign="top">
                <p>
                    Varchar2
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    60
                </p>
            </td>
        </tr>
        <tr>
            <td width="140" valign="top">
                <p>
                    Start_day
                </p>
            </td>
            <td width="142" valign="top">
                <p>
                    Date
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    8
                </p>
            </td>
        </tr>
        <tr>
            <td width="140" valign="top">
                <p>
                    Finish_day
                </p>
            </td>
            <td width="142" valign="top">
                <p>
                    Date
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    8
                </p>
            </td>
        </tr>
        <tr>
            <td width="140" valign="top">
                <p>
                    Planed_cost
                </p>
            </td>
            <td width="142" valign="top">
                <p>
                    Float
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    13
                </p>
            </td>
        </tr>
        <tr>
            <td width="140" valign="top">
                <p>
                    Actual_cost
                </p>
            </td>
            <td width="142" valign="top">
                <p>
                    Float
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    13
                </p>
            </td>
        </tr>
        <tr>
            <td width="140" valign="top">
                <p>
                    %completed
                </p>
            </td>
            <td width="142" valign="top">
                <p>
                    Number
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    3
                </p>
            </td>
        </tr>
        <tr>
            <td width="140" valign="top">
                <p>
                    New_actual_cost
                </p>
            </td>
            <td width="142" valign="top">
                <p>
                    float
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    13
                </p>
            </td>
        </tr>
        <tr>
            <td width="140" valign="top">
                <p>
                    T_date
                </p>
            </td>
            <td width="142" valign="top">
                <p>
                    date
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    8
                </p>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong>Table 30:</strong>
    project_information
</p>
<p>
    <strong> </strong>
</p>
<p>
    <strong>
        <img
            width="413"
            height="140"
            src="http://i64.tinypic.com/2d14jyg.png"
        />
    </strong>
    <strong></strong>
</p>
<p>
    <strong>Attributes :</strong>
    project_id,project_name,project_manager, start_day,
    planned_cost,actual_cost, %completed<strong></strong>
</p>
<p>
    <strong>RelationshipType:</strong>
    One - to – one
</p>
<p>
    <strong>Figure 10:</strong>
    Project-task
</p>
<p>
    <img
        width="493"
        height="158"
        src="http://i65.tinypic.com/24mxp53.png"
    />
</p>
<p>
    <strong>Attributes :</strong>
    project_id,task_id,planned_cost,actual_cost
</p>
<p>
    <strong>RelationshipType:</strong>
    Many - to – one
</p>
<p>
    <strong>Figure 11:</strong>
    risk-cost<strong></strong>
</p>
<p>
    <strong> </strong>
</p>
<p>
    <strong>
        <img
            width="427"
            height="121"
            src="http://i65.tinypic.com/1iebgo.png"
        />
    </strong>
    <strong></strong>
</p>
<p>
    <strong>Attributes :</strong>
    project_id,project_name,project_manager, start_day,
    planned_cost,actual_cost, %completed
</p>
<p>
    <strong> </strong>
</p>
<p>
    <strong>RelationshipType:</strong>
    One - to –many<strong></strong>
</p>
<p>
    <strong>Figure 12:</strong>
    Project - risk<strong></strong>
</p>
<p>
    <strong> </strong>
</p>
<p>
    <strong> </strong>
</p>
<p>
    <strong> </strong>
</p>
<table border="1" cellspacing="0" cellpadding="0">
    <tbody>
        <tr>
            <td width="130" valign="top">
                <p>
                    <strong>Name </strong>
                </p>
            </td>
            <td width="113" valign="top">
                <p>
                    <strong>Type </strong>
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    <strong>size </strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="130" valign="top">
                <p>
                    Project_id
                </p>
            </td>
            <td width="113" valign="top">
                <p>
                    number
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    6
                </p>
            </td>
        </tr>
        <tr>
            <td width="130" valign="top">
                <p>
                    Task_name
                </p>
            </td>
            <td width="113" valign="top">
                <p>
                    Varchar2
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    60
                </p>
            </td>
        </tr>
        <tr>
            <td width="130" valign="top">
                <p>
                    Task_id
                </p>
            </td>
            <td width="113" valign="top">
                <p>
                    number
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    12
                </p>
            </td>
        </tr>
        <tr>
            <td width="130" valign="top">
                <p>
                    Person
                </p>
            </td>
            <td width="113" valign="top">
                <p>
                    Varchar2
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    60
                </p>
            </td>
        </tr>
        <tr>
            <td width="130" valign="top">
                <p>
                    Start_day
                </p>
            </td>
            <td width="113" valign="top">
                <p>
                    date
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    8
                </p>
            </td>
        </tr>
        <tr>
            <td width="130" valign="top">
                <p>
                    Finish_day
                </p>
            </td>
            <td width="113" valign="top">
                <p>
                    date
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    8
                </p>
            </td>
        </tr>
        <tr>
            <td width="130" valign="top">
                <p>
                    %completed
                </p>
            </td>
            <td width="113" valign="top">
                <p>
                    number
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    3
                </p>
            </td>
        </tr>
        <tr>
            <td width="130" valign="top">
                <p>
                    Specific_cost
                </p>
            </td>
            <td width="113" valign="top">
                <p>
                    float
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    13
                </p>
            </td>
        </tr>
        <tr>
            <td width="130" valign="top">
                <p>
                    Role
                </p>
            </td>
            <td width="113" valign="top">
                <p>
                    Varchar2
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    30
                </p>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong>Table 31</strong>
    :task_information
</p>
<p>
    <strong>
        <img
            width="433"
            height="151"
            src="http://i63.tinypic.com/1rvj4o.png"
        />
    </strong>
</p>
<p>
    <strong>Attributes :</strong>
    project_id,task_name,task_definition, start_day,finish_day , %completed,
    specific_cost
</p>
<p>
    <strong> </strong>
</p>
<p>
    <strong>RelationshipType:</strong>
    One - to – one
</p>
<p>
    <strong>Figure 13:</strong>
    Project-task<strong></strong>
</p>
<table border="1" cellspacing="0" cellpadding="0">
    <tbody>
        <tr>
            <td width="140" valign="top">
                <p>
                    <strong>Name </strong>
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    <strong>Type </strong>
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    <strong>Size </strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="140" valign="top">
                <p>
                    Tc
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    number
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    1
                </p>
            </td>
        </tr>
        <tr>
            <td width="140" valign="top">
                <p>
                    Role
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    Varchar2
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    20
                </p>
            </td>
        </tr>
        <tr>
            <td width="140" valign="top">
                <p>
                    Hourly_cost
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    float
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    13
                </p>
            </td>
        </tr>
        <tr>
            <td width="140" valign="top">
                <p>
                    Task_id
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    number
                </p>
            </td>
            <td width="123" valign="top">
                <p>
                    15
                </p>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong>Table 32: </strong>
    follow_up_hours
</p>
<p>
    <strong>
        <img
            width="478"
            height="140"
            src="http://i66.tinypic.com/auibns.png"
        />
    </strong>
</p>
<p>
    <strong>Attributes :</strong>
    task_id, hourly_cost,name,surname.
</p>
<p>
    <strong> </strong>
</p>
<p>
    <strong>RelationshipType</strong>
    : Many - to – one<strong></strong>
</p>
<p>
    <strong>Figure 14:</strong>
    statu-follow up
</p>
<p>
    <strong> </strong>
</p>
<h2>
    <a name="_Toc311920414"></a>
    <a name="_Toc484227103">3.1 INTERFACE DESCRIPTION</a>
</h2>
<p>
    <strong>3.1.1 </strong>
    <strong>Module Interfaces</strong>
</p>
<h2>
    <a name="_Toc484227104"></a>
    <a name="_GoBack"></a>
    3.1.2 User Interface
</h2>
<p>
    <img
        width="604"
        height="345"
        src="http://i67.tinypic.com/2cnhvg5.png"
    />
</p>
<p>
    <strong>Figure 15: </strong>
    LoginPage<strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <img
        width="604"
        height="270"
        src="http://i67.tinypic.com/hu248z.png"
    />
</p>
<p>
    <strong>Figure 16: </strong>
    Admin Home Page<strong></strong>
</p>
<p align="center">
    <strong>
        <img
            width="604"
            height="267"
            src="http://i66.tinypic.com/21eau7b.png"
        />
    </strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong>Figure 17 : </strong>
    Admin Project Cost Page<strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong>
        <img
            width="604"
            height="299"
            src="http://i66.tinypic.com/mua3oo.png"
        />
    </strong>
    <strong></strong>
</p>
<p>
    <strong>Figure 18: </strong>
    Project Upgrade Page<strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p>
    <strong>
        <img
            width="604"
            height="419"
            src="http://i65.tinypic.com/242zkv5.png"
        />
    </strong>
    <strong></strong>
</p>
<p>
    <strong>Figure 19 : </strong>
    User Lists<strong></strong>
</p>
<p>
    <img
        width="604"
        height="267"
        src="http://i66.tinypic.com/21eau7b.jpg"
    />
</p>
<p>
    <strong>Figure 20: </strong>
    Timeline Page<strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p align="center">
    <strong></strong>
</p>
<p align="center">
    <strong></strong>
</p>
<p>
    <strong></strong>
</p>
<p align="center">
    <strong></strong>
</p>
<p align="center">
    <strong></strong>
</p>
<p align="center">
    <strong></strong>
</p>
<h1>
    <a name="_Toc484227105">4 DETAILED DESIGN</a>
</h1>
<h2>
    <a name="_Toc484227106"></a>
    <a name="_Toc311920416">4.1 Module Detailed Design</a>
</h2>
<h4>
    <a name="_Toc484227107">4.1.1 Class Diagram</a>
</h4>
<p>
    <img
        width="603"
        height="356"
        src="http://i65.tinypic.com/wjb28l.png"
    />
    <strong></strong>
</p>
<p align="center">
    <strong>Figure 23: </strong>
    Class Diagram
</p>
<h4>
    <a name="_Toc484227108">4.1.2 Project Organization Activity Diagram</a>
</h4>
<p>
    <img
        width="604"
        height="388"
        src="http://i64.tinypic.com/i5vvvt.png"
    />
</p>
<p>
    <strong>Figure 22 : </strong>
    Admin Login Module Activity Diagram
</p>
<p>
    <strong>
        <img
            width="602"
            height="295"
            src="http://i63.tinypic.com/2usc089.png"
        />
    </strong>
</p>
<p>
    <strong>Figure 23:</strong>
    Task Assign Module Activity Diagram
</p>
<p>
    <strong>
        <img
            width="605"
            height="439"
            src="http://i63.tinypic.com/el1ou9.png"
        />
    </strong>
</p>
<p>
    <strong>Figure 24:</strong>
    Risk Module Activity Diagram
</p>
<p>
    <strong>
        <img
            width="605"
            height="365"
            src="http://i65.tinypic.com/w88eg7.png"
        />
    </strong>
</p>
<p>
    <strong>Figure 25:</strong>
    Cost Module Activity Diagram
</p>
<h2>
    <a name="_Toc484227109"></a>
    <a name="_Toc311920417">4.2 Data Detailed Design</a>
</h2>
<p>
    In this section, we show the type of the data and size of the data.
</p>
<p>
    <img
        width="605"
        height="190"
        src="http://i66.tinypic.com/2j3qgqt.png"
    />
</p>
<p>
    <strong>Table 33: </strong>
    Project_information
</p>
<p>
    <img
        width="605"
        height="170"
        src="http://i66.tinypic.com/24mhvr9.png"
    />
</p>
<p>
    <strong>Table 34:</strong>
    Task_information
</p>
<p>
    <img
        width="603"
        height="147"
        src="http://i66.tinypic.com/a5b7fa.png"
    />
</p>
<p>
    <strong>Table 35:</strong>
    Risk_information
</p>
<p>
    <img
        width="606"
        height="111"
        src="http://i65.tinypic.com/2ljjrkk.png"
    />
</p>
<p>
    <strong>Table 36:</strong>
    Cost_information
</p>
<p>
    <img
        width="604"
        height="155"
        src="http://i64.tinypic.com/27yrinq.png"
    />
</p>
<p>
    <strong>Table 37:</strong>
    Personal_information
</p>
<p>
    <strong>
        <img
            width="603"
            height="57"
            src="http://i63.tinypic.com/1izvo8.png"
        />
    </strong>
</p>
<p>
    <strong>Table 38:</strong>
    Role_information
</p>
<p>
    <img
        width="604"
        height="92"
        src="http://i66.tinypic.com/29lcyu8.png"
    />
</p>
<p>
    <strong>Table 39:</strong>
    Follow_up_hours
</p>
<p>
    <strong>4.3 RequirementsTraceability Matrix(RTM)</strong>
</p>
<p align="center">
    <strong>RequirementsTraceability Matrix(RTM)</strong>
</p>
<table border="1" cellspacing="0" cellpadding="0">
    <tbody>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    <strong>ID</strong>
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    <strong>REQUIREMENT</strong>
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    <strong>DESIGN SPECIFICATION</strong>
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    <strong>PROGRAM MODULE</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    1.1
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Admin, Project maneger and team member can login the
                    system.
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Loginmodule
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    2.1
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Admin can createnewproject.
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Adminmodule
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    2.2
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Admincan assignprojectmanager.
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Adminmodule
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    2.3
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Admin can createnewuser
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Adminmodule
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.1
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Project manager can assigntask
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project plan
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Taskassignmodule
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.2
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Project manager can assign role
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project plan
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Taskassignmodule
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.3
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Project manager can enter time period
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project plan
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Taskassignmodule
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.4
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Team member can updatetaskinformation
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project plan
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Taskassignmodule
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.5
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Project manager can seeplannedcost, actualcost.
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Costmodule
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.6
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Project manager can reportthecost
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Costmodule
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.7
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Project manager canenternewactualcost
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Costmodule
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.8
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Team member can enternewactualcost
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Costmodule
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.9
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Project manager can see risk table .
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Risk module
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.10
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Project manager can enterrisks.
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Risk module
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.11
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Project manager can acceptorrejectthenew risk
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Risk module
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.12
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Project manager can reporttherisks
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Risk module
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.13
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Project manager can seeothersand his/her
                    personalinformation.
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Personalinformation
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Profile module
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.14
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Project manager can change his/her personalinformation.
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Personalinformation
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Profile module
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.15
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Project manager can changepassword.
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Personalinformation
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Profile module
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.16
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Team member can changethepassword.
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Personalinformation
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Profile module
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.17
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Team member can see risk table.
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Risk module
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.18
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Team member can enternew risk
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Risk module
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.19
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Team member canseeplannedcostandactualcost.
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Costmodule
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.20
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Team member can enterextracost.
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Project organization
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Costmodule
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.21
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Team member can seeallpersonalinformation.
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Personalinformaton
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Profile module
                </p>
            </td>
        </tr>
        <tr>
            <td width="48" valign="top">
                <p align="center">
                    3.22
                </p>
            </td>
            <td width="208" valign="top">
                <p align="center">
                    Team member can change his/her personalinformation.
                </p>
            </td>
            <td width="189" valign="top">
                <p align="center">
                    Personalinformaton
                </p>
            </td>
            <td width="172" valign="top">
                <p align="center">
                    Profile module
                </p>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <strong>Table 40:</strong>
    RTM
</p>
<p>
    <strong></strong>
</p>