---
# This file is licensed under the MIT License (MIT) available on
# http://opensource.org/licenses/MIT.

id: mycelium
title: "Mycelium"
titleshort: "Mycelium"
compat: "mobile android"
level: 3
platform:
  - mobile:
    name: mobile
    os:
      - name: android
        text: "walletmyceliumwallet"
        link: "https://play.google.com/store/apps/details?id=com.mycelium.wallet"
        source: "https://github.com/mycelium-com/wallet"
        screenshot: "mycelium.png"
        features: "bech32 hardware_wallet legacy_addresses segwit"
        check:
          control: "checkgoodcontrolfull"
          validation: "checkfailvalidationcentralized"
          transparency: "checkgoodtransparencydeterministic"
          environment: "checkpassenvironmentmobile"
          privacy: "checkpassprivacybasic"
          fees: "checkpassfeecontroldynamic"
        privacycheck:
          privacyaddressreuse: "checkpassprivacyaddressrotation"
          privacydisclosure: "checkfailprivacydisclosurecentralized"
          privacynetwork: "checkpassprivacynetworksupporttorproxy"
---
