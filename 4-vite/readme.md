# Vite
Vite is similar to Create React App. 

But it is also very different.

Create react app, delegates building and other tasks, to 'react scripts' which is intended to hide away all the details of how stuff works, and hide the configuration from you. In many instances this is a good thing. 


But if we want to do things differently, then we need access to that config.

What is different?

Create react app is great at producing a website. You have don that already (a mini website) 

A UI Component Library, is not a website. It is a library (more on this in the next section on package managers) Pattern library does not have an html page that it ships. So create react app is not ideal.

Vite exposes more config up front, and does not abstract it as much as create react aop does. You can use vite to build websites but you can also use it to build a library by changing the configuration (Show UI LIbrary Config) 

Vite also has a wizard like createReactApp to build a new vite app quickly.
