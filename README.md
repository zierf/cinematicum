# Cinematicum


## Install Ionic

```SH
npm install -g @ionic/cli
ionic --version
```

## Project initialization

```SH
ionic start "cinematicum" blank --project-id=cinematicum --type=angular --capacitor
```


## Build project

```SH
ionic build [--prod]  [--watch]
```

## Serve project

```SH
ionic ssl generate
ionic serve [--prod] [--ssl] [--external]
```


## Android

### Build for Android

```SH
ionic capacitor build android [--prod]
```

### Run for Android

```SH
ionic capacitor run android --livereload --external [--prod]
```

## iOS

### Build for iOS

```SH
ionic capacitor build ios [--prod]
```

### Run for iOS

```SH
ionic capacitor run ios --livereload --external [--prod]
```
