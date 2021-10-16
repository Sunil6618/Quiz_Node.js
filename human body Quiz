var readline = require("readline");
var r1 = readline.createInterface({
    input:process.stdin,
    output:process.stdout,
});
console.log("Welcome to The Human Body Quiz: Human Body Systems & Organs\n")
var name = "";
r1.question("Enter Your Name: ",(nm)=>{
    name = nm;
    console.log("Welcome "+ name+", Let's Play the Quiz!!");
    console.log('==========Rules & Instructions:==========');
console.log('1.',name + ', There are 5 Questions on India and all are Compulsory.');
console.log('2. You will get 5 points on each Right Answer.');
console.log('3. 2 Point will be deducted if the Answer is Wrong.');
    quiz();
});

var i = 0;
var score = 0;
const que = ["Calcium crystals are a normal part of what body region?","What is the largest organ of the human body?","The smallest bones in the human body are found in the...","What percentage of the human body is water?","How many taste buds are on your tongue?"];
const opt = [["Gouty joints","Spine","Nasal cavity","Ears"],["Brain","Liver","Spine","Skin"],["Feet","Ears","Fingers","knees"],["50","66","75","80"],["9000","8000","7000","6000"]];

var quiz = ()=>{
    if(i === 0){
        console.log(que[i]);
        for(var j =0;j<4;j++)
        {
            console.log((j+1)+"-"+opt[i][j]);
        }
        r1.question("Answer:- ",(ans)=>{
            if(ans === "4")
            {
                score += 5;
                console.log("Great Job!!"+"\tYour Score :- "+score);
                i+=1;
                quiz();
            }
            else
            {
                console.log("Sorry Wrong answer!!"+"\nRight answer is ->"+ opt[i][3]+"\tYour Score :- "+score);
                score -= 2;
                i+=1;
                quiz();
            }

        });
    }
    else if(i === 1)
    {
        console.log(que[i]);
        for(var j =0;j<4;j++)
        {
            console.log((j+1)+"-"+opt[i][j]);
        }
        r1.question("Answer:- ",(ans)=>{
            if(ans === "4")
            {
                score += 5;
                console.log("Great Job!!"+"\tYour Score :- "+score);
                i+=1;
                quiz();
            }
            else
            {
               console.log("Sorry Wrong answer!!"+"\nRight answer is ->"+ opt[i][1]+"\tYour Score :- "+score);
                score -= 2;
                i+=1;
                quiz();
            }

        });
    }
    else if(i === 2)
    {
        console.log(que[i]);
        for(var j =0;j<4;j++)
        {
            console.log((j+1)+"-"+opt[i][j]);
        }
        r1.question("Answer:- ",(ans)=>{
            if(ans === "2")
            {
                score += 5;
                console.log("Great Job!!"+"\tYour Score :- "+score);
                i+=1;
                quiz();
            }
            else
            {
               console.log("Sorry Wrong answer!!"+"\nRight answer is ->"+ opt[i][2]+"\tYour Score :- "+score);
                score -= 2;
                i+=1;
                quiz();
            }

        });
    }
    else if(i === 3)
    {
        console.log(que[i]);
        for(var j =0;j<4;j++)
        {
            console.log((j+1)+"-"+opt[i][j]);
        }
        r1.question("Answer:- ",(ans)=>{
            if(ans === "2")
            {
                score += 5;
                console.log("Great Job!!"+"\tYour Score :- "+score);
                i+=1;
                quiz();
            }
            else
            {
               console.log("Sorry Wrong answer!!"+"\nRight answer is ->"+ opt[i][0]+"\tYour Score :- "+score);
                score -= 2;
                i+=1;
                quiz();
            }

        });
    }
    else if(i === 4)
    {
        console.log(que[i]);
        for(var j =0;j<4;j++)
        {
            console.log((j+1)+"-"+opt[i][j]);
        }
        r1.question("Answer:- ",(ans)=>{
            if(ans === "1")
            {
                score += 5;
                console.log("Great Job!!"+"\tYour Score :- "+score);
                i+=1;
                quiz();
            }
            else
            {
               console.log("Sorry Wrong answer!!"+"\nRight answer is ->"+ opt[i][0]+"\tYour Score :- "+score);
                score -= 2;
                i+=1;
                quiz();
            }

        });
    }
    else
    {
        console.log("Final Score Of "+name+": "+ score+"/"+(que.length*5));
        r1.close();
    }
}
