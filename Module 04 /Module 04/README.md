# Module 4: Open Source Software — Personal Project & Reflection

Welcome to my personal project repository! This Readme serves as my comprehensive, individual submission for **Module 4 — Open Source Software**.

This document is divided into three main sections to fulfill the assignment requirements:
* **Hands-On Work:** Screenshots and commands demonstrating my practical terminal work.
* **Concept Breakdown:** Detailed explanations of the concepts I learned regarding source code, Linux, standards, licensing, and business models.
* **Reflection:** How I learned, the challenges I faced, and my core takeaways.

---

## Part 1: Hands-on Work & Terminal Execution

To understand the core difference between source code and machine code (and the difference between compiled and interpreted languages), I engaged in hands-on terminal exercises.

### Commands Used & Explanations

To test a compiled language, I used C:

```bash
nano program.c

```
What it does: Opens the nano text editor in the terminal to create and write a basic C program. This represents writing source code—the human-readable set of instructions.


```bash
./program

```
What it does: Executes the newly compiled machine code binary directly in the Linux environment.

## Part 2: Course Concepts & Details
## 4.1 Introduction
This module introduced me to the relationship between Linux and open source software. I learned that software is normally created as source code, which is written in a programming language that humans can understand. A compiler can then translate the source code into machine instructions, producing a binary or executable program that a computer can run.

I also learned that not all software is created in the same way. Closed-source software normally gives users permission to use the compiled program, but the source code is kept private by the developer or company. This means users generally cannot inspect or modify the underlying code.

Open source software takes a different approach. The source code is made available so that users and developers can study it, modify it and, depending on the license, redistribute it.

## What I understood about Linux and open source
Linux developed alongside the growth of the open source movement. Because the source code is available, programmers from different backgrounds and organizations can examine the software, identify problems, improve it and contribute changes.

One important benefit is that the code can be inspected. This makes it possible for developers to look for problems such as security vulnerabilities, unwanted functionality and bugs.

I also learned that open source development is strongly based on collaboration. Instead of one company being solely responsible for developing a piece of software, many developers can contribute ideas and improvements.

## UNIX and Linux
The module also introduced the history of UNIX.
UNIX was originally created in 1969 and was later rewritten in the C programming language. UNIX became important in universities, scientific organizations and businesses because of its stability and useful development environment.

Linux was influenced by UNIX and adopted many of its concepts and design principles. Standards and compatibility specifications helped different UNIX and Linux systems work together.

## Standards
I learned that standards are important because they allow different software and operating systems to communicate and work together.
Organizations such as IEEE and POSIX help establish standards that improve compatibility between systems.
This means that software designed according to common standards can be easier to move from one operating system or environment to another.

## 4.2 Open Source Licensing
One of the most important concepts I learned in this module is that ownership, payment and licensing are different things.

When we talk about software, we need to ask three separate questions:

1. Who owns the intellectual property?

2. Does the user have to pay?

3. What is the user legally allowed to do with the software?

Open source does not necessarily mean that software costs nothing. The word "free" in free software mainly refers to freedom, not price. A license determines what users are allowed to do with software.

## Closed-source example
Microsoft Windows is an example of traditionally closed-source software. The company controls the source code and normally distributes compiled versions of the software. Users receive a license that defines how they may use the software.

## Open-source example
Linux is distributed under the GNU General Public License version 2 (GPLv2).
The GPL allows people to access and modify the source code. When modified versions are distributed under the relevant GPL requirements, the license helps preserve the ability of others to access and modify the software as well.
This taught me that an open source license is not simply permission to look at the code. It also defines what people can do with that code.

## 4.2.1 Free Software Foundation
The Free Software Foundation (FSF) was founded by Richard Stallman in 1985. I learned that the FSF uses the word "free" to mean freedom rather than zero cost.

The FSF promotes the idea that users should have the freedom to:

- Study software

- Share software

- Modify software

- Distribute modified versions

## Copyleft
An important concept introduced in this section was copyleft.
Copyleft is designed to make sure that the freedoms provided by a license continue to be available when software is modified and redistributed.

In simple terms: If you receive software with certain freedoms and distribute a modified version under a copyleft license, you may have to preserve those freedoms for the next users.

The GPL is a major example of a copyleft license.

## GPLv2 and GPLv3
I also learned that different versions of licenses can address different issues.
The module used the example of TiVoization, where hardware could prevent users from running modified versions of software even though the source code was available. This helped me understand that software freedom can involve more than simply providing source code. The practical ability to modify and use the software can also become an important licensing issue.

## 4.2.2 Open Source Initiative
The Open Source Initiative (OSI) was founded in 1998 by Bruce Perens and Eric Raymond.
The OSI promotes the concept of open source software and maintains a list of licenses that meet its open source definition. One important difference I learned is that not all open source licenses require modified software to remain under the same license.

## Permissive licenses
Licenses such as the BSD and MIT licenses are examples of permissive open source licenses.
They generally provide developers with considerable freedom to use, modify and redistribute the software, subject to the license conditions. For example, permissively licensed code can generally be incorporated into a larger proprietary product while following the requirements of the license. This is different from the stronger copyleft requirements associated with licenses such as the GPL.

## FOSS and FLOSS
The module explained that the terms Free and Open Source Software (FOSS) and Free/Libre/Open Source Software (FLOSS) are commonly used to bring these ideas together. The word "libre" helps distinguish freedom from the idea of something simply being free of charge.

## 4.2.3 Creative Commons
I learned that software licenses are not always appropriate for other types of creative work. For example, someone creating a photograph, article, illustration or educational resource may want to allow others to use their work while placing certain conditions on that use.
This is where Creative Commons (CC) licenses are useful.

Main Creative Commons conditions:
* **BY — Attribution**: The creator must be credited.

* **SA — ShareAlike**: Modified versions must generally be shared under the same licensing terms.

* **NC — NonCommercial**: The work cannot be used commercially under that license.

* **ND — NoDerivatives**: The original work can be shared, but modified versions cannot be distributed under that license.

These conditions can be combined to create different Creative Commons licenses. Examples include CC BY, CC BY-SA, CC BY-ND, CC BY-NC, CC BY-NC-SA, and CC BY-NC-ND. There is also CC0, which is intended to place a work as close to the public domain as legally possible.

## What I learned from Creative Commons
The important lesson for me is that "open" does not always mean that everything can be done with a work. The license tells me exactly what permissions and restrictions apply.

## 4.3 Open Source Business Models
At first, open source business models seemed confusing because I associated open source with software being free of charge. The module clarified that companies can make money from open source software.

* **The key idea is**: Open source describes how software can be used, studied, modified or distributed. It does not automatically mean that a company cannot charge money.

* **Support and services**: One business model is to provide paid support, maintenance, warranties or enterprise services around open source software. Companies can distribute software while charging customers for professional services.

* **Hardware**: Another model is to use open source software as part of a physical product. For example, a company can build hardware around Linux and sell the complete device. Examples include network equipment, security cameras, entertainment systems, and embedded devices.

* **Commercial products and services**: Companies can also build additional tools, platforms or services around open source projects. This allows businesses to create value without necessarily keeping the underlying software completely closed.

* **Community development**: I also learned that companies can employ developers to work on open source projects. Businesses may contribute to open source because they depend on the software themselves, want to improve the technology they use, or want to help influence the future direction of a project.

## Part 3: Reflections & Takeaways
## What I Learned
The biggest lesson from this module is that open source is more than simply software that is free to download.

It is an approach to software development and distribution that gives users access to source code and provides specific freedoms depending on the license. I learned that licensing determines what users can legally do with software.

I also learned that different open source philosophies exist. Some licenses emphasize preserving software freedoms through copyleft, while others are more permissive and allow developers to use the software in proprietary products.

## How I Learned It
I learned these concepts by studying the history of Linux and the development of the open source movement, alongside practicing with compiling code in the terminal.
The examples involving Linux, UNIX, GPL, BSD, Creative Commons and open source businesses helped me connect the theoretical ideas to real-world software. Comparing different licenses was particularly useful because it showed me that "open source" does not mean every project has exactly the same rules.

## Challenges I Faced
One of the main challenges was understanding the difference between:

- Free software

- Free-of-charge software

- Open source software

- Closed-source software

- Copyleft licenses

- Permissive licenses

Another challenge was understanding why different organizations have different philosophies about software freedom. The concept became easier once I separated price from freedom and focused on what the license actually permits users to do.

## Key Takeaways
Source code is the human-readable form of a program.

Closed-source software normally keeps its source code private.

Open source software makes its source code available under specific licensing conditions.

Free software does not necessarily mean free of charge.

Licenses determine what users can legally do with software.

GPL is an example of a copyleft license.

BSD and MIT are examples of more permissive open source licenses.

Creative Commons provides licensing options mainly for creative works rather than software.

Open source businesses can make money through support, services, hardware, products and other forms of added value.

Standards such as POSIX help different systems work together.

## My Overall Understanding
Before this module, I mainly thought of open source as software that people could download without paying. After studying the module, I understand that open source is fundamentally about access, permissions, collaboration and licensing.

The most important thing I learned is to never assume that software being "open source" means I can do absolutely anything with it. I need to check the specific license because different licenses provide different rights and responsibilities.

This understanding will be important as I continue learning Linux because Linux itself is closely connected to the open source development model.



