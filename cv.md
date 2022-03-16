# Andrey Rafalsky

## My contact information
* **Phone:** +375 29 586-81-32
* **E-mail:** andraffal@gmail.com
* **Telegram:** [Rafa_lsky](https://t.me/Rafa_lsky)
* **GitHub:** [Slanx](https://github.com/Slanx)
* **Linkedin:** [Slanx]([www.linkedin.com/in/Slanx)
* **Discord:** Rafa(@Slanx)

## About me
I am 23 years old, graduated from BSUIR and I work there. After the army I began to develop in various areas, including front-end development. I don't know how to live without it anymore. In the future, I want to become a sought-after specialist, maybe try myself in the backend.

## Skills
* HTML5
* CSS3(SASS/SCSS, BEM)
* JavaScript(Fundamentals, Functional Programming, Asynchronous JavaScript, ES6+, DOM, JSON).
* Git/GitHub
* ReactJS(basic level knowledge)
* VSCode
* Figma

## Code Examples
**Solution of kata 6 key:** *Write a function that takes a string of parentheses, and determines if the order of the parentheses is valid. The function should return true if the string is valid, and false if it's invalid.*
```
function validParentheses(parens) {
    let arrParens = [...parens];
    let counter = 0;

    for(let item of arrParens){
        if (item === '('){
            counter++;
        }else{
            counter--;
            if (counter < 0){
                return false;
            }
        }
    }
    if (counter === 0){
        return true;
    }else{
        return false;
    }
}
```

## Education
* **BELARUSIAN STATE UNIVERSITY OF INFORMATICS AND RADIOELECTRONICS**
    * faculty of infocommunications
* **Html Academy**
    * basic knowledge of HTML and CSS
* **Udemy**
    * [JavaScript/ReactJS (in process)](https://www.udemy.com/course/javascript_full/)

## Languages
* **Russian** - native
* **Engligh** - pre-intermediate