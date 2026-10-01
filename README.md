<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/icone-escuro.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/icone-claro.png">
    <img src="assets/icone-claro.png" width="112" alt="Símbolo laranja do Pad Cut AI">
  </picture>
  <h1>Pad Cut AI</h1>
  <p><strong>Do vídeo longo ao corte pronto para postar.</strong></p>
  <p>Encontra os melhores trechos, reenquadra, legenda e entrega.</p>
  <p>
    <img alt="Versão 0.5.0" src="https://img.shields.io/badge/versão-0.5.0-FF7900?style=flat-square&amp;labelColor=100E0C">
    <img alt="Versão de teste" src="https://img.shields.io/badge/versão_de_teste-FF7900?style=flat-square&amp;labelColor=100E0C">
  </p>
  <p>
    <a href="https://github.com/padilhaDEVELO/pad-cut-ai-releases/releases/download/v0.5.0-tecnico/PadCutAI-0.5.0-macOS-AppleSilicon-tecnico.dmg"><img alt="Baixar para macOS Apple Silicon" src="https://img.shields.io/badge/macOS_Apple_Silicon-BAIXAR-FF7900?style=for-the-badge&amp;logo=apple&amp;logoColor=white&amp;labelColor=100E0C"></a>
    <a href="https://github.com/padilhaDEVELO/pad-cut-ai-releases/releases/download/v0.5.0-tecnico/PadCutAI-0.5.0-Windows-x64-tecnico.exe"><img alt="Baixar para Windows 64 bits" src="https://img.shields.io/badge/Windows_64_bits-BAIXAR-FF7900?style=for-the-badge&amp;logo=windows11&amp;logoColor=white&amp;labelColor=100E0C"></a>
  </p>
  <p>
    <a href="https://github.com/padilhaDEVELO/pad-cut-ai-releases/releases/tag/v0.5.0-tecnico"><img alt="Ver todos os arquivos e hashes" src="https://img.shields.io/badge/arquivos_e_SHA--256-VER-9D9D9F?style=for-the-badge&amp;logo=github&amp;logoColor=white&amp;labelColor=100E0C"></a>
  </p>
  <p><sub><strong>Versão de teste para convidados.</strong> Ainda não é a versão final do produto.</sub></p>
</div>

---

## Qual arquivo baixar

| Computador | Arquivo | Tamanho |
|---|---|---|
| Mac com Apple Silicon (M1 ou posterior) | `PadCutAI-0.5.0-macOS-AppleSilicon-tecnico.dmg` | 402 MB |
| Windows 11, 64 bits | `PadCutAI-0.5.0-Windows-x64-tecnico.exe` | 343 MB |

Mac com processador Intel ainda não tem versão.

## Como instalar no Mac

1. Abra o arquivo `.dmg` e arraste **Pad Cut AI** para **Aplicativos**.
2. Abra o app pela pasta Aplicativos. O macOS vai avisar que não conseguiu verificar o app.
3. Vá em **Ajustes do Sistema → Privacidade e Segurança**, role até o aviso sobre o Pad Cut AI e clique em **Abrir Mesmo Assim**.
4. Confirme com a senha ou o Touch ID. Isso só é pedido na primeira abertura.

## Como instalar no Windows

1. Abra o arquivo `.exe`.
2. Se aparecer a tela azul **"O Windows protegeu o computador"**, clique em **Mais informações** e depois em **Executar assim mesmo**.
3. Siga o instalador. Ele não pede senha de administrador.

O passo a passo completo está no [manual de instalação em PDF](https://github.com/padilhaDEVELO/pad-cut-ai-releases/releases/download/v0.5.0-tecnico/Manual-de-instalacao-Pad-Cut-AI-0.5.0-Windows.pdf). O manual chama o instalador de `Instalar Pad Cut AI 0.5.0.exe`; é o mesmo arquivo `.exe` desta página.

## O que você precisa saber antes de testar

- **O instalador do Windows 0.5.0 ainda não foi testado em um Windows real.** Ele foi montado em um Mac. A versão anterior (0.4.1) foi testada em Windows 11.
- **Problemas conhecidos no Windows**, já corrigidos no código e ainda fora deste instalador:
  - a capa falha quando o projeto fica em uma unidade diferente da do app (por exemplo, app em `C:` e projeto em `D:`);
  - o enquadramento automático falha quando o nome do usuário do Windows tem acento (por exemplo, `C:\Users\joão`).
- **O app não se atualiza sozinho nesta versão.** Para atualizar, baixe o instalador novo nesta página.
- **Os avisos de segurança do macOS e do Windows aparecem** porque os instaladores ainda não têm assinatura reconhecida pelos sistemas.

## Como conferir o arquivo baixado

Os hashes SHA-256 estão no arquivo `SHA256.txt` da [página da versão](https://github.com/padilhaDEVELO/pad-cut-ai-releases/releases/tag/v0.5.0-tecnico).

- Mac: `shasum -a 256 PadCutAI-0.5.0-macOS-AppleSilicon-tecnico.dmg`
- Windows (PowerShell): `Get-FileHash PadCutAI-0.5.0-Windows-x64-tecnico.exe`

## Encontrou um problema?

Abra um aviso em [Issues](https://github.com/padilhaDEVELO/pad-cut-ai-releases/issues) contando o que fez, o que apareceu e qual sistema usa. Não anexe vídeos nem chaves de API.
