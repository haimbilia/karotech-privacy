# Privacy Policy for Karo Pulse

_Last updated: 8 May 2026_

Karo Pulse ("the app") is developed by Karo Tech ("we", "us"). This policy describes how the app handles your information.

## Summary

Karo Pulse does not collect, transmit, or share any personal data with us or any third party. Everything the app stores stays on your device.

## What the app stores on your device

To work, Karo Pulse saves the following information locally in the app's private storage:

- The Bluetooth MAC address and name of the controller you choose to pair with the app
- The MAC address and friendly name of the PC or PCs you want to wake
- Your Wi-Fi-related preferences (e.g. the wake target ports)
- Optional Pulse hardware connection details (IP address, port) if you use a Pulse ESP32 device

This information is stored only on your device, in storage private to the app. We do not have access to it. We do not transmit it to any server we operate.

## What the app sends over the network

When the app wakes your PC, it sends a "magic packet", a short, standard Wake-on-LAN broadcast, over your local Wi-Fi network to the PC's MAC address. This packet does not leave your local network and is not sent to any server.

If you use the app's test mode with the Pulse Windows companion application, the app also exchanges short text-based control messages with the Windows app over your local network. These messages stay on your local network and are not sent to any server we operate.

The app does not contact any analytics service, advertising network, crash-reporting service, or any other third-party server.

## Permissions and how they are used

Karo Pulse requests the following Android permissions strictly for the purposes described:

- **Bluetooth scan and connect**, to discover and detect your saved controller. The app does not use Bluetooth scan results to determine your physical location.
- **Internet, network state**, to send Wake-on-LAN packets and to communicate with the Pulse Windows companion app on your local network only.
- **Foreground service (connected device)**, to keep Bluetooth detection running while the app is in the background, so your PC wakes when your controller is in range. While running, the app shows a persistent notification you can tap to disarm at any time.
- **Post notifications**, to show the persistent "armed" status notification described above and to confirm wake events.

## Data that Google Play may collect

Independent of the app, Google Play may collect anonymous installation, crash, and usage statistics for any app distributed through the Play Store. We can see only aggregate, anonymized statistics through the Play Console; we do not receive any personally identifying information about you. You can review Google Play's privacy practices at https://policies.google.com/privacy.

## Children

The app is not directed at children under 13. We do not knowingly collect any data from anyone, including children.

## Deleting your data

Because all data Karo Pulse stores is on your device, you can remove it completely by uninstalling the app. There is nothing for us to delete on our side because we do not store anything.

## Changes to this policy

If we change this policy in any material way, we will update the "Last updated" date above and, where appropriate, note the change in the app's release notes.

## Contact

If you have any questions about this policy or about how the app handles your information, contact us at: info@karotech.io
