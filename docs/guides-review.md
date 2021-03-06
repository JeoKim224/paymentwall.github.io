---
id: development-review
title: Project Review
sectionid: docs
permalink: guides/review-home
---

# Project Review

Your project is always in the sandbox environment when its status is not live, where only the [test payment](/sandbox/test-payment) method is allowed to be used.

You can submit your project for review by clicking the **SUBMIT FOR REVIEW** button.

<div class="docs-img">
	<img src="/textures/pic/guides/review/review-submit.png" style="max-width: 30%">
</div>

## Adjustments before going live

Paymentwall team will take a whole review of your project and set your project status according to [checklist](#checklist). You just need to do a few adjustments to assurance your project could work normally in live environment.

* API credentials

This mostly depends on the product you are using.

[Widget API](/integration/widget-home) and [checkout API](/integration/checkout-home) use same API credentials in both sandbox and live environment.

For merchants who are using [Brick](/integration/direct/brick-home), you will need to replace your brick test credentials to the live one.

* Disable test payment method

By default, we disable the test payment method on your project immediately once its status is changed to live. 

We recommend you to create another project under your Paymentwall account as staging project.
