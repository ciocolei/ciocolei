<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: 'Comic Sans MS', cursive, sans-serif; /* playful font */
      line-height: 1.6;
      background-color: #ffe4e1; /* soft pink background */
      color: #4b0082; /* indigo text color */
      text-align: center; /* center-align text */
      padding: 20px;
    }

    h1, h2 {
      color: #ff69b4; /* hot pink color for headers */
    }

    a {
      color: #ff1493; /* deep pink links */
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .emoji {
      display: inline-block;
      animation: bounce 1s infinite; /* bounce animation */
    }

    @keyframes bounce {
      0%, 20%, 50%, 80%, 100% {
        transform: translateY(0);
      }
      40% {
        transform: translateY(-10px);
      }
      60% {
        transform: translateY(-5px);
      }
    }

    .icon {
      width: 40px; /* size of the moving icons */
      margin: 0 5px;
      animation: float 2s infinite; /* floating animation */
    }

    @keyframes float {
      0%, 100% {
        transform: translatey(0px);
      }
      50% {
        transform: translatey(-10px);
      }
    }
  </style>
</head>
<body>

  <h1>Hi there <span class="emoji">👋</span> I'm Leah</h1>
  <p>
    I'm a UP Applied Math major from Bacolod, Negros Occidental <span class="emoji">🇵🇭</span>
  </p>

  <h2>🤔 Currently Learning</h2>
  <p>
    I'm currently learning React Native.
  </p>

  <h2>💬 For Math 154 Classmates</h2>
  <p>
    Here's the <a href="https://youtube.com/playlist?list=PL1LCgbfQ4xJMlnHyKrIULASOfzcTMA5mT&si=3qu7h-pKP67a34H_" target="_blank">tutorials playlist</a> for our course.
  </p>

  <h2>📫 How to Reach Me</h2>
  <p>
    Feel free to contact me via email at <a href="mailto:lgcioco@up.edu.ph">lgcioco@up.edu.ph</a> or <a href="mailto:lcioco@indie-co.com">lcioco@indie-co.com</a>.
  </p>

  <h2>😄 Pronouns</h2>
  <p>
    My pronouns are she/her.
  </p>

  <img src="https://i.imgur.com/A6Y4Rkg.png" alt="flower icon" class="icon">
  <img src="https://i.imgur.com/A6Y4Rkg.png" alt="flower icon" class="icon">
  <img src="https://i.imgur.com/A6Y4Rkg.png" alt="flower icon" class="icon">

</body>
</html>
