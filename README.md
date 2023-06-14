# ItemID Plugin

O ItemID Plugin é um plugin para servidores Minecraft Pocket Edition (PocketMine-MP) que permite aos jogadores ver o ID dos itens que estão segurando no jogo.

![Demonstração](demo.png)

## Recursos

- Mostra o ID do item na forma de uma dica flutuante para jogadores com permissão de operador (OP).
- Comando `/id` para ativar ou desativar a exibição do ID do item.
- O slogan pode ser configurado através do arquivo `config.yml`.

## Instalação

1. Baixe o arquivo do plugin na página [Releases](link_para_as_releases).
2. Coloque o arquivo do plugin na pasta `plugins` do seu servidor PocketMine-MP.
3. Reinicie o servidor.

## Uso

- Para ver o ID do item que você está segurando, digite o comando `/id`.
- Ao digitar o comando novamente, a exibição do ID do item será desativada.
- Apenas jogadores com permissão de operador (OP) podem usar o comando `/id`.

## Configuração

Você pode personalizar o slogan exibido antes do ID do item através do arquivo `config.yml`. O arquivo será criado automaticamente na primeira execução do plugin.

Exemplo de arquivo `config.yml`:

```yaml
# Configurações do ItemID Plugin
slogan: "§f§l[§eITEM ID§f]"
