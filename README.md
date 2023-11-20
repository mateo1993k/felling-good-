<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Positive Communication Platform</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/R8aC1O4AOmiBCeGUliIx0ZowzAuFJ0Vcftg6" crossorigin="anonymous">
</head>
<body>
    <div class="container mt-5">
        <h1 class="mb-4">Welcome to the Positive Communication Platform</h1>
        <form action="#" method="post" id="loginForm">
            <div class="form-group">
                <label for="gender">Select your gender:</label>
                <div class="gender-selection d-flex justify-content-center">
                    <div class="gender-option" onclick="selectGender('male')">
                        <i class="fas fa-male"></i>
                        <p>Male</p>
                    </div>
                    <div class="gender-option" onclick="selectGender('female')">
                        <i class="fas fa-female"></i>
                        <p>Female</p>
                    </div>
                </div>
            </div>
            <button type="button" class="btn btn-success" onclick="showSections()">
                Login <i class="fas fa-sign-in-alt"></i>
            </button>
        </form>
    </div>

    <div id="textSection" class="hidden">
        <div class="communication-box">
            <i class="fas fa-comment"></i>
            <h2>Text Communication Section</h2>
            <!-- Add your HTML code for text communication here -->
        </div>
    </div>

    <div id="voiceSection" class="hidden">
        <div class="communication-box">
            <i class="fas fa-microphone"></i>
            <h2>Voice Communication Section</h2>
            <!-- Add your HTML code for voice communication here -->
        </div>
    </div>

    <script src="script.js"></script>
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-ur2H+CLYHzLjYlUvOG6flAZDwJlq3d5l1cP/6MuvHj/VF3h6I4j5F3Pj7Mg1o9M" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6YK+LTAQl3/TJtz3O6pD5ymIXA5b5b4MXYuSY" crossorigin="anonymous"></script>
</body>
</html>
# felling-good-
how do you feel now ?
