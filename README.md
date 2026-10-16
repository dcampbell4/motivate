# Mamba Mode

A tough-love phone app for workout and no-sugar streaks, inspired by the competitive drive of Michael Jordan and Kobe Bryant.

- **Workout streak:** a day counts if you do 2 drills or 1 gym session.
- **No-sugar streak:** a day counts only if you check in "clean". That means no sweets, desserts, soda, or sweet coffee drinks. Fruit is fine.
- **Ghost You:** your best streaks and last week's numbers are the opponent you're playing against.
- **Excuse button:** pick your excuse and get roasted.
- **Craving button:** a 10-minute timer to outlast the urge.
- **Weekly weigh-ins:** a progress bar and chart toward your goal weight.

Everything is saved on your phone. There's no account and no server.

## 1. Put it online (one time, about 2 minutes)

1. On GitHub, open this repo and go to **Settings → Pages**.
2. Under **Build and deployment**, set Source to **Deploy from a branch**.
3. Pick the branch that has this code (`main` once it's merged) and the folder **/ (root)**, then click **Save**.
4. After a minute or two, your app is live at `https://dcampbell4.github.io/motivate/`.

## 2. Put it on your iPhone

1. Open that link in **Safari**.
2. Tap **Share** (the square with an arrow), then **Add to Home Screen**.
3. If you see an **Open as Web App** switch, **turn it off**. That way the reminder links and the Home Screen icon share the same streak data.
   On older iOS versions without that switch, use a regular Safari bookmark instead of the Home Screen icon.

## 3. Set up the buzzes (iPhone Shortcuts)

In the app, open **Setup → Phone reminders**. It lists your 5 links (9:30, 11:30, 2:00, 4:00, and a 6:00 PM gym nudge) and gives step-by-step instructions. Each one is a **Time of Day** automation set to **Run After Confirmation** with an **Open URLs** action.

## Make it yours

All the trash talk lives at the top of `index.html`, in the `MSG`, `EXCUSES`, and `DRILLS` lists. You can edit, add, or delete lines in plain English.

## Back up your streaks

Your data lives only on your phone. Every so often, go to **Setup → Copy backup** and paste the result into Notes.
