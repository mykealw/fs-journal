# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
the controller is what the answer used to be, I'm not sure if frameworks change things. 
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
A page is the total application currently on the routerview (often times made of many componets). A componet is a self sufficient element that can be displayed on the page. 

```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
v-for. This is the new school for each we used to use.
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
template- this is where we put the html -- 
script- this is where we do the JS logic and functions -- 
style- where we make it pretty. 
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Liskov Substitution Principle, good think his name wasn't Albert, too many vowels in a row. This principle is by far the hardest to understand. The best explaination I have found is, it's an extension of open-closed principle, as it’s a way of ensuring that derived classes extend the base class without changing behavior.

```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
I'm not sure what exactly this is asking. I am going to make a long explaination of what I think this is ask. Vue displays on the Vue.app. At that level you can place elements that will always be on the screen. Navbars, and other elements like a fab (floating action button) are examples. On that page there is also the router-view. On the router-view we display pages, like shows on a tv. There is a router js file that directs the router view to the right url, like flipping channels on a tv. The answer is somewhere in there, I hope. 
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
SCOPE! appState is global, the state is local.

```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
The responsibility of Services hasn't changed. It is to manipulate the data. Still cooks in the kitchen. 
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
Vue.app is the root element. Everything else is built upon it. 

```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
style whole vue project in sass, or on vue.app? not adding scope makes it global? 
add scope makes it limited to the page.

```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
react and ref. React is for full objects whereas ref is for primitive values. 

```