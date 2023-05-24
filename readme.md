## Description
**What is RDP?**<br>
* RDP (Remote Desktop Protocol) is a network communication protocol developed by Microsoft, which allows users to connect to another computer from a remote location

**How long does this RDP stay active?**<br>
* This RDP stays active for up to 2 hours<br>

## How to use it?

#### First Step
1. Press the **Fork** button  
2. Login or signup to ngrok: https://ngrok.com
3. Now visit here for token: https://dashboard.ngrok.com/auth/your-authtoken

#### Second Step
1. In your forked repo: **Go to Settings > Secrets and variables > Actions > New repository secret**
2. In the Name section, enter this text **TOKEN**
3. In the Secret section, enter your **ngrok token**
4. Then press **Add secret**
5. Now go to **Actions > RDP > Run workflow**
6. Refresh the page and go to **RDP > build** option
7. You'll get IP, Username & Password from **Connect to RDP** section

#### Third Step
1. Search **Remote Desktop Connection** and open
2. Put IP without **tcp://** and click **Connect**
3. Enter Username and Password
