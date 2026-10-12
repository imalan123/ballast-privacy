# Privacy Policy — Ballast

**Effective 11 October 2026.** Applies to the Ballast iPhone app (`com.alanjin.ballast`), its
Apple Watch app, its widgets, and its Siri and Shortcuts actions.

## The short version

Ballast has no account, no analytics, and no server. It makes no network connection of its
own. Your training log lives on your iPhone and, with iCloud sync (on by default, and off with
one switch), in **your** private iCloud account, which nobody else — including the developer —
can read.

## What Ballast stores, and where

| What | Where it lives | Who can read it |
|---|---|---|
| Your workouts, plans, exercises and notes | On your iPhone | You |
| The same data, while **iCloud sync** is on (the default) | Your private iCloud database | You |
| Today's workout, and sets you log on the watch until your iPhone receives them | Your paired Apple Watch, if you use the Watch app | You |
| Your settings and plate inventory | On your iPhone | You |
| A workout record, if **Apple Health** is on | Your Health app, on your iPhone | You, and any app you grant Health access to |

The developer of Ballast has no access to any of it. There is no server to send it to.

## What Ballast does not do

- **No account.** There is nothing to sign up for and no password to lose.
- **No analytics, no telemetry, no crash SDK, no advertising identifier, no tracking** of any
  kind, and no third-party SDKs — Ballast has zero third-party dependencies.
- **No ads**, in any tier.
- **No selling or sharing of your data.** There is no data to sell.
- **No network requests of Ballast's own.** The only network traffic is Apple's own: iCloud
  sync, if you turn it on, and the App Store when you buy or restore the one-time unlock.

## iCloud sync

On by default, and off with one switch in Me → iCloud sync. When it is on, Ballast uses Apple's
CloudKit to keep your training in your **private** iCloud database so your devices agree.
That database belongs to your Apple Account. Apple's handling of it is covered by
[Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

Turning sync off stops this iPhone syncing from the next launch. It does not delete what is
already in iCloud — you can remove that in iOS Settings under your name → iCloud.

## Apple Health

Optional, off by default, and asked for only when you turn it on in Me → Apple Health.

- Ballast **writes** one workout per finished session — the activity type, the start time,
  the end time, and an identifier linking it to the Ballast session it came from — into your
  own Health store.
- Ballast **reads nothing** from Health. It requests no read permission at all.
- No health data ever leaves your iPhone by way of Ballast, and none is transmitted to the
  developer or anyone else.

You can revoke this at any time in the Health app, and Ballast keeps working.

## Notifications

All reminders are scheduled and delivered locally by your iPhone. There is no push server
and no remote notification content. Ballast uses a silent iCloud push only to learn that
another one of *your* devices changed something; it carries no message and no data.

## Purchases

Ballast Pro is a one-time purchase handled entirely by Apple's In-App Purchase system.
Ballast never sees your payment details, your Apple Account, or your name — only whether
this device is entitled to the unlock.

## Exporting your data

Me → Export CSV writes a file containing your full training history and hands it to the
iOS share sheet. Where it goes from there is your choice. The file is written to a temporary
location the system reclaims.

The **Export Ballast Log** action in Siri and Shortcuts produces the same file and hands it to
the shortcut that asked for it. It only runs on an unlocked iPhone. What the shortcut does
with it is up to you.

## The Apple Watch app and widgets

The Watch app receives today's workout from your iPhone and sends back the sets you log on
your wrist, directly between your own two devices. Nothing goes through a server. The Home
Screen and Lock Screen widgets read your next workout from the app's storage on your iPhone.
A widget on the Lock Screen can be seen while the phone is locked. It shows the next
workout's name, how many exercises it has, and how many sessions you have done this week —
never weights or notes. The rest timer's Live Activity and its "Rest finished" notification
show the set you just logged on the Lock Screen too. Turn the notification off in
Me → Reminders, and the Live Activity off in iOS Settings → Ballast.

## Deleting your data

Deleting the Ballast app removes everything stored on the iPhone. If iCloud sync was on,
remove the iCloud copy in iOS Settings → your name → iCloud → Manage Account Storage.
Workouts already written to Apple Health are yours and stay there; delete them in the Health
app if you want them gone.

## Children

Ballast is not directed at children and collects nothing from anyone, including children.

## Changes

If this policy changes, the effective date above changes with it, and the change will be
described in the app's release notes.

## Contact

Questions about this policy: [developer.cloud26@gmail.com](mailto:developer.cloud26@gmail.com)
