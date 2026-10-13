# Update-CREAS

Versão publicada: 1.0.33.

Corrige a falha do dashboard causada por collations diferentes na consulta UNION. Mantém identidade central e sigilo somente online. Falhas de consulta não são exibidas como contagens de zero.

18 testes passaram. Consulta corrigida validada no MySQL de produção, somente leitura. Sem migração nova.

Use Sobre > Verificar / Atualizar agora e reinicie quando solicitado. O nome físico do JAR permanece estável. Manifesto e binário assinados; confira CORRECOES_1.0.33.md para detalhes.

Limitações: NÃO remove caches/anexos antigos, NÃO altera grants nem separa contas do banco e NÃO encerra a validação completa de todas as telas. A publicação não instala automaticamente nos computadores.
