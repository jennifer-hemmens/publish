# Add payment methods to your shop

With Mollie Payments for PrestaShop, you can offer [a wide range of
payment methods](available-payment-methods) in your shop. After connecting the module to your Mollie
account, it retrieves and lists the payment methods active in your
Mollie Dashboard. To add them to your shop's checkout, you must enable them in
PrestaShop as well.

## Before you start

  - Make sure all of the payment methods that you want to offer in your
    shop are active in your Mollie Dashboard.

## Enable a payment method

1. Log in to PrestaShop and select **Mollie** in the left
navigation panel. This opens the **General settings** configuration tab.
2. Scroll down to **Payment methods**.
3. Click a payment method to expand it.
4. Select **Yes** in the **Enabled** dropdown.
5. Optional: Configure the other available settings for the payment method
as needed:
    - **Title**: Display a different name for the payment method in your
    checkout.
    - **Method**: Select whether to use [Payments
    API](https://docs.mollie.com/reference/v2/payments-api/overview) or
    [Orders
    API](https://docs.mollie.com/reference/v2/orders-api/overview/) to
    handle payments using the payment method.
      > in3, Klarna payment methods, and vouchers always use the [Orders
    API](https://docs.mollie.com/reference/v2/orders-api/overview/).
    - **Description**: Define which information to include in transaction
    descriptions in your Mollie Dashboard for payments that used the
    payment method. The description contains the order number by
    default. You can enter any of the available variables and plain
    text.
    - **Payment allowed from**: Select the countries in which customers can
    pay with the payment method.
      - **All countries** (default): Offer the payment method to customers
        from all countries. To exclude countries, select them from the
        **Exclude payment from specific countries** dropdown.
      - **Selected countries**: Offer the payment method to customers in
        selected countries. You can select the countries from the **Allow
        payment from specific countries** dropdown.
    - **Payment surcharge**: Charge an additional fixed and/or percentage fee
    when customers use the payment method. The fixed fee is based on
    your shop's currency.
      > Not all countries allow you to add payment fees. Always check your
    local legislation before applying a surcharge.
6. Scroll down to the bottom of the page and click **Save**.

After enabling your payment methods, you can drag-and-drop them to change their display order in your checkout, and you can [run test
payments](run-test-payments) to make sure
they're working as intended.

## Disable a payment method

1. Log in to PrestaShop and select **Mollie** in the left
navigation panel. This opens the **General settings** configuration tab.
2. Scroll down to **Payment methods**.
3. Click a payment method to expand it.
4. Select **No** in the **Enabled** dropdown.
5. Scroll down to the bottom of the page and click **Save**.

The payment method no longer appears as an available option in your
shop.
