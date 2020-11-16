---
title: Features
estimated_read: 10
card_overview: true
description: |
    In this section you find various resources for Swedbank Pay’s API Platform.
icon:
  content: remove_red_eye
additional: true
menu_order: 1000
card_list: 
- title: Abort
  description: Aborting a created payment
  url: /features/core-features#abort
  icon:
    content: highlight_off
    outlined: true
- title: Cancel
  description: Cancelling the authorization and releasing the funds
  url: /features/core-features#cancel
  icon:
    content: pan_tool
    outlined: true
- title: Capture
  description: Capturing the authorized funds
  url: /features/core-features#capture
  icon:
    content: compare_arrows
    outlined: true
- title: Payment resource
  description: When initiating a payment process
  url: /features/core-features#payment-resource
  icon:
    content: credit_card
    outlined: true
- title: Reversal
  description: How to reverse a payment
  url: /features/core-features#reversal
  icon:
    content: keyboard_return
    outlined: true
- title: Settlement & Reconciliation
  description: Balancing the books
  url:  /features/core-features#settlement-and-reconciliation
  icon:
    content: description
    outlined: true
card_list_2:
- title: Callback
  description: Getting updates about payment or transaction changes
  url:  /features/technical-reference#callback
  icon:
    content: low_priority
    outlined: true
- title: CompleteUrl
  description: Where you go when the payment is completed
  url:  /features/technical-reference#completeurl
  icon:
    content: link
    outlined: true
- title: Create Payment
  description: Creating the payment
  url:  /features/technical-reference#create-payment
  icon:
    content: note_add
    outlined: true
- title: Description
  description: The purchase summed up in a few words
  url:  /features/technical-reference#description
  icon:
    content: assignment
    outlined: true
- title: Metadata
  description: Store payment associated data for later use
  url:  /features/technical-reference#metadata
  icon:
    content: code
    outlined: true
- title: PayeeInfo
  description: Payment specific merchant information
  url:  /features/technical-reference#payeeinfo
  icon:
    content: account_box
    outlined: true
- title: PayeeReference
  description: The merchant's reference for a specific payment
  url:  /features/technical-reference#payee-reference
  icon:
    content: assignment_ind
    outlined: true
- title: Payment & Transactions States
  description: Possible states of the payments and transactions
  url:  /features/technical-reference#payment-and-transaction-states
  icon:
    content: hdr_weak
- title: PaymentUrl
  description: Redirecting the payer back to your site
  url:  /features/technical-reference#payment-url
  icon:
    content: link
    outlined: true
- title: Prices
  description: The payment's prices resource
  url:  /features/technical-reference#prices
  icon:
    content: attach_money
    outlined: true
- title: Problems
  description: Information when something goes wrong
  url:  /features/technical-reference#problems
  icon:
    content: report
    outlined: true
- title: Seamless View Events
  description: Possible events during Seamless View payments
  url:  /features/technical-reference#seamless-view-events
  icon:
    content: event
    outlined: true
- title: Transactions
  description: The transactions making up a specific payment
  url:  /features/technical-reference#transactions
  icon:
    content: done_all
    outlined: true
card_list_3: 
- title: Payment Link
  description: Sending the payment via mail or SMS
  url:  /features/optional-features#payment-link
  icon:
    content: link
    outlined: true
- title: Payout
  description: Making deposits to payers' cards
  url:  /features/optional-features#payout
  icon:
    content: monetization_on
    outlined: true
- title: Recur
  description: Setting up subscriptions and recurring payments
  url:  /features/optional-features#recur
  icon:
    content: cached
    outlined: true
- title: Verify
  description: Validating the payer's payment details
  url:  /features/optional-features#verify
  icon:
    content: verified_user
    outlined: true
---

{:.heading-line}

## Core Features

{% include card-list.html card_list=page.card_list
    col_class="col-lg-4" %}

## Technical Reference

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