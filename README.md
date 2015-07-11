Raneto
======

[Raneto](http://raneto.com) is a free, open, simple Markdown powered Knowledgebase for Nodejs. [Find out more &rarr;](http://docs.raneto.com/what-is-raneto)

khomco/Raneto Contribution
------------
My goal is to implement multiple roles for Raneto to be run.  One role, the current role of Raneto, is for a single instance of a knowledge base tied to a
single isolated group of content.  The second role, which I hope to implement, is an aggregator which will consume the content of a distributed set
of single instance Raneto installs. This comes from a need for an organization where there are a disparate set of teams with their own knowledge base needs (private/public, hosted in their own repo) and yet create an ecosystem where teams can learn about the other's products/services without bothering them with emails, IMs, incident tickets, etc.

Requirements
------------

* [Node.js](http://nodejs.org) **v0.10+**

Install
-------

1. Download the latest version of Raneto from the [releases page](https://github.com/gilbitron/Raneto/releases)
2. Create a new directory where you would like to run the app, and un-zip the package to that location
3. Fire up a Terminal, the Node Command Prompt or shell and change directory to the root of the Raneto application (where app.js and config.js are)
4. run `npm install` to install the node dependencies
5. To start Raneto, run `npm start`
6. Visit `http://localhost:3000` in your web browser

Note: When running on a live site you'll want to set the `PORT` env variable to `80` so you don't need to add `:3000` to the URL.

Demo & Docs
-----------

See http://docs.raneto.com

Contribute
----------

See http://docs.raneto.com/contributing

Showcase
--------

Using Raneto in the wild? We'd love to see it. Add your site to the [Raneto Showcase](https://github.com/gilbitron/Raneto/wiki/Raneto-Showcase).

Credits
-------

Raneto was created by [Gilbert Pellegrom](http://gilbert.pellegrom.me) from
[Dev7studios](http://dev7studios.com). Released under the [MIT license](https://raw.githubusercontent.com/gilbitron/Raneto/master/LICENSE).
