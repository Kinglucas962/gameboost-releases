# GameBoost

Otimizador de jogos para Windows 11, feito para rodar no seu próprio PC: sem conta, sem serviço pago.

**Baixar:** pegue o `GameBoostSetup-x.y.z.exe` mais recente em [Releases](https://github.com/Kinglucas962/gameboost-releases/releases/latest). O código-fonte não fica neste repositório; aqui ficam só os instaladores e o arquivo de atualização automática.

## O que ele faz

- **Modo jogo:** fecha os programas que você escolher, troca o plano de energia e reverte tudo quando o jogo acaba. Pode ligar sozinho ao detectar um jogo, por atalho de teclado ou pelo ícone ao lado do relógio.
- **Início:** mostra o que está usando mais processador, memória e disco/internet agora, com botão para fechar o que pesa.
- **Ajustes do Windows e da NVIDIA:** gravação do Xbox, Modo de Jogo, HAGS, prioridade de jogos, telemetria, mouse e configurações globais da placa NVIDIA. Cada ajuste tem backup e dá para desfazer.
- **Perfis por jogo (NVIDIA):** escolha o perfil de cada jogo.
- **Serviços e Inicialização:** pergunta quais programas você quer dispensar ao iniciar o Windows e quais serviços pausar. Nada é apagado; dá para religar.
- **Limpeza:** arquivos temporários, caches, cache do Windows Update, Otimização de Entrega e instaladores de driver antigos.
- **Diagnóstico:** confere temperatura, discos, Resizable BAR, driver do chipset, monitor e outros pontos que afetam o desempenho.
- **Teste de internet para jogos:** ping, variação e perda até o roteador, a internet, os servidores da Valve (São Paulo) e a API da Riot, e avisa se o problema está dentro de casa.
- **Gargalo:** estimativa de quem limita o FPS (placa de vídeo ou processador) durante o jogo. É uma estimativa, não uma medida exata.
- **Copiar relatório:** resumo do seu PC para colar numa conversa, sem nome, endereços ou pastas.
- **Exportar e importar configuração:** passe seus ajustes para um amigo; quem importa vê o que muda antes e a importação só liga e acrescenta.

## Atualizações

O GameBoost verifica este repositório ao abrir (e de tempos em tempos), confere o SHA-256 (impressão digital) do instalador e atualiza sozinho. O app pede administrador sempre, porque os ajustes mexem no sistema.

## Segurança

Ele não desliga o Defender, a integridade de memória nem mitigações de CPU. Antes de aplicar ajustes, o app pode criar um ponto de restauração do Windows.

## Avisos

- O Windows SmartScreen ou o antivírus podem avisar sobre o instalador, porque ele não tem certificado de assinatura de código pago.
- Teste de Wi‑Fi e a medição de gargalo ainda foram pouco testados fora do PC do autor.
