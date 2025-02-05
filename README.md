- **Render Deployment:**
1. If you don’t have a **Render** account, click [**here**](https://dashboard.render.com) to create one.
2. Create a new web service.  
3. Choose **Public Git Repository**.  
4. In the field, enter `(https://github.com/kinghanstz/YESSIR-MD-V1)`.
5. Click **Connect**.  
6. Select the **Free Plan** if you don’t want to pay.
7. In the **Environment Variable** section, click **Add from .env** and copy the content below:

```env
PREFIX=.
AUTO_READ_STATUS=yes
AUTO_DOWNLOAD_STATUS=yes
PM_PERMIT=no
BOT_NAME=YESSER-MD
BOT_MENU_LINKS=YESSER
PUBLIC_MODE=yes
HEROKU=no
OWNER_NAME=HANS TECH
NUMERO_OWNER=255756530143
WARN_COUNT=3
STARTING_BOT_MESSAGE=yes
PRESENCE=1
PM_CHATBOT=no
SESSION_ID=zokk
ANTI_VIEW_ONCE="yes
ANTI_COMMAND_SPAM=yes
ANTI_DELETE_MESSAGE=yes
AUTO_REACT_MESSAGE=no
```
