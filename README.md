# JunkCoin Mining Setup

## Hardware Setup

1. **Download the Bin File**  
   - Download the `.bin` file corresponding to your ESP device type from our [GitHub repository](#).

2. **Connect Your ESP Device**  
   - Connect your ESP device to a computer via USB.

3. **Flash the ESP Device**  
   - Flash the ESP with the bin file using an online flasher like **[ESPTool](https://espressif.github.io/esptool-js/)**.
   - Select a baud rate of **115200** and click the **Erase** button.
   - Select your `.bin` file and set the flash address to 0x0000
   - Click the **Program** button

4. **Power the Device**  
   - Once programmed, unplug your ESP device from the computer and connect it to a power source.

5. **Watch the Example Video**  
   - Follow our example video for guidance [here](https://www.youtube.com/watch?v=25Znu_Eb8ks).

## WiFi Connection

1. **Power Your ESP Device**  
   - Plug your ESP device into a power source.

2. **Connect to JunkCoin WiFi**  
   - Open your phone or computer's WiFi settings and connect to the **JunkMiner** WiFi network.  
   - Password: **MineYourJunk** (Old binaries password is hoarder420).

3. **Open Configuration Page**  
   - Open a web browser and go to **192.168.4.1**.

4. **Enter Credentials**  
   - Enter your WiFi name (SSID), WiFi password, and your API key when prompted.

5. **Connect**  
   - Click **Connect** to start collecting Junk!

6. **Wifi Access Point**
   - If the JunkMiner wifi access point disappears after connecting, then it was a success. Otherwise retry.

## Internet Verification and Wallet Connection

- Your ESP device should be connected to the internet. Verify by opening the **JUNK** console [here](https://junkcoin.lol/console).
- Connect the **Solana** wallet you provided when applying for a **Hoarder** role.
- Give your Junk Collector **1 hour** to communicate with the **JUNK** servers. You will see an **"ALIVE"** status at the top of the page.

## Contributions

The main display assets for the lilygo were created by **Milan Maheshwari** from the Figma Community.  
These assets are licensed under **CC BY 4.0**.
