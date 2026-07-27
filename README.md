# 📊 Visualização Interativa

> Aplicação para visualização interativa de dados através de servidor HTTP local.

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Status](https://img.shields.io/badge/Status-Ativo-success?style=for-the-badge)

---

## 📁 Estrutura de Arquivos

Para garantir o funcionamento correto da aplicação, mantenha os arquivos organizados no mesmo diretório:

```text
visualizacao_interativa/
├── 📄 index.html          # Interface principal da aplicação
└── 📊 sechselaeuten.csv   # Base de dados utilizada pela visualização
```

## Passo a Passo para Execução

### 1. Abra o terminal na pasta do projeto:
```bash
cd ~/visualizacao_interativa
```

### 2. Inicie o servidor local:
```bash
python -m http.server 80
```
ou
```bash
sudo python -m http.server 80

### 3. Abra no navegador:
```text
http://localhost
```

### 4. Para encerrar o servidor, volte ao terminal e pressione:
`Ctrl` + `C`
