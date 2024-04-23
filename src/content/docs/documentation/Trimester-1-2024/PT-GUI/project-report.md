---
title: PT-GUI Overview - Trimester 1 24
description: A final report for the PT-GUI project.
---

## 1. Objectives and Structure

### 1.1 Overview, Goals and Objectives
The Deakin Detonator Toolkits (DDT) aims to simplify penetration testing by integrating a user-friendly 
interface that narrows the gap between the operator and command line. It includes 
comprehensive documentation and instructions for each tool which will transform the learning
experience for beginner developers and reshape how penetration testing methods are applied.
Currently, DDT comprises of 44 built-in tools, 5 Attack Vectors and 12 walkthroughs, of which 36
tools have achieved basic functionality.
This trimester, the DDT team aims to make sure all the current 44 tools achieve maximum 
functionality and meet industry standards. Moreover, we have decided to resume integrating new 
tools into DDT. To make sure every implementation of new tools and functions works as expected 
we would deploy testing frameworks developed last year to identify underlying bugs before
merging them into the main product.
Upon finishing sprint 3, a refurbished version of DDT will be released for Hardhat Enterprise,
establishing itself as a benchmark for penetration testing tools. Feedback and analysis generated
by real-world usage through Hardhat Enterprise developers will offer valuable insights, benefiting
the ongoing development of DDT.

### 1.2 Aims for the Trimester
 - **Refine existing tools**: Enhancement of the usability and functionality of current tools within
DDT.
 - **Improve usability**: Investigate the implementation of file uploader functionalities and
explore other general improvements as well.
 - **Standardize coding practice**: Develop a framework to standardize coding practices
across all contributors in the project.
 - **Integrate new tools**: Research and implement new penetration testing tools into DDT.

### 1.3 Trimester Deliverables
 - **Enhancement of existing tools**: Fix current bugs that exist within tools in DDT to 
achieve maximum functionality. The current plan isto eliminate all bugs across various
tools existing under the “tools” section.
 - **Usability improvement**: Implement file uploader, save output files and process
termination functionalities to all tools to improve the functionality and usability of 
DDT.
 - **Coding style framework**: Develop a framework that outlines the coding practices and
13
stylesthat are currently used to ensure efficiency and quality throughout the whole project.
- **Test Summary Report**: This report tracks the progress made in DDT. This report will
serve as a detailed snapshot of the testing process, providing an overview of the testing,
highlighting not only pass/fail outcomes but also the test coverage, any issues
encountered and any pending tasks.
- **New release of DDT version**: Release an updated and refurbished version of DDT with
improved functionalities to Hardhat Enterprise by the end of sprint 3.

### 1.4 Long Term Deliverables
 - **Test Summary Report**: To keep a detailed record of progress, a comprehensive Test 
Summary Report will be generated at the conclusion of each upcoming trimester until the
development of DDT reaches completion.
 - **Test Automation**: Utilize automated testing to enhance efficiency, uniformity and
uphold industrial standards.
 - **Test Closure Report**: Once the application has met all its desired functionalities and is
set to be deployed to the public, the Test Closure Report will sum up the entirety of the 
testing process, emphasizing valuable insights, knowledge gained and future 
recommendation for upcoming projects.

### 1.5 Project Members

| Name         | Role           |
|--------------|----------------|
| Bradley Bogg | Project Lead   |
| Zhen Kang Kok | Project Co-Lead |
| Michael John Pigott | Project Co-Lead |
| Sebastian Rao | Project Member |
| Seth Johnson | Project Member |
| Arshpratap Singh Somal | Project Member |
| Matthew Mina Mikhail | Project Member |
| Jashanpreet Singh Kamboj | Project Member |
| Syed Ubaid Ahmed | Project Member |
| Stephen Peterson | Project Member |
| Abbas Biju | Project Member |
| Neris Sherwell | Project Member |
| Vittorio Truglio | Project Member |
| Naveenkumar Yogavijayan | Project Member |
| Aafiya Irfan | Project Member |
| Jonathon Guido Schlack | Project Member |
| Anjo Puthanpurackal Joseph | Project Member |
| Kevin Jose | Project Member |
| Naman Bakshi | Project Member |
| Srujana Sravanthi Gudey | Project Member |
| Luv Manish Ghodasara | Project Member |
| Ankit Bhardwaj | Project Member |
| Siddharth Raj | Project Member |
| Gurneet Singh | Project Member |
| K S H M Vihare Walawwe Sameera Buwaneka Senevirathne | Project Member |
| Shubham Chandel | Project Member |
| Waqas Sarwar | Project Member |
| Cyriac Jose | Project Member |
| Maria Rose Francis | Project Member |
| Ganga Marx | Project Member |
| Justin Carr | Project Member |
| Isaiah Spokes | Project Member |
| Gia Thien Thai | Project Member |
| Harsh K Patel | Project Member |

## 2. Mid Trimester Review

### 2.1 Progress Update
 - **Tool Enhancement and Bug Fixes**: Considerable progress has been made in 
enhancing the functionality of existing tools within DDT. The team has diligently 
worked on fixing numerous bugs across various tools ensuring that they are fully 
functional. These efforts have resulted in a robust and reliable toolset, laying a solid 
foundation for further development. 
 - **Useability Improvements**: A key milestone has been reached with the successful 
implementation of the file uploader feature. This enhancement improves the ability for 
the customer to elegantly make files available to the application free of permission 
errors and manual path finding. This has significantly enhanced the user experience of 
DDT. The DDT leadership team has laid the groundwork for implementing a new UI 
across all existing tools. This provides plentiful opportunities for student engagement, 
bug identification and testing and UX. 
 - **Coding Standard Framework**: A draft framework for coding standards has been 
developed, indicating a proactive approach to ensuring efficiency and quality 
throughout the project by the team. It includes multiple underpinning coding standards 
exhibited throughout the code and enables identification of inconsistencies.
 - **Baseline Component Development**: The creation of a reference component marks a 
pivotal step in establishing a baseline for all components within DDT. This component serves 
as a benchmark for identifying bugs and ensuring consistency across the project. 
By laying this groundwork, the team has set the stage for more efficient bug 
identification and resolution in the upcoming phases. This baseline component will be 
used in tandem with the coding standard framework.

### 2.2 Project Plan Updates
 - **Testing document**: While progress has been substantial in various areas, work on the 
testing document (closure report) has yet to commence. However, this presents an 
opportunity for the team to focus its efforts on documenting the testing process 
comprehensively in the remaining time. By prioritising this task, the team will ensure 
that valuable insights and lessons learned are captured to inform future development 
phases effectively. This will be a key deliverable in the second half of the trimester.
 - **Testing Automation**: Although testing automation has not yet been initiated, this 
aspect remains on the plans for future implementation if time permits. The team 
recognizes the potential benefits of automated testing in enhancing efficiency, 
uniformity, and upholding industry standards. As the project progresses, efforts will be 
directed towards exploring and implementing automated testing solutions to further 
streamline the testing process.
 - **Priority Refocus**: Our initial goals included the scope of improving upon existing tools. 
This trimester deliverable has been adjusted to meeting the requirements from the 
product owner. The team will priortise the implementation of goals 1-3 for the second
half of this trimester.


### 2.3 Member Contributions
| Name         | Contribution           |
|--------------|------------------------|
| Bradley Bogg | Uploader Feature, Runtime Dependency Installer, CI Update, Arjun Bug Fix, ArpSpoof Bug Fix, Airbase NG Bug Fix, Aircrack NG Bug Fix, Component Baselining Development, UI Feature Design and Creation, Airbase NG Feature Implementation: UI, Foremost Feature Implementation: Dependency, SMB Tooltip |
| Zhen Kang Kok | UI Design Update, Component Baselining Development, WPScan Fix, PKExec Bug Fix |
| Michael John Pigott | Eyewitness Tooltip, Arjun Feature Improvement (Stability option), Readme Cleanup |
| Sebastian Rao | Netcat Improvements, Netcat Bug Fix |
| Seth Johnson | - |
| Arshpratap Singh Somal | - |
| Matthew Mina Mikhail | - |
| Jashanpreet Singh Kamboj | - |
| Syed Ubaid Ahmed | - |
| Stephen Peterson | - |
| Abbas Biju | - |
| Neris Sherwell | Path Mapping Bugs, Gyoithon Dependencies Bug |
| Vittorio Truglio | - |
| Naveenkumar Yogavijayan | - |
| Aafiya Irfan | - |
| Jonathon Guido Schlack | - |
| Anjo Puthanpurackal Joseph | - |
| Kevin Jose | - |
| Naman Bakshi | - |
| Srujana Sravanthi Gudey | - |
| Luv Manish Ghodasara | - |
| Ankit Bhardwaj | Feature Improvement Airbase NG |
| Siddharth Raj | - |
| Gurneet Singh | - |
| K S H M Vihare Walawwe Sameera Buwaneka Senevirathne | - |
| Shubham Chandel | Traceroute Tooltip, Crackmapexec Tooltip |
| Waqas Sarwar | - |
| Cyriac Jose | - |
| Maria Rose Francis | - |
| Ganga Marx | Application Testing |
| Justin Carr | - |
| Isaiah Spokes | - |
| Gia Thien Thai | - |
| Harsh K Patel | NBTScan Tooltip |

## 3. Project Handover

### 3.1 Project Contributions
| Name         | Contribution           |
|--------------|------------------------|
| Member 1     | Contribution           |
| Member 2     | Contribution           |
| Member 3     | Contribution           |
| Member 4     | Contribution           |
### 3.2 Knowledge Transfer
[Describe the process for knowledge transfer, including any training or documentation that will be provided to ensure a smooth handover.]

### 3.3 Status and Health
[Status and health – should this project continue or is it complete? How well prepared 
are you to progress this next trimester?]


## Resources
[ Make sure that each project indicates where the important project 
resources are, and any details needed to ensure that the company can progress this 
next trimester. Make sure to put all links here!]
