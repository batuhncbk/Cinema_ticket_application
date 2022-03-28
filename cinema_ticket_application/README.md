# cinema_ticket_application
Cinema Ticket Application

#### This project is my exercise to learn html, css and javascript.

#### It is a web page design with a visual interface where the ticket purchase screen from a cinema or theater site is presented and the selection is made and the entered data is kept in the datastorage.

#### This is the interface that when using this application.
_______________________________________________________________________________________________________________________

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Cinema Ticket Reservation</title>
</head>
<body>
    <div class="container">
        <div class="screen">
        </div>
        <div class="row">
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
        </div>
        <div class="row">
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat reserved"></div>
            <div class="seat"></div>
            <div class="seat reserved"></div>
            <div class="seat"></div>
            <div class="seat"></div>
        </div>
        <div class="row">
            <div class="seat reserved"></div>
            <div class="seat reserved"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
        </div>
        <div class="row">
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
        </div>
        <div class="row">
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
            <div class="seat"></div>
        </div>
    </div>
    <div class="movie-list">
        <select id="movie">
            <option disabled>Select the Film</option>
            <option value="2">Deadpool 3</option>
            <option value="2.5">The Batman</option>
            <option value="3">Avengers 4</option>
        </select>
    </div>
    <u1 class="info">
        <li>
            <div class="seat selected"></div>
            <small>Selected</small>
        </li>
        <li>
            <div class="seat reserved"></div>
            <small>Reserved</small>
        </li>
        <li>
            <div class="seat"></div>
            <small>Blank</small>
        </li>
    </u1>
    <p class="text">
        <span id="amount">1</span> $ for these <span id="count">1</span> seat
    </p>
    <script src="script.js"></script>
</body>
</html>

## License
#### [MIT](https://choosealicense.com/licenses/mit/)
