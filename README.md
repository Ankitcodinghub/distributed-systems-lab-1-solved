# distributed-systems-lab-1-solved
**TO GET THIS SOLUTION VISIT:** [Distributed Systems Lab 1 Solved](https://www.ankitcodinghub.com/product/distributed-systems-lab-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100305&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Distributed Systems Lab 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
The two main topics that are addressed in this laboratory activity are: ▪ design of JSON schemas;

▪ design of REST APIs.

In order to have a complete experience, an implementation of the designed REST APIs will also be developed, by completing an already existing implementation.

The context in which this laboratory activity is carried out is a ToDo Manager service, where users can keep track of the tasks they must do in the future. If you have attended the Web Applications I course delivered by Politecnico di Torino in the A.Y. 2019/2020, you may be already familiar with the main concepts behind the ToDo Manager, and you are invited to reuse what you did for the Labs of that course for carrying out this activity. Otherwise, you are invited to look at the documentation of the Web Applications I labs (https://elite.polito.it/teaching/current-courses/521-wa1?start=1) and to use, as starting point for your activity, the solution of Laboratory 10 (https://github.com/polito-WA1- 2020/lab10-task-manager-app).

The tools that are recommended for the development of the solution are:

<ul>
<li>▪ &nbsp;Visual Studio Code (https://code.visualstudio.com/) for the validation of JSON files
against the schemas, and for the implementation of the REST APIs;
</li>
<li>▪ &nbsp;OpenAPI (Swagger) Editor, extension of Virtual Studio Code, for the design of the
REST APIs;
</li>
<li>▪ &nbsp;Swagger Editor (https://editor.swagger.io/) for the automatic generation of a
server stub;
</li>
<li>▪ &nbsp;PostMan (https://www.postman.com/) for testing the web service implementing
the REST APIs;
</li>
<li>▪ &nbsp;DB Browser for SQLite (https://sqlitebrowser.org/) for the management of the
database.

The Javascript language and the Express (https://www.npmjs.com/package/express) framework of node.js platform are recommended for developing the implementation of the RESTful web service.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1. Design of JSON schemas

The first activity is about the design of JSON schemas for two core data structures of the ToDo Manager, i.e., the users who want to manage their task lists by means of this application, and the tasks they must carry out. All the design choices for which there are no specific indications are left to the students.

A user data structure is made of the following fields:

<ul>
<li>▪ &nbsp;id: unique identifier of the user in the ToDo Manager service (mandatory);</li>
<li>▪ &nbsp;name: user name of the user (mandatory);</li>
<li>▪ &nbsp;email: email address of the user, which must be used for the authentication to the
service (mandatory, it must be a valid email address);
</li>
<li>▪ &nbsp;password: the user’s password, which must be used for the authentication to the
service (the password must be at least 6 characters long).

A task data structure is made of the following fields:
</li>
</ul>
<ul>
<li>▪ &nbsp;id: unique identifier of the task in the ToDo Manager service (mandatory);</li>
<li>▪ &nbsp;description: textual description of the task (mandatory);</li>
<li>▪ &nbsp;important: this Boolean property is set to true if the task is marked as important,
false otherwise (default value: false);
</li>
<li>▪ &nbsp;private: this Boolean property is set to true if the task is marked as private, false if
the task is public (default value: true);
</li>
<li>▪ &nbsp;projects: the names of the projects in which the task is inserted. In the ToDo
Manager service, only a predetermined set of possible values for projects must be accepted (e.g., you can suppose that “Personal”, “WA1_Project”, “WA2_Project”, “DSP_Project” are the only acceptable values for the projects field);
</li>
<li>▪ &nbsp;date: the due date and hour of the task. The ToDo Manager service must accept only dates following January 1st, 2020;</li>
<li>▪ &nbsp;completed: this Boolean property is set to true if the task is marked as completed, false otherwise (default value: false);</li>
<li>▪ &nbsp;assignedTo: list of the users this task has been assigned to.

The JSON Schema standard that must be used for this activity is the Draft 7 (http://json-

schema.org/draft-07/schema#).

After completing the design of the schemas, it is suggested to write some JSON files as

examples, and to validate them against the schemas in Visual Studio Code. In this 2
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
development environment, validation errors are shown in the editor and in the “Problem” view. You can access this view in two alternative ways:

<ul>
<li>following the path View→Problems;</li>
<li>pressing Ctrl+Shift +M.
2. Design and implementation of REST APIs

The second activity is about the design of REST APIs for the ToDo Manager service. Specify and document your design of the REST APIs by means of the “OpenAPI (Swagger) Editor” extension of Visual Studio Code. For the design, you should reuse the schemas developed in the first part of the assignment, customizing them for being used in the REST APIs (e.g., you can suppose that each task is inserted into at most one project, for simplicity).

Then, the resulting openAPI document can be used as the starting point to develop an implementation of the designed REST APIs in a semi-automatic way: after importing the OpenAPI file to the stand-alone Swagger Editor (the online version or the locally installed version), you can automatically generate a server stub, corresponding to the design, to be filled with the requested functionalities. The implementation of many of the necessary functionalities is already available in the solution of the WA1 Lab 10. You are invited to reuse them in your implementation.

In greater detail, the service has to be designed and implemented according to the following specifications.

The service maintains information about the users who are enabled to use it and their tasks in a database. In particular, as common practice recommends, the password of the users’ accounts is not stored in the database, but instead a hash is computed and stored. Hint: For the computation of hash, you can use the bcrypt module of node.js. You can use the following website to generate the hash of a password, according to bcrypt: https://www.browserling.com/tools/bcrypt. If the generated hash starts with $2y$, replace that part with $2b$, as the node bcrypt module does not support $2y$ hashes.

Most of the features of the service can be accessed only after authentication. The only two operations that can be used without authentication are:

▪ the log-in operation;

▪ the GET operation to retrieve the list of all the tasks that are marked as public.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
In the authentication, the user must send the pair “email” and “password” to the service. If the log in is successful, the service creates a JWT token and sends it to the client. In greater detail, the service sets the expiration of the token to 7 days, puts the user’s “id” and “name” in the payload of the token, and sends it in a cookie.

After the authentication, the user has access to the traditional CRUD operations for the task elements:

<ul>
<li>▪ &nbsp;The user can create a new task (note that this task won’t be necessarily assigned to its creator – the assignment of a task to the users is explained later in this document). If the creation of the task is successful, the service assigns it a unique identifier and sends back the task data structure.</li>
<li>▪ &nbsp;The user can retrieve an existing task, identified by the specified id.</li>
<li>▪ &nbsp;The user can retrieve all the tasks that are assigned to himself.</li>
<li>▪ &nbsp;The user can update an existing task, identified by the specified id. For example,
this operation is useful to mark a task as completed, or to change its visibility from

public to private (and vice versa).
</li>
<li>▪ &nbsp;The user can delete an existing task, identified by the specified id.
Here are some recommendations for the design and development of the REST APIs related to these operations:
</li>
</ul>
<ul>
<li>▪ &nbsp;When a list of tasks is retrieved, a pagination mechanism is recommended, in order to limit the size of the messages the service sends back.</li>
<li>▪ &nbsp;When the users send a JSON task element to the service (e.g., for the creation of the task in the database managed by the ToDo Manager service, or for the update of an existing task), this input piece of data should be validated against the corresponding JSON schema. Hint: An express.js middleware suggested for validating requests against JSON schemas is express-json-validator-middleware (https://www.npmjs.com/package/express-json-validator-middleware ), based on ajv module (https://www.npmjs.com/package/ajv).</li>
<li>▪ &nbsp;The service should be HATEOAS (Hypermedia As The Engine of Application State) compliant. Hyperlinks should be included in responses and features should be self- describing. Therefore, when the ToDo Manager service sends back a JSON task or user object, this should include a self link referring to the URI where the resource can be retrieved with a GET operation. Moreover, a client should be able to perform all operations without having to build URLs.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
A central feature of the ToDo Manager service is the assignment of the tasks stored in the database to the users who have access to the service. It is suggested to organize the design and implementation of this feature in two subsequent steps.

<ol>
<li>First, design and implement the service in such a way that a task can be assigned to one and only one user. Only this user has the possibility to mark this task as completed.</li>
<li>Then, modify the service design and implementation in such a way that a task can be assigned to multiple users at the same time. Each user the task has been assigned to can mark the task as completed. Besides, the service allows a user to retrieve the list of users assigned to a task, and to remove the assignment of a task to a user. Hint: you might need to create a new table in the database, to represent this kind of relationship between tasks and users, and define some foreign keys so as to link this table with the tables storing the records related to users and tasks.</li>
</ol>
Finally, the service must offer an additional operation to assign automatically the non- assigned tasks to the users, in such a way that the assignments are balanced. While the design of this feature is mandatory, its implementation is optional.

Hint: This feature does not map to the classical database operations, but it is an operation that updates a number of resources. Therefore, it requires a dedicated POST operation and a transaction on the database.

Guidelines for the solution development How to make the server stub run

After you automatically generate the server stub using Swagger Editor, you need to perform some routing operations. Routing refers to determining how an application responds to a client request to a particular endpoint, which is a URI (or path) and a specific HTTP request method (GET, POST, and so on). More specifically, some route methods must be defined: a route method is derived from one of the HTTP methods, and is attached to an instance of the express class.

Unfortunately, routing is not automatically managed in the code generation mechanism provided by Swagger Editor. As such, before testing your stub server, you need to introduce the required route methods.

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Let us suppose that you must map a GET method to the “/api/tasks/public” path; additionally, in the corresponding route method, the callback function that must be invoked is getPublicTasks, located in the “controllers/Tasks.js” file automatically generated by Swagger Editor.

To manage the routing of this GET method, the file that must be modified is “index.js”. More specifically, after creating the Express app object, you need to perform two operations:

<ol>
<li>1) &nbsp;importing the module represented by “controllers/Tasks.js” using the require function, and thus getting an object (taskController) which gives access to the exported functions of “controllers/Tasks.js”;</li>
<li>2) &nbsp;creating the routing method for the GET operation, and mapping the path “/api/tasks/public” to the callback “taskController.getPublicTask”.</li>
</ol>
These two operations are depicted in the following screenshot, where they appear in lines 18-19. Comparing this screenshot with your “index.js” file, you can note that these two lines are the only ones that have been modified.

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
After installing the required node.js modules, you can test the server stub with Postman. At this point, you can proceed to populate the stub with the code that is required to provide the functionalities previously described in this document.

Database management

You are free to create your own database for your personal solution, using DB Browser for SQLite. However, we provide two databases, already populated with some records, which you can use or extend for your implementation of the server:

<ol>
<li>1) &nbsp;“databaseV1.db” contains only the users and tasks tables, and it has been designed be used for the ToDo Manager version where a single user can be assigned to each task;</li>
<li>2) &nbsp;“databaseV2.db” additionally contains the assignments table, and it has been designed to be used for the ToDo Manager version where multiple users can be assigned to each task.</li>
</ol>
</div>
</div>
</div>
