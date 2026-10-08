# Update-CREAS

Versão publicada: 1.0.31.

Consulta identidade central atual nas medidas e alertas, preservando históricos e registros sem vínculo. Novas réplicas não copiam tabelas sigilosas do CREAS nem views desconhecidas. Consultas e gravações sigilosas offline são recusadas; auditoria sigilosa usa conexão online. Agenda, encaminhamentos, histórico e documentos ficam online por conterem vínculos sigilosos. 14 testes passaram. Não exige migração nova.

Use Sobre > Verificar / Atualizar agora e reinicie quando solicitado. A publicação não instala automaticamente nos computadores.

LIMITAÇÃO: esta versão NÃO apaga fisicamente dados existentes em arquivos offline antigos. O programa bloqueia consultas sigilosas offline, mas acesso direto ao arquivo antigo ainda precisa ser tratado. Grants do servidor e a revisão completa dos outros programas continuam pendentes. Não representa garantia de isolamento completo.

Publique o conteudo desta pasta no repositorio:

https://github.com/conectcras-ai/Update-CREAS

Estrutura esperada:

- manifest.xml
- app/conect-creas-1.0.0-completo.jar

Para o botao Sobre > Atualizar sistema detectar nova versao, a versao do manifest precisa ser maior que a versao instalada.
