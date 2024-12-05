# MCQ
Using HTML &amp; JAVASCRIPT 

Sure! To provide an explanation of My code, we can break it down step by step and design a Multiple-Choice Quiz (MCQ). Here's a structure for it:

Example Code:
Suppose your HTML and JavaScript code looks something like this:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quiz Example</title>
</head>
<body>
    <h1>Simple Quiz</h1>
    <p id="question">What is the capital of France?</p>

    <button onclick="checkAnswer('A')">A. Paris</button>
    <button onclick="checkAnswer('B')">B. Berlin</button>
    <button onclick="checkAnswer('C')">C. Madrid</button>
    <button onclick="checkAnswer('D')">D. Rome</button>

    <p id="result"></p>

    <script>
              function checkAnswer(answer) 
              {
                const correctAnswer = 'A'; // The correct answer is 'A'
                const result = document.getElementById("result");
            
                if (answer === correctAnswer) {
                    result.innerText = "Correct! Paris is the capital of France.";
                } else {
                    result.innerText = "Incorrect! Please try again.";
                }
              }
    </script>
</body>
</html>

Explanation of the Code

  Question 1: What is the purpose of the <button> element in the HTML file?
              A) To display the title of the page.
              B) To allow the user to input text.
              C) To create clickable options for the quiz.
              D) To link to an external JavaScript file.
  Correct Answer: C

Explanation: The <button> elements create clickable options for the quiz. The onclick attribute is used to execute a JavaScript function (checkAnswer) when the button is clicked.

                Thanks & Regards
                Ishwar Bhati 
                Web Devloper
