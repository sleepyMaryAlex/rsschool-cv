# **Maria Huchkova**

### *I'm beginner front-end web-developer*  
  
![My photo](my_photo.jpg)

***

## **Contacts**
#
**Location**: Belarus Minsk  
**GitHub:** [sleepyMaryAlex](https://github.com/sleepyMaryAlex)  
**Discord:** Mary Guchkova (@sleepyMaryAlex)  
**Telegram:** @mariaguchkova  
**Phone:** +375 33 3377504  
**Email:** mariaguchkova1@gmail.com  

***

## **About myself**
#
I chose to be a programmer because I would like to constantly develop, comprehend new technologies. It is important for me to cooperate and exchange experience with other countries, to be in a friendly and intelligent team. I believe that all of the above applies to the profession of a programmer.

In turn, I am hardworking and responsible. I try to complete my task as efficiently as possible and treat my colleagues in a friendly and respectful manner, observing subordination.

My goal is to become a professional in my field.

***

## **Skills**
#
* HTML5
* CSS3
* Markdown
* Git | GitHub
* JavaScript basics
* VS Code

***

## **Code example**
#
*Given an array of integers, find the one that appears an odd number of times.  
There will always be only one integer that appears an odd number of times.*

```
function findOdd(numbers) {
  const counters = new Map();
  for (const number of numbers) {
    if (counters.has(number)) {
      let counter = counters.get(number);
      counter++;
      counters.set(number, counter);
    } else {
      counters.set(number, 1);
    }
  }
  for (const number of counters.keys()) {
    let counter = counters.get(number);
    if (counter % 2 === 1) {
      return number;
    }
  }
}
```

***

## **Education**
#
* Belarusian State Academy of Music (2014 - 2019)
* RS Schools Course "JavaScript/Front-end. Stage 0" (in progress)

***

## **English**
#
**B1.**  I'm studying English with a tutor and communicating with a native speaker, I'm also reading English grammar books.