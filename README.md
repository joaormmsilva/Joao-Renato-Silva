from pathlib import Path

# Conteúdo do README.md formatado em Markdown
readme_content = """\
# ✨ João Renato Moreira Mendes da Silva

🎓 Estudante de **Análise e Desenvolvimento de Sistemas** em transição de carreira para a área de **programação**.  
Tenho interesse em desenvolvimento web com foco em **Python**, **JavaScript**, **HTML/CSS** e estou sempre em busca de novos aprendizados.

🎮 Gosto de videogames, fotografia e tocar instrumentos.  
🐾 Sou formado como Técnico Veterinário e tenho grande carinho por animais, especialmente felinos.

## 🔧 Tecnologias que estou aprendendo

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)

## 📫 Contato

- 📧 joaormmsilva@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/jo%C3%A3o-renato-moreira-mendes-da-silva-926734351/)
- 💻 [GitHub](https://github.com/joaormmsilva)
"""

# Caminho para salvar o arquivo
file_path = Path("/mnt/data/README.md")
file_path.write_text(readme_content, encoding="utf-8")
file_path.name
