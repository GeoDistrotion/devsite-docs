---
sites_supported:
  - mla
  - mlb
  - mco
  - mlu
  - mlm
  - mlc
---

# Payment Preferences
<br/>

Find the payment preference settings in the 'WooCommerce Settings' once you have installed the module. There, go to the 'Payments' section, activate the checkout you want to offer and configure the options you prefer for your shopping gateway.

> NOTE
>
> Note
>
> Remember that we have different [checkout types]() that adapt to your business’ needs and that each one has its own settings.

## Business information

Enter the **name of the business** to appear on your customers' invoice and make it easier for them to recognize the payment when a purchase summary arrives. Select to which **category** the products or services offered by the store belong and make other adjustments according to your needs.

![Basic information](/images/woocomerce/es_info_basica.png)

> WARNING
>
> Important
>
> **Are you a Mercado Pago partner?** Don’t forget to enter your Sponsor_ID, so we can identify all your transactions and know how many orders your account processes.

## Basic configuration

Activate the checkout you want to offer your customers according to your preferences and choose the payment methods with which they can make the purchase.

1) Activate a checkout type

  * Use Smart checkout to support payments with cards, cash and money in the Mercado Pago account.
  * Use the Custom Checkout to have control over other settings.

> WARNING
>
> Important
>
> Note that the [Smart Checkout](https://www.mercadopago.com.ar/developers/es/guides/payments/web-payment-checkout/introduction) is exclusive of the Custom Checkout and vice versa. You can use both custom checkouts at the same time to offer all means of payment.

2) Choose the [payment methods available](https://www.mercadopago.com.ar/developers/en/guides/localization/payment-methods/) to your customers according to the marketplace in which you operate and the type of checkout you are configuring.

3) Set the maximum number of installments in which they can pay you.

4) Activate the currency conversion with the one you have in Mercado Pago.

> NOTE
>
> Note
>
> The option to the activate currency conversion is available only for the Custom Checkout. The Smart Checkout converts automatically.

## Advanced configuration

You will have different settings available depending on the type of checkout you activate in your store. Customize the shopping experience with the advanced settings that apply to each.

### Common settings to all checkouts

| Configuration                 | Description                                                                 	                |
|-------------------------------|-----------------------------------------------------------------------------------------------|
| Binary Mode     	            | Activate this option when you do not want to leave payments pending or under review. With binary mode payments will be accepted or rejected automatically.|
| Gateway Mode              	  | If you operate with the [gateway mode](https://www.mercadopago.com.ar/developers/es/guides/gateway/general-considerations/introduction/) as a payment processor and have your own trade numbers, you can set up discounts and commissions to your customers for paying with Mercado Pago.|

### Smart Checkout

#### Payment experiences in Smart checkout

Choose what shopping experience your customers will have when paying: 

| Payment experience            | Characteristics                                                              	                                 |
|-------------------------------|----------------------------------------------------------------------------------------------------------------|
| Redirect     	                | Your customers will be redirected to a Mercado Pago page with the payment form to complete the purchase.       |
| Modal                       	| Your customers will access the Mercado Pago payment form without leaving your store.                           |

> NOTE
>
> Nota
>
> Check out the [Smart Checkout documentation](https://www.mercadopago.com.ar/developers/es/guides/payments/web-payment-checkout/introduction/) to learn more about all its features and functionalities.

| Configuration                 | Description                                                               	                  |
|-------------------------------|-----------------------------------------------------------------------------------------------|
| Back to the store     	      | When you choose redirect, you will always have the option of having your customers return or not to your store once the payment is finished.|
| Configurable URLs           	| Payment successful, declined or pending.|

### Custom Checkout

#### Card payments

| Configuration                 | Description                                                                 	                |
|-------------------------------|-----------------------------------------------------------------------------------------------|
| Discount coupon       	      | Activate this option when you want to offer discounts to your customers. A field will appear on the form where they can enter their coupon.|

#### Pay with cash

| Configuration                 | Description                                                                 	                |
|-------------------------------|-----------------------------------------------------------------------------------------------|
| Discount coupon       	      | Activate this option when you want to offer discounts to your customers. A field will appear on the form where they can enter their coupon.|
| Reduce inventory      	      | Activate this option when you want to automate the inventory reduction for each purchase order that is approved after a payment with Mercado Pago.|

---

### Next steps

> LEFT_BUTTON_REQUIRED_ES
>
> Test and receive payments
>
> Test the module and verify that everything works well to start receiving money from your sales in Mercado Pago.
>
>
> [Receive payments](http://www.mercadopago.com.ar/mla/en/plugins_sdks/plugins/woocommerce/receive-payments/)