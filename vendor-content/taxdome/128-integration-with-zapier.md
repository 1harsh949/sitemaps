<!-- Source: https://help.taxdome.com/article/128-integration-with-zapier (official TaxDome help page, mirrored 2026-06-06 for KB ingestion) -->

# Zapier integration

## Zapier, explained

TaxDome doesn't have a public API, but you can use Zapier to integrate your firm's account with other applications. Zapier allows two apps that don't have native integration to interact with each other. TaxDome supports Zapier, so the application you want to integrate with TaxDome through Zapier should also support it.

With Zapier integration, you can sync TaxDome accounts and contacts with your favorite apps, so your data stays updated without entering it twice. Make updates in one place, and all connected apps will be updated automatically.

We've already created Zapier templates of popular integrations with TaxDome. Please check the TaxDome Integration page on Zapier.

To check compatibility with the application you're using, visit the Apps Zapier page and search for the application.

To make the integration work, you need to:

1. Create a Zapier account
2. Connect it to your TaxDome account
3. Make a Zap

A Zap is a connection between two applications, say between TaxDome and Google Spreadsheets, TaxDome and Google Forms, etc. The main thing to understand when you create a Zap is the two-part logic: you set a trigger (a condition), and when it is met, certain actions are executed.

TaxDome can be both a trigger (condition) application and an application in which the event is performed (action).

## Connect to Zapier

Only a firm owner or admin can connect the account with Zapier. To do so:

1. Navigate to **Settings > Integrations** from the sidebar menu.
2. Go to the **Zapier** tab.
3. Click **Connect**.
4. Log in to your Zapier account, then accept the invite to use the TaxDome app on Zapier by clicking **Accept invite and build a Zap**.

You should make the first Zap to complete the TaxDome integration with Zapier.

> **Note:** Connecting to Zapier will be reflected on the Activity feed page.

## Make Zaps

The creation of Zaps differs depending on what should be achieved:

- when TaxDome acts as an application in which a condition (trigger) must be met
- when, because of a met condition in another application, an action is performed in TaxDome

You can find detailed examples in the respective articles, but the general scheme for creating a Zap is as follows:

1. Start creating a Zap from the home page.
2. Configure the trigger which will be executed:
   - Select the application.
   - Select the available trigger event.
   - Connect your account to the application.
   - Configure the needed conditions.
   - Test the first part of the integration.
3. Configure the action which will be performed:
   - Select the application.
   - Select the available action event.
   - Connect your account to the application.
   - Configure the needed conditions.
   - Test the second part of the integration.
4. Publish a Zap and try the integration by executing the condition configured as a trigger and see if it produces the desired action.

## Disconnect from Zapier

If your Zapier account has changed or you don't want to use it anymore, disable the connection with your previous account.

> **Note:** Once you have disconnected, all your existing Zapier connections that use the TaxDome app will stop working.

1. Navigate to **Settings > Integrations** from the sidebar menu.
2. Go to the **Zapier** tab.
3. Click **Revoke**.

---
*Source: [Zapier integration](https://help.taxdome.com/article/128-integration-with-zapier) — official TaxDome documentation.*
