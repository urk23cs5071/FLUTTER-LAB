# Student Records (Flutter + SQLite) - Ex. 6

## Setup in VS Code
1. Install Flutter SDK + VS Code "Flutter" extension.
2. Open this folder in VS Code (File > Open Folder).
3. In the terminal, generate platform folders (keeps lib/ and pubspec.yaml):
       flutter create . --platforms=web,windows,android
4. Install packages:
       flutter pub get
5. Web only - install the sqflite web binaries (creates sqflite_sw.js and sqlite3.wasm in web/):
       dart run sqflite_common_ffi_web:setup
6. Run:
       flutter run -d chrome
   (or pick a device at the bottom-right of VS Code and press F5)

## For your record
Enter your own details in the form, e.g.
- Priyanka | URK23CS5071
- Vinisha  | URK23CS5041
then take screenshots of: initial screen, record insertion, multiple records.
