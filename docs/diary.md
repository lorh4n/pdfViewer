# 📅 Diário de Desenvolvimento — 16/08/2025

## 🕚 11:29 — Inicialização do Projeto

- Criei o projeto e organizei as pastas principais.
- Optei pela licença **GNU GPLv3** para garantir que o projeto seja sempre open-source.

### Estrutura de Pastas

```
├── CMakeLists.txt             # Configuração principal do build
├── assets/                    # Ícones (SVG), fontes, imagens da UI
├── docs/                      # Documentação do projeto
├── libs/                      # Bibliotecas externas (ex: MuPDF, Slint)
├── src/                       # Código-fonte principal
│   ├── core/                  # "Cérebro" em C++
│   │   ├── services/          # Lógica principal (ex: PdfService.cpp)
│   │   └── models/            # Estruturas de dados (ex: Document.h)
│   ├── ui/                    # Interface em Slint e integrações
│   │   ├── components/        # Arquivos .slint (ex: MainWindow.slint)
│   │   └── bindings/          # Código C++ de ligação com a UI
│   └── main.cpp               # Ponto de entrada da aplicação
└── tests/                     # Testes automatizados
```

---

## ⚙️ Configuração Inicial

- Instalei o **vcpkg** como gerenciador de dependências.
- Configurei o **CMake** básico com `add_executable(...)`.
- Testei o CMake com um "Hello World" — funcionou! ✅
- Adicionei a pasta `build/` ao `.gitignore`.

---

## 🕜 13:36

*(Continuação do desenvolvimento...)*