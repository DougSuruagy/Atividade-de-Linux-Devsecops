# Atividade-de-Linux-Devsecops
# Script de Verificação de Serviço

## Descrição
Este script verifica se o serviço especificado está online e gera logs indicando o status do serviço. Dois arquivos de log são gerados: um para quando o serviço está online e outro para quando está offline.

## Requisitos
- Sistema operacional Linux
- Serviço a ser monitorado (por exemplo, Nginx)
- Permissões de root para configurar crontab

## Instalação
1. Copie o script para um diretório de sua preferência.
2. Edite o script `verificar_servico.sh` para definir o nome do serviço e o diretório de saída dos logs.
3. Configure o crontab para executar o script a cada 5 minutos:
   ```sh
   crontab -e
