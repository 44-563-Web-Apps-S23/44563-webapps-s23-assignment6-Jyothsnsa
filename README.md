
# WebApps-S23-Assignment-6
Assignment introduction to Java Script and DOM
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-iYQeCzEYFbKjA/T2uDLTpkwGzCiq6soy8tYaI1GyVh/UjpbCx/TYkiZhlZB6+fzT" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"
        integrity="sha384-oBqDVmMz9ATKxIep9tiCxS/Z9fNfEXiDAYTujMAeBAsjFuCZSmKbSSUnQlmh/jp3"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/js/bootstrap.min.js"
        integrity="sha384-7VPbUDkoPSGFnVtYi0QogXtr74QeVeeIs99Qfg5YCF+TidwNdjvaKZX19NZ/e6oz"
        crossorigin="anonymous"></script>
    <title>Assignment-6</title>
</head>

<body>
    <h1>Musician guess by Pankaj Sanjay Vishwakarma</h1>
    <form style="width: 300px;">
        <div class="form-check">
            <label for="form1_age" class="form-label">Enter the secret musician name</label>
            <input type="password" class="form-control" id="form1_age" name="form1_age" min=10 max=50 step=2
                value="John Lennon" aria-describedby="emailHelp">

        </div>
        <div class="form-check">
            <label for="form1_nick" class="form-label">Guess the musician</label>
            <input type="text" class="form-control" id="form1_nick" name="form1_nick" autofocus>
        </div><br>
        <div class="form-check">
            <button type="button" class="btn btn-danger" onclick="checkGuess()" value="Check the guess">Submit</button>
        </div> <br>
        <div class="form-check">
            <p id="result">Counter text will be displayed here !!! </p>
        </div>
    </form>
    <br>