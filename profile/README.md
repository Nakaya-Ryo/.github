# PharmaForest (we have already 45 packages🎉🎉)

**A collaborative repository of SAS packages for pharmaceutical industry**, powered by PHUSE Data Visualization & Open-Source Technology(DVOST) Working Group.       
<p>
       <img src="https://github.com/PharmaForest/.github/blob/main/pharmaforest.png"
                      alt="pharmaforest" width="300" height="300">
       <img src="https://github.com/PharmaForest/.github/blob/main/pharmaforest_map.png"
                      alt="pharmaforest" width="300" height="300">
</p>


For more details about PharmaForest and the DVOST WG activity, please visit the PHUSE page:  
[PharmaForest: A Collaborative Repository of SAS Packages for Pharmaceutical Industry](https://advance.hub.phuse.global/wiki/spaces/WEL/pages/406355969/PharmaForest+A+Collaborative+Repository+of+SAS+Packages+for+Pharmaceutical+Industry)

**-Goal-**  
Through SAS Packages, we want to **actively encourage sharing of SAS know‑how** that has often stayed within individuals. By doing this, we aim to build up collective knowledge, boost productivity, ensure quality through standardization, and energize our community. 

**-Priority-**  
Our first priority is to **share openly**—and get others to share as well—so that more people can join in. On that basis, we’ll work on **improving quality, driving standardization, and creating long‑term value**.  

# Table of Contents

- [Packages](#packages)  
       - [Gallery Page](#gallery-page)  
       - [Ecosystem Map](#ecosystem-map)  
       - [GPT Navigators](#gpt-navigators)  
       - [How to install packages](#how-to-install-packages)  
- [Documents](#documents)
- [How to join PharmaForest](#join-our-pharmaforest--collaborators-welcome)
- [What is SAS Packages? / How to use SAS Packages? (quick start)](#what-is-sas-packages)
---

## Packages

PharmaForest already provides a wide range of SAS packages, and we will continue contributing even more packages over time. **To help users reach the package they need quickly, we provide several navigation options and discovery paths**, and we are committed to continuously improving the user experience.

### Gallery Page

The PharmaForest Gallery lets you browse and search detailed information for each package: [https://pharmaforest.github.io/](https://pharmaforest.github.io/)

<a href="https://pharmaforest.github.io/">
  <img src="https://github.com/PharmaForest/.github/blob/main/QR_pharmaforest.png"
       alt="QR" width="150" height="150">
</a>

### Ecosystem Map

Package ecosystem map summarizes overview and category of packages in PharmaForest.   

<img src="https://github.com/PharmaForest/.github/blob/main/ecosystem.png" alt="ecosystem_map" width="800">   

### GPT Navigators

You can use the **PharmaForest Navigators to ask** not only how to use individual packages, but also what packages are available across PharmaForest.

<img src="https://github.com/PharmaForest/.github/blob/main/forest_navigator_long.png" 
       alt="Dr.Forest" height="100" align="left" style="margin-right:10px;">
**Master Navigator(Beta version)** [Dr. Forest link](https://chatgpt.com/g/g-699610471260819196be8f76e324dafa-dr-forest)  
Dr. Forest is a master navigator of PharmaForest. He is an excellent and diligent GPT assistant who can answer most questions about PharmaForest and details of #1-#15 packages. However, please understand that he is not speaking on behalf of our organization. You need to sign up to ChatGPT (at least a free user account) to talk to him. See more about [his background](https://github.com/PharmaForest/.github/blob/main/DrForest_background.md).

<img src="https://github.com/PharmaForest/.github/blob/main/apple.png" 
       alt="Dr.Forest" height="100" align="left" style="margin-right:10px;">
**Support Navigator(Beta version)** [Dr. Apple link](https://chatgpt.com/g/g-6996134ec0848191958c0dd931333f8c-dr-apple)  
Dr. Apple is a support navigator of PharmaForest. He has a strong character but cool GPT assistant who can asnwer details of #16 - #30 packages. Please understand that he is not speaking on behalf of our organization. You need to sign up to ChatGPT (at least a free user account) to talk to him. See more about [his background](https://github.com/PharmaForest/.github/blob/main/Apple_background.md).

<br><img src="https://github.com/PharmaForest/.github/blob/main/Rio.png" 
       alt="Rio" height="100" align="left" style="margin-right:10px;">
**Support Navigator(Beta version)** [Rio link](https://chatgpt.com/g/g-69961574d1d48191bf402340734acf25-rio)  
Rio is a support navigator of PharmaForest. She/He is a mysterious GPT assistant who can asnwer details of #31 - #45 packages. Please understand that she/he is not speaking on behalf of our organization. You need to sign up to ChatGPT (at least a free user account) to talk to her/him. See more about [her/his background](https://github.com/PharmaForest/.github/blob/main/Rio_background.md).

<br><img src="https://github.com/PharmaForest/.github/blob/main/SASUKE.png" 
       alt="SASUKE" height="100" align="left" style="margin-right:10px;">
**Support Navigator(Beta version)** [SASUKE link](https://chatgpt.com/g/g-69bda538e5c88191b00e804a5984a03a-sasuke)  
SASUKE is a support navigator of PharmaForest. He is a GPT assistant ninja who can asnwer details of #46 - #60 packages. Please understand that he is not speaking on behalf of our organization. You need to sign up to ChatGPT (at least a free user account) to talk to him. See more about [his background](https://github.com/PharmaForest/.github/blob/main/SASUKE_background.md).

<br><img src="https://github.com/PharmaForest/.github/blob/main/SASPackageLady.png" 
       alt="SAS Package Lady" height="100" align="left" style="margin-right:10px;">
**SAS Package Lady (Oba-chan) (Beta version)** [SAS Package Lady link](https://chatgpt.com/g/g-6996168447ec8191a238046fbba86451-sas-package-lady-oba-chan)  
SAS Package Lady (Oba-chan) is a warm diner-auntie GPT persona who helps you create SAS packages. Please understand that she is not speaking on behalf of our organization. You need to sign up to ChatGPT (at least a free user account) to talk to her.<br><br>

(2026/2/18: Link to GPT navigators has been changed.)

### How to install packages

PharmaForest SAS packages can be installed to your environment by using mirror=3 or mirror=PharmaForest in %installPackage() of SPF thanks to Bart.
~~~sas
%installPackage(OncoPlotter, mirror=PharmaForest)
%installPackage(OncoPlotter, mirror=3)
~~~

## Documents

### PharmaForest Rules

Rules of PharmaForest are here [PharmaForest Rules](https://github.com/PharmaForest/.github/tree/main/docs/Rules%20of%20the%20forest.md).

### Papers and Presentations

Papers and presentations of PharmaForest are here [Papers and Presentations](https://github.com/PharmaForest/.github/tree/main/papers).


### Agent Skills

Agent skill([spf-skills](https://github.com/PharmaForest/spf-skills)) is ready to support your SAS packages Framework(SPF) and PharmaForest life. Please check it out!

--- 


## Join Our "PharmaForest" – Collaborators Welcome!  
We are actively looking for collaborators to join and contribute to our program package. If you're interested in participating in any of the following ways, feel free to get in touch with us!
 
1. Become a PharmaForest Manager<br>
Help manage and lead the package alongside the current team.

2. Co-develop Original Packages<br>
Collaborate with us on building new tools such as "OncoPlotter," "misc", and more.

3. Mirror Your Own Packages<br>
Share your packages by hosting mirrors with us.

4. Contribute Macros and Tools to the "Devil Package"<br>
Add useful macros or functionalities to our "Devil" package to expand its features. "Devil" is a package for casually sharing playful or simple programs.

5. Join as a User<br>
Simply participate in the package as an active user, provide feedback, and stay up to date.
 
We welcome all levels of involvement. Whether you're a developer, researcher, or just someone interested in what we’re building, we’d love to hear from you!
 
Contact us if you're interested!
[Ryo Nakaya](https://www.linkedin.com/in/ryo-nakaya-a93292348/), 
[Yutaka Morioka](https://www.linkedin.com/in/morioka%E3%80%80%E6%A3%AE%E5%B2%A1-yutaka-%E8%A3%95-5ab910185/), 
[Hiroki Yamanobe](https://www.linkedin.com/in/hiroki-yamanobe-85a49a361/)

<p align="center">
  <img src="https://github.com/PharmaForest/.github/blob/main/wewantyou.png" alt="wewantyou" width="300">
</p>

---

## What is SAS Packages?

The package is built on top of **SAS Packages Framework(SPF)** developed by Bartosz Jablonski.

For more information about the framework, see [SAS Packages Framework](https://github.com/yabwon/SAS_PACKAGES).

You can also find more SAS Packages (SASPacs) in the [SAS Packages Archive(SASPAC)](https://github.com/SASPAC).

## How to use SAS Packages? (quick start)

### 1. Set-up SAS Packages Framework

First, create a directory for your packages and assign a `packages` fileref to it.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~sas
filename packages "\path\to\your\packages";
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Secondly, enable the SAS Packages Framework.
(If you don't have SAS Packages Framework installed, follow the instruction in 
[SPF documentation](https://github.com/yabwon/SAS_PACKAGES/tree/main/SPF/Documentation) 
to install SAS Packages Framework.)

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~sas
%include packages(SPFinit.sas)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


### 2. Install SAS package

Install SAS package you want to use with the SPF's `%installPackage()` macro.

- For packages located in **SAS Packages Archive(SASPAC)** run:
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~sas
  %installPackage(packageName)
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- For packages located in **PharmaForest** run:
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~sas
  %installPackage(packageName, mirror=PharmaForest)
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- For packages located at some network location run:
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~sas
  %installPackage(packageName, sourcePath=https://some/internet/location/for/packages)
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  (e.g. `%installPackage(ABC, sourcePath=https://github.com/SomeRepo/ABC/raw/main/)`)


### 3. Load SAS package

Load SAS package you want to use with the SPF's `%loadPackage()` macro.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~sas
%loadPackage(packageName)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


### Enjoy!

---
