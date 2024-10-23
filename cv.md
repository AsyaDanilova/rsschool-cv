# Anastasiia (Asya) Danilova #
===========
## Junior Sofware Engineer ##
===========
### Contact Information ###

* Phone: +370-660-43-989
* E-mail: asya-1997@yandex.ru
* Telegram: @Asya7991
* [LinkedIn] (https://www.linkedin.com/in/anastasiia-danilova-2985b729a/)
* [GitHub] (https://github.com/AsyaDanilova)

============
### Brief Summary ###

As a Senior Project Administrator at EPAM, I combine the roles of Business Analyst and administrator-engineer, utilizing extensive technical expertise.

Currently, I am advancing my skills in web development, focusing on HTML, CSS, and JavaScript, aiming to transition to a front-end engineering role. Started diving into React basics.

I have rebuilt the Concur Request and Expense modules from the ground up, demonstrating strong capabilities in business communication and the resolution of critical issues. I am skilled at negotiating business needs with technical teams to achieve optimal outcomes.

============
============

### Skills and Proficiency ###

* HTML5, CSS3
* JavaScript Basics
* Git, GitHub
* VS Code
* SAP Concur

=============

### Code Example ###

``` js
function toggleCreateReport(sectionId) {
        const allQuestions = document.querySelectorAll('.question-block');
        const allPluses = document.querySelectorAll('.plus');


        // Get the specific section and marker
        const section = document.getElementById(sectionId);
        const marker = document.querySelector(`[id='${sectionId + '-marker'}']`);

        // Check if the clicked section is currently open
        const isOpen = section.style.display === 'block';

        // Close all sections and reset markers to '+'
        allQuestions.forEach((sec) => {
            sec.style.display = 'none';
        });
        allPluses.forEach((mk) => {
            mk.innerText = '+';
        });

        // If the clicked section was not open, open it and set marker to '×'
        if (!isOpen) {
            section.style.display = 'block';
            marker.innerText = '×';
            allQuestions.style.boxShadow = 'none';
        }
    }

```
==============
==============

### Languages ###

* Russian (native)
* English (B2+)
* Lithuanian (A1) 
