<link rel="icon" type="image/png" href="./assets/favicon-96x96.png" sizes="96x96" />
<link rel="icon" type="image/svg+xml" href="./assets/favicon.svg" />
<link rel="shortcut icon" href="./assets/favicon.ico" />
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png" />
<link rel="manifest" href="./assets/site.webmanifest" />

![GSOCxDyalog Banner](./assets/banner.png)

## About Dyalog

Dyalog APL is a high-performance implementation of the APL programming language, renowned for its expressive syntax and mathematical elegance. Designed for problem-solving, rapid prototyping, and concise code expression, Dyalog APL is widely used in domains like finance, analytics, and engineering.

Learn more on the Dyalog [Homepage](https://www.dyalog.com) or check out the [Documentation](https://help.dyalog.com).

## For discussions and questions:

- Each project idea has a post in the discussions tab where the idea can be discussed
- There is an open track in the discussions where any interested mentee can add their own ideas and based on our mentor availability we can accept the ideas

## Discussions and Community  

### Community Discussion Channels  
- **[APL Orchard](https://apl.chat)**: A chat room dedicated to learn and teach APL, and to ask and answer questions about both golfing and general coding in APL. 
- **[GitHub Discussions](https://github.com/Dyalog/GSOC-Ideas/discussions)**: Participate in structured discussions about GSoC projects, share your ideas, and engage with mentors and peers.  

### How to Get Involved  
- **Project-specific Discussions**: Each finalized project idea will have a dedicated post in the GitHub Discussions tab. 
- **Open Idea Submissions**: Got your own project idea? Share it in the open discussion track on GitHub. Based on mentor availability, we may guide and accept community-proposed ideas.

## Learn Dyalog APL

Whether you're new to APL or an experienced programmer looking to master Dyalog, these resources will help you on your journey:

- [Learning APL by Stefan Kruger](https://xpqz.github.io/learnapl/intro.html): A beginner-friendly resource that introduces APL concepts interactively and intuitively.
- [Mastering Dyalog APL](https://www.dyalog.com/mastering-dyalog-apl.htm): A comprehensive guide to building expertise in Dyalog APL, from basics to advanced topics.

Join the vibrant APL community at APL Orchard to connect with enthusiasts and mentors!

## Finalised Ideas for GSoC 2025

### Make the TryAPL front end mobile friendly
- Project: TryAPL Front End
- Size: 175 hours
- Difficulty Level: Medium
- Project URL: https://github.com/Dyalog/TryAPL
- Potential mentors: [@rikedyp](https://github.com/rikedyp), [@sloorush](https://github.com/sloorush), [@cursork](https://github.com/cursork)
- Discussions: TBA

#### Description:

TryAPL is an online service that allows users to experiment with APL in a web browser without having to install any additional software. APL code entered into the system is sent over HTTP to a sandboxed environment that interprets the code and returns the formatted output to the user. Moreover, the entire state of the execution workspace, including defined functions and variables, is stored in a serialised, compressed format client side in the browser so that no server-side sessions or state need to be maintained. The system includes a JavaScript-based input method for APL symbols for both keyboard and mouse, as well as the ability to interpret and render Dyalog Jupyter notebooks.

The front-end can be used on mobile devices, but was not designed with mobile-first principles and as such has some issues when viewed on some touch-screen devices. Improvement to the TryAPL front end will make APL more accessible to users on a wider range of devices.

This project is to develop the front end of TryAPL to be mobile friendly; the interface will be accessible on touch screen devices. The input system will be refactored to an entirely managed system using JavaScript that prevents the device operating system's keyboard from popping up. There will need to be an on-screen keyboard that allows input of ASCII and APL characters. There should be some consideration for the use of interactive Jupyter notebook tutorials.

#### Expected outcomes:
The TryAPL project will have a new front end that can be deployed on https://tryapl.org.

#### Technologies involved:
HTML, CSS, JavaScript

### Scientific Graphics Library for EWC

- Project: EWC(Everywhere Window Create)
- Size: 175 hours
- Difficulty Level: Medium
- Project URL: https://github.com/dyalog/ewc and https://github.com/dyalog/ewc-client 
- Potential Mentors: [@cursork](https://github.com/cursork), [@mkromberg](https://github.com/mkromberg)
- Discussions: TBA
 
Description:
 
EWC (Everywhere Window Create) is an emulation of Dyalog's highly successful object library for Windows Win32 GUI applications. While the original is limited to Windows Desktops, EWC allows the creation of web applications and cross-platform desktop or mobile applications using a combination of APL code on the server and JavaScript/React on the client side.
 
EWC has wrapper classes for ApexCharts and KendoCharts, but these packages focus on business-oriented charting, and do not provide features like surface or contour charts, or other technical charting features that scientific users are likely to want. The task is to research available JavaScript libraries, identify one that will fit comfortably within EWC, and implement a wrapper class that makes it easy for the APL user to wield it. The EWC development team will be available for consultation and doing server-side work to create and optimise the new class if necessary.
 
#### Expected outcomes:

A new EWC object type that can be used in APL applications, a handful of samples demonstrating its use, and documentation that explains how to make use of the JavaScript library via EWC.
 
#### Technologies involved:
HTML, CSS, JavaScript, React, some basic APL

<p align="center">Made with ❤ at Dyalog</p>
