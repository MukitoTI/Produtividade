## Analise 
### 1. Premissas Utilizadas na Análise
  * Horizonte de análise: 48 meses
  * Ambiente típico de **órgão público**, com:
      * Estações Windows
      * Forte dependência de documentos Office (Excel, Word, PowerPoint)
      * Exigências de segurança, conformidade, auditoria, LAI e LGPD

  * Base de comparação:
      * Microsoft 365 G3/G5 (Governo)
      * Google Workspace Enterprise (Standard / Plus), conforme planilha:
          * Preço aproximado: R$ 135,00 a R$ 195,00 por usuário/mês
          * Recursos avançados de colaboração, porém segurança e governança parcialmente dependentes de soluções externas
       

-------------------------------------------------------------------------------------------------------


### 2. Análise de TCO por Pilar de Custo
#### 2.1 Consolidação de Licenciamento e Stack de Segurança

| Elemento	| Microsoft 365 G3/G5	| Google Workspace Enterprise | 
|-----------|---------------------|-----------------------------|
| Antivírus / EDR	| Microsoft Defender for Endpoint (incluso, líder de mercado)	| Necessidade de contratação adicional (CrowdStrike, SentinelOne, etc.) | 
| MDM / MAM	| Microsoft Intune (incluso)	| Funcionalidades limitadas, exigindo ferramentas externas  
| Identidade e Acesso	| Microsoft Entra ID (IAM, MFA, Conditional Access)	| Google Identity com menor granularidade |
| Governança e Compliance	| Microsoft Purview (DLP, retenção, classificação, eDiscovery avançado)	| Google Vault com capacidades mais restritas |

#### Impacto no TCO:
Embora o valor mensal do Google Workspace Enterprise seja competitivo, a necessidade de múltiplos contratos adicionais (segurança endpoint, DLP avançado, IAM corporativo) eleva significativamente o custo total ao longo de 48 meses.
No Microsoft 365, esses custos já estão embutidos no licenciamento, reduzindo despesas e complexidade contratual.

--------------------------------------------------------------------------------
#### 2.2 Custo de Interoperabilidade e Produtividade

| Aspecto	 | Microsoft 365	| Google Workspace |
|----------|----------------|------------------|
| Compatibilidade de arquivos | Nativa (Office Desktop)	| Conversões frequentes e perda de formatação |
| Uso intensivo de Excel	| Total (macros, Power Query, Power Pivot) |	Limitações funcionais no Google Sheets |
| Necessidade de Office adicional	| Não	 | Sim, para áreas críticas |

#### Impacto no TCO:
Em ambientes Google, é comum a manutenção paralela de licenças do Microsoft Office Desktop para setores como orçamento, planejamento, engenharia e jurídico.
Esse custo oculto, somado à perda de produtividade e retrabalho, gera impacto financeiro recorrente ao longo do ciclo de vida da solução.

---------------------------------------------------------------------------------

#### 2.3 Custos de Implementação e Curva de Aprendizado
| Fator	| Microsoft 365	| Google Workspace |
|-------|---------------|------------------------------|
| Familiaridade dos usuários| 	Alta	| Média/baixa |
| Necessidade de capacitação	| Reduzida	| Elevada |
| Chamados de suporte	| Menor	| Maior nos primeiros ciclos |

--------------------------------------------------------

#### Impacto no TCO:
Considerando que o corpo de servidores já domina o ecossistema Windows/Office, a adoção do Microsoft 365 reduz:
  * Horas de treinamento
  * Custos de capacitação
  * Sobrecarga da equipe de suporte técnico

No Google Workspace, a mudança de paradigma operacional implica custos iniciais e recorrentes de adaptação.

#### 2.4 Automação de Processos e Business Intelligence
| Elemento	| Microsoft 365	| Google Workspace |
|-----------|---------------|------------------|
| BI Corporativo	| Power BI integrado	| Necessidade de Tableau, Qlik ou similares | 
| Automação	| Power Automate nativo	| Dependência de ferramentas externas |
| Integração com dados	| Nativa com Excel, SharePoint, SQL |	Integrações mais limitadas |

#### Impacto no TCO:
O Power BI incluso no ecossistema Microsoft representa economia significativa ao longo de 48 meses, especialmente para:
  * Relatórios de transparência pública
  * Painéis gerenciais
  * Monitoramento de políticas públicas

No cenário Google, ferramentas de BI e ETL elevam substancialmente o custo total.

#### 2.5 Infraestrutura, Suporte e Governança de TI
| Aspecto	 |  Microsoft 365	|  Google Workspace | 
|----------|----------------|-------------------|
| Armazenamento corporativo	| OneDrive + SharePoint	| Google Drive |
| Substituição de file servers	| Total	| Parcial | 
| Controle de Shadow IT	| Elevado |	Mais difícil de mitigar |

#### Impacto no TCO:
O Microsoft 365 permite aposentadoria segura de servidores de arquivos locais, com controle de acesso, versionamento e auditoria, reduzindo custos de infraestrutura e riscos de segurança.
Além disso, a integração nativa diminui significativamente práticas de Shadow IT.

### 3. Tabela Comparativa Consolidada de TCO (48 meses)
| Categoria de Custo	| Microsoft 365 G3/G5	| Google Workspace Enterprise |
|---------------------|---------------------|-----------------------------|
| Licenciamento base	| Médio/Alto	| Médio | 
| Ferramentas de segurança adicionais	| Não	| Sim | 
| Custos de interoperabilidade	| Baixos	| Elevados | 
| Treinamento e suporte	| Reduzidos	| Elevados | 
| BI e automação	 | Inclusos	 | Contratações adicionais |
| Infraestrutura local	| Reduzida	| Parcial | 
| TCO Final (48 meses)	| Menor e previsível	| Maior e fragmentado |

--------------------------------------------------------------------------------------
### 4. Sumário Executivo

Apesar de o Microsoft 365 G3/G5 apresentar um investimento nominal inicial superior, a análise de TCO em 48 meses demonstra que:

  * A consolidação de licenciamento, especialmente em segurança, governança e identidade, reduz custos ocultos relevantes
  * A alta interoperabilidade com o ecossistema Office evita retrabalho e perda de produtividade
  * A curva de aprendizado reduzida diminui despesas com capacitação e suporte
  * A inclusão de Power BI e Power Automate elimina a necessidade de soluções externas de BI e automação
  * O ambiente integrado fortalece a segurança, a conformidade legal e a governança institucional

Dessa forma, o Microsoft 365 se mostra a opção mais segura, eficiente e economicamente vantajosa para o órgão público ao longo do ciclo de vida da solução, traduzindo um investimento nominal maior em menor custo operacional final e menor risco institucional.






