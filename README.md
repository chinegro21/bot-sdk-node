# Wire™

![Wire logo](https://github.com/wireapp/wire/blob/master/assets/logo.png?raw=true)

This repository is part of the source code of Wire. You can find more information at [wire.com](https://wire.com) or by contacting opensource@wire.com.

You can find the published source code at [github.com/wireapp/wire](https://github.com/wireapp/wire).

For licensing information, see the attached LICENSE file and the list of third-party licenses at [wire.com/legal/licenses/](https://wire.com/legal/licenses/).

If you compile the open source software that we make available from time to time to develop your own mobile, desktop or web application, and cause that application to connect to our servers for any purposes, we refer to that resulting application as an “Open Source App”.  All Open Source Apps are subject to, and may only be used and/or commercialized in accordance with, the Terms of Use applicable to the Wire Application, which can be found at https://wire.com/legal/#terms.  Additionally, if you choose to build an Open Source App, certain restrictions apply, as follows:

a. You agree not to change the way the Open Source App connects and interacts with our servers; b. You agree not to weaken any of the security features of the Open Source App; c. You agree not to use our servers to store data for purposes other than the intended and original functionality of the Open Source App; d. You acknowledge that you are solely responsible for any and all updates to your Open Source App.

For clarity, if you compile the open source software that we make available from time to time to develop your own mobile, desktop or web application, and do not cause that application to connect to our servers for any purposes, then that application will not be deemed an Open Source App and the foregoing will not apply to that application.

No license is granted to the Wire trademark and its associated logos, all of which will continue to be owned exclusively by Wire Swiss GmbH. Any use of the Wire trademark and/or its associated logos is expressly prohibited without the express prior written consent of Wire Swiss GmbH.

## Wire Bot Python

Wire bot API is currently in alpha. This fork will be even more sparse. 

### Bot registration and creation

* Go to https://wire.com/b/devbot (not supported on mobile browsers, or Safari yet) and log in with your Wire credentials - "DevBot" is a bot to set up your developer account and create your own bots.

* Register to the bot service:
  - Email - This is a separate developer account, you can reuse the same email (if you've added an email to your Wire account)
  - Website (you can leave it blank: `https://`)
  - Developer description (e.g. “Pied Piper”)
  - Verification email
  - Account review by Wire
  - Account approved email

* Create a new bot (with DevBot, type `/help` for available commands)
  - Name - name of the bot, will also be used as the URL for the bot
  - Base URL (you can put: `https://[Your_Public_IP]:8050`)
  - Description
  - Copy and paste the RSA key (found in `./hello-bot/certs/pubkey.pem`) $ADD?

* Enable bot (with DevBot) - one of DevBot's commands to activate a bot.

### Todo

- Start work
