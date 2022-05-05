<!-- Updates to this file will be overwritten -->
<!-- markdown-link-check-disable -->
|  School of Computing |  |
| --------------- | --------------- |
| Title | Internet of Things |
| Module Coordinator| Uchenna Ogenyi |
| Email | [uchenna.ogenyi@port.ac.uk](mailto:uchenna.ogenyi@port.ac.uk) |
| Code | M30226|
| Moodle | [https://moodle.port.ac.uk/course/view.php?id=15563](https://moodle.port.ac.uk/course/view.php?id=15563) |

<!-- markdown-link-check-enable -->
## **Internet of Things**

Schedule and Deliverables

| Item | Value | Format | Outcomes | Deadline |
| --- | --- | --- | --- | --- |
| CW | 100% of CW | 2500 word PDF; Source Repo; Video | % |  13 May 2022, 23:00 |

## Marking Scheme

|Mark | Section|
|--|-----|
| 15% | Introduction |
| 35% | Details of the design |
| 15% | Discussion |
| 30% | Implementation of your design (Advanced) |
| 5% | References |
| **100%** |Total |

> Limit:  2500 words

## Notes and Advice

<!-- markdown-link-check-disable -->
* The [Extenuating Circumstances procedure](https://www.upsu.net/advice) is
  there to support you if you have had any circumstances (problems) that have
  been serious or significant enough to prevent you from attending, completing
  or submitting an assessment on time.
* [ASDAC](http://www2.port.ac.uk/additional-support-and-disability-advice-centre/)
  are available to any students who disclose a disability or require additional
  support for their academic studies with a good set of resources on the [ASDAC
  Moodle site](https://moodle.port.ac.uk/course/view.php?id=3012)
* The University takes plagiarism seriously. Please ensure you adhere to the
  plagiarism guidelines [https://www.upsu.net/advice/plagiarism](https://www.upsu.net/advice/plagiarism).
* Any material included in your coursework should be
  fully cited and referenced in APA format (**seventh** edition). Detailed advice on
  referencing is available from [http://referencing.port.ac.uk/](http://referencing.port.ac.uk/)
* Any material submitted that does not meet format or submission guidelines, or
  falls outside of the submission deadline could be subject to a cap on your
  overall result or disqualification entirely.
* If you need additional assistance, you can ask your personal tutor, learning
  support ana.baker@port.ac.uk and xia.han@port.ac.uk or your lecturers.
<!-- markdown-link-check-enable-->

## How to submit

This repository is your own private repository and all content must be submitted in this repository. This repository is closed at the deadline and **only** the content in this repository is marked:

* The video file must be saved in the `Submit` folder
* All source code must be saved in the `src` folder
* The PDF must be saved in the `Submit` folder
  * It is recommended you use the `.pandoc.yml` with Markdown and the `Pandoc` workflow to build your PDF. (Strongly advised)
  * You can submit a custom PDF in the `Submit` folder if you wish. Name this file using your **Student ID** (Not recommended)

## Internet of Things Coursework

The goal of this coursework is to apply your knowledge and practical skills to design and build an IoT application.

The deliverables of the coursework consist two artifacts:

1. A final report that details the design **(70%)**
2. A demo of your application (a video recording) along with implementation GitHub code repository **(30%)**

Your final report should address but is not limited to the following parts regarding your design:

* Introduction: Define the application scenario and the problem, justify why an IoT
solution is needed, propose your design and the main functionality, decompose
the design into smaller tasks, and give a basic outline of what you propose to
implement. The main tasks and the logic flow should be well justified.
* Details of the design: Include any tools, sensors, modules, protocols, platforms,
pseudo code, and diagrams -- anything that is necessary to clearly explain your
IoT system/steps. You are expected to go further beyond what you have been
provided with for your practical exercises. You need to compare the useful
components/sensors/modules before you adopt any of them for your design.
Browse the Internet, look for more sensors, identify their operating/working
conditions (e.g. power supply), and include them in your design. Describe the
communication protocols and application protocols that you will use with
detailed data flow and pseudo code. Even though some sensors/functions will
not be implemented due to the limited resources, a consistent representation of
them in data flow and pseudo code is expected across all stages. If you are
considering using a commercial platform as a public broker/server, name the
one you want to use and provide evidence of testing the platform. Besides, the
technical issues, the cost of your design should be quantitatively evaluated.
**Justify all your choices for this part.**
* Discussion: Summarize the main insights into your design and map your
solutions to the defined scenario and problems. Discuss the potential pitfalls,
advantages and disadvantages of your design and how your design could be
improved.

**Identify clearly which part you are going to implement as a tangible output and why the rest are not implemented.**

The implementation could implement only a part of your design. It is acceptable for
you to have a sophisticated design but without an implementation of the entire
design due to the limits on available tools or resources. Basic requirements for your
implementation include:

* The system functions without errors,
* Hardware components are well connected,
* The design/function logic is clear,
* The demo is self-explanatory and the code is clearly **commented**

## Grading

Grading will be based on the quality of the design (for example: originality, thoroughness, extent
of analysis, justification), the clarity of the written report, and the
implementation quality based on the demo and code. Ideally, you are encouraged to
try something novel or apply ideas out of our workshops to the given problems. You
can get a good grade for the design even if your innovative ideas do not work out
well, as long as your final report shows evidence of extensive analysis and
exploration, provides sound justification for your choices of modules / sensors /
methods / platforms, and provide thoughtful reviews / reflections / comparisons on
the existing solutions. For the implementation, you are asked to explain the code
and logic in your demo.


### Originality check

The design and implementation should be done all by yourself independently.

**Your marks will be capped if the implementation has been proved to have not been done on your own.**

### The marking criteria below apply for both the design and implementation

* Introduction **15%**

  * Understanding of your application scenario and problem
  * Justification of the need of an IoT solution to your problem
  * Provide the motivation of your design and justification
  * Design decomposition into subsystems/submodules
  * Include your innovative thinking

* Details of the design **35%**

  * Clear description of the chosen solutions/tools for each
    subsystem/submodule
  * Justification behind the chosen solutions/tools that they
    are the most appropriate choice to the given scenario
  * Comparison with different modules/sensors/protocols that
    you may choose as alternatives
  * Clear reference of the tools/sensors, modules, protocols,
    platforms (where you found them)
  * Use pseudo code or code with syntax to demonstrate the
    functions in each subsystem/submodule (applicable to all
    subsystems/submodules including the ones not to be
    implemented)
  * Use flowchart/diagram to intuitively demonstrate the logic,
    data flow (control command + actuator signals) of your
    finalized design
  * The working conditions of your design
  * The design is both innovative and practical
  * Cost estimation of your design/implementation

* Discussion **15%**

  * Summary of your design
  * Map your solutions to the given scenario and problem
  * Potential pitfalls, advantages, disadvantages
  * Alternative solutions and suggestions
  * Future work/direction to improve the current solutions

* Implementation of your design (Advanced) **30%**

  * Implement the whole design or part of your design
  * The implementation is functioning well without errors
  * The hardware components are well connected without obvious pitfalls
  * The logic in your functions is clear during the demo
  * The code can be well explained by you in the demo
  * The implementation is not trivial or singly run on the code
  * given to you in previous practicals
  * The innovative part of the implementation including, but not limited to data fusion, human factor, user interface.

* References **5%**
 
  * Including conference papers, journal papers, and URLs for any external code or data used.
