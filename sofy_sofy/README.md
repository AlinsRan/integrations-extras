# SOFY

## Overview

SOFY is a no-code platform for creating automated tests on mobile Apps. Users can integrate with their CI/CD pipelines to execute tests on real devices and view the results of their functional tests along with performance metrics.

With this integration, you have deeper insight into your testing process by visualizing key metrics and trends such as load time, network, memory utilization and CPU. The out-of-the-box dashboard provides real-time visibility into your SOFY test results, enabling you to monitor and analyze performance over time, and make data-driven decisions to improve overall software quality.

## Data Collected
### Metrics

See [metadata.csv][8] for the full list of metrics provided by this check.


## Setup
Get set up in just a few steps:

1. Go to your [Datadog Integrations page][1] and click on the SOFY tile. Then go to the **Configuration** tab and click **Install Integration** at the bottom.

1. Click **Connect Accounts** to begin authorization of the SOFY integration from the Login page in SOFY.

3. Log in to [SOFY][2]: Start by logging in to SOFY and navigating to the Account Setting page by selecting Account -> Account Setting from the left-hand navigation menu.

4. Connect Datadog to your SOFY Account: Once on the Account Setting page, select the [Integration tab][3] and locate the Datadog tile. Click the "Connect" button to begin the integration process.

5. Follow OAuth Steps: SOFY will prompt you to follow a series of OAuth steps to authorize the integration with Datadog. Follow these steps carefully, making sure to grant the necessary permissions to allow SOFY to send data to Datadog.

6. Enable Datadog Monitoring: Once the integration is complete, navigate to the App Manager page by selecting it from the left-hand navigation menu. From there, click on the monitoring tab on the right-hand side of the page. Enable Datadog monitoring for the selected app by toggling the appropriate switch.

7. SOFY will now begin sending data to Datadog after each run in the selected app, allowing you to monitor and analyze the results in real time.


## Uninstallation
* Ensure that all API keys associated with this integration have been disabled by searching for SOFY on the [API Keys management page][4] in Datadog.

## Support
Need help? Contact [SOFY support][5].

## Further Reading
Additional helpful documentation, links, and articles:
* [Blog Post][6]
* [Documentation][7]


[1]: https://app.datadoghq.com/account/settings#integrations
[2]: https://portal.sofy.ai
[3]: https://portal.sofy.ai/app/user-settings?selectedTab=integration
[4]: https://app.datadoghq.com/organization-settings/api-keys
[5]: https://support.sofy.ai/support/tickets/new
[6]: https://sofy.ai/blog/
[7]: https://docs.sofy.ai
[8]: https://github.com/DataDog/integrations-extras/blob/master/sofy_sofy/metadata.csv