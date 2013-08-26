jquery.inner-scroll
===============

isolate scroll event within an element.

## installation:

- include jQuery first:

        <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>

- include jquery.inner-scroll.js

        <script type="text/javascript" src="jquery.inner-scroll.js"></script>


## usage

html markup:

      <div class="popbox-menu">
        <p>pcontents here</p>
      </div>

javascript:

      var options = {
        paddingClass: "the-padding-class"
      }; 
      $(".popbox-menu").innerScroll(options);


## options

- `paddingClass`: class name of padding element without the prefixing `.`
                  default to `inner-scroll-padding`


## sample:

see `sample.html`


