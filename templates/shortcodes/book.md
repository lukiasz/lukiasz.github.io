<br><br>
<h3>{{ title }} <small><i>— {{ author }}</small></i></h3>

<div class="bookrow">
    <div class="book-left-column">
    <img src="{{ image }}" alt="{{ title }}">
    </div>
    <div class="book-right-column">
    {{ body | markdown(inline=true) }}
    </div>
</div>
<hr>