![Olha Stanislavska](/img/OlhaStanislavska.png)
# Olha Stanislavska
## Junior Front-end Developer

### Contacts
+380 (99) 008 48 70
olha.stanislavska@gmail.com
github.com/OlhaStanislavska
Kyiv,  Ukraine

### Skills
* HTML 70%
* CSS 60%
* JS 30%
* GIT 30%
* PHOTOSHOP 90%
* ILLUSTRATOR 90%

### Languages
* English  Entermediate
* Ukrainian  Native

### Hobbies
![Desktopgames](/img/desktopgames.png)
![Hiking](/img/hiking.png)
![Sewing](/img/sewing.png)

### About me

### Education
* **Master of Degree**
National Technical University of Ukraine «Igor Sikorsky Kyiv Polytechnic Institute»
Computer Science 2006 - 2012

* **Courses**
    + RS Schools «JS/FE. Stage 0»
    + HTML/CSS/JS Fundamentals 
    + SoftServe Academy
    + FreeCodeCamp
    + CS50

### Work Experience 
* **Graphic Designer**
_Zaporuka Foundation  Nov 2017 - Jul 2019_
Created of informational materials and presentation, promotional 
products, design of external stands.

* **Graphic Designer**
_AA «Craftsmenship»  Mar 2012 - May 2015_
Created all types of advertising products, from business cards to 
billboards, design of shopping places, advertising in magazines.

### Projects
* [Browser Game «Tractor Army»](https://olhastanislavska.github.io/TractorArmy/)
* [WebSite Portfolio and FAQ block](https://koldovsky.github.io/725-team-03/)
* Code example
```
(() => {
    document.querySelectorAll('.faq__question-acordion').forEach( (el) => {
        el.addEventListener('click', () => {
            let content = el.lastElementChild;
            let expand = el.firstElementChild.lastElementChild;
            if (content.style.maxHeight) {
                content.style.maxHeight = null;
                expand.classList.remove('active');
            } else {
                document.querySelectorAll('.faq__question-answer').forEach((el) => el.style.maxHeight = null);
                document.querySelectorAll('.faq__question-expand').forEach((el) => el.classList.remove('active'));
                content.style.maxHeight = content.scrollHeight + 'px';
                expand.classList.add('active');
            }
        });
    });
})();
```
![github](/img/github-logo.svg)
![2022](/img/2022.svg)
![RSSchool](/img/rs-logo.svg)


