**Automação de Renomeação de Comprovantes**

Script em Python para extrair informações de comprovantes em PDF e renomear os arquivos automaticamente.

**Funcionalidades**
- Extrai o nome do beneficiário.
- Identifica a data do pagamento.
- Captura o valor do pagamento.
- Renomeia os PDFs com as informações extraídas.
- Evita nomes duplicados adicionando um contador ao final do arquivo.
- Permite executar o processo pelo Windows usando um arquivo .bat.
  
**Tecnologias**
- Python
- PyMuPDF
- Expressões regulares

**Como utilizar**
1. Instale o Python no Windows.
2. Instale a dependência com py -m pip install pymupdf.
3. Configure o caminho da pasta de PDFs no arquivo renomear.py.
4. Execute EXECUTAR.bat.

**Observação**

Confira os arquivos renomeados e valide as informações extraídas antes de utilizar os dados em processos financeiros.
