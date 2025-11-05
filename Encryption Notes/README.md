🔒 Advanced Security Design

A web-based encrypted notes system that allows users to securely encrypt and decrypt text and images using a hybrid encryption model combining RC4 and XChaCha20 algorithms.
All processes run entirely on the client side, ensuring full data confidentiality without any server or external storage.
By integrating the speed of RC4 with the robust cryptographic strength of XChaCha20, this application achieves exceptional balance between efficiency and security.
Users define their own encryption key, which is never stored or transmitted, guaranteeing complete privacy and control.

⚡ Key Advantages:
- High Performance (optimized for real-time in-browser encryption and decryption)
- Dual Encryption Layers (RC4 and XChaCha20 deliver multi-level protection)
- User-Centric Privacy (only users with the correct key can decrypt notes)
- Full Client-Side Processing (no servers or databases involved)
- Offline Access (works seamlessly without internet connection)
- Smart Integration (blends classic and modern encryption methods efficiently)

⚙️ Features:
- Create and encrypt text or image-based notes.
- Key-based decryption with optional key visibility toggle.
- Local storage for safe offline access.
- Secure deletion with confirmation prompt.



🖼️ Application Preview
Below is a step-by-step explanation of the application interface and workflow.
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/1.png))
📸 Figure 1 (Main Interface)
Displays the encryption–decryption interface for text and image-based notes using the RC4 and XChaCha20 algorithms.
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/2.png))
📸 Figure 2 (New Note Input)
Users can type text, enter an encryption key, and choose whether to show or hide the key.
Once saved, the note is securely encrypted and stored.
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/3.png))
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/4.png))
📸 Figure 3 – 4 (Stored Notes List)
Saved notes are displayed on the right side of the interface.
To open a note, the user must enter the same encryption key used during its creation.
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/5.png))
📸 Figure 5 (Incorrect Key)
If the key entered is incorrect, the content remains encrypted and unreadable.
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/6.png))
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/7.png))
📸 Figure 6 – 7 (Correct Key)
When the correct key is provided, the encrypted text is successfully decrypted and displayed in readable form.
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/8.png))
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/9.png))
📸 Figure 8 – 9 (Saving Text and Images)
The system supports encryption and secure storage of both text and image content simultaneously.
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/10.png))
📸 Figure 10 (Hidden Key Mode)
The encryption key can be hidden for better privacy and visual simplicity.
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/11.png))
📸 Figure 11 (Ordered Note Display)
Saved notes are displayed in reverse chronological order — from the newest to the oldest.
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/12.png))
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/13.png))
📸 Figure 12 – 13 (Testing with Incorrect Key)
When an incorrect key is entered, both text and images remain fully encrypted and inaccessible.
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/14.png))
📸 Figure 14 (Testing with Correct Key)
With the correct key, both text and images are decrypted perfectly, restoring the note to its original form.
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/15.png))
![Logo AgroAI](https://github.com/zooyyy/image/blob/main/Encryption%20Notes/16.png))
📸 Figure 15-16 (Note Deletion)
Click the 🗑️ icon to delete a note.
A confirmation dialog appears before permanent deletion to ensure safety.




🔒 Security Overview
This system uses dual-layer hybrid encryption, combining RC4 for lightweight symmetric processing and XChaCha20 for advanced nonce-based protection.
All encryption occurs entirely within the browser, ensuring that data never leaves the local environment.
The user-defined key guarantees total ownership, privacy, and integrity of every stored note.
