---
id: 6
title: test
date: '2019-08-15T22:02:21+02:00'
author: Fedir
layout: page
guid: 'https://podaruyimeni.000webhostapp.com/?page_id=6'
---

<form class="cart" enctype="multipart/form-data" method="post"> <?php do_action( 'woocommerce_before_add_to_cart_button' ); ??>
 <?php if ( ! $product-?>
is\_sold\_individually() )  
 woocommerce\_quantity\_input( array(  
 ‘min\_value’ =&gt; apply\_filters( ‘woocommerce\_quantity\_input\_min’, 1, $product ),  
 ‘max\_value’ =&gt; apply\_filters( ‘woocommerce\_quantity\_input\_max’, $product-&gt;backorders\_allowed() ? ” : $product-&gt;get\_stock\_quantity(), $product )  
 ) );  
 ?&gt;

 <input class="single_add_to_cart_button button alt" name="add-to-cart" submit="" type="hidden" value="<?php echo esc_attr( $product->id ); ?>” /></p>
<p>   <button type="></input><?php echo $product-?>
single\_add\_to\_cart\_text(); ?&gt;

 <?php do_action( 'woocommerce_after_add_to_cart_button' ); ??>

</form> <?php do_action( 'woocommerce_after_add_to_cart_form' ); ??>