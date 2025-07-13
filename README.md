import { CapacitorConfig } from '@capacitor/cli';

const config: CapacitorConfig = {
  appId: 'app.lovable.a5659a6da5594370b7668d12709baa43',
  appName: 'hospital-sync-plus',
  webDir: 'dist',
  server: {
    url: 'https://a5659a6d-a559-4370-b766-8d12709baa43.lovableproject.com?forceHideBadge=true',
    cleartext: true
  },
  plugins: {
    SplashScreen: {
      launchShowDuration: 2000,
      backgroundColor: '#ffffff',
      androidSplashResourceName: 'splash',
      androidScaleType: 'CENTER_CROP',
      showSpinner: false,
      androidSpinnerStyle: 'large',
      iosSpinnerStyle: 'small',
      spinnerColor: '#0ea5e9',
      splashFullScreen: true,
      splashImmersive: true
    }
  }
};

export default config;# xy
