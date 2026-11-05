# JEZER / THE ARCHITECT EXPERIENCE — v2

Protótipo de galeria 3D interativa, com 6 estações navegáveis, criado com Three.js e dados públicos da carreira de Jezer Portilho.

## Iniciar no Windows
1. Extraia este ZIP.
2. Na pasta `jezer-experience-v2`, clique na barra de endereço do Explorador, digite `powershell` e pressione Enter.
3. Execute: `python -m http.server 8000`
4. No Chrome, abra manualmente `http://127.0.0.1:8000/` (não use um link que adicione parâmetros).
5. Mantenha o PowerShell aberto. Se 8000 estiver ocupada, use `python -m http.server 8001` e abra a porta 8001.

## Controles
- Clique em ENTRAR NA EXPERIÊNCIA.
- A / D ou setas esquerda/direita: selecionar estação.
- Enter ou botão EXPLORAR: abrir informações.
- Esc: fechar um painel.
- Clique nas instalações 3D, nos marcadores laterais ou use os botões na parte inferior.
- PT / EN: trocar idioma.
- VISÃO GERAL: menu de acesso rápido.

## Observações
- Three.js e fontes são carregados pela internet. É necessária conexão para visualização 3D na versão atual.
- Há modo de cartões de fallback se WebGL falhar.
- Não é uma cópia do site de Rafael Carvalho, nem utiliza elementos visuais do jogo Valorant; segue uma identidade original de luxo tecnológico.
- Conteúdo editorial baseado em dados públicos de jezerportilho.ia.br e currículos já fornecidos. Resultados e projetos devem ser aprovados antes da publicação pública.
- Não inclui coleta de informações, analytics ou backend.
- Efeitos sonoros poderão ser implementados em uma versão futura.
