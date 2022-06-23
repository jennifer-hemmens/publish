# Enable customers to pay with a Bancontact QR code

Bancontact offers customers that use their app a quick way to pay by
scanning a QR code, which you can make available in your shop.

> The Bancontact QR code only works with [Payments API](https://docs.mollie.com/reference/v2/payments-api/overview) and in live mode.

## Before you start

  - Make sure that Bancontact is active in your Mollie Dashboard.

## Enable the Bancontact QR code

1. Log in to PrestaShop and select **Mollie** in the left
navigation panel. This opens the **General settings** configuration tab.
2. Scroll down to **Payment methods**.
3. Click Bancontact to open its settings.
4. If Bancontact is disabled, select **Yes** in the dropdown next to **Enabled**.
5. Select **Yes** in the **QR code** dropdown.
6. Select **Payments API** in the **Method** dropdown.
7. Optional: Configure the other available settings as needed:
    - **Title**: Display a different name for Bancontact in your checkout.
    - **Description**: Define which information to include in transaction
    descriptions in your Mollie Dashboard for Bancontact payments. The
    description contains the order number by default. You can enter any
    of the available variables and plain text.
    - **Payment allowed from**: Select the countries in which customers can
    pay with Bancontact.
      - **All countries** (default): Offer Bancontact to customers from all
        countries. To exclude countries, select them from the **Exclude
        payment from specific countries** dropdown.
      - **Selected countries**: Offer Bancontact to customers in selected
        countries. You can select the countries from the **Allow payment
        from specific countries** dropdown.
    - **Payment surcharge**: Charge an additional fixed and/or percentage fee
    when customers pay with Bancontact. The fixed fee is based on your
    shop's currency.
      > Not all countries allow you to add payment fees. Always check your
    local legislation before applying a surcharge.
8. Scroll down to the bottom of the page and click **Save**.

When customers select Bancontact to pay for their items, a window
containing a QR code appears. They can scan the QR code using their
Bancontact app to complete the payment, or click **Continue without QR
code** to follow the standard Bancontact payment flow.

### Read more

  - [Test the Bancontact QR code](test-bancontact-QR-code)
