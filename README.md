# Pure Bootstrap, Font-awesome and JQuery Star Ranking Control

Star Ranking control is a JavaScript powered based on JQuery simply to use control. It using HTML 5 data attributes to set up.

![Image](https://rustem-bayetov.github.io/Bootstrap4-StarRanking/Preview.jpg)

See the [Star Ranking control in action](https://rustem-bayetov.github.io/Bootstrap4-StarRanking)


## Dependecies
All of you need is:
* Use Bootstrap 4 
* Add JQuery 
* Use Fontawesome 
``` 
<!-- Copy it to head of page -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css" integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU" crossorigin="anonymous">
```

## Usage
Simply add code below where you want

```
<input id="input-1" name="input-1" class="rating rating-loading" data-min="0" data-max="5" data-step="1" value="1" data-size="xs">
```

## Set it up
Use Html attributes to set up your control
* data-min - Minimum stars
* data-max - Maximum stars
* data-step - Increment step 
* disabled - Disable your control
* data-showcaption=false - To switch off the caption (it switched on by default)

## Thanks to
Thanks to anirudhabhowmik for his component https://bootsnipp.com/snippets/lVqo2
I just unlink it from bootstrap 3 and made some changes.
