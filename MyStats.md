# Sreeja Vasa
I am an avid learner with a deep passion for antiques, archaeology, and the mysteries of the universe. Alongside my love for these subjects, I have a strong affinity for music and consider myself a skilled singer. My ultimate goal is to become self-reliant and make my parents proud through my achievements in life.

![My Image](./Myphoto.jpeg)

--------------------------------------------------------------------------------------------------------------------

# Sports Table

|**Sport name**| **reason for playing**                                   | **hours of playing**|
|:-------------|:-------------------------------------------------------: |--------------------:|
| Basketball   | promotes speed, strength.                                | 30 Minutes          |
| tennis       | Tennis is a good for health, fitness.                    | 1 hour              |
| Hiking       | Hiking reduce your risk of heart disease and stroke.     | 2 hour              |
| Swimming     | Swimming is a great stress reducer.                      | 45 minutes          |


--------------------------------------------------------------------------------------------------------------------

# My Favourite Quotes from scientists
> "God is the name people give to the reason we are here"
>
> -- *Stephen hawking*

> "Learn from yesterday, live for today, hope for tomorrow"
>
> -- *Albert Einstein*


--------------------------------------------------------------------------------------------------------------------
# Code Fencing

> **Question:** How to efficiently remove duplicates from an array without using Set
> **Stack Overflow Link:** [How to efficiently remove duplicates from an array without using Set](https://stackoverflow.com/questions/17967114/how-to-efficiently-remove-duplicates-from-an-array-without-using-set)

```const array = [1, 1, 1, 3, 3, 2, 2];

// Method 1: Using a Set
const unique = [...new Set(array)];

// Method 2: Array.prototype.reduce
const unique = array.reduce((result, element) => {
  return result.includes(element) ? result : [...result, element];
}, []);

// Method 3: Array.prototype.filter
const unique = array.filter((element, index) => {
  return array.indexOf(element) === index;
});

```

Snippet Source Link : [Snippet Source Link](https://css-tricks.com/snippets/javascript/remove-duplicates-from-an-array/)

[Click here to know about me](MyStats,md)
