# CREAS 1.0.33

Corrige o painel que falhava com MySQL erro 1271 (Illegal mix of collations for operation UNION).
As dez expressões textuais das cinco partes da consulta usam utf8mb4_unicode_ci explicitamente.
Mantém a identidade atual do cadastro central e os vínculos/destinos protegidos para compromissos sigilosos.
Falha de consulta mostra valores indisponíveis, não contagens fictícias de zero.

Validação: regressão automática e execução da consulta corrigida no servidor 10.147.17.123,
somente leitura, sem exibir cadastros, executar migrações ou alterar permissões.
