# Genspark Membership — Subscription Flow

> For Buddy Agent internal use.
> type: howto | feature: membership | keywords: subscribe, upgrade, purchase, payment, pricing, Checkout, membership, Subscribe
> User loop: Open pricing page → Choose Plus/Pro and tier → Choose monthly/annual → Complete payment → Membership activated

## Where to Start

The pricing page is an in-app modal that can be opened from several entry points:

- **Direct link**: [Click here to open the Plans / Pricing page directly](https://www.genspark.ai/me?open_pricing=help_center) (the pricing modal pops up automatically, saving you from hunting for the entry point).
- **Account menu**: Click the account / avatar menu in the bottom-left corner, where you'll find the entry to upgrade / manage your plan (free users see "Upgrade", existing members see "Manage").
- **Insufficient Credit prompt**: When your Credits run out, the prompt includes buttons to upgrade / buy more.

![Free user: the "Upgrade Plan" entry in the bottom-left account menu](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35767/4018e1bb.png)

![Member user: the same entry shows "Manage Plan" + a membership badge](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35767/757fe847.png)

> The price and Credit allowance for each tier are shown live on the pricing page, **which is authoritative** — the steps below only cover the flow and don't list any numbers.

## Step 1: Choose Plus or Pro

The pricing page presents two main categories: **Plus** (for everyday / light-to-moderate use) and **Pro** (for heavy / professional use). Check the page cards for the specific price and Credit allowance of each tier.

![The in-app pricing modal showing the Plus / Pro cards](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35767/211dff4a.png)

> You may see more than two cards in the modal: Plus is usually split into "a standalone lowest-tier card + a mid-to-high-tier card (switch tiers via the in-card dropdown)", and Pro is also a single card with a tier dropdown. Don't worry if you see multiple cards — you'll pick the tier from the card dropdown in the next step.

## Step 2: Choose a Tier

Each category has multiple tiers, and higher tiers come with more monthly Credits. On the Plus mid-to-high-tier card and the Pro card, you can use the **dropdown menu on the card** to switch between tiers and compare prices and allowances (free users can expand it to look too, without subscribing first).

![The tier dropdown on a card expanded, listing multiple tiers (free users can expand it to view too)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35767/82926054.png)

## Step 3: Choose Monthly or Annual

You can toggle **Monthly / Annual** at the top of the page. Annual billing charges once a year and **works out cheaper per month**; when you switch to annual, the card shows roughly how much you can save — the exact figures are authoritative on the page.

![The Monthly / Annual toggle at the top of the page](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35767/78a2f984.png)

## Step 4: Complete Payment

After clicking the start / subscribe button on the card, you'll be taken to the secure Stripe payment page:

1. Choose a payment method and fill in your details (multiple payment methods are supported, **as shown on the checkout page**)
2. Confirm the amount and subscription period
3. Complete the payment

![The secure Stripe checkout page offering multiple payment methods](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35767/79c5db01.png)

> If your bank requires extra verification (such as 3D Secure), just follow the on-screen prompts to complete it. Payment is processed by Stripe with industry-standard encryption, and Genspark does not store your full card number.

## After a Successful Payment

- You're automatically returned to Genspark, your membership takes effect immediately, and Credits arrive instantly
- A membership badge appears in the account / avatar menu; opening the management modal shows your current plan and **auto-renewal date**
- Your Credit balance updates to the new allowance

## Refunds / Billing Issues

Refund rules vary by **subscription type, regional regulations, and account status**, and **each subscription can only be refunded once** (once a first refund is approved, a second won't be processed; this applies to both Plus / Pro and Genspark Cloud Computer). Common applicable windows:

- **EU / UK / Turkey**: Cancellations **within 14 days** of purchase are refundable (applies to both monthly and annual; note in your request that you're from the EU / UK / Turkey).
- **Other regions**: You can apply **within 24 hours** of a monthly purchase, or **within 72 hours** of an annual purchase.
- If the system detects **heavy usage** of the service before the refund (using up most of the subscription's allowance / quota), the request may be denied.

To **request a refund**, provide: your Genspark login email, your payment email (if different from the login email), the invoice (PDF), and the reason for the refund. **Submit each request only once** (duplicate emails slow down processing); once all materials are complete, **full refunds are processed within 7 business days**. Late requests beyond the applicable window cannot be accepted.

> Specific terms such as refund windows and regional differences may be updated; the [Refunds & Cancellations section of the Membership & Pricing page](https://www.genspark.ai/helpcenter/membership-plans) is authoritative. To request a refund / resolve a billing issue, please **submit a ticket / contact support**.
>
> **In-app purchases (iOS / Android)**: Refunds, invoices, and billing are handled by the respective app store, not via Stripe, and cannot be managed on the web — you'll need to handle it in the subscription settings of the App Store / Google Play.

## FAQ

### Which payment methods are supported?

Payment is processed by Stripe, and which methods are available is **as shown on the checkout page** (options differ by region). Genspark does not store your full card number.

### The price I saw differs from the amount charged?

The pricing page shows the base price, and the actual charge may differ for these reasons:

- **Taxes**: Some regions add VAT / sales tax
- **Exchange rate**: Non-USD regions are converted at the issuing bank's exchange rate
- **Bank fees**: Some banks charge cross-border transaction fees

### I paid but my membership isn't active?

1. **Refresh the page** or sign out and sign back in
2. Confirm you're signed in to the same account you used to pay
3. Check your email for a subscription confirmation
4. Still not active → **contact support** and provide your payment receipt

### I got an error while upgrading?

- Card declined → Check your card balance or try a different card
- Prompt that you already have an active subscription → Check whether you've already subscribed through another channel
- 3D Secure verification failed → Complete verification per your bank's prompts and try again

### Can I cancel an annual plan partway through?

Yes. After cancellation, your benefits remain until the end of the current billing cycle. See [Manage & Change](https://page.gensparksite.com/manual/buddy-guides/v1/en/membership-manage.md) for details.
