# **Bootstrap_Assignment**

## **Q-1.** What are the advantages of Bootstrap?

**Ans.**

    =>  A Time-Saving Solution for Web Design Projects. 
    =>  Easy to Use. 
    =>  Responsive Grid System: Design for All Devices. 
    =>  Customizable: Make it your own. 
    =>  Cross-Browser Compatibility with Responsive Designs. 
    =>  Maintaining Consistency in the Project.  
    =>  Open Source: Collaborate and Grow. 
    


## **Q-2.** What is a Bootstrap Container, and how does it work?

**Ans.**

=> this container class provides a responsive fixed width container a container 80% width fixed in bootstrap

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset='utf-8'>
        <meta http-equiv='X-UA-Compatible' content='IE=edge'>
        <title>Bootstrap</title>
        <meta name='viewport' content='width=device-width, initial-scale=1'>
        <link rel='stylesheet' type='text/css' media='screen' href='main.css'>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
            integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js"
            integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB"
            crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js"
            integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13"
            crossorigin="anonymous"></script>
        <script src='main.js'></script>
        </head>
        <body>
        <div class="container p-5 bg-success">80% width fixed
        </div>
        </body>

=> The .container-fluid class provides a full width container, spanning the entire width of the viewport

    <!DOCTYPE html>
    <html lang="en">
    <head>
            <meta charset='utf-8'>
            <meta http-equiv='X-UA-Compatible' content='IE=edge'>
            <title>Bootstrap</title>
            <meta name='viewport' content='width=device-width, initial-scale=1'>
            <link rel='stylesheet' type='text/css' media='screen' href='main.css'>
            <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
                integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
            <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js"
                integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB"
                crossorigin="anonymous"></script>
            <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js"
                integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13"
                crossorigin="anonymous"></script>
            <script src='main.js'></script>
            </head>
            <body>
            <div class="container-fluid p-5 bg-warning">full width container
            </div>
            </body>


## **Q-3.** What are the default Bootstrap text settings?

**Ans.**

    =>Bootstrap's global default font-size is 14px, with a line-height of 1.428.
    =>This is applied to the <body> element and all paragraphs (<p>).
    =>In addition, all <p> elements have a bottom margin that equals half their computed line-height (10px by default).
    =>By default, Bootstrap will style the HTML headings (<h1> to <h6>)
    => h1 Bootsrap heading (36px)
    => h2 Bootsrap heading (30px)
    => h3 Bootsrap heading (24px)
    => h4 Bootsrap heading (18px)
    => h5 Bootsrap heading (14px)
    => h6 Bootsrap heading (12px)



## **Q-4.** What do you know about the Bootstrap Grid System?

**Ans.**

    =>Bootstrap's grid system allows up to 12 columns across the page.
    =>If you do not want to use all 12 columns individually, you can group the columns together to create wider columns
    =>Bootstrap's grid system is responsive, and the columns will re-arrange automatically depending on the screen size.

    *** Grid Classes ***
    =>The Bootstrap grid system has four classes:

    1.  xs (for phones - screens less than 768px wide)
    2.  sm (for tablets - screens equal to or greater than 768px wide)
    3.  md (for small laptops - screens equal to or greater than 992px wide)
    4.  lg (for laptops and desktops - screens equal to or greater than 1200px wide)

    Exampale:-

    <div class="container">
    <div class="row">
    <div class="col-md-6"></div>
    <div class="col-md-6"></div>
    </div>

    <div class="row">
    <div class="col-md-4"></div>
    <div class="col-md-4"></div>
    <div class="col-md-4"></div>
    </div>


## **Q-5.** What is the difference between Bootstrap 4 and Bootstrap 5

**Ans.**

    =>  Bootstrap is an open-source tool collection
        for creating responsive web pages and web
        apps. It is the combination of HTML, CSS,
        and JavaScript framework that makes it easy
        to develop responsive, mobile-first websites.
        It mainly aims to resolve the
        cross-browser compatibility issue.

    *** Bootstrap is ***

    =>Faster and Easier
    =>Mobile First style
    =>free Available Browser Support
    =>Browser support
    =>Responsive Design

    *** bootstrap-4 ***

    => It has 5 tier (xs, sm, md, lg, xl)
    => It has limited colors
    => It has jquery and all related plugins
    => Bootstrap 4 supports both IE 10 and 11
    => Columns can be positioned relative
    => Bootstrap 4 doesn’t have its own SVG icons,
  we have to use font-awesome for icons
    => It does not support Offcanvas Component
    => We have inline-block property and we will get white dropdown as default for dropdown-menu-dark class.

    *** bootstrap-5 ***

    => It has 6 tier (xs, sm, md, lg, xl, xxl)
    => Extra colors added with the looks, A card improved color palette. there are various shades available to choose.
    => Jquery is removed and switched to vanilla JS with some working plugins
    => Bootstrap 5 doesn’t support IE 10 and 11
    => Columns cannot be positioned relative
    => Bootstrap 5 have its own SVG icons
    => It supports Offcanvas Component(that is it is available now)
    => Inline-block property is removed and we will get black dropdown as default for dropdown-menu-dark class.


## **Q-6.** What is a Button Group, and what is the class for a basic Button Group?

**Ans.**

        => Button Groups in Bootstrap is a class of name btn-group which is used to create a series of buttons in groups (without spaces) vertically or horizontally

        <!DOCTYPE html>
        <html>
        <head>
        <meta charset='utf-8'>
        <meta http-equiv='X-UA-Compatible' content='IE=edge'>
        <title>Bootstrap</title>
        <meta name='viewport' content='width=device-width, initial-scale=1'>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.3/js/bootstrap.min.js" integrity="sha512-ykZ1QQr0Jy/4ZkvKuqWn4iF3lqPZyij9iRv6sGqLRdTPkY69YX6+7wvVGmsdBbiIfN/8OdsI7HABjvEok6ZopQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
        </head>
        <body>
        <div class="container">

        <div class="btn-group">
            <button type="button" class="btn btn-primary">btn1</button>
            <button type="button" class="btn btn-primary">btn2</button>
            <button type="button" class="btn btn-primary">btn3</button>
        </div>
    
        <div class="btn-group btn-group-lg">
            <button type="button" class="btn btn-primary">btn1</button>
            <button type="button" class="btn btn-primary">btn2</button>
            <button type="button" class="btn btn-primary">btn3</button>
        </div>
        
        <div class="btn-group btn-group-sm">
            <button type="button" class="btn btn-primary">btn1</button>
            <button type="button" class="btn btn-primary">btn2</button>
            <button type="button" class="btn btn-primary">btn3</button>
        </div>

        <div class="btn-group btn-group-xs">
            <button type="button" class="btn btn-primary">btn1</button>
            <button type="button" class="btn btn-primary">btn2</button>
            <button type="button" class="btn btn-primary">btn3</button>
        </div>

        <div class="btn-group-vertical">
        <button type="button" class="btn btn-success">btn1</button>
        <button type="button" class="btn btn-success">btn2</button>
        <button type="button" class="btn btn-success">btn3</button>
        </div>
        </div>

        </body>
        </html>


## **Q-7.** How can you use Bootstrap to make thumbnails?

**Ans.**

=> A thumbnail is a small image that represents a larger image when clicked on, and is often recognized with a border around it

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Thumbnail images</title>
        <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.3/js/bootstrap.min.js" integrity="sha512-ykZ1QQr0Jy/4ZkvKuqWn4iF3lqPZyij9iRv6sGqLRdTPkY69YX6+7wvVGmsdBbiIfN/8OdsI7HABjvEok6ZopQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    </head>
    <body>
        <h3 style="color: green">Bootstrap thumbnails</h3>
        <div class="row">
            <div class="col-sm-6 col-md-3">
                <a href="#" class="thumbnail">
                    <img src="https://images.pexels.com/photos/20888057/pexels-photo-20888057/free-photo-of-kleinhorn-rosenlaui-switzerland.jpeg?auto=compress&cs=tinysrgb&w=600&lazy=load" style="height: 100px; width: 100px;">
                </a>
            </div>
            <div class="col-sm-6 col-md-3">
                <a href="#" class="thumbnail">
                    <img src="https://images.pexels.com/photos/17950554/pexels-photo-17950554/free-photo-of-palm-tree-next-to-a-blocky-concrete-building.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" style="height: 100px; width: 100px;">
                </a>
            </div>
            <div class="col-sm-6 col-md-3">
                <a href="#" class="thumbnail">
                    <img src="https://images.pexels.com/photos/20470948/pexels-photo-20470948/free-photo-of-tennis-rackets-and-balls.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" style="height: 100px; width: 100px;">
                </a>
            </div>
        </div>
    </body>
    </html>



## **Q-8.** In Bootstrap 4, what is flexbox?

**Ans.**

------ Bootstrap 4 Flex ------
=> Use flex classes to control the layout of Bootstrap 4 components.

------ Flexbox ------
=> The biggest difference between Bootstrap 3 and Bootstrap 4 is that Bootstrap 4 now uses flexbox, instead of floats, to handle the layout.

------- Extra property --------
            => flex-row and flex-row-reverse
            => flex-column and flex-column-reverse
            => all justify property
            => flex-grow-1
            => flex-shrink-1
            => flex-wrap all property
            => align-content all property

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <title>Bootstrap Example</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.7.1/dist/jquery.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body> 

    <div class="container mt-3">
    <h2>Flex</h2>
    <p>To create a flexbox container and transform direct children into flex items, use the d-flex class:</p>
    <div class="d-flex p-3 bg-secondary text-white">  
        <div class="p-2 bg-info">flexbox1</div>
        <div class="p-2 bg-warning">flexbox2</div>
        <div class="p-2 bg-primary">flexbox3</div>
    </div>
    </div>

    </body>
    </html>
    </body>

## **Q-9.**     How can one create an alert in Bootstrap?

**Ans.**

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <title>Bootstrap Example</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    </head>
    <body>

    <div class="container">
    <h2>Alert Links</h2>
    <p>Add the alert-link class to any links inside the alert box to create "matching colored links".</p>
    <div class="alert alert-success">
        <strong>Success!</strong> You should <a href="#" class="alert-link">read this message</a>.
    </div>
    <div class="alert alert-info">
        <strong>Info!</strong> You should <a href="#" class="alert-link">read this message</a>.
    </div>
    <div class="alert alert-warning">
        <strong>Warning!</strong> You should <a href="#" class="alert-link">read this message</a>.
    </div>
    <div class="alert alert-danger">
        <strong>Danger!</strong> You should <a href="#" class="alert-link">read this message</a>.
    </div>
    </div>

    </body>
    </html>



## **Q-10.**    What is a bootstrap card and how would you create one?

**Ans.**

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width,initial-scale=1.0" />
        <title>Document</title>
        <link
        href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
        rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
        crossorigin="anonymous"
        />
    </head>
    <body class="px-5 mt-5">
        <div class="card" style="width: 20rem">
        <img
            src="https://images.pexels.com/photos/399161/pexels-photo-399161.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
            class="card-img-top rounded-5 p-2" 
            alt="..."
        />
        <div class="card-body">
            <h5 class="card-title">Card Bootstrap</h5>
            <p class="card-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum magnam corrupti obcaecati omnis assumenda. Quae labore minima numquam non nulla recusandae ab natus fugit, molestiae impedit nisi, dolorum optio beatae.
            </p>
            <a href="#" class="btn btn-primary">Click me</a>
        </div>
        </div>

