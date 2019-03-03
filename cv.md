
# Bakytzhan Kudebayev

## Contacts
* +77779777390
* [bakytzhan90kz@gmail.com](mailto:bakytzhan90kz@gmail.com)


## Summary
Software Developer in delivering Web-based applications. Having a solid understanding of Object-Oriented Design Principles and architecture of integration solutions. Have a good analytical skills valuable in any software development environment, keen learner.


## Technical Skills
* Programming Languages: C#, C, JavaScript
* Databases: MS SQL, MySQL, Oracle
* Frameworks: ASP.NET, Angular
* Version Control: Git
* Methodology: Agile


## Code Examples
This code was used in checking if any given two strings are valid anagram or not.
```javascript
var isAnagram = function(s, t) {
    //create counter for first string
    if(s.length!=t.length) return false;
    let lettersCount = {};
    
    for(let c of s){
        lettersCount[c] = ++lettersCount[c] || 1;    
    }
    
    //check second string with counter
    for(let c of t){
        if(!lettersCount[c]) return false;
        lettersCount[c] = --lettersCount[c];   
    }
    
    return true;
};
```


## Experience
### Software Developer | Chipsoft `2014 October - Present`
* Designing and developing web applications
* Designing and implementing web services
* Writing technical documentation


## Education
### Purdue University, West Lafayette, IN `Fall 2010 - Spring 2014 `
```
Computer Science
```
- GPA: 3.5


## English Language Proficiency
```Native or bilingual```
* Advanced English Language Courses - `Fall 2009 - Fall 2010`