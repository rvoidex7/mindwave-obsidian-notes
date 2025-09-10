tags: #reactnative #info 

npx react-native start
npx react-native run-android
npx @react-native-community/cli init ProjeAdin
npm install kutuphane-adi
adb logcat "*:S" ReactNativeJS:V


# Hard Reset
- ```
    cd android
    ./gradlew clean
    ```
    
    (Windows'ta `gradlew.bat clean`)
    
- **Metro Bundler Önbelleğini Temizle:** React Native'de, Metro'nun kendi önbelleği de sorunlara yol açabilir. Bu komut, Metro önbelleğini temizler.
    
    Bash
    
    ```
    npm start -- --reset-cache
    ```
    
- **Yükleyici Önbelleklerini ve Geçici Dosyaları Sil:** Bu, en agresif temizleme yöntemidir. `node_modules` ve kilit dosyalarını silip, tüm bağımlılıkları yeniden kurar.
    
    Bash
    
    ```
    rm -rf node_modules
    rm -rf package-lock.json
    npm install
    ```
    
    (Windows'ta `del /s /q node_modules` gibi komutlar kullanman gerekebilir)
    
- **Native Derleme Önbelleklerini Temizle:** Android Gradle'ın derleme önbelleklerini temizlemek için, Android klasörü içindeki `build`, `.gradle` ve `app/build` gibi dizinleri silmek de faydalı olabilir.
    
    Bash
    
    ```
    cd android
    rm -rf build .gradle app/build
    cd ..
    ```

