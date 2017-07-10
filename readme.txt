=== WooCommerce Installments ===
Contributors: andersonfranco
Donate link: http://francotecnologia.com/donate
Tags: woocommerce, pagseguro, paypal, payment, parcelamento, installments
Requires at least: 3.8.1
Tested up to: 4.0
Stable tag: 1.4.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds installments into the price. Adiciona parcelamento ao preço.

== Description ==

This plugin appends installments into the product price. Was created to be used with PagSeguro, PayPal and similars.

More info and screenshots in our GitHub repository:
https://github.com/AndersonFranco/woocommerce-installments

(Portuguese)

Adiciona parcelamento ao preço do produto. Foi criado para ser utilizado com PagSeguro, PayPal e similares.

== Installation ==

1. Upload the entire `woocommerce-installments` folder to the `/wp-content/plugins/` directory
2. Edit plugin settings in `woocommerce-installments.php` file
3. Activate the plugin through the `Plugins` menu in WordPress

(Portuguese)

1. Envie toda a pasta `woocommerce-installments` para a pasta `/wp-content/plugins/`
2. Edite no arquivo `woocommerce-installments.php` as opções do plugin
3. Ative o plugin através do menu `Plugins` no WordPress

== Frequently Asked Questions ==

= Sample of CSS to show the price like the screenshots =

(Portuguese)
Ajuste o CSS para exibir conforme os screenshots

  ul.products li.product .price {
    display: inline;
  }

  .francotecnologia_wc_parcpagseg_table th,
  .francotecnologia_wc_parcpagseg_table td {
    padding: 0;
    border-bottom: 1px solid #e8e4e3;
  }

= Where can I report bugs or contribute to the project? =

Preferably in our GitHub repository
https://github.com/AndersonFranco/woocommerce-installments

== Screenshots ==

1. Catalog page.
2. Product page.
3. Cart page.

== Changelog ==

= 1.4.0 =

* Table - Total column
* Table - Header and footer message

= 1.3.1 =

* Refactoring

= 1.3.0 =

* OOP structure

= 1.2.1 =

* Cart page fix
* CSS file

= 1.2.0 =
* Product variation
* Javascript file

= 1.1.2 =
* Bug fix

= 1.1.1 =
* Small Tweak

= 1.1.0 =
* Settings

= 1.0.1 =
* Readme file in Portuguese

= 1.0 =
* Initial Release

== Upgrade Notice ==

= 1.0.1 =
Readme Update
