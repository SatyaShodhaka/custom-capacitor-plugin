**Clone the Repository*
Clone\ the\ project\ repository\ to\ your\ local\ m ` bash git clone https://github.com/your-repo/custom-capacitor-plugin.git cd custom-capacitor-plugin


Install the required dependencies using `pnpm`:
```
pnpm install
```
Install the custom plugin as a package:

```
pnpm install /custom-capacitor-plugin/crepe-plugin
```

Sync the plugin with android:

```
npx cap sync android
```

Open in android studio:

```
npx cap open android
```
