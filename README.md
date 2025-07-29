# Rename Research Papers with PowerShell

When doing research on a specific topic, we often download a large number of scientific papers from platforms like **Google Scholar**, **PubMed**, or **Semantic Scholar**. To organize them properly, it's useful to arrange them into folders by year (e.g., `2025`, `2024`, `2023`, etc.).

However, manually renaming 20, 50, or even 100+ papers can be extremely time-consuming.

This script allows you to **automatically rename** PDF files in a folder using **Windows PowerShell**, assigning them sequential numbers like `1.pdf`, `2.pdf`, `3.pdf`, etc. This makes referencing, manuscript writing, and future retrieval much easier.

---

## 🔧 Features

- Bulk rename research papers in `.pdf` format
- Customizable starting number
- Prevents overwriting existing files
- Simple and fast for organizing large folders

---

## 📂 Folder Structure Example

📁 ResearchPapers/
├── 2025/
├── 2024/
├── 2023/

Place the script inside a year folder (like `2023/`) or update the `$folderPath` in the script.

---
You can download the script file directly or clone the repo using:
[git clone https://github.com/your-username/Rename-Research-Papers.git](https://github.com/Abidn007/Rename-Folder/blob/main/RenameFolder.txt)

##  How to Use

1. **Download or clone** this repository.
2. Edit the script file `RenameFolder.ps1` if needed.
3. Make sure your `.pdf` files are in the target folder.
4. Open **PowerShell** and run the script: ```powershell
.\RenameFolder.ps1



## 🙋‍♂️ Author

**Md. Abid Hassan**  
Undergraduate Student  
Department of Genetic Engineering and Biotechnology  
University of Rajshahi, Bangladesh
[LinkedIn](https://www.linkedin.com/in/md-abid-hassan-067783288/) [Github](https://github.com/Abidn007)
