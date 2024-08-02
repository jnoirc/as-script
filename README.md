# Script for Android Studio on Linux > Ubuntu

## Start:

1. Git clone:

```
 git clone https://github.com/jnoirc/as-script.git

```

2. Enter the folder:

```
cd as-script

```

3. Move:

```
sudo mv run-an.sh /usr/local/bin

```

4. Run in terminal:

```
run-an

```

## Creating the script manually:

1. Create the file:

- `touch ~/run-an`: This command creates a new file named run-an in your home directory (~). You can choose any name you prefer.

```
touch ~/run-an

```

2. Add Script Content:

- Open the newly created run-an file with a text editor.
- Paste the following line:

```
#!/bin/bash
/usr/local/android-studio/bin/studio.sh

```

- This line tells the system that the script is written in Bash and specifies the command to execute: running studio.sh from the Android Studio installation directory. Replace /usr/local/android-studio/bin/studio.sh with the actual path to your Android Studio installation's studio.sh file if it's different.

3. Make the script executable:

- chmod +x ~/run-an: This command grants the script permission to be executed.

```
chmod +x ~/run-an

```

4. Move

```
sudo mv ~/run-an /usr/local/bin

```

5. Run the Script:

- Open a terminal window.
- Type run-an and press Enter. This will launch Android Studio.

```
run-an

```
