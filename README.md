#post2home


A good way to do define featured posts without interfering with sticky posts logic. Originally done by the good guys at [Hacklab](http://hacklab.com.br).

## Usage
Simply create a new query passing as arguments `_post2home` meta key and its value:

`$featured_posts = new WP_Query( array( 'ignore_sticky_posts' => 1, 'meta_key' => '_post2home', 'meta_value' => 1 ) );`

