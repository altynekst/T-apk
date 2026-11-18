# T-apk (Android client, Nullcki)

Клиент Nullcki (DDNet 20.2.1 + NullClient + KRX) под Android.

- Сурс НЕ хранится в репо: workflow скачивает пин `59e02c55e7`
  из `altynekst/Nullcki` и собирает APK (arm64-v8a, пакет com.altynekst.tapk,
  имя приложения T-apk). Touch-контролы и мобильные меню уже в клиенте.
- ddnet-libs материализуется из ddnet/ddnet-libs @c0e6703fbc.
- APK: Releases -> tapk-v<N> -> T-apk.apk; подпись постоянная (CN=T-apk),
  обновления ставятся поверх старых без удаления и потери данных.
