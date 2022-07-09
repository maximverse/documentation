## Architecture

CycoPay is a platform that allows individuals and organizations to leverage our infrastructure in order to accept payments online.

In this documentation you will find APIs, Integration types and how to get started.

You can accept payments online using CycoPay in 2 ways

-   **Dashboard:** Use our dashboard in order to create payment links manually.

-   **API:** Use CycoPay's APIs to generate Modals, Payment Links or create your own Plugins (besides ours at github.com/cycopay).

![Architecture](/docs/docs/v2/arch.png)

## Basic Concepts

-   `Payment Links` A secure payment link that can be created from the dashboard or by API. Useful for applications that are built on frameworks such as VueJS. Note that every payment link expires 30 minutes after creation.
-   `Modal` A modal is a dialog box/popup window that is displayed on top of the current page. Developers prefer this type of integration since the whole process happens on the same page, it does not involve redirection.
-   `API Keys` Private Identifier used to identify vendors in order to access our APIs. It can be found in our dashboard.
-   `Webhooks` Webhook is an HTTP(S) endpoint used for pushing the notifications to your application. It will be invoked by CycoPay's servers to notify events of payments.

## Steps to accept payments
1. Sign up on CycoPay using the **Sign up** button in the top navbar.

    ![Signup for 100ms account](/docs/docs/v2/signup.png)
2. Once you're logged in to the dashboard, click on the `Gear`  Icon which represents settings.

    ![Signup for 100ms account](/docs/docs/v2/create-your-first-app.png)
3. Click on the **API** link. 

    ![Dashboard _ 100ms.png](/docs/docs/v2/select-starter-kit.png)
4. Confirm your password and click on the **Create API Key** button.

    ![Dashboard _ 100ms.png](/docs/docs/v2/personal-details.png)
5. Choose a deployment option. This could be 100ms or Vercel (based on the Starter Kit you are deploying)

    ![Video Conferencing Starter Kit](/docs/docs/v2/choose-your-deployment.png)
6. Enter a subdomain of your choice. Please avoid entering https/http/www or dots while entering the subdomain. Select a region closest to you and hit Continue. 

    ![choose subdomain](/docs/docs/v2/choose-subdomain.png)
7. Join or Invite someone to your deployed app with one of the roles: 

    ![join or invite](/docs/docs/v2/demo-your-app.png)

## Where should I start?
