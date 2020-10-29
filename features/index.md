---
title: Introduction - Features
estimated_read: 10
card_overview: true
description: |
    In this section you find various resources for Swedbank Pay’s API Platform.
icon:
  content: remove_red_eye
additional: true
menu_order: 5
card_list: 
- title: Payment resource
  description: When initiating a payment process
  url: /checkout/features/payment-orders
  icon:
    content: view_list
    outlined: true
- title: 3D Secure 2
  description: Initialize payment process containing the order
  url:  /checkout/features/recurring-payments
  icon:
    content: autorenew
- title: Settlement & Reconciliation
  description: Initialize payment process containing the order
  icon:
    content: description
    outlined: true
card_list_2:
- title: Purchase
  description: Initialize payment process containing the order
  icon:
    content: settings
    outlined: true
- title: Payment & Transactions States
  description: Initialize payment process containing the order
  icon:
    content: http
- title: Create Payment
  description: Initialize payment process containing the order
  icon:
    content: shopping_basket
    outlined: true
- title: CompleteUrl
  description: Initialize payment process containing the order
  icon:
    content: attach_money
    outlined: true
- title: Description
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: PaymentUrl
  description: Initialize payment process containing the order
  icon:
    content: undo
- title: Callback
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: Transactions
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: Card authorization transaction
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: PayeeInfo
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: PayeeReference
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: Prices
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: Metadata
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: Problems
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: Seamless View Events
  description: Initialize payment process containing the order
  icon:
    content: construction
card_list_3: 
- title: Recur
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: Unscheduled Purchase
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: Payout
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: Verify
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: One-Click Payments
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: Payment Link
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: Co-badge Card Choice for Dankort
  description: Initialize payment process containing the order
  icon:
    content: construction
- title: MOTO
  description: Initialize payment process containing the order
  icon:
    content: construction
---

{:.heading-line}

## Core Features

{% include card-list.html card_list=page.card_list
    col_class="col-lg-4" %}

## Technical Features

{% include card-list.html card_list=page.card_list_2
    col_class="col-lg-4" %}

## Optional Features

{% include card-list.html card_list=page.card_list_3
    col_class="col-lg-4" %}

[purchase]: #purchase
[user-agent]: https://en.wikipedia.org/wiki/User_agent
[cancel]: /payment-instruments/card/after-payment#cancellations
[capture]: /payment-instruments/card/capture
[callback]: /payment-instruments/card/other-features#callback
[card-badge]: /assets/img/card-badge.png
[dankort-eu]: https://www.dankort.dk/Pages/Dankort-eller-Visa.aspx
[eu-regulation]: https://ec.europa.eu/commission/presscorner/detail/en/MEMO_16_2162
[mcc]: https://en.wikipedia.org/wiki/Merchant_category_code
[price-resource]: /payment-instruments/card/other-features#prices
[redirect]: /payment-instruments/card/redirect
[hosted-view]: /payment-instruments/card/seamless-view
[one-click-payments]: #one-click-payments
[payee-reference]: #payee-reference
[split-settlement]: #split-settlement
[settlement-and-reconciliation]: #settlement-and-reconciliation
[swedbankpay-support]: https://www.swedbankpay.se/support
[recurrence]: #recur
[verify]: #verify
[payout]: #payout
[card-payment]: /assets/img/payments/card-payment.png