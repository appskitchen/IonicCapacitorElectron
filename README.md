# IonicCapacitorElectron

### 1. Created the app using - 
```
ionic start IonicCapacitorElectronApp blank --capacitor
```
### 2. Moved to the folder and changed the base path of `src/index.html` 
from `<base href="/" />` to `<base href="./" />`

### 3. Did an ionic build using
```
ionic build
```
### 4. Added electron using following command
```
npx cap add electron
```
### 5. Did an ionic build again
```
ionic build
```
### 6. copied file using
```
npx cap copy
```
###7. Synced (skiped once too)
```
npx cap sync

```
### 8. Run electron using
```
npx cap open electron
```
