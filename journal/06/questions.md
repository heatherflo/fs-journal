# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > The main.js file is the entrypoint to the application. This is where the app decides what index.html file to be connected to and it initializes the app. 
  >src file (contains)>> main.js / app.vue / components / assets 

02. What is the difference between a vue `component` and `page`?

  > A 'page' is a view component that is pointed directly at a web page you will be viewing. 
  > A 'component' is a smaller piece of code that can be seen on multiple pages or views.
  * Both of these are essentially the same except that they have different hierarchies. 

03. What is ***Component-Based Architecture***?

  > CBA is the ability to see objects in code as one component and makes changes easier over a broader scope. We can change one aspect of the page without altering anything else on the page. Essentially it is a new and easier way to code for the front end. 

04. What are the three tags that make up a Vue component?

  > Template, Style, and Script

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > Lifestyle hooks are the stages of a component. There are various ones you use from the creation of your component to its deletion. 

06. Which component in Vue does the vue-router use to mount pages onto?

  > The vue router is what lets you navigate between pages. The navigation guards are what guides the ability to navigate based on the needs. 

07. What is the difference between the `AppState` and the state object within a component?

  > The appstate is a global storage unit that holds all the data that the application needs in the MVC. 
  > A state object is an object that holds all the data a component needs in the VueJS.

08. What is the responsibility of `Services` in our Vue projects?

  > Services are JS files that allow us to make functionality that will be exportable through our entire application. This could be accessing an API or any kind of functionality. 

09. What are ***props*** and how are they used? Provide an example

  > Props are how we pass values down from parent objects/elements to child elements within a component. If we register these props inside the app.vue then they can be used all over our application. Otherwise they are used locally within the component we are placing them inside. 

  ex: 
  <template>
  <div>
    <h2>{{ foodName }}</h2>
  </div>
</template>

<script>
  export default {
    props: [
      'foodName'
    ]
  }
</script>
*the props now equals food name and can be used in the header in the template. 


10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > We use the 'watch' method to watch for changes in the state so we can have other things occur as well- "side-effects" of actions taking place. 
