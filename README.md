<link rel="icon" type="image/png" href="./assets/favicon-96x96.png" sizes="96x96" />
<link rel="icon" type="image/svg+xml" href="./assets/favicon.svg" />
<link rel="shortcut icon" href="./assets/favicon.ico" />
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png" />
<link rel="manifest" href="./assets/site.webmanifest" />

![GSOCxDyalog Banner](./assets/banner.png)

## Finalised Ideas for GSoC 2025

### Make the TryAPL front end mobile friendly
- Project: TryAPL Front End
- Size: 175 hours
- Level: Medium
- Project URL: https://github.com/Dyalog/TryAPL

#### Description:

TryAPL is an online service that allows users to experiment with APL in a web browser without having to install any additional software. APL code entered into the system is sent over HTTP to a sandboxed environment that interprets the code and returns the formatted output to the user. Moreover, the entire state of the execution workspace, including defined functions and variables, is stored in a serialised, compressed format client side in the browser so that no server-side sessions or state need to be maintained. The system includes a JavaScript-based input method for APL symbols for both keyboard and mouse, as well as the ability to interpret and render Dyalog Jupyter notebooks.

The front-end can be used on mobile devices, but was not designed with mobile-first principles and as such has some issues when viewed on some touch-screen devices. Improvement to the TryAPL front end will make APL more accessible to users on a wider range of devices.

This project is to develop the front end of TryAPL to be mobile friendly; the interface will be accessible on touch screen devices. The input system will be refactored to an entirely managed system using JavaScript that prevents the device operating system's keyboard from popping up. There will need to be an on-screen keyboard that allows input of ASCII and APL characters. There should be some consideration for the use of interactive Jupyter notebook tutorials.

#### Expected outcomes:
The TryAPL project will have a new front end that can be deployed on https://tryapl.org.
Technologies involved: HTML, CSS, JavaScript

## For discussions and questions:

- Each project idea will have a post in the discussions tab where the idea can be discussed
- There is an open track in the discussions where any interested mentee can add their own ideas and based on our mentor availability we can accept the ideas

## Discussions and Community  

### Community Discussion Channels  
- **[APL Orchard](https://apl.chat)**: A chat room dedicated to learn and teach APL, and to ask and answer questions about both golfing and general coding in APL. 
- **[GitHub Discussions](https://github.com/Dyalog/GSOC-Ideas/discussions)**: Participate in structured discussions about GSoC projects, share your ideas, and engage with mentors and peers.  

### How to Get Involved  
- **Project-specific Discussions**: Each finalized project idea will have a dedicated post in the GitHub Discussions tab. 
- **Open Idea Submissions**: Got your own project idea? Share it in the open discussion track on GitHub. Based on mentor availability, we may guide and accept community-proposed ideas.

## About Dyalog

Dyalog APL is a high-performance implementation of the APL programming language, renowned for its expressive syntax and mathematical elegance. Designed for problem-solving, rapid prototyping, and concise code expression, Dyalog APL is widely used in domains like finance, analytics, and engineering.

Learn more on the Dyalog [Homepage](https://www.dyalog.com) or check out the [Documentation](https://help.dyalog.com).

## Learn Dyalog APL

Whether you're new to APL or an experienced programmer looking to master Dyalog, these resources will help you on your journey:

- [Learning APL by Stefan Kruger](https://xpqz.github.io/learnapl/intro.html): A beginner-friendly resource that introduces APL concepts interactively and intuitively.
- [Mastering Dyalog APL](https://www.dyalog.com/mastering-dyalog-apl.htm): A comprehensive guide to building expertise in Dyalog APL, from basics to advanced topics.

Join the vibrant APL community at APL Orchard to connect with enthusiasts and mentors!


<p align="center">Made with ❤ at Dyalog</p>
