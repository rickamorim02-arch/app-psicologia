# Psicologia — aplicativo de estudos V1

Projeto independente. Sete PDFs = sete matérias. Inclui leitura de PDFs, 14 questões objetivas iniciais com referência de página, 7 propostas discursivas, simulado, desempenho, anotações, backup JSON e PWA.

## Publicar
1. Crie um repositório novo `app-psicologia` no GitHub.
2. Envie **todo o conteúdo** deste ZIP à raiz do repositório (incluindo `pdfs/`).
3. Importe o repositório na Vercel como projeto estático; não há comando de build. Output directory: `.`.
4. Abra a URL HTTPS publicada no Chrome e use Instalar aplicativo.

## Limitações importantes
- O navegador pode não exibir PDFs dentro do iframe em todos os celulares; use “Abrir PDF em nova guia”.
- Offline: shell do app em cache; PDFs são armazenados após abertura online, conforme espaço e políticas do navegador. O PDF de Gaskell tem ~36 MB.
- A versão inicial **não** possui caneta sobre PDF, geração automática de questões, agendamento espaçado nem correção de discursivas.
- Banco inicial de 14 questões elaborado com base em trechos verificáveis dos materiais.
- Para atualizar arquivos grandes no GitHub pelo celular, use upload pelo navegador (limite da interface pode afetar o PDF de 36 MB).
- O progresso é local ao navegador/aparelho, não sincroniza entre dispositivos.
