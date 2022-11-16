---
title: "Configuring S.M.A.R.T. Service"
description: "This article provides information on S.M.A.R.T. service screen settings."
weight: 40
aliases: /scale/scaleuireference/dataprotection/smartservicesscreen/
tags:
 - scalesmarttests
 - scaleservices
---

{{< toc >}}

Use the **Services > S.M.A.R.T.** screen to configure when S.M.A.R.T. tests run and when to trigger alert warnings and send emails.

![ServicesSMARTScreen](/images/SCALE/22.02/ServicesSMARTScreen.png "Services S.M.A.R.T. Options")

Click the <i class="material-icons" aria-hidden="true" title="Configure">edit</i> **Configure** icon to open the screen.

Enter the time in minutes [smartd](https://www.freebsd.org/cgi/man.cgi?query=smartd&manpath=FreeBSD+11.1-RELEASE+and+Ports) to wake up and check if any tests are configured to run in **Check Interval**.

Select the power mode.

Set the temperatures that trigger alerts in **Difference**, **Informational** and **Critical**.

Click **Save** after changing any settings.

Start the service.

{{< taglist tag="scalesmarttests" limit="10" >}}