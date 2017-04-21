Create branch thursday (git checkout -b thursday);

git add -p (or git add .)
git commit -m "message"
git push origin thursday

File system                   Git repository
notes/thursday              git checkout - b thursday (creating a branch within your repository)
(file one your computer)     (representation of your file)

            git push   origin            thursday
            (command) (remote(location)) (branch)
repository = collection of files themselves stored in other places.
remote = where you store your files (alias -> URL for copy of repository)
branch =

command + / allows you to comment out multiple lines of code.

truthy and falsey
1           0
'Thursday'    undefined
8            null
28.65       false
'false'

(In Javascript ambiguity is given either true or false).

2 == "2"
true (it could potentially convert to a string parseInt("2") = 2)
2 === "2"
false(strict comparison, numbers do not equal strings javascript won't make an allowance).

DRY = don't repeat yourself. (make the code concise like switch or for loop).
  1.Make it run
  2.Make it right.
  3.Make it fast and concise.

  Functions:
  Syntax                    
    function(){          
      //codeblock          
    }
    //named functions usually put at the bottom. (not common but can be executed anywhere)
   function doSomething(){
      codeblock
    }

    Anonymous function (more common, put it before it's referenced, or else you'l get an error)
    var doSomething = function(){
        codeblock
}

    call a function
    doSomething('baseball');
    doSomething(); (parenthesis tells the computer to invoke it as a function, and not a variable)

    Immediately invoked function expression
    (function(ballType) {
      var play = "We're playing" + ballType + " with an IIFE!";
      console.log(play);
    } ('rugby'));

    Function names should be verbs (they do things)
    variables should be nouns because they are things.

    named function
    function add(num1, num2){
      return num1 + num2;
    }

    cannot call subtract here, is has not been declared but you can call add.
    anonymous function
    var subtract = function(num1, num2){
      return num1 - num2;
    };
    call it
    add(1,2);
    subtract(3,2);
