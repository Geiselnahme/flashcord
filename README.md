# This is Flashcord.
## The most advanced Discord Theme to date.
![](https://raw.githubusercontent.com/SiriusBYT/flashcord/main/FC-PREVIEW/FC-LMH.gif)
# Flashcord is all about Maximising your Chat Space.
![](https://raw.githubusercontent.com/SiriusBYT/flashcord/main/FC-PREVIEW/FC-DKM.gif)
# While also being the pinacle of Customisable Eye Candy.
![](https://raw.githubusercontent.com/SiriusBYT/flashcord/main/FC-PREVIEW/FC-CBGR.gif)
## Notice: Flashcord is still in very early Alpha.

# ⬇️ Installing Flashcord Stable
To install Flashcord, for [Replugged Users, simply click here](https://replugged.dev/install?identifier=SiriusBYT/flashcord&source=github).
You can install Flashcord for BetterDiscord and Vencord this way, add the following line to your client's QuickCSS and apply it.
### Please use Flashcord with Replugged if you can. Flashcord will never fully support BetterDiscord or Vencord due to plugin shenanigans. Worst of all, certain clients introduces weird bugs that seem to be an absolute nightmare to fix, please stay away from clients other than Replugged if you can.
```
@import url("https://raw.githubusercontent.com/SiriusBYT/flashcord/main/src/main.css");
```
The instructions to install Flashcord SID are the same across all clients. Check the section about SID to learn more and how to install Flashcord SID instead.

After that, make sure to read the Instructions and Tips tab to make sure you get the full Flashcord Experience!


## 🔄️ Flashcord Version Status
🦺 Flashcord Stable: [aSTB-230714_HF1] | **6 Feature Updates Behind SID.** | 🌐 Root Code Base: aSID-230714-HF1

🔥 Flashcord SID: [aSID-230720] | **6 Days without an Emergency Hotfix Update.**

## 💡 Instructions and Tips
ℹ️ It is not recommended to use Flashcord on Low-End Systems, you could, but in that case, disable animations, transitions and especially blur with the variables provided.

Flashcord recommends using **Discord Canary** as it was made on it.

### ⚠️ Flashcord requires the "Channel Emojis" Discord Experiment for the best experience.
Flashcord can work without this experiment, however without it, Flashcord looks more dead and less full of life, it is very recommended to enable that experiment. Make sure to set it to "Treatment 2", not 1.

### 🛑 NOTICE ABOUT CUSTOM IMAGE BACKGROUNDS: Requires "LegalDiscordBypass" or Discord Nitro
Due to the complexity of Flashcord, it is better to seperate the Custom Background Image Theme into another one, problem is that the only other "it just works" theme is a Discord Nitro theme. 
Using the plugin [LegalDiscordBypasses by @loneweeb.tsx](https://replugged.dev/install?identifier=dev.tharki.LegalDiscordBypasses) is thus necessary if you wanna use said feature without Nitro.
![](https://raw.githubusercontent.com/SiriusBYT/flashcord/main/FC-PREVIEW/DiscordCanary_6RUcvA0asO.png)
Choosing any of those themes will activate the Custom IMG mode. It is recommended to use a dark themed one for visibility reasons.
Notice: Since aSID-230720, this is no longer a problem thanks to the Apperance Tab redesign.

### 🎉 Flashcord Chat Effects

Adding any of these URLs at the end of your Discord message will add a special effect to your message. These also work for attachements.
```
(aSID-230714+) Rainbow Text Effect: http://flashcord/rainbow
(aSID-230714+) Small Text Effect: http://flashcord/small
(aSID-230714+) Shake Effect: http://flashcord/shake
(aSID-230714+) Dramatic Effect: http://flashcord/dramatic

(aSID-230715+) Red Background Message: http://flashcord/background/red
(aSID-230715+) Green Background Message: http://flashcord/background/green
(aSID-230715+) Blue Background Message: http://flashcord/background/blue

(aSID-230717+) Loud Effect: http://flashcord/loud
(aSID-230717+) Quiet Effect: http://flashcord/quiet

(aSID-230719+) Rainbow Shadow Effect: http://flashcord/rainbow-shadow
(aSID-230719+) Spin Effect: http://flashcord/spin
(aSID-230719+) Fade from Bottom Effect: http://flashcord/fade-bottom
(aSID-230719+) Splash Text Effect: http://flashcord/splash

You can use markdown to hide the link to non-flashcord users. Example: [This message has a Flashcord Chat Effect. Install it to view the effect.](http://flashcord/rainbow)
```
If these effects cause way too much lag, **consider disablming them using the variable provided below**.

### 🔁 User Variables
The following variables can be changed to improve your Flashcord Experience. The values specified for each variable are their default values. 

If you are running Flashcord SID, your variables **must be after the "@import" line**.
```
* {
  /* aSID-230707+: Control Blur Intensity, recommended to set to 0px on low end systems. */
  --BlurInt-Big: 16px;
  --BlurInt-Med: 8px;
  --BlurInt-Sma: 4px;

  /* aSID-230702+: Control the Transition Speed of Elements. Set to 0 to Disable.*/
  --AnimMult-Fast: 1;
  --AnimMult-Normal: 1;
  --AnimMult-Slow: 1;

  /* aSID-230704+: Self Explanatory, set to 0 to Disable. [!] DOES NOT DISABLE CHAT EFFECTS */
  --Enable-Animations: 1;

  /* aSID-230703+: Custom Background Customisation */
  --CustomBGR-IMG: url("https://sirio-network.com/flashcord/bgr-test.jpg");
  --CustomBGR-Filter: blur(16px) brightness(0.5);

  /* aSID-230704+: If you are having severe issues in the friends tab because you have too many friends, set this to block */
  --Friend-Redesign: flex; 

  /* aSID-230706+: Setting this to 0 disables most of the Flashcord Swag for specific users. */
  --Brand-Mode: 1;

  /* aSID-230712+: High End Systems Only. Puts a bunch more random crap that looks cool but blows computers up */
  --IridescentMode: 0;

  /* aSID-230714+: Enable Chat Effects, disabling them will stop their animations. (Set to 0 to disable) */
  --Enable-ChatEffects: 1;

  /* aSID-230715+: See the Flashcord Benchmark Channel on the SGN Discord Server for more information. This is not very useful honestly. */
  --Flashbench: 0;

  /* aSID-230718+: Edit the Server Unread Glow/Shadow, set to 0 to disable it if it distracts you too much */
  --Server-Glow: 1;
  --Server-Glow_Color: blue;

  /* aSID-230718+: Edit the Channel Unread Glow/Shadow, set to 0 to disable it if it distracts you too much */
  --Channel-Glow: 1;
  --Channel-Glow_Unread_Color: rgba(0,0,255,0.5);
  --Channel-Glow_Mention_Color: rgba(255,0,0,0.5);

  /* aSID-230720+: IridescentMode starting from aSID-230720 no longers disables animations when you're not hovering Discord, set the variable to 1 to re-enable them. */
  --Disable-Idle_Optimizations: 0;

  /* aSID-230720+: Setting this to 0 causes most warnings such as "Flashcord is in Alpha; X Mode is unfinished" to get removed.*/
  --Allow-Warnings: 1;
}
```

### 💉 Plugin Support

Flashcord supports many pretty cool Replugged Plugins such as:

[Platform Indicators by @puyodead1](https://replugged.dev/install?identifier=me.puyodead1.PlatformIndicators)

[Staff Tags (in Crown Mode) by @puyodead1](https://replugged.dev/install?identifier=me.puyodead1.StaffTags)

[Statistic Counter by @harley.0](https://replugged.dev/install?identifier=griefmodz/statistic-counter&source=github)

[Badges Everywhere by @12944qwerty](https://replugged.dev/install?identifier=dev.kingfish.BadgesEverywhere)

[ShowHiddenChannels by @loneweeb.tsx](https://replugged.dev/install?identifier=dev.tharki.ShowHiddenChannels)

[ReMessageLogger by @sammcheese](https://replugged.dev/install?identifier=SammCheese/ReMessageLogger&source=github)

[Channel Typing by @asportnoy](https://replugged.dev/install?identifier=dev.albertp.ChannelTyping)

Plugin support ranges from simple alignment fixes to complete visual overhaul.

More plugins are expected to be supported in the future.

## 🔥 Switching from Stable to Flashcord SID
Flashcord SID is the very much unstable version of Flashcord. **Unlike Flashcord Stable, who's getting updates every week, SID gets updated every night** on average around 21:30 UTC+01.

⚠️ You cannot decide if you wanna update or not with Flashcord SID, it updates as soon as your client fetches for Flashcord's code.
### It is SERIOUSLY NOT recommended to switch to SID. The Closed Alpha testers can tell you that when aSID-230703 came out, everyone died in pain and agony.
To switch to Flashcord SID, please **Paste the Following Line** into your **Quick CSS** and then click on **"Apply Changes"**
```
@import url("https://sirio-network.com/flashcord/fc-sndl.css");
```
To force update Flashcord SID, open the **DevTools** (CTRL + SHIFT + I), head over to the **Network** Tab, then check **"Disable Cache"** and click on **"Apply Changes"**.

ℹ️ Make sure to also not have Flashcord Stable still enabled after switching to SID to prevent code conflicts.

## ✅ Platform Compatibility

| Platform     | Replugged                 | BetterDiscord                                    | Vencord                                          |
|:-------------|:--------------------------|:-------------------------------------------------|:-------------------------------------------------|
| 🪟 Windows   | ✅ Perfect Compatibility | ⚠️ Missing & Incompatible Plugins, seems fine    | ⚠️ Missing Plugins, some compatible, seems fine |
| 🍎 MacOS     | ☑️ Seems Perfectly Fine  | ❓Unknown Compatibility                          | ❓Unknown Compatibility                         |
| 🐧 GNU/Linux | ☑️ Seems Perfectly Fine  | ⚠️ Missing & Incompatible Plugins + Weird Issues | ❓Unknown Compatibility                         |

| 📱 Enmity (iOS)     | ☎️ Android             |
|:--------------------|:------------------------|
| [⛔ Color Theme Only](https://github.com/SiriusBYT/flashcord-ios) | ⛔ Unsupported for now |

## 💾 Flashcord Archive
Older versions of Flashcord are available on the [Sirio Network Website](https://sirio-network.com).
To use an older version of Flashcord, add this to your QuickCSS while replacing [Branch] by either STB (Stable) or SID and [Version Number].
```
@import url("https://sirio-network.com/flashcord/archive/[Status][Branch]-[Version Number].css");

Valid Example:
@import url("https://sirio-network.com/flashcord/archive/aSID-230715.css");
```

### Available Versions
#### Flashcord Stable Archive
-  aSTB-230714
-
  -  aSTB-230714_HF1

#### Flashcord SID Archive.
-  aSID-230720
-  aSID-230719
-  aSID-230718
-  aSID-230717
-  aSID-230716
-  aSID-230715
-  aSID-230714
-
  -  aSID-230714_HF1
-  aSID-230713
-  aSID-230712
-  aSID-230711

  -  aSID-230711_HF1
-  aSID-230710
-  aSID-230709
-
  -  aSID-230709_HF1
-  aSID-230708
-  aSID-230707
-  aSID-230706
-  aSID-230705
-
  -  aSID-230705_HF1
-  aSID-230704
-  aSID-230703
-
  -  aSID-230703_HF1
  -  aSID-230703_HF2
  -  aSID-230703_HF3
  -  aSID-230703_HF4
  -  aSID-230703_HF5
-  aSID-230702
-  aSID-230701
-  aSID-230630
-  aSID-230629
-
  -  aSID-230629_HF1
  -  aSID-230629_HF2
-  aSID-230628
-
  -  aSID-230628_HF1
-  aSID-230627
-  aSID-230626

If for some reason you wanna go even further back, way back before Flashcord's rewrite, check out [Flashcord Legacy](https://github.com/SiriusBYT/flashcord-legacy). It's not a good idea though.

##### [Flashcord](https://github.com/SiriusBYT/flashcord) © 2023 by [SiriusBYT](https://sirio-network.com) is licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/).
