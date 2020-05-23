Hello everyone! My name is Sergey and I am a beginner frontend developer. I want to introduce such a js framework as Vue.js. As a beginner developer and a native js student, I really like this framework, because it is easy to learn and easy to learn. I hope I can convey this to you in my presentation. I will not compare it with other frameworks, but just talk about Vue.js

Let's start with this one. From a rating on GitHub. This is not a photoshop, I took screenshots about 5 days ago, preparing for the presentation. Of course, Vue.js and React.js are about the same in popularity. Until recently, they changed places, but for some time the first place belongs to Vue.js.

Vue.js was released by one person in 2014. And it was not a framework that was released by any large company. It was released by one person, it was Evan Yu. And because of his Asian appearance and origin, it seems to many that Vue.js is some kind of Chinese framework. But this, of course, is not true. Ewan Yu is Chinese by nationality, but lives in the USA, worked for Google. Worked with Angular, maybe this encouraged him to develop his own framework. Since 2016, the second version has been released.

These are the logos of various companies. Which services one way or another use Vue.js.

What is Vue.js in general, what does it carry there. Reactive components, this is a component framework, it uses a virtual DOM. He is for a predictable data stream, he is an all-inclusive framework, a lot of things are included in it out of the box. You do not need to build a framework from the library and the zoo of different plugins.

This is the root instance of any Vue.js application. We just import Vue from Vue. We make new Vue, mount some div with id app in it. Vue is going to webpack. But more often they use Vue CLI - command line intarface, which allows you to create a new project, assemble a config, etc.

This is what the HTML Vue application looks like. Just id app. <App /> and inside <App /> we already mount the components.

Theoretically, of course, you can. If we immediately put components in the div id = app, some reactive data that we would like to use will work too. But most likely we will not do that.

And it is important that a lot revolves around the relationship of the parent and the child component. Vue.js due to single threaded data. We make sure that the parent transfers some data to the child, and the child informs the parent about what the parent needs to do.

This is the parent component and it has a Child and, at some event, calls the handelNameChange method and gives props name.

This is a child component. It will receive name props, display it in input, and when some action happens on this input, just a native event, it will call handleInput, which will do this. $ Emit, will issue a custom event.

The central entity we are working with in Vue.js is the component. It offers such a thing as Single File Component. This is a file with the Vue extension. And the component essentially consists of three things. This is a template where we write html, script and style. We will not talk about style, because these are the usual styles css, less, sass, scss. The only feature is scoped styles. These are styles that will be available only in this component.

 

This is how the template of any Vue.js application looks. All interactive work with js in template is done using directives. This is the v-bind directive, it binds some data to the component. This is the v-if, v-else directive, they allow you to draw some elements or not to draw, depending on the conditions. V-on listener event. It was a complete view of these directives.

And this is an abbreviated record of the same directives.

This is actually conditional rendering. If there is some local state in the component, then we can draw or not draw any element.

In the first case, we do not draw the node in the DOM tree at all. In this case, we draw, but they have display: none by default.

This is an example of how we can change classes. Or js expression, an ordinary ternary operator. Or you can use such a map.

Let's move on to another very important directive. In no application, we can do without cycles. And let's try to see how we will render such a list of products.

There is a v-for directive for this. In fact, a loop through an array, through objects, works too. Here we have each element of the array, here is the index, the index is needed for each element. Well, for each element we pass props.

Well, the funniest thing about template is event modifier. Such a modifier as prevent allows you to call this event, Vue itself will substitute the default behavior. On forms, if necessary, prevent.

Stop is the stopPropagation modifier. You can combine, for example, stop.prevent.

And you can continue to delve further into the work of Vue.js, but this is at the training stage. But Vue.js still has a lot of interesting things. For example computed properties, component transition for animation. Components slots for transmitting props. And reactivity is very interesting.

There are also many community projects. There is ssr in the form of nuxt.js, there is pwa in the form of quasar, there is material disagn. And a lot of many things. The community is expanding, Vue is growing.

Well, what is on the way. This is Vue Composition Api.

Thank you for the attention.