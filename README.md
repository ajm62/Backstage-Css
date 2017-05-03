# Backstage Css
This is a lightweight basic CSS framework that uses a row and column system to make responsive sites or applications.

## Usage
Backstage CSS uses a 12 column layout to create its responsive design.  

First you need to create a parent div with a class of row: 
```html
<div class="row">
</div>
```

Then you need to create more nested divs that add up to 12 under that div:
```html
<div class="row">
    <div class="col-3">
        <!--some content-->
    </div>
    <div class="col-9">
        <!--some content-->
    </div>
</div>
```

You can use any combination of col classes has long as each row adds up to 12 columns.  

