# Margarita Okencits
## Junior Full-stack developer
## Contacts information
###### Phone: +375 29 772 88 45
###### E-mail: agreatpie@gmail.com
###### Telegram: @Tomato_tomatos

## Briefly About Myself:
###### In 2021 I received my BA in Psychology and Social Work. 
###### For 4 years of study I have achieved great success: I was nominated for the title "The best graduate of BSU", received a diploma with honors and more.
###### Since 2015, programming has been just a hobby. But now I have serious intentions to change the field of activity.

###### For July 2021 I:
1. completed 1 freelance order. I created a [landing page](https://skvazzhin.by/), placed it on the server and set up mail .
2. created a web application for librarians. Within the framework of the project, I learned to work with Orakle, Java, Spring, Js (*sorry, but I don't have a link to this project yet. It's coming soon*).

## Skills and Proficiency:
* HTML5, CSS3
* JavaScript Basics
* Git, GitHub
* Oracle
* Java, Spring 
* Postman
* Figma, Adobe Photoshop
* * Web Storm, IntelliJ IDEA

## Code example
###### Task: write a function that takes in a string of one or more words, and returns the same string, but with all five or more letter words reversed (like the name of this kata).
* Strings passed in will consist of only letters and spaces.
* Spaces will be included only when more than one word is present.

~~~
function reverseWord(str) {
    var newString = "";
    for (var g = str.length - 1; g >= 0; g--) {
        newString += str[g];
    }
    return newString;
}

function spinWords(string){
    let i = string;

    let o = i.split(" ");

    for (var j = 0; j < o.length; j++) {
        if (o[j].length >= 5) {
            o[j] = reverseWord(o[j]);
        }
    }

    return o.join(" ");

}
~~~
