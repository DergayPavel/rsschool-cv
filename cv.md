1. Pavel Dergay

2. Contacts:
    Mobile phone: +375339030965
    Mail: pavel.dergay@mail.ru
    Telegram: @PavelDergay
    LinkedIn: https://www.linkedin.com/in/pavel-dergay/

3. About me: 
    BSU graduate (with an average score of 7.3), thanks to my studies at the Faculty of Physics, I have an excellent mathematical and physical base,as well as the basics of quantum mechanics, thermodynamics. More than two years of experience in automation of technological processes and software development for human-machine interface. I have been studying Frontend development for more than a year. I am currently participating in a project to develop a website for chatbot orders.

4. Skills:
    HTML
    CSS(Sass,Botstrap)
    JavaScript
    TypeScript
    React
    Git

5. Сode example from Сodewars:
    Kata: https://www.codewars.com/kata/52742f58faf5485cae000b9a
    Code:
        function formatDuration (s) {
            if(s===0){
                return 'now'
            }
            let y=Math.floor(s/60/60/24/365);  
            let d=Math.floor(s/60/60/24)-y*365;  
            let h=Math.floor(s/60/60)-d*24-y*365*24;
            let m=Math.floor(s/60)-h*60-d*24*60-y*365*24*60;
            s=s-y*365*24*60*60-d*24*60*60-h*60*60-m*60;
            let result='';
            if(y!=0){
                if(y===1){
                    result+=y+' year';
                }
                else{
                    result+=y+' years';
                }
                if(d!=0 || m!=0 || s!=0 || h!=0){
                    result+=', ';
                }
            }
            if(d!=0){
                if(d===1){
                    result+=d+' day';
                }
                else{
                    result+=d+' days';
                }
                if( (m!=0 && s!=0) || (h!=0 && s!=0) || (h!=0 && m!=0)){
                    result+=', ';
                }
            }
            if(h!=0){
                if((d!=0 || d!=0) && (s===0 && m==0)){
                    result+=' and '
                }
                if(h===1){
                    result+=h+' hour'
                }
                else{
                    result+=h+' hours'
                }
                if(s!=0 && m!=0){
                    result+=', ';
                }
            }
            if(m!=0){
                if((d!=0 || h!=0) && s===0){
                    result+=' and '
                }
            if(m===1){
                result+=m+' minute'
            }
            else{
                result+=m+' minutes'
            }
        }
        if(s!=0){
            if(d!=0 || m!=0 || h!=0){
                result+=' and '
            }
            if(s===1){
                result+=s+' second'
            }
            else{
                result+=s+' seconds'
            }
        }
        return result
    }

6. Experience:
    Learning projects:
        1. https://github.com/DergayPavel/Diploma - React, JS, TS, Axios.
        2. https://github.com/DergayPavel/Project_NBRB - HTML, CSS, JS, Fetch API 
        3. https://github.com/DergayPavel/PokemonPage - HTML, CSS, JS, Fetch API 
        4. https://github.com/DergayPavel/ProjectOne - HTML, CSS
        5. https://github.com/DergayPavel/ProjectTwo - HTML, SCSS

7. Education
    2022-2023 TeachMeSkills FrontEnd developer (React)
    2018-2022 BSU Faculty of Physics, Physics (industrial activity) - score 7.3

8. English:
    Level: A2-B1
    Experience: Reading and discussing technical documentation.