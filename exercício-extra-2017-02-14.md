# Apache HTTP Server 2.3 para 2.4

# MPMs de carga em tempo de execução
# Múltiplos MPMs agora podem ser criados como módulos carregáveis em tempo de compilação. O MPM de escolha pode ser configurado em tempo de execução via LoadModulediretiva.
# Evento MPM
# O Event MPM não é mais experimental, mas agora é totalmente suportado.
# Suporte assíncrono
# Melhor suporte para leitura / gravação assíncrona para suporte de MPMs e plataformas.
# Configuração LogLevel por módulo e por diretório
# O LogLevelagora pode ser configurado por módulo e por diretório. Novos níveis trace1 de trace8foram adicionados acima do debugnível de log.
# Seções de configuração por solicitação
# <If>, <ElseIf>E as <Else> seções podem ser usadas para configurar a configuração com base em critérios por solicitação.
# Analisador de expressão de propósito geral
# Um novo analisador de expressão permite especificar condições complexas usando uma sintaxe comum em directivas como SetEnvIfExpr, RewriteCond, Header, <If>, e outros.
# KeepAliveTimeout em milissegundos
# Agora é possível especificar KeepAliveTimeoutem milissegundos.
# Diretriz NameVirtualHost
# Não é mais necessário e agora está obsoleto.
# Substituir a Configuração
# A nova AllowOverrideList diretiva permite um controle mais fino que as diretivas são permitidas nos .htaccessarquivos.
# Variáveis ​​do arquivo de configuração
# Agora é possível as Define variáveis ​​na configuração, permitindo uma representação mais clara se o mesmo valor for usado em muitos lugares na configuração.
# Redução de uso de memória
# Apesar de muitos novos recursos, 2.4.x tende a usar menos memória do que 2.2.x.
#
# NGINX 1.12 para 1.13
#
# Olhando adiante para NGINX 1.13
# A série de lançamento NGINX 1.13 também promete trazer avanços significativos, incluindo aprimoramentos para HTTP / 2 e recursos de cache. Também faremos melhorias contínuas ao nginScript em termos de suporte ao idioma JavaScript e habilitaremos uma configuração programática ainda mais sofisticada. As demandas de aplicações modernas, distribuídas e de microservices também estão direcionando parte do nosso roteiro, e mais serão compartilhadas em nossa conferência anual de usuários, nginx.conf 2017 , nos dias 6 e 8 de setembro em Portland, OR.
#
# WordPress 4.8 para 4.8.1
#
# Depois de mais de 13 milhões de downloads do WordPress 4.8, temos o prazer de anunciar a disponibilidade imediata do WordPress 4.8.1, uma versão de manutenção.
# Esta versão contém 29 reparos de manutenção e aprimoramentos, o principal entre eles são correções para o widget rich Text e a introdução do widget HTML personalizado. Para obter uma lista completa de alterações, consulte as  notas de versão , os  bilhetes fechados e a  lista de alterações.
