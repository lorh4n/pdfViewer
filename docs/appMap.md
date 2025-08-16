├── CMakeLists.txt             # Arquivo principal de configuração do build.
├── assets/                    # Ícones (SVG), fontes, imagens da UI.
├── docs/                      # Documentação do projeto.
├── libs/                      # Onde bibliotecas como MuPDF e Slint podem ser adicionadas (ex: via git submodule).
├── src/                       # Todo o seu código-fonte.
│   ├── core/                  # O "cérebro" em C++.
│   │   ├── services/          # Lógica principal (ex: PdfService.cpp, DrawingService.cpp).
│   │   └── models/            # Estruturas de dados (ex: Document.h, Annotation.h).
│   ├── ui/                    # A "cara" em Slint e o código de ligação.
│   │   ├── components/        # Seus arquivos .slint (ex: MainWindow.slint, Toolbar.slint).
│   │   └── bindings/          # Código C++ que conecta a lógica do 'core' com a UI.
│   └── main.cpp               # Ponto de entrada da aplicação: inicializa tudo.
└── tests/                     # Testes automatizados para garantir que o 'core' funciona.
