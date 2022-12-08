# Yaroslav Kim
Junior Frontend Developer
***
### Contact information:
Phone: +8 775 8818206  
E-mail: Korean_mafia_01@gmail.com  
Telegram: @koreeckrg
***
### About me:  
Since childhood I was interested in electronics, in particular computers, so I am a confident PC user. Recently I got interested in Frontend-development, because I can immediately see the result of my efforts. I have no coding experience, but I have a great desire to learn new profession. While working in commerce I have gained experience in teamwork and conflict resolution. From personal qualities I would like to note attention to detail, the ability to listen and a love of order.
***
### Skills and Proficiency:  
- Basic HTML and CSS
- Basic Git and GitHub
- Basic VS code
- Microsoft Excel
- 1С
***
### Code example:
I solved this task on the "learn.javascript.ru".  
The code asks a login from user and checks it:  
1. If the login is Admin -> asks for a password ->
- -> if password is "I'm Admin" -> Show "Hello, Admin!"
- -> if password is incorrect -> Show "Wrong password!"
- -> if string is empty -> "You didn't enter anything!"
- -> if user use "Cancel" button -> Show "Of course you are mistaken :)"
2. If the login isn't empty and not an "Admin" -> "I don't know you!"
3. If user use "Cancel" button -> Show "Canceled".  

        let userlogin = prompt('Enter your login:');
        if (userlogin == "Admin") {
            let adminpassword = prompt('Enter Admin's password:');
            if (adminpassword == 'I'm Admin') {
                alert('Hello, Admin!');
            } else if (adminpassword !== 'I'm Admin' && adminpassword !== ('') && adminpassword !== null) {
                alert('Wrong password!');
            } else if (adminpassword == null) {
                alert('Of course you are mistaken :)');
            } else ('You didn't enter anything!')
        }
        else if (userlogin !== "Админ" && Boolean(userlogin)) {
            alert('I don't know you!');
        } else {
            alert('Canceled');
        }
***
### Work experience
I don't have any IT work experience.
***
### Courses:
RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
***
### Languages:
Russian: Native  
English: A2
