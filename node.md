# Node 

<details>
<summary>What is Node?</summary>
  
Node (more formally _Node.js_) is a runtime executed as a process on your computer which can run JavaScript code.

After downloading it from [its homepage](https://nodejs.org/en/) or better installing it through [your operating systems package manager](https://nodejs.org/en/download/package-manager/) (e.g. on Ubuntu `curl -sL https://deb.nodesource.com/setup_11.x | sudo -E bash -; sudo apt-get install -y nodejs`) you then have a program called `node` which you can invoke from the command line:

    node -e 'console.log(Math.random())'

will print a random float on the console.

You can also execute a JavaScript file like this:

    echo 'console.log(Math.random())' > random.js
    node random.js

_Node.js_ is similar to the JavaScript engine in your browers in the sense that it understands the same language. But when it comes to writing software with it, it is very different. You will very quickly encounter a package manager like [npm](https://docs.npmjs.com/about-npm/) to pull in libraries which you need for your project. These dependencies are managed through a file called [`package.json`](https://flaviocopes.com/package-json/) which you will find in basically every Node.js project folder.

</details>

----

<details>
<summary>Do I need to learn Express?</summary>
  
Express is the leading Node.js web framework right now. By learning Express you get the advantage of a huge community, great documentation and little trouble finding reusable components or libraries for express itself.

In spite of this, you can also choose another backend framework. Other popular frameworks are for example Hapi.js, Meteor.js or Koa.

</details>

----

<details>
<summary>Does Node replace Java or Python?</summary>
  
Node, Java and Python have different strengths.

With Node you get a Robust technology stack, it is fast due to it's event based character, you can use it very good for scaling(Microservices) and it has a rich ecosystem. On the other hand, due to his non-blocking I/O it is not suited for computation-heavy tasks like machine learning.

In Comparison with node, Java is used in big enterprise solutions and it has as well the advantage of multithreading. Python can be better than node, if you want to do some data science or machine learning.

In conclusion it comes all down to the task you want to accomplish.

</details>
