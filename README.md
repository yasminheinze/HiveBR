# Projeto HiveBR

O projeto HiveBR tem como objetivo a disponibilização de case templates para a ferramenta TheHive com procedimentos padrões para tratamento de incidentes aplicados ao cenário brasileiro. 

Desenvolvido por Yasmin de Oliveira Heinze (yasminoliveiraheinze@hotmail.com) sob orientação do professor Ricardo Borges Almeida como trabalho de conclusão de curso para o curso de especialização em Segurança da Informação da Faculdade de Tecnologia Senac Pelotas

# A estrutura do HiveBR

O objetivo do presente projeto é criar cases templates na lingua portuguesa que tornam possível facilitar para os analistas do cenário brasileiro o tratamento dos incidentes de ransomware e de phishing. Com isto foi utilizado o exemplo o case template para o TheHive do ATT&CK do Mitre, que trata-se de uma base de conhecimento globalmente acessível de táticas e técnicas adversárias com base em observações do mundo real. A base de conhecimento da ATT&CK é usada como base para o desenvolvimento de modelos e metodologias de ameaças específicas no setor privado, no governo e na comunidade de produtos e serviços de segurança cibernética.

Os cases templates também tiveram como base os procedimentos tomados pelo National Institute of Standards and Technology (NIST) e pelo SysAdmin, Audit, Network and Security (SANS) que são organizações com objetivos de padronizar os procedimentos de segurança da informação, sendo instituições que são reconhecidas mundialmente. Porém, também foi adotado nos Response Playbooks a etapa de comunicação, afim de aprimorar e promover uma boa comunicação entre as partes interessadas ao incidente. 

# Sumarização dos cases templates 

Cada ação de resposta mapeada para um estágio de resposta específico.

O primeiro dígito do ID da Ação de Resposta reflete um Estágio ao qual pertence:

1 : Preparação

2 : Identificação

3 : Contenção

4 : Erradicação

5 : Recuperação

6 : Comunicação

7 : Lições Aprendidas


O segundo dígito do ID da ação de resposta no case template de phishing email reflete uma categoria à qual pertence:

0 : Geral

1 : rede

2 : Email 

3 : Arquivo

4 : Processo

5 : Configuração

6 : Identidade


O segundo dígito do ID da ação de resposta no case template de ransomware reflete uma categoria à qual pertence:


0 : Geral

1 : Rede

2 : Ransomware

3 : Endpoint

4 : Arquivos

5 : Configuração

6 : Dados sensiveis


Dessa forma, usando o ID da ação de resposta, você pode ver o estágio e a categoria aos quais ela pertence.
