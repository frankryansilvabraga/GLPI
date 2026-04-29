Aqui está a tradução do README do GLPI:

---

# ![Logo GLPI](https://raw.githubusercontent.com/glpi-project/glpi/main/pics/logos/logo-GLPI-250-black.png)

## Sobre o GLPI

GLPI significa **Gestionnaire Libre de Parc Informatique** e é um pacote de software livre para Gestão de Ativos e TI, que oferece funcionalidades de Service Desk baseadas em ITIL, controle de licenças e auditoria de software.

### Principais Funcionalidades do GLPI

* **Gerenciamento de Ativos e Configurações de Serviço (SACM):** Gerencia seus ativos e configurações de TI, rastreando computadores, periféricos, impressoras de rede e seus componentes. A partir da versão 10, conta com gerenciamento de inventário dinâmico nativo, mantendo um banco de dados de configurações sempre atualizado.

* **Atendimento de Requisições:** Simplifica os processos de atendimento, facilitando o gerenciamento de solicitações de serviço, incidentes e problemas de forma eficiente.

* **Gerenciamento de Incidentes e Problemas:** Suporta os processos ITIL de Gerenciamento de Incidentes e Problemas, garantindo que as causas raiz sejam identificadas e medidas preventivas sejam tomadas.

* **Gerenciamento de Mudanças:** Permite planejar, revisar e implementar mudanças de forma controlada e padronizada, minimizando riscos.

* **Gerenciamento do Conhecimento:** Inclui uma base de conhecimento e suporte a FAQ, permitindo capturar, armazenar e compartilhar soluções valiosas.

* **Gerenciamento de Contratos:** Oferece recursos completos para gerenciar contratos, contatos e documentos associados aos itens de inventário.

* **Gestão Financeira para Serviços de TI:** Auxilia no gerenciamento de informações financeiras, como ordens de compra, garantias e depreciação.

* **Reserva de Ativos:** Permite reservar ativos de TI para fins ou períodos específicos, alinhado ao processo de Gerenciamento de Demanda do ITIL.

* **Gerenciamento de Infraestrutura de Data Center (DCIM):** Oferece recursos para gerenciar a infraestrutura de data centers.

* **Gerenciamento de Software e Licenças:** Garante conformidade e controle de custos relacionados a softwares e licenças.

* **Análise de Impacto:** Auxilia na avaliação das consequências potenciais de mudanças ou incidentes nos serviços de TI.

* **Catálogo de Serviços (com SLM):** Inclui recursos de catálogo de serviços integrados ao Gerenciamento de Nível de Serviço (SLM).

* **Separação por Entidades:** Permite o gerenciamento distinto de diferentes unidades organizacionais.

* **Gerenciamento de Projetos:** Ajuda a organizar e acompanhar projetos e tarefas associadas.

* **Planejamento de Intervenções:** Oferece recursos para agendar e gerenciar intervenções presenciais.

Além disso, suporta diversos [plugins](http://plugins.glpi-project.org) que adicionam funcionalidades extras.

---

## Demonstração

Conheça os recursos do GLPI solicitando uma demonstração pessoal gratuita em **[glpi-network.cloud](https://www.glpi-network.cloud)**

---

## Licença

Distribuído sob a **GNU GENERAL PUBLIC LICENSE Versão 3** — consulte o arquivo [LICENSE](https://raw.githubusercontent.com/glpi-project/glpi/main/LICENSE) para mais detalhes.

---

## Pré-requisitos

* Um servidor web (Apache, Nginx, IIS, etc.)
* MariaDB >= 10.2 ou MySQL >= 5.7
* PHP (veja a matriz de compatibilidade abaixo)

| Versão do GLPI | PHP Mínimo | PHP Máximo |
|----------------|------------|------------|
| 9.4.X          | 5.6        | 7.4        |
| 9.5.X          | 7.2        | 8.0        |
| 10.0.X         | 7.4        | 8.2        |

**Extensões PHP obrigatórias:**
dom, fileinfo, json, session, simplexml, curl, gd, intl, libxml, mysqli, zlib

**Extensões PHP sugeridas:**
exif, ldap, openssl, zip e bz2

**Navegadores suportados:**
Edge, Firefox (incluindo as 2 últimas versões ESR) e Chrome

---

## Download

Veja os [releases](https://github.com/glpi-project/glpi/releases) para pacotes compactados.

---

## Documentação

* [Administrador GLPI](https://glpi-install.readthedocs.io) — Instalação, atualização, ferramentas de linha de comando, fusos horários e configurações avançadas.
* [Usuário GLPI](https://glpi-user-documentation.readthedocs.io) — Primeiros passos, visão geral dos módulos, configuração e administração.
* [Desenvolvedor GLPI](https://glpi-developer-documentation.readthedocs.io) — Gerenciamento de código-fonte, padrões de codificação, API e guias de plugins.
* [Agente GLPI](https://glpi-agent.readthedocs.io) — Instalação, configuração e uso em Windows/Linux/Mac OS.
* [Plugins GLPI](https://glpi-plugins.readthedocs.io) — Uso e funcionalidades dos plugins.

---

## Recursos Adicionais

* [Site oficial](http://glpi-project.org)
* [Demonstração](https://www.glpi-network.cloud)
* [Traduções (Transifex)](https://www.transifex.com/glpi/public/)
* [Problemas/Issues](https://github.com/glpi-project/glpi/issues)
* [Sugestões](http://suggest.glpi-project.org)
* [Fórum](http://forum.glpi-project.org)
* [Diretório de Plugins](http://plugins.glpi-project.org)

---

## Suporte

O GLPI é um software em constante evolução. Para facilitar o suporte, considere o ciclo de vida típico das versões:

* Uma nova versão principal (ex: 9.3) é lançada.
* Versões menores (9.3.x), corrigindo bugs, são publicadas nas semanas seguintes — recomenda-se sempre atualizar para a última versão menor disponível.
* Alguns meses depois, uma nova versão principal (ex: 9.4) é lançada. As versões anteriores deixam de receber suporte — atualize para a nova versão principal. As ferramentas de migração também são suportadas!