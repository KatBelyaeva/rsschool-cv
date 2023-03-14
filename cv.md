# Katerina Beliayeva
### Contacts
**Location:** Minsk, Belarus  
**Phone:** +375 29 621-13-65  
**Email:** kat.belyaeva.it@gmail.com  
**GitHub:** KatBelyaeva  
### About Me
I finished Python-developer courses with honor. Currently, I continue to improve my knowledge in development: I'm studying JavaScript, HTML, CSS.  
I speak English at the level Intermediate (B2).  
I would find a team with which I will grow and develop professionally.
### Skills
* Python
* HTML
* CSS
* MySQL
* NoSQL
* Django
* Telebot
* Git
### Code Example
From CODEWARS:  
Complete the method/function so that it converts dash/underscore delimited words into camel casing. The first word within the output should be capitalized only if the original word was capitalized (known as Upper Camel Case, also often referred to as Pascal case). The next words should be always capitalized.
```
def to_camel_case(text):
    text.replace(' ', '')
    for i in text:
        if i == '-':
            i_index = text.find('-')
            text = text.replace(text[i_index+1], text[i_index+1].upper())
            text = text.replace('-', '', 1)
        elif i == '_':
            i_index = text.find('_')
            text = text.replace(text[i_index+1], text[i_index+1].upper())
            print(i_index)
            text = text.replace('_', '', 1)
    return text
```
### Experience
I have some experience in Python and HTML. I have developed different telegram bots and corporate websites.
### Education
**University:** Minsk State Linguistic University  
**Courses:** Python developer courses, IT english courses, Python trainee, WEB-development (base). 
### Languages
**Russian** - native speaker  
**English** - B1 (B2 in process)  
**French** - B2
