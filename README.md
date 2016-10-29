# Coffeesweeper

A Minesweeper clone.

Requires [jQuery](https://jquery.com/), [Bootstrap](http://getbootstrap.com/) and [Font Awesome](http://fontawesome.io/).

A minimal example to run Coffesweeper:


```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    
    <!-- IMPORTANT: replace this with actual location of coffeesweeper.css -->
    <link rel="stylesheet" href="link_to_coffeesweeper.css">
    
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>
<body>
    <div class="col-xs-10 col-xs-offset-1">
        <div id="game-area"></div>
    </div>
    
    <!-- IMPORTANT: replace this with actual location of coffeesweeper.js -->
    <script type="text/javascript" src="link_to_coffeesweeper.js"></script>
    
    <script type="text/javascript">
        $(function () {
            var game = new MinesweeperGame("game-area");
            game.init();
        });
    </script>
</body>
</html>
```
