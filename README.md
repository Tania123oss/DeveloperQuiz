Quiz program will help taking quiz of students in educational  environment. 

###DESCRIPTION:
I have created a quiz program using Java script. 

###LANGUAGES I USED:
•	Html
•	CSS
•	Java script

This is the index.js part of this project by which these buttons are working.

form.addEventListener('submit',e =>{
    e.preventDefault();
    let score = 0;
    const answers =[form.q1.value,form.q2.value,form.q3.value,form.q4.value]
    answers.forEach((answer,index) =>{
        if(answer == correctAns[index])
        {
            score+=25
        }
    })

