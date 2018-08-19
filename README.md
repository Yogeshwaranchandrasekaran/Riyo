# Riyo
<h1 style="text-align:left;"><b> WatBot - An Android ChatBot powered by IBM Watson </b></h1>
   <p>WatBot is an IBM Watson powered ChatBot running on Android and using    Watson Assistant service on IBM Cloud ( an open standards, cloud    platform for building, running, and managing apps and services).</p>
<h2 style="text-align:left;"> Coding the app on Android Stdio </h2>
   <p>Android Stdio is the official IDE for Android. Android Stdio provides    the fastest tools for building apps on every type of android device.
   <center><img src="https://github.com/Yogeshwaranchandrasekaran/Riyo/blob/master/images/as.png?raw=true alt="Watbot in Android studio" ></center>
<h2 style="text-align:left;"><b>Creation of Watson Assistant service</b></h1>
   <p>Watson Assistant combines a number of cognitive techniques to help     you build and train a bot - definin intents and entities and crafting     dialog to simulate Watson Assistant.
<h3 style="text-align:left;">Getting Started</h3>
    <p>Before start using the Watson Assistant, sign up an IBM cloud     account to create a service instance.</p>
<ol>
    <li>In service name field, type a unique name for the new instance of     the Watson Assistant service.</li>
    <li>Click create. There will be some details about the new instance in     the "Service Details" page</li>
</ol>
<h2 style="text-align:left;"><b>Creating a workspace</b></h2>
     <p>Workspace can be created by either creating a new workspace from      scratch or by importing a workspace from a JSON file.</p>
<ol>
     <li>Click the Watson Assistant service constance on the IBM Cloud      console to open the Service Details page.</li>
     <li>Then click the Watson Assistant<b> tooling </b>and click      <b>Launch</b> tool.</li>
     <li>Click <b>Click</b> to create a new workspace.</li>
     <li>Specify the details for new workspace</li>
<ul>
     <li>Name</li>
     <li>Description</li>
     <li>Language</li>
</ul>
<h2 style="text-align:left;"><b>Creating an Intent</b></h2>
      <p>An intent reprsents the purpose of a user's input such as       answering a question. By recognizing the intent expressed in a user's       input, the Watson Assistant service can choose the correct dialog       flow for responding to it. In the tool, the name of an intent is       always prefixed with the<b>#</b> character.
<ol>
       <li> In Watson Assistant tool, open the<b> Workspace</b> and then           click the <b> Intents </b> tab.</li>
       <li> Create New. </li>
       <li> Create the new Intent Name Field, type the descriptive name for        the intent. For example,</li>
<ul>
<li>#weather_conditions</li>
<li>#pay_bill</li>
<li>#cancel_policy</li>
</ul> 
       <li>    In User example Field, type the text of a user example for  the intent. the following are the examples for #weather_condition intent.</li>
<ul>
       <li>What's the weather?</li>
       <li>Is it raining?</li>
</ul>
       <li>Press Enter or click<b>+</b> to save.</li>
       <li>Repeat the same process to add more examples.</li>
       <li>When you have finished adding examples, click<b>Create</b> to finish creating the intent</li>
</ol>
<h2><b>Results</b></h2>
<p>The intent you created is added to the Intents tab, and the system begins to train itself on the new data.Click any intent in the list to open it for editing. The following changes can be made: </p>
<ul>
<li>Rename Intent.</li>
<li>Delete Intent.</li>
<li>Add, edit, or delete examples.</li>
<li>Move an example to a different intent.</li>
</ul>
<h2 style="text-align:left;"><b>Creating an Entity</b></h2>
<p>An entity represents a term or object that is relevant to the intents and that provides a specific context for an intent. By recognizing the entities the are mentioned int he user's input, the Watson Assistant service can choose the specific actions to take to fulfill an intent. In the tool , the name of an entity is always prefixed with the<b>@</b> character.</p>
<ol>
<li>In Watson Assistant tool, open the workspace and then click the <b> Entities</b> tab.</li>
<li> Click <b> Create New </b>.
<li> In the <b> Add the Entity Name </b> field, type a descriptive name for the entity. For example:</li>
<ul>
<li>@location</li>
<li>@menu_item</li>
<li>@product</li>
</ul>
<li>In the <b>Value</b> field, type the text of a possible value for the intent. An entity value can be any string up to 64 character in length.</li>
<li>In the <b>Synonyms</b> field, type any synonyms for the entity value. Press Enter to save each synonym.</li>
<li>Click <b>+</b> and repeat the process to add more entity values.</li>
<li> When finished adding values and synonoyms, click <b>Create</b>.
<h2 style="text-align:left;"><b>Build the dialog flow</b></h2>
<p>A dialog is a branching conversation flow that defines how your application reesponds when it recognizs the defined intents and entities.</p>
<h2 style="text-align:left;"><b>Configure the App</b></h2>
<p>To configure the App you need to get the Watson Assistant service Username, PassWord and WorkSpaceId.</p>
<ol>
<li>Update the main activity with the username and password of the respective users</li>
<h2 style="text-align:left;"><b>Enable Text to Speech</b></h2>
<ul>
<li>Create a Watson Text to Speech(TTS) service on IBM Cloud</li>
<li>Navigate to Service Credentials tab and click on "View Credentials".</li>
<li>Build and Run your app.</li>
<h2 style="text_align:left;"><b>Chat with your own bot</b></h2>
 <center><img src="https://github.com/Yogeshwaranchandrasekaran/Riyo/blob/master/images/IMG-20180819-WA0003.jpg?raw=true" alt="Android"></center>
<center><img src="https://github.com/Yogeshwaranchandrasekaran/Riyo/blob/master/images/IMG-20180819-WA0002.jpg?raw=true" alt="Android"></center>
     
