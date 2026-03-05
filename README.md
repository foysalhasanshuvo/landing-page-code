Custom Size in Inline Design
```shell script
.wcf-embed-checkout-form .woocommerce-input-wrapper {
    display: flex !important;
    align-items: center;
    flex-wrap: wrap;
}
.wcf-embed-checkout-form .woocommerce .wcf-input-radio-field-wrapper input[type="radio"].input-radio
 {
     margin-right: 4px;
 }
.wcf-embed-checkout-form .woocommerce form .form-row .required {
    margin-left: -4px;
    margin-right: 15px;
}
```
```shell script
@media (max-width: 767px){
.wcf-embed-checkout-form .woocommerce-checkout .wcf-product-option-wrap.wcf-yp-skin-classic .wcf-qty .wcf-qty-selection-wrap{
                margin-left: -22px;
                padding-right: 10px;
            }
span.woocommerce-Price-amount.amount{
		margin-left: 15px;
        }
.wcf-embed-checkout-form .woocommerce form .wcf-shipping-methods-wrapper{
	margin-top: -80px;
}
.wcf-embed-checkout-form-two-column .woocommerce-checkout .wcf-order-wrap{
	margin-top: -50px;
}
}
```

