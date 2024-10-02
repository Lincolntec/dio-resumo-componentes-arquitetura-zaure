<img src="file:///home/lincoln/www/Dio/curso_microsft_azure/dio-resumo-componentes-arquitetura-zaure/image/cursoDioAzure.png" title="" alt="cursoDioAzure.png" width="219">

# [Dio]( [Code your global future now](https://www.dio.me/en)) Componentes de Arquitetura do Azure

**Desafio DIO Formação Microsoft AZ-900 Certification**, resumo sobre componentes de arquitetura do Azure.

## Conteúdos

- [Regiões](#altaDisponibilidade)
- [Pares de Regiões](#pares de regiões)
- [Regiões soberanas do Azure](#regiões soberanas )

## Regiões

    As regiões são composta de um ou mais datacenters muito proximos. Quando é escolhido uma região é importante escolher uma região de baixa latência, ou seja escolher uma região proxíma de onde os clientes vão acessar suas aplicações, é importante também informar que nem todo recurso está disponivel para determinada região, pode acontecer de querer usar um serviço e o mesmo não estar disponivel, outro detalhe importante de se saber é que entre uma região e outra pode ter diferenças de preços na contratação dos recursos. 



## Zonas de disponibilidade

    Zonas de disponibilidade são unidades fisícas de data centers que estão separadas por distâncias significativas dentro de uma região do Azure. Algumas das vantagens de se utilizar  **Zonas de disponibilidade são:** Alta disponibilidade, tolerancia a falhas, escalabilidade e desempenho.



## Pares de Regiões

    É um conceito que se refere a associação de duas Regiões do Azure, dentro da mesma area geográfica em uma configuração de emparelhamento. As vantagens de se utilizar os pares de Região são a capacidade de fornecer alta disponibilidade e resiliência. Ao implantar recursos em um par de região você pode aproveitar a replicação sincrona ou assincrona dos dados e o failover automático entre as regiões primárias e secundárias. 

    **Cenários que os pares de regiões do Azure se aplicam**: 

* Recuperação de desastres
  
      Em caso de falha em uma Regição a segunda pode assumir o trabalho.

* Alta disponibilidade
  
  Com paredes de região você pode distribuir a carga de trabalho entre elas para garantir maior disponibilidade.

* Conformidade com regulamentações

        Em alguns setores regulamentações especificas podem exigir a replicação dde dados em regiões separadas. É importante ressaltar que nem toda região do Azure possui par.



Link dos pares de regiões: https://aka.ms/PairedRegions-ptb



## Regiões soberanas do Azure

    São regiões isoladas designada a oferecer serviços de nuvem exclusivos para entidades governamentais e organizações que precisam cumprir requisitos de soberania, de um país ou região. Essas regiões são projetadas para fornecer controle e proteção adicionais aos dados sensiveis e criticos do governo ou de organizações com quesitos de conformidades rigorosas.

    **Principais Regiões Soberanas do Azure:** 

* Azure governament: Instância para entidades governamentais dos Estados Unidos.

* Azure China 21Vianet.

* Azure Government Secret: Instancia para entidades governamentais dos Estados Unidos com requisitos de segurança ainda mais rigoroso.

* Azure Germany.



**Cenários que as Regiões soberanas se aplicam:**

* Setor publico e governamental.

* Industrias regulamentadas.

* Dados confidencias.



## Assinaturas do Azure

    Uma assinatura é uma conta que fornece acesso aos serviços e recursos do Azure. Uma conta permite que gerencie permissões e acessos para usuários e grupos específicos.



**Vantagens de utilizar as assinaturas:**

* Controle de Custo.

* Gerenciamento Centralizado.

* Escalabilidade.

* Flexibilidade.



## Grupos de gerenciamento

    Grupos de gerenciamento são hierarquias de objetos que ajudam a gerenciar acessos a conformidade e a governancia em grande escala. Eles permitem gerenciar varias assinaturas como uma unica entidade e aplicar politicas e controle em toda a organização. Os grupos permitem que organizem os recursos em uma estrutura hierarquica.



**Vantagens de utilizar os grupos de gerenciamento:**

* Centralização.

* Consistenência.

* Escalabilidade.

* Eficiência.



**Hierarquia de grupos de recursos**, assinaturas e grupos de gerenciamento são modelos de organização e gerenciamento de recursos de nuvem em diferentes niveis de abstração e escopo. Essa hierarquia é composta por grupos de **gerenciamento,** **assinaturas e grupos de recursos.**



## Recursos do Azure

    São os componentes de infraestrutura que constituem os serviço da Azure. Cada recurso do Azure é identificado por um nome exclusivo e uma ID de Recurso.



## Grupo de recurso

    São containers lógicos que permitem gerenciar todos os recursos relacionados. Os grupos de recursos também permitem gerenciar premissões e acesso para usuários e grupos especificos.



**Vantagens em utilizar os grupos de recursos:**

* Organização

* Gerenciamento Centralizado.

* Controle de acesso.

* Faturamento simplificado.



## Confiabilidade:

    Na nuvem podemos ter confiabilidade com a duplicação dos recursos em regiões diferentes, backup e diferentes outras estratégias o que nos traz integridade dos dados, das informações e com isto a confiabilidade.

## Previsibilidade:

    No ambiente de nuvem conseguimos ter uma previsão dos custos e consumo dos serviços o que nos permite definir estratégias de migração para cloud, otimização de serviços, definir melhorias ao passar do tempo pois conseguimos ter um histórico tanto de consumo como de valor obtidos pela utilização dos recursos.

## Segurança:

    A segurança resume-se na capacidade de consumir um serviço em cloud e garantir que o ambiente seja seguro em todas as camadas, seja ela de infraestrutura, camada de aplicação, camada de dados enfim, e este conjunto de regras nos permite estar em conformidade com as políticas de segurança.

## Governança:

    Trata-se de políticas, que dizem o que pode ou não pode ser feito no ambiente de cloud. Se um usuário pode ou não excluir um recurso, se um recurso pode ser acessado, regras específicas para determinado setor de indústria, existem algumas regras que já vem definidas, porém também é possível cria-las.

<a href="www.linkedin.com/in/lincolntec">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/17651227?s=400&u=ed46bef85a6c3069307d3dc6abc5a2777c118355&v=4" width="100px;" alt=""/>
 <br />
</a>

🚀

Desenvolvido por ****[Alcino José Lincoln de Souza](www.linkedin.com/in/lincolntec)**** 👋🏽 Entre em contato!
