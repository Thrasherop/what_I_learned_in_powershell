## How Powershell actually works
* Object oriented (in a terminal???)
* Actual commands are structured like "verb-noun"
* Lots of aliases

I firmly believe that knowing how something actually works (as opposed to just memorizing how to actually use it) is the best way to learn something intuitively. Learning these simple things, and playing around a little bit with proper powershell techniques helps me get this intuitive ability. 

## Favorite things
- By far my favorite command is $wsl
    - This allows me to run all my bash commands that I'm familiar with, which is a game changer for me

- Variables and data types
    - Powershell has some cool built in datatypes, such as MailAddress. These data types all have their own methods and whatnot
    - When initializing a variable of a certain data type, powershell automatically does verification. So tryijng to create a MailAddress with the value "john" will throw an error since there is no host specified

```
PS C:\Users\ultra> $email = [MailAddress]"john@gmail.com"                                                   PS C:\Users\ultra> $email 
DisplayName User Host      Address
----------- ---- ----      -------
            john gmail.com john@gmail.com

```



## Things I won't use but I think are cool

- Execution Policy
    - I'd seen these commands used, but didn't know what they were. It's nice to understand it now






## Conclusion

There is still a lot for me to learn here, but what I have learned is quite helpful and I am much more comfortable in Powershell. Instead of pulling up wsl as my terminal, I plan to start doing Powershell instead. It is just objectively better, especially considering you can use wsl commands inside Powershell. 

I know this file is kind of short, but its just a summary of some of my favorite things. Below is a 6 page Google doc with all my notes. Theres a lot more I have to learn, but this sprint has gotten me very interested in Powershell, and I'm very glad I did this module, and I hope to keep being able to play with and explore powershell.

[This is a 6 page Google doc with my notes of things I learned](https://docs.google.com/document/d/1QQhAKFnuxuoeCC_4SqJYuGftL6Ikr1mbSt_hem07bbM/edit?usp=sharing)
