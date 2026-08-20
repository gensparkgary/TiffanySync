# Genspark Membership — Managing & Changing

> For Buddy Agent internal use.
> type: howto | feature: membership | keywords: upgrade, downgrade, cancel, renew, reactivate, credit usage, billing, manage
> User loop: Check current status → upgrade/downgrade/cancel → handle renewal and payment issues → review Credit usage

## Check Your Current Membership Status

Open the manage / pricing modal ([click here to open the plans page directly](https://www.genspark.ai/me?open_pricing=help_center), or get there via the account menu in the bottom-left corner). The top shows your current plan and **auto-renewal date**; any scheduled downgrade is also flagged here. The adjacent **manage menu** offers shortcuts to upgrade, downgrade, cancel, change billing, and more.

![Entry point: account menu in the bottom-left corner → open the manage / pricing modal](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35768/2b677b86.png)

![The top of the manage modal shows the current plan and auto-renewal date](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35768/37839973.png)

> The exact Credit allowance and price for each tier are as shown on the page — we don't hardcode them here.

## Upgrade

Upgrade = switch to a tier with a higher Credit allowance, or move from Plus to Pro.

1. Open the pricing / manage modal
2. Pick the target tier and click upgrade
3. The confirmation window shows: the amount due today, the Credits granted immediately after upgrading, and the next billing date
4. Confirm and pay

![Upgrade confirmation modal: the amount due today (prorated by remaining days), the full monthly difference in Credits granted immediately, and the next billing date](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35768/c8d75dfb.png)

> An upgrade takes effect **immediately**. Credits are calculated in one of two ways: upgrading **within the same billing cycle** (e.g. moving up a tier on a monthly plan) → keeps your existing Credits and immediately grants the **full monthly difference** for the current month (not prorated by day) — monthly plans get this one-time grant for the current month, annual plans get the new tier's amount each remaining month; upgrading **across billing cycles** (e.g. monthly → annual) → your old unused Credits are **forfeited**, and the **full amount** of the new plan is granted immediately. What's prorated by remaining days is the **amount you pay today**, not the Credit quantity; the amount due today and the quantity granted are **as shown in the upgrade confirmation modal**. For the full mechanics, see [Credit Mechanics — How Credits are calculated on upgrade and downgrade](https://page.gensparksite.com/manual/buddy-guides/v1/en/membership-credits.md).

## Downgrade

Downgrade = switch to a lower tier, or move from Pro to Plus.

1. Open the pricing / manage modal
2. Pick the target tier and click downgrade
3. Confirm

> A downgrade does **not** take effect immediately — it's scheduled to apply after the current billing cycle ends; until then you keep all the benefits of your current tier.
>
> **Credit note**: Once the downgrade takes effect, your allowance resets to the new tier, and any remaining Credits from the old tier **do not carry over** — we recommend using up your Credits for the month before downgrading.

**Cancel a scheduled downgrade**: Changed your mind? You can cancel a pending downgrade from the manage menu / status area.

## Switch Between Monthly / Annual Billing

To switch from monthly to annual (annual works out cheaper per month): open the modal, switch to annual, and complete payment through the upgrade flow on your current tier (the system treats "switching to annual" as an upgrade).

## Cancel Subscription

1. Open the manage modal → Cancel subscription
2. Confirm

> After canceling, your benefits **remain active until the end of the current billing cycle** — they don't expire immediately. You can reactivate anytime before they lapse.

## Reactivate

If you've canceled but are still within the current billing cycle, you can reactivate from the manage menu to restore auto-renewal once the cycle ends — at no extra charge.

## Renew After Expiration

If your subscription has expired, open the pricing modal ([click here to open the plans page directly](https://www.genspark.ai/me?open_pricing=help_center)), pick the tier you want, and resubscribe (complete payment via the [subscription flow](https://page.gensparksite.com/manual/buddy-guides/v1/en/membership-subscribe.md)). Expired accounts will see upgrade / resubscribe entry points.

## Payment Failure / Subscription Expired

When auto-billing fails or your subscription expires, the page shows a persistent notice with an entry point to **update your payment method**. We recommend updating your payment details as soon as possible to avoid an interruption to your benefits. For issues like incorrect charges or refunds → see the [refund / billing section of the subscription flow](https://page.gensparksite.com/manual/buddy-guides/v1/en/membership-subscribe.md) or contact support.

## Change Payment Method / View Invoices

From the manage menu or billing management entry point, you can update your payment details and view past invoices and receipts.

## Membership Is Non-Transferable

A membership subscription is tied to an individual account and can't be transferred between accounts. If you need to switch accounts, cancel on the old account and resubscribe on the new one.

## Review Credit Usage

Go to the [Credit usage page](https://www.genspark.ai/credit-usage) (also reachable via the account menu in the bottom-left corner) to see your remaining / used Credits, your consumption broken down **by AI feature / product**, your consumption history, the start and end dates of your subscription and this month's top-up cycle, and the expiration date of each batch of Credits. For the full mechanics, see [Credit Mechanics](https://page.gensparksite.com/manual/buddy-guides/v1/en/membership-credits.md). (Your specific **auto-renewal date** is shown at the top of the manage modal — see above.)

## FAQ

### Can I still use my Credits after canceling?

Yes. Your benefits remain active until the end of the current cycle, and you can use your Credits normally during that time; any unused Credits expire once the cycle ends.

### Auto-renewal charged me twice?

Check whether you have an active subscription on more than one channel and cancel the extra one; for an incorrect charge that needs a refund → contact support.
