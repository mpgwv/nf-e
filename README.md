## 🧾 O que é NF-e (Nota Fiscal eletrônica)

A **NF-e (Nota Fiscal eletrônica)** é um documento fiscal digital utilizado no Brasil para **registrar e validar operações de venda ou circulação de produtos**.  
Ela substitui a nota fiscal em papel (modelos 1 e 1A) e possui **validade jurídica** garantida pela **assinatura digital** do emitente e pela **autorização da SEFAZ (Secretaria da Fazenda)**.

### 🔍 Estrutura da NF-e
A NF-e é gerada em um arquivo **XML** padronizado nacionalmente, contendo:
- **Emitente:** dados da empresa (CNPJ, razão social, endereço);
- **Destinatário:** dados do cliente;
- **Produtos:** descrição, quantidade, valor, NCM, CFOP;
- **Tributos:** ICMS, IPI, PIS, COFINS, entre outros;
- **Totais e formas de pagamento.**

Após gerada, a NF-e é **transmitida para a SEFAZ** do estado responsável, que valida o conteúdo e retorna a **Autorização de Uso**.  
Com essa autorização, o emitente pode gerar o **DANFE (Documento Auxiliar da NF-e)** — a representação gráfica da NF-e usada para acompanhar o transporte da mercadoria.

### ⚙️ Fluxo simplificado da emissão
1. Geração do XML da NF-e conforme o layout oficial da SEFAZ.  
2. Assinatura digital do arquivo com **certificado A1 ou A3**.  
3. Transmissão do XML para os servidores da **SEFAZ**.  
4. Recebimento da **Autorização de Uso** (ou rejeição).  
5. Emissão do **DANFE** e armazenamento do XML autorizado por **5 anos**.

### 🧩 Tipos de notas eletrônicas relacionadas
| Tipo | Nome completo | Aplicação principal |
|------|----------------|---------------------|
| **NF-e** | Nota Fiscal eletrônica | Venda de **produtos físicos** |
| **NFC-e** | Nota Fiscal de Consumidor eletrônica | **Varejo** e vendas diretas ao consumidor |
| **NFS-e** | Nota Fiscal de Serviços eletrônica | **Prestação de serviços** |
| **CT-e** | Conhecimento de Transporte eletrônico | **Transporte de cargas** |

---

> ℹ️ **Observação:** este projeto tem como objetivo demonstrar o processo de **emissão de NF-e** de forma simplificada, utilizando os ambientes de **homologação (teste)** da SEFAZ, sem validade fiscal real.
