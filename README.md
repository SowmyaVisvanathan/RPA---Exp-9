### Name : Sowmya V
### Reg no : 212222110045
### Date : 
# Exercise 9 - Keyboard Automation - Simulate Keystrokes

### Aim:
To simulate typing and keyboard shortcuts in a desktop application (Notepad).

### Software required:
UiPath Studio-community edition

### Procedure:

1. **Start the Notepad Application**
   - Use the **Start Process** activity.
   - In the properties, set the `FileName` field to `"notepad.exe"` to open Notepad.

2. **Type Text into Notepad**
   - Use the **Type Into** activity to enter text into the Notepad window.
   - Click **Indicate on Screen** in the Type Into activity and select the Notepad text area.
   - In the `Text` field, input `"This is a sample text."` or any text you want to type.

3. **Save the File with a Keyboard Shortcut**
   - Use the **Send Hotkey** activity to open the "Save As" dialog.
   - Click **Indicate on Screen** in the Send Hotkey activity and select the Notepad window.
   - Set the hotkey properties by checking `Ctrl` and selecting `S` as the key. This simulates `Ctrl + S`, which opens the Save As dialog in Notepad.

4. **Enter the File Name**
   - Use another **Type Into** activity to specify the file name in the Save As dialog.
   - Click **Indicate on Screen** in this Type Into activity and select the "File name" field in the Save As dialog.
   - In the `Text` field, enter `"Sample"` or the desired file name.

5. **Press Enter to Save**
   - Use another **Send Hotkey** activity to press the Enter key and complete the save.
   - Click **Indicate on Screen** in this Send Hotkey activity and select the "Save" button in the Save As dialog.
   - Set the `Key` property to `Enter` to simulate pressing Enter.

### Main.xaml:

![image](https://github.com/user-attachments/assets/fa10d03f-7f5c-4b69-aeca-0b57603f2f18)

![image](https://github.com/user-attachments/assets/c57b9f53-197e-4ae4-b592-8b800496c719)


### Output:

![image](https://github.com/user-attachments/assets/f95fdf16-f490-4b71-812c-cfe5e4d20d75)


### Results:
Thus, the automation process of keystroke simulation is executed successfully.


