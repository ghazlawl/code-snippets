### Filters

#### Wrap oEmbed w/ DIV

```
function wrap_embed_with_div($html, $url, $attr) {
    return '<div class="embed-responsive embed-responsive-16by9">' . $html . '</div>';
}

add_filter('embed_oembed_html', 'wrap_embed_with_div', 10, 3);
```
