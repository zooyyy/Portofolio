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
<img width="1365" height="632" alt="image" src="https://github.com/user-attachments/assets/c4e22b88-e645-48f9-a243-7c84dd920a14" />
📸 Figure 1 (Main Interface)
Displays the encryption–decryption interface for text and image-based notes using the RC4 and XChaCha20 algorithms.
<img width="1365" height="631" alt="image" src="https://github.com/user-attachments/assets/df7dc06f-65e3-4120-80b9-0e583fb8b8a3" />
📸 Figure 2 (New Note Input)
Users can type text, enter an encryption key, and choose whether to show or hide the key.
Once saved, the note is securely encrypted and stored.
<img width="1365" height="629" alt="image" src="https://github.com/user-attachments/assets/77238b88-40e2-4923-bc4d-2f4a159e7407" />
<img width="1365" height="629" alt="image" src="https://github.com/user-attachments/assets/a54479c3-7984-48d1-ba35-8792d52a4c38" />
📸 Figure 3 – 4 (Stored Notes List)
Saved notes are displayed on the right side of the interface.
To open a note, the user must enter the same encryption key used during its creation.
<img width="1365" height="636" alt="image" src="https://github.com/user-attachments/assets/dcc179c5-e9c5-4beb-8fd7-03e6a48865da" />
📸 Figure 5 (Incorrect Key)
If the key entered is incorrect, the content remains encrypted and unreadable.
<img width="1365" height="627" alt="image" src="https://github.com/user-attachments/assets/a31633a0-7d0a-4574-a56a-6d5d7ca2b65a" />
<img width="1365" height="623" alt="image" src="https://github.com/user-attachments/assets/32fb2ae3-c58a-44dc-aa1e-8c09f6169a49" />
📸 Figure 6 – 7 (Correct Key)
When the correct key is provided, the encrypted text is successfully decrypted and displayed in readable form.
<img width="1365" height="630" alt="image" src="https://github.com/user-attachments/assets/de55c770-b638-4b64-ab2a-28b8eab1b42c" />
<img width="1365" height="629" alt="image" src="https://github.com/user-attachments/assets/56cd826c-abfa-4cb6-97cd-921adc72fe91" />
📸 Figure 8 – 9 (Saving Text and Images)
The system supports encryption and secure storage of both text and image content simultaneously.
<img width="1365" height="629" alt="image" src="https://github.com/user-attachments/assets/dbb9559b-c15d-46a1-82fc-91be947a487c" />
📸 Figure 10 (Hidden Key Mode)
The encryption key can be hidden for better privacy and visual simplicity.
<img width="1365" height="629" alt="image" src="https://github.com/user-attachments/assets/9277f39e-07fa-42db-b238-8e94a194fe3a" />
📸 Figure 11 (Ordered Note Display)
Saved notes are displayed in reverse chronological order — from the newest to the oldest.
<img width="1362" height="629" alt="image" src="https://github.com/user-attachments/assets/71901d3d-dfe9-44d8-bf47-4cbd748710ad" />
<img width="1365" height="632" alt="image" src="https://github.com/user-attachments/assets/894be17b-6ef8-4726-843c-29d9744bcc95" />
📸 Figure 12 – 13 (Testing with Incorrect Key)
When an incorrect key is entered, both text and images remain fully encrypted and inaccessible.
<img width="1365" height="628" alt="Screenshot 2025-10-12 190111" src="https://github.com/user-attachments/assets/336fea49-9599-4d2d-922c-46f199d6e139" />
📸 Figure 14 (Testing with Correct Key)
With the correct key, both text and images are decrypted perfectly, restoring the note to its original form.
<img width="1365" height="622" alt="image" src="https://github.com/user-attachments/assets/32cd4b25-4466-4ac0-b3e6-0373c2c41aa2" />
<img width="1365" height="628" alt="image" src="https://github.com/user-attachments/assets/22876025-6923-443c-ad80-30dd1ad5531a" />
📸 Figure 15-16 (Note Deletion)
Click the 🗑️ icon to delete a note.
A confirmation dialog appears before permanent deletion to ensure safety.




🔒 Security Overview
This system uses dual-layer hybrid encryption, combining RC4 for lightweight symmetric processing and XChaCha20 for advanced nonce-based protection.
All encryption occurs entirely within the browser, ensuring that data never leaves the local environment.
The user-defined key guarantees total ownership, privacy, and integrity of every stored note.
