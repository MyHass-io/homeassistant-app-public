# Home Assistant App: MyHass.io

## Installation

[![Open your Home Assistant instance and show the add app repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2FMyHass-io%2Fhomeassistant-app-public)

Follow these steps to get the app (formerly known as add-on) installed on your system:

1. Click the button above to add the repository to your Home Assistant instance.
2. In Home Assistant, go to **Settings** > **Apps** > **Install app**.
3. Open the context menu (three dots) and select **Check for updates**.
5. Find the "MyHass.io" app and click it.
6. Click on the "INSTALL" button.

## How to use

1. Visit [MyHass.io](https://myhass.io/) and create an account.
2. Choose a unique name for your instance and register it. This will become your personal access URL.
3. Once created, your subdomain will be ready to be linked to your Home Assistant. After creating your instance, you will receive:
   - **Node ID**
   - **Secret**

   These credentials are used to securely link your Home Assistant.

4. Configure the MyHass.io app  

   In Home Assistant:

   - Open **MyHass.io**
   - Go to the **Configuration** tab
   - Enter your **Node ID** and **Secret**
   - Save the configuration. The app will restart.

5. Start and enable the app  

   - Go to the **Info** tab  
   - Click **Start**  
   - Enable:
     - ✅ **Start on boot**  
     - ✅ **Watchdog**

5. Your Home Assistant is now available everywhere through your personal MyHass.io subdomain.

## Support

Got questions?

You could open an issue here on GitHub. Note, we use a separate
GitHub repository for each app. Please ensure you are creating the issue
on the correct GitHub repository matching the app.

- [Open an issue for the app: MyHass.io][myhassio-issue]


[myhassio-issue]: https://github.com/MyHass-io/homeassistant-app-public/issues