<!Doctype html>
<html>
    <style>
        *{
            margin: 0;
            padding: 0;
        }
        .title{
            width: 100%;
            background-color: #333;
            color: #f1f1f1;
            height: 50px;
        }
        .title .text{
            position: absolute;
            /* width: 0; */
            top: 5px;
            left: calc(50% - 200px);
            font-size: 25px;
            overflow: hidden;
            white-space: nowrap;
            animation: title 8s steps(34);
            animation-iteration-count: infinite;
        }
        @keyframes title{
            0%{
                width: 0;
                left: 50%;
            }
            5%{
                width: 0;
                left: 50%;
            }
            40%{
                width: 400px;
                left: calc(50% - 200px);
            }
            60%{
                width: 400px;
                left: calc(50% - 200px);
            }
            95%{
                width: 0;
                left: 50%;
            }
            100%{
                width: 0;
                left: 50%;
            }
        }
    </style>
	<body>
        <div class="title"><div class="text">I' m Turing158, nice to meet you.&nbsp;</div></div>
    </body>
</html>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Turing158/Turing158/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Turing158/Turing158/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/Turing158/Turing158/output/github-contribution-grid-snake.svg">
</picture>
