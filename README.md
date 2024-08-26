# Phòng Trọ Happy
  1. Setup environment
<details lose="" align="left">
  <summary>
      Install nvm/Nodejs
  </summary>
<div align="center"> INSTALL<br>Link Dowload nvm or Nodejs/NPM </div> 
<br>
<p align="center">
    <a href="https://github.com/nvm-sh/nvm" alt="nvm">
        <img src="https://img.shields.io/badge/nvm-000000?style=for-the-badge&logo=nvm&logoColor=#5FA04E" /></a>
    <a href="https://nodejs.org/en" alt="Nodejs">
        <img src="https://img.shields.io/badge/nodejs-000000?style=for-the-badge&logo=nodedotjs&logoColor=#5FA04E" /></a>
      <a href="https://nodejs.org/en" alt="Nodejs">
        <img src="https://img.shields.io/badge/npm-000000?style=for-the-badge&logo=npm&logoColor=#CB3837" /></a>
</p>

<p align="center">Cài đặt nvm để dễ quảng lý, xóa bỏ version nodejs. NPM giúp quản lý các thư viện Dependencies cho dự án.</p>
<br>
- kiểm tra nvm sau khi cài đặt thành công.

```cmd
nvm -v
```
![image](https://github.com/user-attachments/assets/e73d06d5-7f96-49b5-9111-9eba5946ee90)

- Cài đặt version theo version Node bạn muốn (máy mình có sẵn ròi nên mình up ver lên á): `nvm istall <vX.Y.Z>`
```cmd
nvm istall v20.17.0
```
![image](https://github.com/user-attachments/assets/f9de76ba-add3-473d-9431-94f3d7045a39)

kiểm tra version các phiên bản Node hiện có: `nvm list`

```cmd
nvm list
```

![image](https://github.com/user-attachments/assets/f5a307e9-6495-40c3-a816-f1400bfc754c)


- dùng version: `$ nvm use <vX.Y.Z>` để chọn version node bạn muốn dùng.
  
```cmd
nvm use v20.17.0
```
![image](https://github.com/user-attachments/assets/227cde0d-ea0e-4bcd-bb92-96e639707f2d)

phiên bản bạn đang dùng sẽ có dấu `*`
<br>
![image](https://github.com/user-attachments/assets/afe351d2-88b3-4928-bbc7-aef56b67ac6c)

</details> 

<details lose="" align="left">
  <summary>
    Tạo Project: vite + React + tailwind css + TypeScript
  </summary>
  <div align="center"> CREATE PROJECT </div> 
<br>
<p align="center">
    <a href="https://www.typescriptlang.org/"><img src="https://skillicons.dev/icons?i=typescript" alt="typescript"/></a>
</p>  
<p align="center">
    <a href="https://react.dev/"><img src="https://skillicons.dev/icons?i=react" alt="react"/></a>
    <a href="https://vitejs.dev/"><img src="https://skillicons.dev/icons?i=vite" alt="Vite"/></a>
    <a href="https://tailwindcss.com/"><img src="https://skillicons.dev/icons?i=tailwind" alt="tailwind"/></a>
</p>

B1. Tạo thư mục chứa Project trên máy.
<br>
<br>
B2. Bạn trỏ đến đường dẫn chứa thư mục và nhập lệnh sau `npm create vite@latest` trên terminal để tạo dự án. 
<br>(`latest` đây là phiển cuối cùng được cập nhật của vite)

```cmd
npm create vite@latest
```
hoặc `npm create vite@X.Y.Z` trong đó X.Y.Z là version của bạn.
<br>
<br>
B3. Bạn làm theo các bước sau theo hướng dẫn trên terminal:
<br>
Project name và Package name tùy bạn.
Select a framework >> React (nhấn mũi tên xuống để lựa chọn).
Select a variant: >> TypeScript (nhấn mũi tên xuống để lựa chọn).

![image](https://github.com/user-attachments/assets/7159cbf8-d55a-431d-b418-5d7b77b46475)

B4. Sau khi hoàn tất bạn có thể duy chuyển đến thư mục để kiểm tra: 
<br>
![image](https://github.com/user-attachments/assets/454f5384-b2fb-42bc-9ddc-01cc48d7196d)

</details> 
