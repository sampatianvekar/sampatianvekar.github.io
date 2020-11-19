<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Module2 Assignment</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="css/style.css" />
</head>

<body>
    <h1>Our Menu</h1>

    <div class="col-lg-4 col-md-6 col-sm-12">
        <section>
            <h2 id="chicken">Chicken</h2>
            <ul>
                <li>Balsamic Roasted Brussels Sprouts, Butternut Squash and Chicken Thighs</li>
                <li>Prosciutto-Wrapped Chicken with Garlic and Herb Cheese</li>
                <li>Siri Pinter’s One-Pot Chicken Alfredo</li>
                <li>Florentine Penne with Chicken</li>
                <li>Garlic-Bread Chicken Nuggets with Balsamic Ketchup</li>
            </ul>
        </section>
    </div>

    <div class="col-lg-4 col-md-6 col-sm-12">
        <section>
            <h2 id="pork">Pork</h2>
            <ul>
                <li>Pork Cheek and Black-Eyed Pea Chili</li>
                <li>Braised Pork with Cherry Gravy</li>
                <li>Aleppo-Pepper-Pork-and-Fennel Sandwiches</li>
                <li>Herb-Roasted Pork Subs with Garlicky Spinach</li>
                <li>Chinese-Style Ribs with Guava Barbecue Sauce</li>
                <li>Pork Medallions with Onion Marmalade</li>
            </ul>
        </section>
    </div>

    <div class="col-lg-4 col-md-12 col-sm-12">
        <section>
            <h2 id="steak">Steak</h2>
            <ul>
                <li>Butter-Basted Rib Eye Steaks</li>
                <li>Balsamic Marinated Flank Steak</li>
                <li>Grilled Hanger Steak with Kimchi-Apple Slaw</li>
                <li>Throwback Porterhouse Steaks</li>
                <li>Minute Steak Stacks with Herbed Anchovy Butter</li>
                <li>Grilled Skirt Steak with Salsa Verde</li>
            </ul>
        </section>
    </div>
   </p>
</body>

</html>

* {
    box-sizing: border-box;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

h1 {
    color: blue;
    font-size: 175%;
    text-align: center;
}

section {
    border: 1px solid black;    
    background-color: bisque;
    height: 250px;
    overflow: auto;
}

h2 {
    float: right;
    border:1px solid black;
    color: lavender;
    font-size: 125%;
    padding: 5px 20px 5px 20px;
    margin-top: 0;
    margin-bottom: 20px;
}

ul {
    clear: right;
    width: 90%;
}

#chicken {
    background-color: brown;
}

#pork {
    background-color: darkorchid;
}

#steak {
    background-color: forestgreen;
}


/********** Desktop version **********/
@media (min-width: 992px) {
    .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
      float: left;
      padding: 15px;
    }
    .col-lg-1 {
      width: 8.33%;
    }
    .col-lg-2 {
      width: 16.66%;
    }
    .col-lg-3 {
      width: 25%;
    }
    .col-lg-4 {
      width: 33.33%;
    }
    .col-lg-5 {
      width: 41.66%;
    }
    .col-lg-6 {
      width: 50%;
    }
    .col-lg-7 {
      width: 58.33%;
    }
    .col-lg-8 {
      width: 66.66%;
    }
    .col-lg-9 {
      width: 75%;
    }
    .col-lg-10 {
      width: 83.33%;
    }
    .col-lg-11 {
      width: 91.66%;
    }
    .col-lg-12 {
      width: 100%;
    }
  }
  
  /********** Tablet version **********/
  @media (min-width: 768px) and (max-width: 991px) {
    .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
      float: left;
      padding: 15px;
    }
    .col-md-1 {
      width: 8.33%;
    }
    .col-md-2 {
      width: 16.66%;
    }
    .col-md-3 {
      width: 25%;
    }
    .col-md-4 {
      width: 33.33%;
    }
    .col-md-5 {
      width: 41.66%;
    }
    .col-md-6 {
      width: 50%;
    }
    .col-md-7 {
      width: 58.33%;
    }
    .col-md-8 {
      width: 66.66%;
    }
    .col-md-9 {
      width: 75%;
    }
    .col-md-10 {
      width: 83.33%;
    }
    .col-md-11 {
      width: 91.66%;
    }
    .col-md-12 {
      width: 100%;
    }
  }

  /********** Mobile version **********/
  @media (max-width: 767px) {
    .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
      float: left;
      padding: 15px;
    }
    .col-sm-1 {
      width: 8.33%;
    }
    .col-sm-2 {
      width: 16.66%;
    }
    .col-sm-3 {
      width: 25%;
    }
    .col-sm-4 {
      width: 33.33%;
    }
    .col-sm-5 {
      width: 41.66%;
    }
    .col-sm-6 {
      width: 50%;
    }
    .col-sm-7 {
      width: 58.33%;
    }
    .col-sm-8 {
      width: 66.66%;
    }
    .col-sm-9 {
      width: 75%;
    }
    .col-sm-10 {
      width: 83.33%;
    }
    .col-sm-11 {
      width: 91.66%;
    }
    .col-sm-12 {
      width: 100%;
    }
  }
