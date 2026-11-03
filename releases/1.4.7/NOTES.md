**English**

- Updates in the app: when a new version is out, its notice shows what changed in every version since yours, and Update downloads it, checks it and hands it to Android to install. Nothing is installed unless the file matches the checksum published with the release and is signed by the same key as your Hush. Android asks once to allow Hush to install apps, and asks you to confirm each installation. You can also skip a version.
- Settings › About › Check for updates now asks at once, whether or not the daily check is on, and says when it last looked and what it found.
- The privacy policy says what the update downloads, from where, how it is checked and how long the file is kept, and lists the permission to install apps. You will see a notice about the change once.
- The release APK no longer lists android.permission.DUMP. It was never a permission Hush asked for: a library's receiver was guarded by it, so that only a developer's computer could reach it. Release builds now leave that receiver out.

**한국어**

- 앱 안에서 업데이트합니다. 새 버전이 나오면 알림에서 지금 버전 이후 모든 버전의 바뀐 점을 보여 주고, '업데이트'를 누르면 내려받아 확인한 뒤 안드로이드에 설치를 맡깁니다. 파일이 릴리스와 함께 공개된 체크섬과 일치하고 지금 Hush와 같은 키로 서명된 경우에만 설치합니다. 처음 한 번 안드로이드가 Hush의 앱 설치를 허용할지 묻고, 설치할 때마다 확인을 묻습니다. 원하지 않는 버전은 건너뛸 수 있습니다.
- 설정 › 정보 › '지금 업데이트 확인'은 매일 확인을 켜지 않았어도 바로 확인하고, 마지막으로 언제 확인했는지와 결과를 보여 줍니다.
- 개인정보처리방침에 업데이트가 무엇을 어디서 내려받는지, 어떻게 확인하는지, 파일을 얼마나 두는지와 앱 설치 권한을 적었습니다. 변경 안내가 한 번 표시됩니다.
- 배포용 APK에 더 이상 android.permission.DUMP가 나오지 않습니다. Hush가 요청하던 권한이 아니라, 개발자 컴퓨터만 접근할 수 있도록 라이브러리의 수신기에 걸려 있던 보호 장치였습니다. 이제 배포용 빌드에서는 그 수신기를 뺍니다.

SHA-256 `7e02beb8c04da82dedc554f3ef52943c4f2c4c383a8060ce113d7b2f2ac1846d`
Signing certificate SHA-256 `00:37:AE:C5:11:EF:6B:A7:37:50:6D:24:BD:AC:64:54:04:EE:37:1E:F1:F1:4D:F2:4A:FC:B6:5F:D3:67:8E:52`
