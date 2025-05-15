![Dyalog OSS projects Banner](/assets/banner.png)

## About Dyalog

We (Dyalog Ltd) deliver an APL-based development environment that allows both subject matter experts and IT specialists to efficiently convert ideas into software solutions.
Dyalog APL is a high-performance implementation of the APL programming language, renowned for its expressive syntax and mathematical elegance. It is ideal for problem-solving, rapid prototyping, and concise code expression.
Dyalog is a development environment for Dyalog APL. It is widely used in domains like finance, analytics, and engineering. We also focus on the wider ecosystem by developing libraries and tooling for use with Dyalog.

Learn more by visiting [Dyalog Ltd's website](https://www.dyalog.com) or have a look at the [Dyalog Documentation](https://help.dyalog.com).

## What exactly is open source?

"Open source" refers to software whose design and source code are publicly accessible, allowing anyone to study, modify, and share it. Open source fosters collaboration, transparency, and wider community participation in building and improving technology.

At Dyalog Ltd, we are committed to supporting the open source community. By making more of our tools available as open source, we hope to invite more people to contribute, innovate, and help shape the future of APL together.

## Discussions and Community  

### Community Discussion Channels  
- **[GitHub Discussions](https://github.com/Dyalog/OSS-Projects/discussions)**: Participate in structured discussions about the projects, share your ideas, and engage with mentors and peers.  
- **[APL Orchard](https://apl.chat)**: A chat room dedicated to learn and teach APL, and to ask and answer questions about both golfing and general coding in APL. 

## Learn Dyalog APL

Whether you're new to APL or an experienced programmer looking to master Dyalog APL, these resources will help you on your journey:

- [Learning APL by Stefan Kruger](https://xpqz.github.io/learnapl/intro.html): A beginner-friendly resource that introduces APL concepts interactively and intuitively.
- [Mastering Dyalog APL](https://www.dyalog.com/mastering-dyalog-apl.htm): A comprehensive guide to building expertise in Dyalog APL, from basics to advanced topics.

Join the vibrant APL community at APL Orchard to connect with enthusiasts and mentors!

# Project list

## Project Ideas from the community

Do you have an idea for a project that you or someone should work on, but is not on our list? Great! 💡

We have made a [discussion](https://github.com/Dyalog/OSS-Projects/discussions/6) just for that, so we can comment and help you finalise it. Feel free to provide as much information as possible and then we'll look forward to connecting with you in this discussion

Please try to include as much as possible from this template:
 
```
- Name of the project:
- Estimated workload for you: 90 hours / 175 hours / 350 hours
- Estimated difficulty for you: easy/medium/hard
- Project URL
- Potential mentors/maintainers that would be relevant to talk to : 
- Description:
    Tell us your thoughts: what do you want to do, why and how?
- Skills that will be needed:
    For example: HTML, CSS, JavaScript, (interest in) APL, Python, game programming, guide writing…
- Expected outcomes/benefits for Dyalog and the community
    What are the goals and how do you see us and the community benefitting from your idea?
```

## Make the TryAPL front end mobile friendly
- Project: TryAPL Front End
- Size: Medium - 175h
- Difficulty level: Medium
- Project URL: https://github.com/Dyalog/TryAPL
- Potential mentors: Rich Park ([@rikedyp](https://github.com/rikedyp)), Aarush Bhat ([@sloorush](https://github.com/sloorush)), Neil Kirsopp ([@cursork](https://github.com/cursork))
- Discussions: [https://github.com/Dyalog/OSS-Projects/discussions/10](https://github.com/Dyalog/OSS-Projects/discussions/10)

#### Description:

TryAPL is an online service that allows users to experiment with APL in a web browser without having to install any additional software. APL code entered into the system is sent over HTTP to a sandboxed environment that interprets the code and returns the formatted output to the user. Moreover, the entire state of the execution workspace, including defined functions and variables, is stored in a serialised, compressed format client side in the browser so that no server-side sessions or state need to be maintained. The system includes a JavaScript-based input method for APL symbols for both keyboard and mouse, as well as the ability to interpret and render Dyalog Jupyter notebooks.

The front-end can be used on mobile devices, but was not designed with mobile-first principles and as such has some issues when viewed on some touchscreen devices. Improvement to the TryAPL front end will make APL more accessible to users on a wider range of devices.

This project is to develop the front end of TryAPL to be mobile friendly; the interface will be accessible on touchscreen devices. The input system will be refactored to an entirely managed system using JavaScript that prevents the device operating system's keyboard from popping up. There will need to be an on-screen keyboard that allows input of ASCII and APL characters. There should be some consideration for the use of interactive Jupyter notebook tutorials.

#### Expected outcomes:
The TryAPL project will have a new front end that can be deployed on https://tryapl.org.

#### Technologies involved:
HTML, CSS, JavaScript

## Scientific Graphics Library for EWC

- Project: EWC(Everywhere Window Create)
- Size: Medium - 175h
- Difficulty level: Medium
- Project URL: https://github.com/dyalog/ewc and https://github.com/dyalog/ewc-client 
- Potential mentors: Neil Kirsopp ([@cursork](https://github.com/cursork)), Morten Kromberg ([@mkromberg](https://github.com/mkromberg))
- Discussions: [https://github.com/Dyalog/OSS-Projects/discussions/11](https://github.com/Dyalog/OSS-Projects/discussions/11)
 
#### Description:
 
EWC (Everywhere Window Create) is an emulation of Dyalog's highly successful object library for Windows Win32 GUI applications. While the original is limited to Windows Desktops, EWC allows the creation of web applications and cross-platform desktop or mobile applications using a combination of APL code on the server and JavaScript/React on the client side.
 
EWC has wrapper classes for ApexCharts and KendoCharts, but these packages focus on business-oriented charting, and do not provide features like surface or contour charts, or other technical charting features that scientific users are likely to want. The task is to research available JavaScript libraries, identify one that will fit comfortably within EWC, and implement a wrapper class that makes it easy for the APL user to wield it. The EWC development team will be available for consultation and doing server-side work to create and optimise the new class if necessary.
 
#### Expected outcomes:

A new EWC object type that can be used in APL applications, a handful of samples demonstrating its use, and documentation that explains how to make use of the JavaScript library via EWC.
 
#### Technologies involved:
HTML, CSS, JavaScript, React, some basic APL

## File Picker and similar components for EWC

- Project: File Picker and similar components for EWC
- Size: Medium - 175h
- Difficulty level: Medium
- Project URL: https://github.com/dyalog/ewc and https://github.com/dyalog/ewc-client
- Potential mentors: Neil Kirsopp ([@cursork](https://github.com/cursork)), Morten Kromberg ([@mkromberg](https://github.com/mkromberg))
- Discussions: [https://github.com/Dyalog/OSS-Projects/discussions/13](https://github.com/Dyalog/OSS-Projects/discussions/13)

#### Description:

EWC (Everywhere Window Create) is an emulation of Dyalog's highly successful object library for Windows Win32 GUI applications. While the original is limited to Windows Desktops, EWC allows the creation of web applications and cross-platform desktop or mobile applications using a combination of APL code on the server and JavaScript/React on the client side.

The EWC client can run in any mainstream browser or via the Chromium Embedded Framework on platforms that support it. When running on a single-user machine (typically via CEF), there are a number of classes available to the Windows developer that are not currently supported by JavaScript because access to local resources is restricted. Examples include BrowseBox, FileBox, FontPicker, Printer Selection and Configuration dialogs. These classes necessarily require development on both the APL and the JavaScript sides - prior APL knowledge is not required.

The task is to implement as many as possible of these classes using either existing EWC components (Button, Edit, Combo, ListView, etc) or by implementing new ones, and APL code that will work under Linux, Microsoft Windows and Apple MacOS, to provide EWC users with cross-platform versions of these objects.

The EWC development team will be available for mentoring and to help with any necessary enhancements to EWC to support this work.

#### Required:

- Knowledge of JavaScript and React
- Desire to learn APL

#### Expected outcomes:
New EWC classes that can be used in APL applications, with documentation and examples.

#### Technologies involved: 
APL, EWC, JavaScript, React, HTML, CSS.

## Implement a New Language Backend for Co-dfns
- Project: Co-dfns
- Size: Large - 350h
- Difficulty level: Hard
- Project URL: https://github.com/Co-dfns/Co-dfns
- Potential mentors: Aaron Hsu ([@arcfide](https://github.com/arcfide)), Max Sun ([@MaxCan-Code](https://github.com/MaxCan-Code))
- Discussions: [https://github.com/Dyalog/OSS-Projects/discussions/12](https://github.com/Dyalog/OSS-Projects/discussions/12)

#### Description:

Co-dfns is an APL compiler with a novel architecture that is designed to support compiling APL to multiple different backend languages. 
The goal of this project is to add a new backend to Co-dfns. The choice of backend target language is open to the implementer. The current backend is implemented in C. 

Possible languages include any language of the mentee's choice, but a non-exhaustive list could be: JS, Java, Python, WASM, X86-64 Assembly, SML, OCaml, Zig, Rust, Go, Lua, CUDA, or any language of your choice

#### Expected outcomes:
New backend language support for Co-dfns. 

#### Technologies involved: 
APL, C, Co-dfns, and the language and tooling of the mentee's choice. 

## Dyalog Jupyter Projects

### Introduction

[Jupyter notebooks](https://jupyter.org/) are interactive documents that combine live code, equations, visualisations, and narrative text in a single, shareable format. They allow users to create and share documents containing executable code, output results, explanatory text written in [Markdown](https://en.wikipedia.org/wiki/Markdown), and rich media elements - Jupyter notebooks have become the de facto standard for data science and AI development, enabling researchers and practitioners to document their work, share reproducible analyses, and combine code execution with rich explanations. 

A Jupyter [kernel](https://docs.jupyter.org/en/stable/projects/kernels.html) is the computational engine that executes code contained in a Jupyter notebook. It acts as an independent process that interprets and runs code in a specific programming language (like [Python](https://www.python.org/), [R](https://www.r-project.org/), or [Julia](https://julialang.org/)), manages the notebook's state and variables, and communicates results back to the notebook interface through a standardised protocol. This separation between the notebook interface and kernel allows for language-agnostic functionality while maintaining a consistent user experience.

The [Dyalog Jupyter kernel](https://github.com/Dyalog/dyalog-jupyter-kernel) implements a subset of the Jupyter [protocol](https://jupyter-protocol.readthedocs.io/en/latest/), enabling the creation of [APL notebooks](https://github.com/Dyalog/dyalog-jupyter-notebooks), and APL-driven [Jupyter books](https://www.smashingmagazine.com/2015/01/designing-for-print-with-css/). 

Here are some examples of the kernel in use:

- [https://xpqz.github.io/learnapl](https://xpqz.github.io/learnapl)
- [https://xpqz.github.io/cultivations](https://xpqz.github.io/cultivations)
- [https://github.com/fastai/apl-study](https://github.com/fastai/apl-study)
- [https://github.com/yiyus/data-science-in-APL](https://github.com/yiyus/data-science-in-APL)
- [https://github.com/yiyus/ga](https://github.com/yiyus/ga)
- [https://github.com/yiyus/nu](https://github.com/yiyus/nu)

There are two tasks of medium difficulty that can be undertaken in this project:

### Dyalog Magics
- Project: Dyalog Jupyter Kernel
- Size: Medium - 175h
- Difficulty level: Medium
- Project URL: https://github.com/Dyalog/dyalog-jupyter-kernel
- Potential mentors: Stefan Kruger ([@xpqz](https://github.com/xpqz)), Jesús Galán López ([@yiyus](https://github.com/yiyus)), Martina Crippa ([@martanit](https://github.com/martanit)), Max Sun ([@MaxCan-Code](https://github.com/MaxCan-Code)), Neil Kirsopp ([@cursork](https://github.com/cursork))
- Discussions: [https://github.com/Dyalog/OSS-Projects/discussions/7](https://github.com/Dyalog/OSS-Projects/discussions/7)

The Dyalog Kernel currently does not implement any of the Jupyter [magics](https://ipython.readthedocs.io/en/stable/interactive/magics.html) -- meta-commands that don't get executed by the kernel itself, typically interfacing with the operating system, or with Jupyter extensions, "escaping" the Dyalog kernel in this case. 

The [Jupyter AI extension](https://jupyter-ai.readthedocs.io/en/latest/index.html) is an example of what can be done with magic commands. We would like to implement the magics protocol in the Dyalog Kernel, and implement some of the more commonly used magic commands on top of this. Hooking Dyalog up to the Jupyter AI magics would be a great stretch goal for this. There is a floating boundary on this -- the bulk of this will still be a Python job, but depending on how deep you go, you may want to pick up some Dyalog APL to let the backend drive some of the implementation. This is a good project for the Pythonista that has a burgeoning interest in array programming and APL. 

[Jeremy Howard](https://github.com/jph00) has implemented [Dyalog magics](https://github.com/AnswerDotAI/aplnb) for the Python kernel -- the opposite direction: it makes it possible to execute Dyalog APL commands in a Python notebook.

#### Expected outcomes:
Magics protocol implementation, + support for a set of magics
#### Skills required:
Python, interest in APL
#### Technologies involved:
Python, possibly JavaScript, possibly some APL

### Dyalog Jupyter Widgets
- Project: Dyalog Jupyter Kernel
- Size: Medium - 175h
- Difficulty level: Medium
- Project URL: https://github.com/Dyalog/dyalog-jupyter-kernel
- Potential mentors: Stefan Kruger ([@xpqz](https://github.com/xpqz)), Jesús Galán López ([@yiyus](https://github.com/yiyus)), Martina Crippa ([@martanit](https://github.com/martanit)), Max Sun ([@MaxCan-Code](https://github.com/MaxCan-Code)), Neil Kirsopp ([@cursork](https://github.com/cursork))
- Discussions: [https://github.com/Dyalog/OSS-Projects/discussions/7](https://github.com/Dyalog/OSS-Projects/discussions/7)

Jupyter supports [widgets](https://ipywidgets.readthedocs.io/en/8.1.2/) -- simple in-cell interactive controls, such as sliders, buttons etc. The widget architecture is kernel-agnostic, and any kernel can implement access to such widgets. In this project, we'd like to implement the widget protocol for the Dyalog Jupyter kernel, so that we can show a slider that sets an APL value. This would greatly enhance exploratory programming in a Dyalog APL notebook: hook a slider up to a parameter in a model and see what the effects are without having to actually type and execute cells. 

Implementing the widgets protocol needs to be done firstly in Python, to implement the callbacks, and secondly on the APL side to define ways to create the widgets. 

#### Expected outcomes:
Widgets protocol in kernel, plus APL implementation of the widget classes
#### Skills required: 
Python, and an interest in APL
#### Technologies involved: 
Python, APL

<p align="center">Made with ❤ at Dyalog Ltd</p>
